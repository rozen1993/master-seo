# Requisitos técnicos y medición

Especificación futura. No se ha construido ni desplegado la web. Fuentes rectoras: [F5](fuentes/FASE-5-DIAGNOSTICO-Y-RECOMENDACIONES-2026-11-04.md), filas P01–P37; G5-INS/NOINDEX/FAQ/REV/CONT y comprobaciones G6 registradas.

## Rutas y equivalencia

[rutas.json](rutas.json) enumera 32 combinaciones: ocho paths por HTTP/HTTPS y con/sin www. HOST_CANONICO_PENDIENTE impide tratarlo como configuración ejecutable. Inspeccionar los datos indexados de ambas variantes y contrastarlos con señales actuales, enlaces y objetivo de migración. La selección de Google orienta la decisión; no sustituye el acuerdo técnico. La prueba en vivo no predice la canónica elegida (G5-INS).

El archivo original vercel.json contiene seis 301, incluido index y show, y trailingSlash true; es un hecho de configuración local, no de despliegue. Las reglas del ejemplo de 07 no reemplazan este mapa. No elegir hosting para resolverlo en esta fase.

| Legado | Destino documental | Contenido que debe cotejarse |
|---|---|---|
| /index.html | / | Home; title legado y H1 son distintos |
| /video.html | /servicios/produccion-audiovisual/ | L03: edición, empresarial/publicitario y eventos sociales; conservar o derivar a servicios disponibles |
| /fotografia.html | Pendiente L04 | Sesiones personales, familiares, retratos y usos comerciales/catálogos; resolver piezas audiovisuales mezcladas |
| /marketing.html | /servicios/marketing-digital/ | L05: redes, estrategia, diseño, branding, logotipos y análisis; decidir vigencia antes de omitir |
| /web.html | /servicios/desarrollo-web/ | L06: paquetes y 7/11/18 días históricos; ratificar o retirar de forma documentada |
| /show.html | /show-infantil-navideno/ | L07 íntegro: preservar contenido pertinente; reorganizar cuatro H1 en jerarquía semántica |
| /Brochure.pdf | Misma ruta exacta | Archivo PDF 200 en host canónico; normalización de host separada |

Cada origen requiere un registro párrafo/sección legado → conservar, actualizar, derivar o retirar con motivo y aprobación. Para fotografía, las candidatas P09/P21 no cubren automáticamente todo L04; quien reciba el 301 debe conservar u orientar el contenido vigente de forma útil. No hacer una cadena temporal solo porque una landing esté lista. Si no se resuelve, conservar el legado operativo o posponer ese corte; no apuntar a un destino incompleto. Esta contingencia requiere plan de despliegue posterior, no se implementa aquí.

Objetivo: 301 directo a destino final 200; documentar y evaluar cadenas. Probar variantes, parámetros de atribución necesarios, bucles y enlaces. HTML con barra final; PDF sin barra final y con capitalización exacta. En https y host canónico el PDF no tiene redirect de recurso; en otros hosts/protocolos puede normalizar al mismo path. Show se redirige desde lanzamiento por decisión ya aprobada, independientemente de la temporada. Ensayar antes y comprobar inmediatamente durante el corte real.

## Indexación por tipo

| Clase | Respuesta y directiva objetivo | Sitemap y canonical |
|---|---|---|
| HTML aprobado y publicado | 200, rastreable, sin noindex | Incluir solo canónica; autorreferente al host acordado |
| Privacidad | 200 indexable propuesto, con texto revisado | Incluir si aprobada/200/canónica; decisión local D6-16 |
| Gracias | 200, noindex legible | Excluir; omitir canonical según contrato local; no usarla para excluir |
| Inexistente/404 | 404 real | Excluir; sin canonical a home |
| Reservas y tanda aún no publicada | No crear URL vacía; solicitud inexistente responde 404 | Sin sitemap ni enlaces |
| Redirects legados | 301 cuando se activa la migración aprobada | No incorporarlos al sitemap nuevo |
| Brochure | 200 PDF, sin nueva directiva de indexación en esta fase | No incorporarlo automáticamente al sitemap; revisión específica |

Staging: elegir acceso restringido o noindex que un crawler pueda leer. Si se usa noindex, no bloquear su rastreo con robots.txt. Un staging autenticado no depende de que Google lea un noindex detrás de la autenticación. En producción retirar la protección del staging y las directivas de exclusión solamente de páginas que deban indexarse; gracias conserva su noindex. La accesibilidad técnica no garantiza indexación.

## Datos estructurados

El contrato por tipo y condición está en [schema.json](schema.json). Usar Organization/WebSite y Service cuando representen datos reales visibles. Breadcrumbs solo con rutas disponibles; VideoObject/ImageObject con material y permisos, propiedades verificadas y pruebas posteriores. No inventar precios, dirección, ratings ni fechas.

Comprobación nueva del 04-11: ProfessionalService es un subtipo local deprecado; no se recomienda para la nueva implementación. Esta evidencia sustituye la recomendación histórica sin modificar sus archivos. [Schema.org](https://schema.org/ProfessionalService).

Para elegibilidad de LocalBusiness en Google se requieren nombre y dirección física; teléfono es recomendado. Esto no convierte una dirección pública o una ficha GBP en requisitos universales para publicar HTML. Separar vocabulario válido, elegibilidad y aparición efectiva. [Google Search Central](https://developers.google.com/search/docs/appearance/structured-data/local-business).

Las comprobaciones G5 del 03-11 se reutilizan: FAQ útil no implica resultado enriquecido; no encargar Review/AggregateRating de la propia entidad para buscar estrellas autocontroladas. Las reseñas reales pueden mostrarse como contenido. No se prohíbe todo uso del vocabulario Review. Las propiedades exactas y guías de cada función se revisarán al implementar; ningún marcado está validado hoy.

## Contacto, conversiones y privacidad

[medicion.json](medicion.json) es el diccionario futuro con disparadores, deduplicación y nueve pruebas. Interacción no es aceptación; aceptación no demuestra recepción; recepción no implica cualificación. Un identificador opaco de solicitud correlaciona backend y buzón/CRM. Reintento o doble clic del mismo envío no crea un segundo lead; un envío distinto recibe identificador distinto. Acceso directo o recarga de gracias no confirma nada.

La interfaz muestra confirmación solo tras aceptación comprobable; mensaje neutro si no existe comprobante. No afirmar recepción humana por el mero 200 del backend. Antes de activar contacto se necesitan canal destinatario, atención responsable, privacidad revisada y prueba de recepción. Si una función no supera el control, no se publica como operativa; una alternativa verificada requiere su propio control. No enviar datos personales ni mensajes a analítica; la política real determinará almacenamiento y retención con revisión competente.

Inventario a completar por responsable: dato recogido, finalidad, disparador, proveedor/destinatario, almacenamiento, acceso, conservación, contacto y revisión aplicable. No completar razón social, RUC, dirección ni permisos por inferencia. Esta documentación no dictamina cumplimiento normativo.

## Calidad de implementación futura

Un H1 semántico y visible; title ≤60 y description ≤155 caracteres NFC son reglas editoriales locales, no límites universales de Google. H1 y title no tienen que ser textos idénticos. No exigir 600 palabras. Resolver descriptions de casos pendientes antes de publicarlos; gracias y 404 pueden omitirlas. PDF no tiene campos HTML. Nada de datos ficticios en producción.

Revisar teclado, foco visible, labels, errores, texto alternativo según función de cada imagen, dimensiones reservadas y legibilidad en móvil. Áreas táctiles de 44 px son objetivo local heredado. H1 y frase de valor serán texto real. Estas pruebas no equivalen a certificación de accesibilidad. Imágenes responsivas y carga diferida cuando corresponda, sin retrasar el contenido principal.

Conservar objetivos locales de 07: LCP <2,5 s, INP <200 ms, CLS <0,1, home <1 MB sin videos. Para el peso, documentar una carga móvil inicial con caché vacía y sumar bytes transferidos de HTML/CSS/JS/fuentes/imágenes y terceros; excluir únicamente cuerpos de video. Definir viewport/red/herramienta en el ensayo y repetir en condiciones comparables. Medir laboratorio y campo por separado: TBT no es INP de campo; sin datos de campo suficientes se registra pendiente, no bloqueo automático del lanzamiento.

## Ads: entrega separada

Máximo S/110 mensual y objetivo aproximado S/100. El especialista debe conocer gasto acumulado del mes, configuración y límites efectivos antes de proponer cambios. No convertir un presupuesto diario aproximado en garantía mensual. El S/7,77/día reportado, Perú y PRESENCE_OR_INTEREST se compararán con una propuesta concreta; Lima/Callao por presencia es referencia del documento 11, pendiente de aprobación operativa. El corte 15-11 es propuesto, no impuesto. No actualizar anuncios, conversiones, pujas, destinos ni presupuestos en esta fase. PAGE_VIEW no es prueba de lead.

Como cálculo ilustrativo, sostener S/7,77 durante 30 días daría S/233,10, por encima de S/110. Es una proyección aritmética sobre una configuración histórica reportada, no gasto observado, límite efectivo de Google ni estado actual de cuenta. Antes de reactivar o cambiar campañas, verificar configuración y gasto acumulado y aprobar una propuesta compatible con el máximo; aquí no se modifica nada.
