# Reparación propuesta para el soporte visual de Claudex

Estado: **aplicada tras autorización expresa del dueño el 5 de noviembre de 2026**. No modifica Rhino, el plan SEO, campañas ni credenciales. Registro de instalación y copia de seguridad: [reparacion-instalada.json](reparacion-instalada.json). Doctor y suite de regresión aprobados: [doctor-post-reparacion.json](doctor-post-reparacion.json).

Preparación concreta: [diff de los tres scripts](reparacion-propuesta.patch), [hashes originales y propuestos](reparacion-hashes.json), [26 pruebas offline aprobadas](reparacion-pruebas-aisladas.json). También pasó la suite existente `test-context-policy.ps1` sobre copias aisladas antes de aplicar. Las pruebas offline no acreditan por sí mismas una nueva llamada real a Claude; su resultado se registra por separado.

La prueba real ya acreditó que Opus 5.5 puede ver una imagen. Falló la entrega JSON porque la guardia bloqueó `StructuredOutput`; la recuperación está etiquetada como incompleta. Además, el manifiesto de varias imágenes se interpreta incorrectamente en PowerShell 5.1. El límite actual de 256 KiB impedirá revisar muchos PNG finales originales.

Directorio afectado: `C:/Users/MARCO/Desktop/Sistema_R/claudex/adapters/codex/claudex/scripts/`. Se proponen cambios únicamente en `invoke-claude.ps1`, `read-guard.ps1` y `context-policy.ps1`, más pruebas acotadas. Conservar copias y hashes antes de aplicar para permitir reversión exacta.

## 1. Parseo de varias rutas

En `invoke-claude.ps1`:

```diff
- $readPaths = @([IO.File]::ReadAllText($ReadManifest) | ConvertFrom-Json)
+ $readPaths = ConvertFrom-Json -InputObject ([IO.File]::ReadAllText($ReadManifest)) -ErrorAction Stop
```

Reproducción offline en PowerShell 5.1.26100.9711: `['one.txt','two.txt']` representado como JSON válido produce actualmente un array anidado y luego la ruta combinada `one.txt two.txt`. La asignación propuesta entrega dos rutas. No cambia qué rutas están autorizadas.

## 2. Entrega interna del resultado

La política de lectura incorpora `allowStructuredOutput = ($OutputFormat -eq 'json')`. Antes de validar Read/Grep, la guardia agrega:

```powershell
if ($event.tool_name -ceq 'StructuredOutput' -and $policy.allowStructuredOutput -eq $true) {
    exit 0
}
```

Se mantiene el hook universal y el bloqueo ante fallo. No se emite una decisión `allow` que anule permisos de la CLI; no se habilitan Bash, escritura, Glob, MCP ni herramientas desconocidas. La excepción exacta solo permite entregar el resultado del esquema solicitado.

## 3. Lectura de PNG/JPEG originales

Agregar un parámetro optativo `AllowRasterImage` a `Get-ClaudexSafeFile`. Sin ese parámetro, conservar exactamente el límite de texto de 262144 bytes. Con él, únicamente `.png`, `.jpg` y `.jpeg` pueden alcanzar 10485760 bytes (10 MiB), verificando la firma PNG `89-50-4E-47-0D-0A-1A-0A` o JPEG `FF-D8-FF` y extensión correspondiente.

El manifiesto valida con ese parámetro; la guardia lo activa solo para `Read`. `Grep` de imágenes permanece prohibido. La pertenencia exacta al manifiesto, raíz autorizada, rutas sensibles y rechazo de enlaces/junctions permanecen. El filtro existente de patrones de secretos también se conserva sobre los bytes de la imagen interpretados como Latin-1; no se envían esos bytes como texto al modelo. No se retoca la imagen. Ese detector no interpreta metadatos comprimidos ni es una garantía universal de ausencia de secretos.

## Pruebas antes de la nueva llamada

Ejecutar offline: manifiestos de una y varias rutas; salida estructurada solo con bandera activa; denegación de Bash/Glob/herramientas desconocidas; PNG/JPEG válidos; firma errónea; imagen mayor de 10 MiB; texto mayor de 256 KiB; archivos fuera del manifiesto y raíz; rutas sensibles y enlaces; Grep de imagen; patrón sintético de secreto en bytes. Ejecutar también las pruebas existentes pertinentes y el doctor, sin gastar tokens en esas pruebas.

Tras aprobación y pruebas, hacer una nueva comprobación real acotada y registrar modelo y consumo. Una salida parcial nunca se reclasifica retroactivamente como validada. No cambiar modelo, perfil, autenticación, límites de cuota ni configuración persistente de Claude Code.

## Por qué se pide aprobación

El encargo autoriza mockups y documentos nuevos. Esta reparación toca una herramienta compartida fuera de `design/` y amplía expresamente el tamaño de imágenes admitidas. La skill Claudex exige usar su wrapper y conserva lectura restringida; no corresponde sustituirlo por una llamada directa o desactivar las guardias para continuar.
