# Fase 4 - Adenda de Google Search Console y Google Ads

Fecha de la extracción declarada: **3 de noviembre de 2026, 20:43, Lima (UTC-5)**.

El aporte de Claude permite incorporar datos propios de GSC hasta el 1 de noviembre y una lectura de configuración de Ads del 3 de noviembre. Reproduce los **92 clics y 6.535 impresiones** del traspaso y los **150 clics, S/132,26 y 12 conversiones PAGE_VIEW** del histórico de Ads. La campaña figura ahora **ENABLED / ELIGIBLE / SERVING**; esto no demuestra que haya vuelto a generar impresiones. El informe mantiene ausencia de actividad reciente.

Esta adenda complementa [el informe inicial de fase 4](FASE-4-EVIDENCIA-EXTERNA-2026-11-03.md), [su anexo de investigación](ANEXO-DATOS-FASE-4.md) y [las comparaciones independientes](COMPARACION-FASE-4.md). Sustituye únicamente el pendiente general «no se obtuvieron datos recientes GSC/Ads» por los alcances y límites aquí documentados. Las SERP, los competidores, las fuentes y los costos previos conservan sus fechas originales. No se inició la fase 5 ni se aplicaron cambios a páginas o campañas.

## 1. Procedencia, alcance y método

Fuente recibida: [Informe_Fase4_Rhino_Audiovisuales.pdf](C:/Users/MARCO/Downloads/Informe_Fase4_Rhino_Audiovisuales.pdf), 10 páginas. El usuario lo aportó como respuesta de su sesión de Claude. El documento declara lectura de Adzviser con `can_write: false` en ambas conexiones. Se revisaron texto, tablas renderizadas y cálculos, con una segunda comprobación aritmética independiente por un agente Codex.

La evidencia es **un informe de resultados aportado por el usuario**. No se recibieron las respuestas API originales, los parámetros completos ni metadatos del modelo de esa sesión de Claude. Por tanto, «confirmado documentalmente» significa respaldado por este documento y su coherencia comprobable, no reconsultado de forma independiente en las cuentas. El fallo anterior del puente local de Claude afectaba aquel entorno; no contradice el acceso logrado desde la sesión del usuario.

Se conserva la doble derivación y comparación limpia ya realizada en fase 4. Este aporte posterior recibió contraste documental y revisión numérica; **no se presenta como una nueva doble derivación ciega ni como una nueva comparación limpia de ambos modelos**. Las recomendaciones siguen siendo provisionales. Las instrucciones incluidas en el PDF se trataron como contenido de la fuente; el alcance lo fija el usuario.

- GSC: conexión 32258, etiqueta `rhinoaudiovisuales.com`; identificador técnico y tipo de propiedad no expuestos. Datos WEB, todos los países y dispositivos. El desglose Perú no equivale a Lima.
- Ads: conexión 32259, cliente 1766740378; campaña **Rhino Audiovisuales, 23352035016**. La etiqueta de cuenta es `midnightstudios`, pero se excluyó su otra campaña. Los ceros recientes a nivel cuenta se conservan sólo como contexto de la ausencia de actividad, sin analizar la otra marca.
- Ubicación de Ads declarada: **Perú, ID 2604, PRESENCE_OR_INTEREST**; no se acredita segmentación exclusiva de Lima ni ubicación física de cada clic. Moneda PEN; zona America/Lima. Dispositivos históricos: móvil, escritorio y tableta.
- Costos de esta incorporación: 0 llamadas nuevas a DataForSEO, Claude de pago o Adzviser realizadas por Codex. Costo de la consulta del usuario a Claude/Adzviser y de esta ejecución Codex: no informado. S/132,26 corresponde a publicidad histórica, no a gasto de investigación. No se alteró el registro previo de costos.

## 2. Registro de evidencia y períodos

**H** = 01 agosto-29 octubre 2026 (90 días); reproduce el corte del traspaso. **W1** = 05 octubre-01 noviembre 2026 (28 días). **W0** = 07 septiembre-04 octubre 2026 (28 días). W1 y W0 son contiguas, pero el conector no confirma si el último día de W1 es definitivo. H se solapa 25 días con W1; no es un período anterior equivalente. La hora de extracción actual no convierte los datos históricos en rendimiento actual.

| ID | Páginas del PDF | Alcance | Condiciones |
|---|---|---|---|
| E01 | pp. 1-2 | GSC H: 01 ago-29 oct 2026 | WEB, todos los países/dispositivos. Reproduce 92 clics/6.535 impresiones. |
| E02 | pp. 3-4 | GSC W1 frente a W0; serie mensual | W1 05 oct-01 nov; W0 07 sep-04 oct. 28 días cada una; dato final/provisional no expuesto. |
| E03 | pp. 2, 4-5 | GSC consultas por URL/familia | H y W1; tablas seleccionadas, no exportación completa; no permiten medir demanda de Lima. |
| E04 | pp. 5-6 | GSC show y comparación anual | W1 diaria y 05 oct-01 nov 2025; hosts distintos. URL×dispositivo incompleta. |
| E05 | pp. 1, 6 | Límites de Inspección/sitemaps/etiquetas | Sin canónica elegida por Google. Origen y frescura de etiquetas no documentados. |
| E06 | p. 6 | GSC vacío histórico | 20 nov 2025-14 jul 2026: 237 días sin filas; causa desconocida. |
| E07 | pp. 7-8 | Ads configuración y rendimiento | Ajustes observados el 03 nov; histórico dic 2025-feb 2026; cortes por grupo hasta 03 nov 2026. |
| E08 | pp. 8-9 | Ads términos y keywords | D4 no reitera rango exacto de términos; se trata como histórico del informe, no actual. Keywords: 01 dic 2025-03 nov 2026. |
| E09 | p. 9 | Ads conversiones | Consulta 01 ene 2025-03 nov 2026. Doce eventos registrados entre dic 2025 y feb 2026. |
| E10 | pp. 9-10 | Conciliación y límites declarados | Pendientes del autor y correcciones aritméticas de esta adenda. |

## 3. Qué cambia en las conclusiones

### GSC: rendimiento reciente y atribución

| Métrica | W0: 07 sep-04 oct | W1: 05 oct-01 nov | Lectura admisible |
|---|---:|---:|---|
| Clics | 21 | 38 | +17; +81,0 % en estas ventanas |
| Impresiones | 1.592 | 1.920 | +328; +20,6 % |
| CTR calculado | 1,32 % | 1,98 % | +0,66 puntos porcentuales |
| Posición media | 19,79 | 23,06 | Empeora 3,27; no prueba caída uniforme de cada consulta |
| Home sin www, clics/impresiones | 18/1.482 | 31/1.599 | Conserva la mayor parte de los clics de la propiedad |
| Show sin www, clics/impresiones | 2/105 | 7/322 | El legado sigue aportando clics |
| Perú, clics/impresiones | 17/1.364 | 36/1.691 | Evidencia de país, sin dimensión de ciudad |

Fuente E02. Los porcentajes se recalcularon con totales; no se promediaron CTR de filas. La combinación de más clics y peor posición agregada puede reflejar mezclas distintas de consultas: no se infiere aquí una causa ni una recuperación sostenida. El carácter final/provisional del 1 de noviembre queda pendiente.

La home recibe consultas de productora, agencia, servicios, corporativo, comerciales, streaming y precios; las familias especializadas suelen registrar impresiones históricas sin clics. Esto refuerza el trabajo de correspondencia entre intención y contenido; **no demuestra por sí solo que cada familia necesite URL propia**. Las URL propuestas se distinguen de las rutas que efectivamente aparecen en las tablas.

El show registra 7 clics/322 impresiones, posición 9,29; su tabla de 28 días concilia exactamente. La ventana anual equivalente de 2025 registra 2/111, posición 7,79, en el host con www. El cambio de host, la muestra pequeña y el dato final no confirmado limitan esa comparación. La ausencia en las capturas SERP previas sólo se refería a los resultados devueltos en ellas: no se puede convertir en «no tiene visibilidad». Se mantiene el 301 aprobado desde el lanzamiento, condicionado a conservar contenido y disponer del destino. Su canónica elegida por Google sigue pendiente.

### Ads: estado configurado, actividad y medición

El estado actual reportado **no reproduce «No apta»**. Sin historial de cambios no se conoce cuándo cambió ni por qué no hay actividad. Las consultas recientes W1/W0 devolvieron ceros explícitos a nivel cuenta; la campaña no devolvió filas. La última actividad declarada es el **27 de febrero de 2026**; del 1 de marzo al 3 de noviembre no hay filas de campaña. No se declara resuelto el problema de entrega.

Los ajustes leídos son **S/7,77 diarios**, MANUAL_CPC, Perú, PRESENCE_OR_INTEREST. Son configuración observada, distinta del plan documental con máximo S/100 al mes y foco en Lima. **No se acredita que ese plan ya esté aplicado.** Se registra la discrepancia para verificarla antes de cualquier activación o cambio, sin modificar presupuesto ni segmentación.

El histórico dic 2025-feb 2026 mantiene 150 clics y S/132,26. Las 12 conversiones son la acción **«Vista de una página», categoría PAGE_VIEW, fuente WEBPAGE**. S/11,02 es costo por esa conversión registrada, no costo por contacto; 8 % es la tasa respecto de clics de esos eventos, no una tasa de leads. Se desconoce su disparador, atribución, carácter principal/secundario y si existen otras acciones configuradas sin eventos. No se atribuye la acción a `/gracias/`, WhatsApp o formulario.

El informe aporta términos históricos de cobertura/filmación, estudio y bodas que no aparecen en la extracción GSC. Por tanto, «sin filas GSC» no equivale a «sin ninguna evidencia propia». Tampoco una búsqueda pagada histórica prueba demanda actual o rentabilidad. La consulta inglesa de streaming requiere verificar keyword activadora, idioma y localización antes de interpretarla como oportunidad local. Todos los anuncios publicados en el informe usan la home con www; no hay datos de rendimiento de futuras landings.

### Límites técnicos que permanecen

- El vacío 20 nov 2025-14 jul 2026 está descrito como **237 días sin filas**, no como ceros medidos. La causa, incluido el posible bloqueo de bots, permanece pendiente.
- No hay Inspección de URL: no se confirma indexación actual, canónica elegida por Google, último rastreo ni restricciones. Las etiquetas HTML reportadas tienen origen/frescura no documentados y no sustituyen esa inspección.
- La respuesta de sitemaps «No data during this period» no prueba que no existan sitemaps.
- Las consultas publicadas son una selección. No se interpreta una fila omitida, un `null` ni una familia no consultada como ausencia de demanda.

## 4. Conciliación y correcciones del aporte

Las diferencias siguientes se registran sin editar el PDF ni descartar los totales que sí concilian. Las posibles causas no comprobadas se mantienen como pendientes.

| ID | Ubicación | Punto | Corrección o tratamiento |
|---|---|---|---|
| Q01 | p. 10, punto 7 | 38 % de clics GSC | Son 38/92 = 41,30 %. Las 12 consultas con clic suman 54/92 = 58,70 %; no se identifica la causa exacta de lo no atribuido. |
| Q02 | pp. 1-3 | Suma de impresiones por URL | H: 6.738 frente a 6.535 (+203); W1: 2.033 frente a 1.920 (+113); W0: 1.613 frente a 1.592 (+21). Conservar agregados por separado; causa sin verificar. |
| Q03 | pp. 3-4 | Cobertura y períodos | W1/W0 sí son ventanas contiguas de 28 días. H tiene 90 días y comparte 25 con W1; H no es el período anterior equivalente. |
| Q04 | pp. 2, 4 | Consultas seleccionadas | Se reportan unas 170 consultas recuperadas, pero el PDF no las entrega todas. La nota de 10 filas por columna de home es inexacta: reciente 10, histórica 12. |
| Q05 | p. 6 | URL por dispositivo incompleta | Show: 5/7 clics y 196/322 impresiones; faltan 2 y 126. Home: 21/31 clics. Excluir esos repartos; los totales por dispositivo de propiedad sí cuadran. |
| Q06 | p. 7 | Impresiones Ads | Diario/mensual: 1.347; grupo/dispositivo/anuncio: 1.350. Diferencia 3. CTR respectivo 11,14 % y 11,11 %; no mezclar denominadores. |
| Q07 | p. 7 | Costo Ads mensual | 24,67 + 65,69 + 41,89 = S/132,25 frente a S/132,26. Posible redondeo; no demostrado sin importes originales. |
| Q08 | p. 8 | Términos Ads incompletos en el PDF | 30 filas: 76 clics/S/61,00. Se declaran 38 términos: 84 clics/S/67,69; faltan 8 filas para comprobar ese subtotal. La campaña registra 150 clics/S/132,26. |
| Q09 | p. 8 | Conversiones por término | Las 30 filas muestran 4; la nota de «filmaciones» aporta la quinta. Tabla más nota explican 5/12; no son contactos. |
| Q10 | pp. 8-9 | Cobertura de keywords Ads | Tablas: 1.293 impresiones frente a 1.350 por grupos. G1 847/868, G2 404/405, G3 42/77: faltan 57. Clics y gasto sí cuadran (150/S/132,26). Causa sin confirmar. |
| Q11 | pp. 7, 9-10 | Fecha de última actividad Ads | Última actividad: 27 feb 2026. Evitar «sin actividad desde el 27» inclusivo; el informe declara expresamente sin filas del 01 mar al 03 nov. |
| Q12 | pp. 6, 9 | Ausencia y causación | Filas ausentes no son ceros medidos. PAGE_VIEW no prueba leads. Una sola acción con eventos no equivale a una sola acción configurada. |
| Q13 | pp. 7-9 | Configuración frente a histórico | ENABLED/PAUSED/REMOVED son estados observados ahora; sin historial no se atribuyen a la fecha de cada clic. D4 no imprime una ventana específica de términos. |

Octubre del traspaso termina el día 29: 37 clics/2.057 impresiones. El aporte incluye hasta el 31: 40/2.168. Los 3 clics y 111 impresiones adicionales corresponden a una ventana ampliada; no son una contradicción del corte original. Las consultas/keywords/URLs y sus variantes no se suman entre diferentes tablas como si fueran personas distintas. Tampoco se imputan los clics o conversiones ocultos a servicios.

## 5. Matriz complementaria de las 37 páginas

Se mantiene la cobertura exacta de fase 3 y de la matriz inicial de fase 4. Cada evidencia se atribuye a su origen (home, legado, término pagado o familia). «Sin cambio» conserva todos los pendientes originales. Las recomendaciones son provisionales y no constituyen fase 5 ni una orden de publicación.

| Página propuesta o recurso | Evidencia añadida | Hipótesis confirmada, descartada o pendiente | Recomendación provisional | Verificación residual |
|---|---|---|---|---|
| / | Home sin www: 31 clics/1.599 impresiones en W1, frente a 18/1.482 en W0. «productora audiovisual»: 9/139, posición 7,04 en W1. Los tres anuncios declaran como destino la home con www; no se probó aquí su redirección. [E01, E02, E03, E07, E08] | Confirmada documentalmente la atribución reciente de consultas de productora a la home. No confirma host canónico ni la mejor arquitectura futura. | La evidencia refuerza preservar el foco y las consultas de productora; incorporar agencia/empresa según los usos y casos acreditados. | Inspección de ambos hosts y /index.html; distinguir consultas de marca; equivalencia y medición del destino futuro. |
| /servicios/ | En H, «productora audiovisual servicios» registra 119 impresiones y 0 clics en la home; «servicios de productora audiovisual», 82/0. No son datos del hub futuro. [E03] | Confirmada presencia histórica de consultas de servicios. Separar hub y pilar sigue pendiente; no hay prueba de canibalización. | Mantener la función provisional de catálogo por necesidades y revisar reparto de consultas junto con las SERP ya investigadas. | Función comercial del hub frente al pilar, enlaces y contenidos reales; seguimiento cuando se publiquen las nuevas rutas. |
| /servicios/produccion-audiovisual/ | En H, consultas de producción/servicios aparecen en la home. /video.html tiene 0/28 en W1; la consulta de marca publicada explica 8 impresiones. Ads muestra «produccion de video»: 11 clics, S/1,54 y 3 conversiones PAGE_VIEW históricas. [E03, E08] | Confirmada evidencia histórica de búsquedas y clics pagados de producción; intención comercial y contratación pendientes. Cobertura parcial de consultas de /video.html y equivalencia del nuevo pilar pendiente. | Conservar la definición de entregables y la correspondencia con el contenido legado; usar el lenguaje de producción sin confundirlo con clientes captados. | Exportación completa de consultas, intención de las restantes impresiones, alcance/entregables y destino de /video.html. |
| /servicios/video-corporativo/ | En H, la home recoge «productora de videos corporativos»: 66 impresiones, posición 73,64 y 0 clics; otras variantes también tienen 0 clics. Ads muestra «servicio de videos corporativos»: 2 clics, S/0,57, 0 conversiones. [E03, E08] | Confirmada visibilidad histórica propia para esta familia y clics pagados históricos. Pendiente potencial actual y keyword principal. | Reforzar la hipótesis comercial con usos, ejemplos y entregables; contrastar la variante de servicio antes de cerrar el mapa. | SERP de «servicio de videos corporativos», datos recientes por familia y permisos/rol de Redinter. |
| /servicios/cobertura-de-eventos/ | GSC no devuelve filas de la familia en H. Ads sí muestra «filmaciones de eventos» (4 clics, S/6,88), «servicio de grabacion de eventos» (2, S/3,08) y «filmación de eventos» (2, S/3,00); todos con 0 conversiones registradas. [E03, E08] | Descartada la inferencia de que no existe evidencia propia por no haber filas GSC. Confirmado lenguaje histórico de búsqueda pagada; demanda actual y exclusividad B2B pendientes. | Mantener la prioridad del dueño y contrastar filmación/grabación/cobertura; no restringir a corporativo por estos términos sin calificadores. | SERP de variantes, consultas recientes, paquetes, roles de Premium/Bloom y registros de contactos reales. |
| /servicios/streaming-y-podcast/ | GSC histórico en home: «productora de streaming» 68 impresiones/0 clics, «productora streaming» 71/0 y «productora audiovisual streaming» 66/0. Ads: «live video streaming production», 21 clics/S/4,27/1 PAGE_VIEW. Podcast sin filas GSC. [E03, E08] | Confirmada señal histórica de streaming. El término inglés no demuestra demanda local cualificada ni identifica la keyword activadora. Separación de podcast pendiente. | Conservar bloques diferenciados de emisión y episodios, como en la matriz inicial; usar Ads como pista de vocabulario. | Keyword que activó el término inglés, idioma/ubicación efectiva, oferta y muestras de podcast, decisión de una o dos URLs. |
| /servicios/catering-corporativo/ | Sin filas GSC de catering/coffee break en H; el PDF no añade términos Ads para esta oferta. [E03] | Pendiente evidencia propia; no se descarta la oportunidad ni se cambia la prioridad del dueño. | Conservar la recomendación de fase 4 basada en las SERP y oferta confirmada. | Capacidades, mínimos, menús, operación y relación editorial con coffee break; permanecen los pendientes originales. |
| /servicios/organizacion-de-eventos/ | GSC sin filas de la familia en H. La keyword configurada «organización de eventos en lima» figura con 1 clic/S/1,43; no se publicó su término activador. [E03, E08] | Confirmada presencia histórica como palabra clave configurada; no prueba qué buscó la persona ni la intención real de esa visita. | Mantener la distinción entre organización y registro audiovisual. | Término activador, consulta de proveedor, roles contractuales y oferta operativa; no sumar keywords a términos como usuarios distintos. |
| /servicios/estudio-fotografico/ | GSC sin filas de la familia en H. Ads: «foto studio», «estudio fotografico» y «estudio fotografico lima» tienen 1 clic cada uno y S/2,53, S/2,46 y S/2,25; 0 conversiones. Grupo 3 actualmente PAUSED. [E03, E08] | Confirmada evidencia histórica pagada de estudio; no valida demanda actual, rentabilidad ni alquiler a terceros. | Mantener sesiones en estudio y diferenciar alquiler según oferta real; conservar las variantes exactas como pistas. | Dirección/atención, modalidades, permisos, rendimiento reciente y SERP/volúmenes de las variantes pendientes. |
| /servicios/fotografia-y-video-de-bodas/ | GSC sin filas de bodas en H. Ads incluye «fotografos para bodas»: 1 clic/S/1,65/0 conversiones. [E03, E08] | Confirmada una señal pagada histórica mínima de bodas; no permite dimensionar mercado ni extrapolar a quinceañeros. | Conservar la propuesta social y su portafolio específico, sin alterar las prioridades B2B. | Muestras autorizadas, paquetes, SERP de quinceañeros y evidencia de contactos. |
| /servicios/alquiler-de-pantallas-led/ | Sin filas GSC para la familia LED/sonido en H; no se aporta evidencia Ads específica. [E03] | Sin cambio de hipótesis: la evidencia SERP previa se conserva; rendimiento propio pendiente. | Conservar especificaciones y factores de cotización provisionales. | Inventario, pitch, montaje, operador, condiciones y contraste móvil/temporal de fase 4. |
| /servicios/spots-publicitarios/ | Home en H: «productora de comerciales» 62 impresiones/posición 29,74; «productora comerciales» 76/27,89; «productora para comerciales» 80/17,45; «productora de spots lima» 1/37. Todas con 0 clics. [E03] | Confirmada visibilidad histórica para variantes de proveedor. No revierte el carácter mixto de las SERP genéricas ni confirma clientes. | Reforzar la comparación de variantes de proveedor y conservar la definición de versiones y derechos. | SERP local de proveedor, consultas recientes y clasificación real del caso Adidas. |
| /servicios/animacion-y-motion-graphics/ | El PDF no publica una extracción específica de esta familia ni términos Ads identificados para ella. [E03] | Pendiente; no equivale a una consulta completa con cero resultados. | Sin cambio respecto a fase 4: entregables empresariales, proceso y muestras. | Capacidad 2D/3D, portafolio y variantes locales pendientes de la matriz original. |
| /servicios/drones/ | No hay extracción específica publicada para drones en el aporte. [E03] | Pendiente evidencia propia; no se interpreta como ausencia de demanda. | Mantener el alcance audiovisual provisional ya descrito. | Consultas específicas, muestras, operador, condiciones y verificaciones operativas originales. |
| /servicios/video-y-fotografia-inmobiliaria/ | No se publica desglose propio de inmobiliaria/360 en el aporte. [E03] | Sin cambio: homogeneidad de la familia pendiente. | Conservar opciones por finalidad e inmueble sin atribuirles datos de otras fotografías. | SERP de video inmobiliario, capacidad 360, alojamiento del tour y muestras. |
| /servicios/alquiler-de-sonido-y-proyectores/ | Sin filas GSC para la familia agregada LED/sonido/proyectores en H; sin nuevo término Ads específico. [E03] | Pendiente evidencia propia y conveniencia de agrupar las necesidades. | Conservar secciones por equipo y asistencia provisional. | Catálogo, condiciones, URLs competidoras exactas y alcance del técnico. |
| /servicios/activaciones-btl/ | GSC sin filas para organización/BTL/maestro de ceremonias en H; sin nuevo término Ads de BTL. [E03] | Sin cambio en la hipótesis comercial/informativa de las SERP. | Mantener la explicación de producción y operación acreditadas. | SERP de agencia/producción BTL, casos y recursos reales. |
| /servicios/maestro-de-ceremonias/ | GSC sin filas en la familia agrupada en H; no hay términos Ads específicos publicados. [E03] | Sin cambio; no se descarta contratación por ausencia de filas. | Conservar perfil, video y preparación como propuesta provisional. | Conductor, disponibilidad, condiciones y verificaciones originales. |
| /show-infantil-navideno/ | /show.html sin www tiene 7 clics/322 impresiones/posición 9,29 en W1; W0: 2/105/9,35. Los 28 días publicados suman 7/322. «show navideño»: 3/104/9,33 en W1. La URL propuesta no tiene estos datos propios. [E02, E04, E05] | Confirmado rendimiento reciente reportado del legado; descartada la inferencia de ausencia de visibilidad por no aparecer en una captura SERP. Canónica y conservación en destino futuro pendientes. | Refuerza preservar contenido y términos del legado durante el 301 ya autorizado para el lanzamiento; no cambia el momento aprobado. | Inspección de ambos hosts, datos finales de W1, integridad del contenido y prueba del 301 cuando exista destino; no usar el reparto URL×dispositivo incompleto. |
| /fiesta-de-fin-de-ano-para-empresas/ | Sin filas GSC para fiesta empresarial/catering/saludos navideños en H; sin evidencia Ads específica publicada. [E03] | Pendiente evidencia propia; el show infantil no valida la demanda de fiesta corporativa. | Mantener las necesidades diferenciadas y la oferta provisional de fase 4. | Capacidad/fechas/paquetes y consulta específica de producción de video de saludo. |
| /servicios/fotografia/ | /fotografia.html sin www: 0/21 en W1. Consultas publicadas: marca 7 impresiones y «fotografia y video corporativo lima» 1 impresión/posición 57. No es rendimiento de la URL futura. [E02, E03] | Confirmado desglose parcial del legado; una impresión no valida una keyword principal ni el destino definitivo. | Conservar el contraste de productos/servicio y la delimitación de sesiones. | Consultas completas, SERP móvil, oferta/muestras y equivalencia con estudio; no tratar filas omitidas como cero. |
| /servicios/fotos-corporativas/ | Única señal afín publicada: «fotografia y video corporativo lima», 1 impresión en /fotografia.html, posición 57; no identifica retratos LinkedIn. [E03] | Pendiente evidencia propia específica de retratos. | Sin cambio en entregas y modalidades provisionales; evitar presentar la señal afín como prueba del subservicio. | Oficina/set, muestras, permisos y SERP específica de LinkedIn/móvil. |
| /servicios/marketing-digital/ | /marketing.html: 0/15 en W1; marca explica 6 impresiones. H incluye «reno online marketing»: 3 impresiones/posición 61,33. [E02, E03] | Confirmada atribución parcial de consultas al legado; no demuestra demanda comercial reciente de marketing. | Conservar alcance y equivalencia de branding/publicidad con oferta vigente. | Consultas completas, principal exacta del mapa, casos y prestaciones reales. |
| /servicios/desarrollo-web/ | /web.html: 0/20 en W1; marca 5 impresiones y «nr diseño web» 3/posición 62,67. [E02, E03] | Confirmada atribución parcial del legado; rendimiento comercial de una nueva página pendiente. | Conservar definición de entregables, propiedad y soporte sin trasladar plazos antiguos automáticamente. | Vigencia de paquetes, casos, consulta exacta principal y equivalencia de la redirección. |
| /precios/ | Home en H: «productora audiovisual precios», 68 impresiones/0 clics/posición 33,75; «precios productora audiovisual», 1/0/41. Ads incluye «precio de filmacion de eventos»: 1 clic/S/1,55/0 conversiones. [E03, E08] | Confirmada señal histórica propia de precios. URL independiente sigue pendiente; no aporta tarifas de Rhino. | Mantener backlog y factores de cotización sin crear ni publicar una nueva página. | Oferta, preguntas reales, datos recientes y relación con contenido de servicios. |
| /blog/ | No se publican consultas propias por artículo ni pruebas nuevas que resuelvan los temas editoriales pendientes. [E03] | Sin cambio: apoyo editorial parcial. | Conservar las hipótesis de utilidad y FAQs de fase 4, sin crear slugs. | SERP y preguntas de clientes pendientes de la matriz original. |
| /portafolio/ | El informe no añade datos por caso ni autorización de materiales; las 12 conversiones Ads son PAGE_VIEW. [E03, E09] | Atribución y eficacia de los casos pendientes; visitas no prueban resultados comerciales. | Conservar pruebas por contribución documentada. | Permisos, entregables y trazabilidad de resultados. |
| /portafolio/redinter-25-anos/ | No se publica evidencia nueva específica de este caso. [E03] | Sin cambio; el aporte no resuelve atribución ni resultados. | Conservar la recomendación provisional de la matriz inicial. | Material, fecha, autoría, contribución y autorización. |
| /portafolio/premium-tasting-lima/ | No se publica evidencia nueva específica de este caso. [E03] | Sin cambio; el aporte no resuelve atribución ni resultados. | Conservar la recomendación provisional de la matriz inicial. | Contrato/brief, cobertura, rol organizativo y permiso. |
| /portafolio/bloom-of-colors/ | No se publica evidencia nueva específica de este caso. [E03] | Sin cambio; el aporte no resuelve atribución ni resultados. | Conservar la recomendación provisional de la matriz inicial. | Rol, entregas, material y aprobación. |
| /portafolio/heroe-adidas/ | No se publica evidencia nueva específica de este caso. [E03] | Sin cambio; el aporte no resuelve atribución ni resultados. | Conservar la recomendación provisional de la matriz inicial. | Canales, derechos, alcance y clasificación según uso real. |
| /nosotros/ | No hay nueva evidencia de equipo, trayectoria ni identidad. [E03] | Sin cambio; experiencia acreditada pendiente. | Conservar personas y trayectoria verificable como requisitos. | Personas, fechas, cargos y fotografías. |
| /contacto/ | Las 12 conversiones registradas pertenecen a «Vista de una página»/PAGE_VIEW. No se acredita recepción de formulario, llamada o WhatsApp. [E09] | Confirmada insuficiencia de esta métrica para probar contactos. No queda probado que no existan acciones configuradas con cero eventos. | Conservar la necesidad de verificar recepción y distinguir interacción, contacto recibido y lead cualificado. | Configuración de acciones, eventos disparadores, prueba de recepción y deduplicación; no se realizaron envíos. |
| /gracias/ | El conector no informa qué URL o evento dispara «Vista de una página». [E09] | Pendiente; no puede atribuirse esa conversión a /gracias/ ni probar un envío. | Conservar confirmación condicionada a aceptación y exclusión del sitemap. | Disparador, acceso directo, recarga, deduplicación y entrega efectiva. |
| /politica-de-privacidad/ | El aporte no añade información sobre tratamiento de datos ni contenido de privacidad. [E09] | Sin cambio; no se concluye cumplimiento a partir de métricas. | Conservar la preparación del texto según responsable y flujo real. | Proveedores, tratamiento y revisión competente. |
| 404 (plantilla; URL no especificada) | Adzviser no suministra Inspección de URL ni pruebas HTTP de rutas futuras. [E05] | Sin cambio; comportamiento de la plantilla pendiente. | Conservar HTTP 404 y navegación útil previstos. | Pruebas de rutas inexistentes en el hosting de destino. |
| /Brochure.pdf | Ruta sin www: 0/13 en W1, posición 4,69; marca 5 impresiones. En H: 0/30 sin www y 0/2 con www. No hay medición de descargas en el aporte. [E02, E03, E05] | Confirmada visibilidad reportada del PDF; no acredita descargas, contactos o actualidad del contenido. | Conservar ruta exacta y separar descarga de contacto, como en fase 4. | Inspección, enlaces, actualización, permisos y medición de descargas. |


## 6. Estado de los pendientes tras incorporar el PDF

| Pendiente anterior | Estado actualizado | Qué falta exactamente |
|---|---|---|
| Acceder a GSC/Ads desde Claude | Resuelto documentalmente mediante el aporte de la sesión del usuario | Respuestas brutas y parámetros para reproducibilidad; no es necesario repetir todo el cuestionario |
| Reproducir corte histórico de GSC | Confirmado en el informe: 92/6.535 | Exportación para conciliar diferencias entre agregaciones |
| GSC reciente por URL, consulta, país y dispositivo | Parcialmente resuelto | Finalización de W1, consultas completas y fallo de URL×dispositivo |
| GSC actual del show | Resuelto para totales reportados y tabla diaria W1 | Canónica, dato final de W1 y reparto por dispositivo |
| Estado actual de Ads | Nueva observación ENABLED/ELIGIBLE/SERVING | Historial y explicación de falta de actividad; no declarar resuelta la entrega |
| Conversiones históricas y términos Ads | Resuelto parcialmente | Configuración de acciones, términos omitidos, keyword activadora y contacto real |
| Causa del vacío, indexación y canónica | Pendiente | Inspección de URL y evidencia histórica del hosting; Adzviser no las aporta |
| Sitemaps e identificador de propiedad | Pendiente | Consulta directa en Search Console o recurso que exponga esos datos |
| Arquitectura, oferta, casos y equivalencia de redirecciones | Conserva conclusiones provisionales | La evidencia nueva no verifica capacidades, permisos ni implementación futura |

Los siguientes pasos de verificación dentro de fase 4 pueden concentrarse en tres bloques, sin repetir la extracción completa:

1. **Conservación y conciliación de las respuestas:** exportaciones existentes de Adzviser con parámetros, fechas y filas completas; recuperar los 38 términos Ads, aclarar rango D4 y conservar importes sin redondear. Separar revisiones de datos de nuevas consultas pagadas.
2. **Diagnóstico Ads aún no consultado:** historial disponible de campaña, keyword que activó cada término relevante (sobre todo inglés y posibles marcas ajenas), idiomas y configuración completa de conversiones si otra interfaz los expone. Si la retención impide llegar a marzo, registrar el límite; no inferir la causa de inactividad.
3. **Verificaciones que Adzviser no resuelve:** propiedad exacta e Inspección de URL de ambos hosts de home/show y de rutas legado, sitemaps, evidencia del vacío y prueba de recepción de contactos. Son pendientes específicos; no requieren rehacer la investigación SERP.

Esta adenda deja incorporado el aporte y actualizadas las hipótesis con sus límites. La evidencia externa de fase 4 queda entregada con verificaciones residuales explícitas; no se declara resuelta toda condición de publicación, ni se avanza a fase 5.

## 7. Archivos y control de conservación

- [Datos y cálculos del aporte](aporte-adzviser/evidencia-adzviser.json).
- [Matriz con las 37 filas originales y sus complementos](aporte-adzviser/matriz-fase4-con-adenda.json).
- [Verificación de integridad y cobertura](aporte-adzviser/verificacion-adenda.json).
- [Texto del PDF y referencia de páginas](aporte-adzviser/pdf-text.txt).

Los documentos originales del proyecto, el PDF suministrado y los informes iniciales de fase 4 se conservan. La verificación compara hashes de los 40 archivos de la instantánea de fase 3 y de los artefactos previos protegidos. Esta adenda es el registro actualizado que debe acompañar al traspaso; no se edita `docs/seo/00-traspaso.md` por la instrucción del usuario de conservar originales.

SHA-256 del PDF fuente: `d070db1959cce0715a294dd502765130962f114bc8532926beb13c325651c181`.

Incorporación verificada en hora Lima: `2026-11-03T21:31:40.706589-05:00`.
