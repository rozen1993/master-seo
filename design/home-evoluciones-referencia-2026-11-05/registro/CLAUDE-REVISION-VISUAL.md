# Revisión visual de Claude — evoluciones de la referencia

6 de noviembre de 2026. Revisión hecha por Claude Opus 5.5 (`claude-opus-5-5`) directamente desde Claude Code, **no a través del wrapper Claudex**: Codex se quedó sin cuota y no pudo operar la llamada ni su propia revisión. Se examinaron los tres PNG completos, ampliaciones 2× de las zonas de texto y la referencia `fuentes/original.png`. Coste por llamada no expuesto; no se inventa.

## Verificaciones comunes

- Todo el texto coincide con `CONTENIDO-COMUN.txt`: H1, subtítulo, tres servicios con su descripción, «Ver servicio», seis enlaces del catálogo, tres pasos, seis campos vacíos, política de privacidad y pie. No aparecen cifras, clientes, premios, REC/timecode ni microtexto decorativo.
- «Imágenes ilustrativas» aparece junto a cada fotografía.
- **Resolución:** los tres PNG miden 735 × 2140 px, no los 1440 × 4200 pedidos en `plan-generacion.json`. Sirven para elegir dirección, no como mockup a tamaño de escritorio.
- Textura de generación: se ven vetas verticales tenues sobre fondos planos (sobre todo naranja y marfil). Es artefacto de imagen, no intención de diseño.

## 01 — Subtítulos

Hero sólido: H1 dominante a la izquierda, cámara visible a la derecha, «en» en ámbar y CTA bermellón, como pidió la cocreación. Las tres bandas de servicio (foto panorámica + barra con título, frase y botón) dan buena lectura y jerarquía. Débil: el bloque de servicios repite tres veces la misma estructura y alarga la página; las barras inferiores parecen tarjetas, algo que la cocreación quería evitar. Formulario oscuro sobre marfil, correcto. Sin erratas detectadas.

## 02 — Luz de rodaje

La más cercana a la referencia del dueño y la más clara para comparar servicios: hero negro con foto de evento a sangre y H1 entero sobre negro (sin corte LI|MA), servicios en tres columnas abiertas sobre plata/marfil, catálogo y footer negros. Cumple «sin sombras ni cajas». Débil: el subtítulo del hero queda pegado al H1 y la foto se superpone a la zona de lectura en la parte baja. «Fotografía» aparece sin tilde en el catálogo («Fotografia»): **errata a corregir**.

## 03 — Corte cálido

La de mayor personalidad: bloque naranja continuo con tres filas y texto negro, catálogo en lista limpia de una columna (la mejor resuelta de las tres) y formulario marfil sobre carbón. Débiles: el hero es más bajo y la foto queda menos protagonista que en la referencia; el pedido de «fotografía vertical» no se cumple (es horizontal); el texto negro sobre naranja necesita comprobación de contraste en desarrollo. **Errata:** «Registro audio*s*isual» (glifo deformado) en Cobertura de eventos.

## Veredicto de Claude

Las tres son válidas para que el dueño elija dirección. Recomendación: **02 como base** por lectura y fidelidad a la referencia, tomando de 03 el catálogo en lista de una columna. Antes de cualquier entrega final hay que corregir las dos erratas y regenerar a 1440 px de ancho.

## Pendiente (no se declara hecho)

- Revisión visual de Codex Astra Ultra — bloqueada por falta de cuota.
- Correcciones y regeneración (Codex es el único operador de generación en este encargo).
- Elección del dueño; después, móvil o desarrollo.
