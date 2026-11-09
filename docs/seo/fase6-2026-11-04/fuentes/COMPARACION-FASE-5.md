# Comparaciones íntegras de fase 5

Sesiones limpias A y B. Respuestas conservadas sin corregir retroactivamente. Las resoluciones editoriales posteriores y la evidencia exacta que prevalece están en el informe final, sección 7. No interpretar toda frase del comparador como hecho comprobado.


## Componente A


### pipeline


core

### coincidencias


- Cobertura: ambas tablas tienen exactamente 37 filas únicas (33 HTML, /precios/, /blog/, /Brochure.pdf y la plantilla 404), sin la fila colectiva de 301 que Claude añadía en F3. Demostrado por conteo de las dos tablas recibidas.

- Protección antes de publicar (P0, verificación y no defecto): / con /index.html, /show-infantil-navideno/ con el 301 desde el lanzamiento y el texto de L07, /Brochure.pdf en su URL exacta sin barra ni 301, /contacto/, /gracias/, 404 y política de privacidad. Ninguno revierte decisiones del dueño ni elige hosting o dirección visual.

- Host canónico no_verificado: AD E05 url_inspection es null. Según G5-INS, la canónica elegida por Google se consulta en los datos indexados y la prueba en vivo no la predice. Ninguno la deduce del tráfico ni del HTML.

- Rendimiento propio reportado (AD E02/E04, W1 05 oct–01 nov 2026): la home tiene 31 clics y 1.599 impresiones; /show.html, 7 clics y 322 impresiones en posición 9,29. Los demás legados no tienen clics en W1. Ambos lo usan como reporte de cuenta y no como acceso propio en vivo.

- Medición: las 12 conversiones son PAGE_VIEW (AD E09) y no acreditan contactos. /gracias/ debe contar solo un envío aceptado, deduplicado, y no contar el acceso directo ni la recarga (F3 C10).

- Las prioridades del dueño (cobertura, streaming/podcast, catering) siguen en la tanda A y en P1. La ausencia de filas GSC no se trata como demanda cero (Q12).

- LED: ambos proponen «alquiler de pantallas led» como principal y dejan «pantalla led para eventos» como variante, con la SERP S022/S023 que mezcla alquiler y venta. Ambos piden alinear la meta 06:372 con el [VALIDAR] de 06:374.

- Metas que prometen alcance sin validar (F3 C04, demostrado en los documentos): LED, sonido (06:382 frente a 06:384) y fotos corporativas (06:343 frente a 06:347).

- Casos: se atribuye solo el rol acreditado. Se corrige Premiun a Premium. Héroe Adidas no se clasifica automáticamente como spot. No se usan métricas del JSON de prueba.

- Se mantienen las agrupaciones streaming/podcast, sonido/proyector, catering/coffee break e inmobiliaria/360. Solo se dividirían con oferta diferenciada y SERP propia; compartir dominios no prueba canibalización.

- El destino de /fotografia.html depende de que el estudio salga en la tanda A (00 §9.2). Las sesiones van al estudio y los retratos a fotos corporativas.

- /precios/ y /blog/ quedan en P2, sin slugs. Los factores de cotización van primero dentro de cada servicio.

- Criterios G5 respetados: no hay resultados enriquecidos de FAQ desde el 7 de mayo de 2026 (G5-FAQ), no hay estrellas para las reseñas propias (G5-REV) y no hay mínimo de palabras (G5-CONT). El límite 60/155/un H1 es convención local.

- Ninguno trata ENABLED/ELIGIBLE/SERVING (ajustes observados el 3 nov) como actividad ni da «No apta» por estado actual probado.

### discrepancias


**punto:** Escala común

**claude:** Usa valores intermedios (Medio-alto, Bajo-medio, «Alto potencial, condicionado», Media-alta) y urgencias divididas en una misma celda.

**codex:** Usa solo alto/medio/bajo y una urgencia por fila; las verificaciones van en la columna de dependencias.

**evidencia:** Restricción del paquete: escala común alto/medio/bajo y P0/P1/P2.

**resolucion:** Se normaliza a la escala común. Cuando Claude divide la urgencia, la parte P0 se expresa como verificación concreta en Dependencia y el contenido conserva P1 o P2. Es un ajuste de formato, no de fondo.


**punto:** /servicios/produccion-audiovisual/: impacto y confianza

**claude:** Impacto medio; P0 para la equivalencia y P1 para el resto; confianza media.

**codex:** Impacto alto, P0, confianza alta.

**evidencia:** AD E02: /video.html 0 clics y 28 impresiones en W1. AD E08: «produccion de video», 11 clics pagados y 3 PAGE_VIEW históricos (no son leads). La equivalencia con L03 está pendiente (F4).

**resolucion:** Impacto medio: el legado no tiene clics y el ahorro pagado no acredita leads. P0 solo para la equivalencia con L03 y el 301→200. Confianza alta para conservar y condicionar; media para la keyword principal.


**punto:** /servicios/video-corporativo/ y /servicios/streaming-y-podcast/: impacto

**claude:** Medio en ambas (streaming: «prioridad 2; demanda medida baja»).

**codex:** Alto en ambas.

**evidencia:** Video: 66 impresiones en posición 73,6 en la home y 2 clics pagados (AD E03/E08). Streaming: K003 10; 00 §5.1 «demanda mínima»; S5 en pausa. Las variantes de streaming están en posición 53–58, el rango que 00 §3.7 #2 asocia a herramientas de seguimiento.

**resolucion:** Impacto medio en captación medible. La prioridad 2 del dueño se respeta con la tanda A y P1, sin rebajar el servicio. Las variantes en posición mayor de 30 son pistas con esa salvedad, no demanda.


**punto:** /servicios/catering-corporativo/: urgencia

**claude:** P1, y P0 antes de publicar afirmaciones sanitarias; confianza media.

**codex:** P1 con revisión competente de requisitos; confianza alta.

**evidencia:** 00 §14: permisos sanitarios pendientes del dueño. Las SERP S012/S052 confirman contratación corporativa.

**resolucion:** Se adopta la división de Claude: P0 de verificación solo para cualquier afirmación de permisos o requisitos sanitarios; el resto, P1. Confianza alta para la intención y media para capacidades y menús.


**punto:** /servicios/fotografia/: impacto

**claude:** Medio; confianza media para el destino y baja para la keyword.

**codex:** Alto; confianza media.

**evidencia:** AD E02: /fotografia.html 0 clics y 21 impresiones en W1. S015 es mayoritariamente educativa.

**resolucion:** Impacto medio. P0 para decidir y probar el destino del 301; P1 para la keyword, con confianza baja-media.


**punto:** /servicios/estudio-fotografico/: urgencia y confianza

**claude:** P1 (afecta al P0 de /fotografia.html); confianza media; cita 2.900/260 como no reverificado.

**codex:** P0; confianza alta.

**evidencia:** La dirección y la atención presencial no se conocen (00 §14). F4 deja sin verificar los volúmenes exactos. El estudio está confirmado por el dueño (CLAUDE.md).

**resolucion:** P0 solo para decidir si sale en la tanda A, porque eso fija el 301 de /fotografia.html. El contenido de la página va en P1. Confianza media. El negocio no se cuestiona.


**punto:** /servicios/alquiler-de-pantallas-led/: impacto

**claude:** Alto; confianza media-alta.

**codex:** Medio; confianza alta.

**evidencia:** 00 §8 #6 y §12.1: ~450–550 de volumen comercial (0,94) y una estimación de 20–40 visitas (no es promesa). F4: «competencia orgánica débil: pendiente».

**resolucion:** Impacto alto, porque es de las oportunidades documentales más sólidas. Confianza media-alta: la competencia débil y el inventario siguen pendientes.


**punto:** /servicios/marketing-digital/ y /servicios/desarrollo-web/: variante e impacto

**claude:** Marketing: variante «agencia de marketing digital lima» (S024); impacto bajo. Web: «diseño de páginas web en lima» (título legado); impacto bajo.

**codex:** Marketing: «gestión de redes sociales Lima»; impacto medio. Web: variante Lima o landing corporativa; impacto medio.

**evidencia:** F4 describe S024 como «variante con Lima» de la principal y deja pendiente la «principal sin Lima». El paquete no muestra que S024 sea «agencia de marketing digital lima». 00 §3.6 confirma el título legado de web. AD E02: 0/15 y 0/20 en W1, explicados en parte por la marca.

**resolucion:** Marketing: la variante de Codex es la mejor respaldada; la de Claude es una sospecha no documentada. Web: la variante de Claude tiene base. Impacto bajo en ambas, con P0 solo para el destino y la equivalencia del 301.


**punto:** /servicios/spots-publicitarios/: candidata principal

**claude:** Valorar «productora de comerciales/para comerciales» como principal y dejar «productora audiovisual publicidad» en la home.

**codex:** Candidata «producción de spots publicitarios», con productora de comerciales y video publicitario como variantes.

**evidencia:** AD E03 (H): «productora para comerciales» 80 impresiones en posición 17,45; «productora comerciales» 76 en 27,89; «productora de comerciales» 62 en 29,74; todas con 0 clics. El paquete no aporta evidencia para «producción de spots publicitarios». S026 (video publicitario) es de recursos y tutoriales.

**resolucion:** La candidata de Claude tiene visibilidad documental; la de Codex, ninguna citada. Ninguna se fija: se contrasta con una SERP local fechada. Se mantiene P2 para la página y P1 para la decisión del mapa.


**punto:** /servicios/maestro-de-ceremonias/: variante de contratación

**claude:** Principal recomendada: la variante «para eventos», atribuida a S036.

**codex:** Principal provisional: «maestro de ceremonias en Lima»; «para eventos corporativos» como variante.

**evidencia:** F4: «S036 ofrece perfiles locales y directorios… variante local null»; «Variante local con contratación: confirmada».

**resolucion:** S036 respalda la variante local (Lima), no «para eventos». Se adopta la de Codex y «para eventos» queda por validar. Coinciden en que «responder primero cuánto cobra» no tiene respaldo como orden (F3 C01).


**punto:** /servicios/cobertura-de-eventos/: variantes

**claude:** Añade «foto y video para eventos»; confianza media-alta; unificar el H1 (06:96 frente a 03:150).

**codex:** Variantes filmación/grabación de eventos; confianza alta.

**evidencia:** 00 §4.3: «servicio de fotografía y video para eventos», 31 clics y la keyword con más gasto. Sus conversiones son PAGE_VIEW. F3 registra la diferencia de H1.

**resolucion:** Se incorpora la aportación de Claude como variante por validar; los clics pagados no prueban leads. Unificar el H1 es P1.


**punto:** Especialidades de la tanda B (animación, drones, inmobiliaria, BTL, bodas): impacto

**claude:** Bajo en general; drone: video con drone o tomas aéreas.

**codex:** Medio; drone: «servicio de drone audiovisual».

**evidencia:** Tanda B; SERP educativas o mixtas (S027, S029–S031, S034); sin extracción GSC propia. 00 §5.1: tomas aéreas 70, comercial 0,86. «Servicio de drone audiovisual» no aparece como consulta medida.

**resolucion:** Impacto bajo; BTL, bajo-medio por el material del brochure (p.26). Para drones se prefieren las variantes de Claude; la etiqueta de Codex describe el servicio, no es una keyword validada.


**punto:** /servicios/alquiler-de-sonido-y-proyectores/: urgencia de la meta

**claude:** P2, con la corrección de la meta en P1.

**codex:** P2 único.

**evidencia:** F3 C04: la contradicción entre 06:382 y 06:384 ya está en la documentación vigente.

**resolucion:** Se adopta la de Claude: corregir la meta antes de cerrar la documentación (P1); la página sigue en P2.


**punto:** /fiesta-de-fin-de-ano-para-empresas/

**claude:** P1 si se publica esta temporada, si no P2; confianza baja.

**codex:** P1; confianza media.

**evidencia:** Sin filas en AD E03; K003 0 (que no significa demanda inexistente); S039–S041 muestran necesidades distintas. Hoy es 4 nov 2026 y la temporada es diciembre. En 00 §11, T2 solo se activa con la página publicada.

**resolucion:** Se adopta la condición temporal de Claude, con confianza media-baja. No se transfiere la visibilidad del show.


**punto:** Los cuatro casos de portafolio: urgencia y confianza

**claude:** P0 para el permiso y P1 para el contenido; confianza media.

**codex:** P1; confianza alta; la autorización figura solo en dependencias.

**evidencia:** 00 §14: la autorización para nombrar a Redinter, Premium, Bloom y Adidas está pendiente. Las páginas son de la tanda A. Que L01 publique los proyectos no sustituye esa autorización.

**resolucion:** P0 como compuerta de permiso antes de publicar (verificación, no defecto) y P1 para el contenido. Confianza alta para condicionar la publicación.


**punto:** /Brochure.pdf, /portafolio/ y privacidad: impacto

**claude:** Brochure bajo-medio, con P0 para el 200 y P2 para la actualización; portafolio medio; privacidad medio.

**codex:** Alto en los tres; Brochure con P0 único que incluye aprobar su vigencia.

**evidencia:** AD E02: PDF 0 clics y 13 impresiones en W1. La URL exacta es decisión del dueño. La actualización del PDF no es requisito de lanzamiento.

**resolucion:** Brochure: impacto bajo-medio, P0 solo para la URL exacta, el 200 y la ausencia de 301; actualización en P2. Portafolio y privacidad: medio; privacidad sigue en P0 antes de activar el formulario.


**punto:** Hallazgos transversales distintos

**claude:** Añade dos: los anuncios declaran la home con www, y el staging combina noindex con bloqueo en robots.txt (sospecha).

**codex:** No los incluye; menciona el noindex legible en /gracias/.

**evidencia:** Adenda de la fila /: la redirección de las URL finales con www no se probó. 00 §11: URL finales sin www. F3 C12 y G5-NOINDEX.

**resolucion:** Se conservan los dos: el de www como no_verificado (corresponde a B/SEM) y el del staging como sospecha. Ninguno es un defecto publicado.


### recomendacion


Se toma la tabla de Codex como base: cumple estrictamente la escala y detalla más las dependencias. Sobre ella se aplican estas correcciones: (1) urgencias divididas de Claude en catering (P0 solo para afirmaciones sanitarias), estudio (P0 solo para decidir la tanda A), sonido (meta en P1), los cuatro casos (P0 como compuerta de permiso), Brochure (P0 para el 200 y P2 para la actualización) y fiesta (condición temporal); (2) impactos según la evidencia reportada: producción, fotografía y video corporativo en medio, LED en alto, marketing, web y las especialidades de la tanda B en bajo; (3) keywords: spots se contrasta con «productora de comerciales», maestro de ceremonias con «en Lima» (S036), cobertura añade «foto y video para eventos» como variante, drones usa tomas aéreas o video con drone, y marketing conserva «gestión de redes sociales Lima». Sin diferencia material: /, /servicios/, organización, show, contacto, gracias, 404, nosotros, bodas, precios y blog. Las variantes en posición mayor de 30 se tratan solo como pistas (00 §3.7 #2). Antes de cerrar el mapa se necesitan SERP fechadas en Perú, con dispositivo declarado. Presupuesto (dato posterior a ambas derivaciones; no se les reprocha no conocerlo): con un techo de S/110 al mes, los nominales del plan dejan de ser objeción: noviembre S/100,80 (S/4,80 diarios × 21 días desde el 10 nov), enero S/102,30 (S/3,30 × 31) y diciembre unos S/99,70 si C1 termina el 22 dic. En cambio, el ajuste observado el 3 nov, S/7,77 diarios con Perú y PRESENCE_OR_INTEREST, supone unos S/233 al mes en nominal (×30) y no coincide con «Lima y Callao por presencia» del plan. No hay gasto demostrado: la campaña no tiene filas desde el 1 de marzo. Si se reactiva, hay que contrastarlo con el plan y lo ejecuta el dueño a mano tras ver una vista previa. El cálculo nominal no garantiza la facturación, y el sobregasto diario permitido no está verificado en las fuentes del paquete. Nada de esto modifica la matriz SEO. El componente B (diagnóstico, plan y dictamen) no viene en este paquete: queda no_verificado y no se supone su contenido.

### riesgos


- Componente B ausente: la comparación del diagnóstico, el plan y el dictamen no se ha hecho; no extrapolar desde A.

- Reactivar la campaña sin ajustar los S/7,77 diarios y la orientación a Perú con PRESENCE_OR_INTEREST podría superar el techo de S/110 y salir de Lima y Callao. Es un riesgo, no un gasto demostrado.

- Fijar keywords principales (spots, maestro de ceremonias, video corporativo, animación) a partir de SERP de una sola fecha y de consultas GSC seleccionadas, no exportadas (Q04).

- Leer las impresiones en posición 30–90 como demanda real (00 §3.7 #2) o los clics y PAGE_VIEW de Ads como leads (E09, Q12).

- Publicar casos con nombres de clientes sin la autorización documentada (00 §14) o metas con alcances aún en [VALIDAR].

- Migrar el show en temporada sin comparar con L07 y sin la inspección de los dos hosts (riesgo aceptado por el dueño; no revertirlo).

- Las fuentes no se releyeron: SERP, HTTP, el PDF y los legados L03–L07 solo constan resumidos en F4.

### confianza


- **nivel:** media
- **motivo:** Las dos matrices y sus fuentes estaban completas en el paquete. Las resoluciones se apoyan en F3, F4, la adenda AD y G5, pero los datos brutos no se pudieron releer y el componente B no estaba incluido. El modo plan pedía un archivo de plan y ExitPlanMode; no se usaron porque el paquete prohíbe herramientas y escritura, y la salida va solo por StructuredOutput, sin cambios.

## Componente B


### pipeline


core

### coincidencias


- Dictamen común: el diagnóstico documental de fase 5 se cierra con reservas. No se declara la web lista, no se aprueba publicar ni activar Ads y no se aprueba la fase 6. Los P0 son condiciones o verificaciones antes de publicar o activar, no defectos de un sitio Astro que aún no existe (supuesto expreso del paquete).

- «No apta» ya no es el estado reportado. E07 (reporte de cuenta, 03 nov) da ENABLED/ELIGIBLE/SERVING sin filas de campaña del 01 mar al 03 nov; la última actividad es del 27 feb (Q11). ELIGIBLE/SERVING no prueba entrega y la causa de la inactividad no se infiere. El requisito «resolver No apta» de 00 §11 y 11 debe reformularse como entrega verificada y configuración conciliada.

- La configuración observada (S/7,77 diarios, MANUAL_CPC, Perú ID 2604, PRESENCE_OR_INTEREST) no coincide con el plan de 11 §3.1–3.2 (Lima y Callao por presencia, presupuesto por período). El plan no consta como aplicado. Ningún cambio sin vista previa y aprobación expresa.

- La medición prevista registra interacciones, no contactos. 07 A.6 define form_submit como carga de /gracias/ e importa brochure_download como conversión; 11 §3.6 pone los clics en WhatsApp y teléfono como conversiones principales. E09: las 12 conversiones son PAGE_VIEW con disparador desconocido. Hace falta probar un envío recibido, la deduplicación y que recargar /gracias/ no genere evento.

- Conflicto real de señales en el sitio antiguo (F4 hallazgo 4, GET del 03 nov): www redirige con 301 a HTTPS sin www, pero el HTML declara canónica www; /index.html responde 200 con el mismo cuerpo que /; el sitemap tiene 7 URLs www, incluye index y omite el show. robots.txt 404 no demuestra bloqueo.

- La canónica elegida por Google y el acceso de Googlebot real no están verificados (G5-INS, E05). Que GSC atribuya los datos a la versión sin www es un dato reportado, no la selección de Google. «Canónica cambiada (confirmado)» en 00 §3.4 es una sobreafirmación.

- El vacío del 20 nov 2025 al 14 jul 2026 son 237 días sin filas, no ceros medidos, y su causa es desconocida (E06). La hipótesis anti-bots sigue sin probar.

- El legado aporta clics recientes, por lo que hay que proteger la home y el show: W1 31 clics/1.599 impresiones en la home sin www y 7/322 (posición 9,29) en /show.html (E02/E04; el carácter definitivo del 1 nov no está confirmado). Se respetan el 301 del show desde el lanzamiento (decisión del dueño) con contenido equivalente a L07 y un solo H1, y /Brochure.pdf en la misma URL.

- 07 A.7 combina noindex con un robots que bloquea; según G5-NOINDEX, Google no podría leer el noindex. Solución: noindex legible por cabecera sin bloquear rastreo, o staging protegido por acceso.

- Datos estructurados: no hay resultados FAQ desde el 7 may 2026 (G5-FAQ); las reseñas propias de Organization/LocalBusiness no dan estrellas aunque sean reales (G5-REV); LocalBusiness exige dirección física; Google no fija número de palabras (G5-CONT). El contrato 60/155/H1 y las 400–700 palabras son reglas locales.

- 07 se contradice: 07 A.2 conserva public/show.html y la decisión es redirigirlo con 301; además habla de 12 servicios frente al catálogo de 00 §10.1.

- Prioridades del dueño: las SERP del 03 nov muestran proveedores para cobertura, streaming, podcast y catering. Que K003 dé 0 o null no anula la prioridad. Streaming y podcast son encargos distintos (S009/S011 sin dominios comunes); su separación en dos URL queda condicionada a la oferta de podcast. Coffee break se mantiene como sección de catering.

- Se descartan como fundamentos: dificultad 0 = competencia débil, nacional = Lima, etiqueta de intención = porcentaje de compradores, sumar variantes como compradores, PAGE_VIEW = lead, y las proyecciones 270–500 visitas / 6–18 consultas como pronóstico. Dominios comunes no prueban canibalización.

- Siguen sin verificar la ficha de Google y las menciones en IA (verificación del 1 nov, no repetida), las modalidades y el set de podcast, la atención presencial del estudio y la atribución de los cuatro casos. El estudio y los negocios confirmados por el dueño no se cuestionan.

### discrepancias


**punto:** Presupuesto SEM: aritmética del plan frente al techo (actualización del usuario posterior a ambas derivaciones)

**claude:** Solo contrasta la configuración observada con el plan: S/7,77 × 30 = S/233 frente a S/100. No evalúa si los totales nominales del propio plan superan el techo.

**codex:** Calcula los totales nominales del plan: noviembre 4,80 × 21 = S/100,80 y enero 3,30 × 31 = S/102,30. Los presenta como desviación sobre el techo de S/100 y recomienda «mantener S/100 como máximo».

**evidencia:** 11 §3.2: noviembre S/4,80 al día con activación el 10 nov (21 días); diciembre 2,70 × 22 + 1,30 × 31 = S/99,70; desde enero 3,30 × 31 = S/102,30. E07: S/7,77 diarios. Mensaje del usuario del 2026-11-04: objetivo de unos S/100 al mes y máximo S/110; sustituye el tope de S/100 sin alterar los originales.

**resolucion:** La aritmética de Codex es correcta, pero la objeción decae: S/100,80, S/99,70 y S/102,30 quedan por debajo de S/110. Ninguno de los dos pares conocía el nuevo techo. Sigue vigente la incompatibilidad de la configuración observada: S/7,77 × 30 = S/233 supera S/110. Es una sospecha de gasto excesivo solo si la campaña llega a entregar. La regla de 11 (lo que queda del mes ÷ días que quedan) debe calcularse con el techo vigente: si se activa antes del 10 nov con S/4,80 al día, por ejemplo el 5 nov, el total nominal sería S/124,80 y superaría S/110. La reasignación del dinero del show a C2 tras el corte del 15 nov tampoco debe superar S/110. Los cálculos nominales no son facturación: el límite efectivo se verifica en la cuenta antes de activar. Esta actualización no autoriza cambios en la campaña.


**punto:** Cobertura de las sobreafirmaciones de 00/11

**claude:** Señala «~800 búsquedas de compra», «competencia débil», «Ads subestima lima», «el más rentable», el horario «validado», Rhino 3.º en el show (no reproducido), los 2.900 de estudio no reverificados y la justificación de S5 por «casi sin búsquedas».

**codex:** Señala además que «la migración elimina el bloqueo» (00 §15), «reseñas = causa de recomendación IA», «gasto bajo = inventario limitado», «lunes–sábado no validado con datos por hora», la concordancia amplia inferida desde estados actuales y que la muestra no demuestra imposible llegar a 5.000 visitas.

**evidencia:** 00 §4.3 (cuota baja con presupuesto sin agotar: se perdía por ranking) frente a §4.6.4 (el límite es el inventario); 00 §15 (la migración lo elimina) frente a E06 (causa desconocida); 11 §1 solo trae franjas horarias, no días de la semana; 11 §3.3 S6 (entraban por concordancia amplia); 00 §5.2 (Bolívar Studio sale por reseñas); K003: «estudio fotográfico en lima» = 10; F4 deja sin verificar las variantes históricas.

**resolucion:** Unir ambas listas: cada punto tiene una fuente que lo contradice o lo limita. Precisiones: la migración reduce un riesgo atribuido al hosting, pero no prueba que elimine una causa desconocida. Con los datos por franja horaria no se puede validar la restricción a lunes–sábado. Reseñas → IA es una correlación observada, no una causa. 2.900 (Perú) y 10 (Lima K003) son geografías y fuentes distintas: el volumen del estudio queda no_verificado, sin negar el negocio. 5.000 visitas al mes: muy improbable según la evidencia de mercado, pero no demostrado imposible. Se conserva como objetivo del dueño.


**punto:** Estado de streaming/podcast

**claude:** Clasifica como «sospecha» el hallazgo de que streaming y podcast son encargos distintos y de que separarlos queda condicionado.

**codex:** Da por demostrado el apoyo comercial a las prioridades, entre ellas streaming y podcast, sin rentabilidad ni arquitectura final demostradas.

**evidencia:** F4 matriz: «Dos encargos diferenciados: confirmada. Conveniencia de dos URLs y estudio propio: pendientes». S009/S011 sin dominios comunes; S010 son guías; CP02/CP03.

**resolucion:** Hay que separar dos niveles. Que son necesidades distintas está demostrado en una captura externa de un solo snapshot. Hacer una o dos URL es una decisión condicionada a la oferta y al set de podcast. La etiqueta «sospecha» de Claude subclasifica la primera parte. Se mantiene una URL agrupada con dos bloques como hipótesis provisional.


**punto:** Cuándo alinear la etiqueta canónica del sitio antiguo

**claude:** Entre las decisiones «recomendables ahora»: alinear la canónica HTML con la redirección 301 (riesgo bajo, decisión del dueño, sin presuponer qué eligió Google).

**codex:** Elegir el host solo con la inspección indexada y la coherencia de señales; no propone cambiar la etiqueta antes.

**evidencia:** 00 §9.2: «Al confirmarlo… en la web actual cambiar la etiqueta canónica a la versión sin www (alinea las señales; riesgo bajo)». G5-INS: la canónica solo se ve en los datos indexados.

**resolucion:** Recomendación condicionada y en secuencia: primero la Inspección de URL (P0, dueño), después alinear la etiqueta con lo que muestre, con aprobación del dueño. Encaja con la secuencia de 00 §9.2 y evita fijar host antes del dato. La alineación sigue siendo de bajo riesgo y puede hacerse la misma semana. Es una recomendación, no se aplica.


**punto:** Granularidad del plan y uso de la escala P0/P1/P2

**claude:** Diecisiete acciones con impacto, urgencia, confianza, dependencia, responsable y cierre. Marca P0 «antes de construir» para corregir 07 (staging, host en 07) y para vigilar GSC a diario.

**codex:** Ocho bloques agrupados (legado, medición, Ads, contrato de producción, vigencia, oferta, keywords, expansión) con responsables y cierres. No incluye la vigilancia diaria de GSC.

**evidencia:** Escala del paquete: P0 antes de publicar o activar; P1 antes de cerrar contenido o documentación; P2 posterior. 00 §15 y §3.7 recomiendan vigilar las impresiones diarias mientras siga el hosting antiguo.

**resolucion:** Usar la granularidad de Claude, que cumple mejor «tabla priorizada con evidencia y cierre verificable», con dos ajustes. (1) Corregir texto de 07 es P1 (documentación); probarlo en staging o en el lanzamiento es P0. «Antes de construir» no es un nivel de la escala. (2) La vigilancia diaria de GSC es mitigación operativa de solo lectura: se incluye como continua (P1) con confianza media, no como defecto. La agrupación de Codex sirve de resumen ejecutivo.


**punto:** Fragmento de redirecciones en 07 A.5

**claude:** No lo señala.

**codex:** El fragmento está incompleto y usa permanent:true, mientras el propio texto exige un 301 explícito.

**evidencia:** 07 A.5: cuatro reglas con permanent:true; /index.html → / en una viñeta; el show se trata aparte; nota: «permanent:true envía un 308… El archivo vercel.json del repositorio usa statusCode: 301». vercel.json no está en el paquete.

**resolucion:** Es una inconsistencia documental menor y demostrada: el ejemplo de 07 no coincide con lo que 07 dice del archivo real y no recoge index.html ni show.html. El contenido real de vercel.json queda no_verificado. Cierre: prueba HTTP real de cada ruta antigua (código 301 y destino 200), coherente con el 301 decidido para el show. Severidad baja, P1 en documentación y P0 en la prueba.


**punto:** Severidad del hallazgo sobre los clics del legado

**claude:** Hallazgo «demostrado» con severidad info.

**codex:** Hallazgo «demostrado» con severidad alta.

**evidencia:** E02/E04: home 31 clics y show 7 clics en W1; Q05 (reparto por dispositivo incompleto).

**resolucion:** No es un defecto, es un activo demostrado según un reporte documental: severidad info es correcta como defecto, pero su protección tiene impacto alto y es P0 al publicar. Ninguno de los dos se contradice en el fondo.


**punto:** Nivel de confianza global

**claude:** Media: alta en errores documentales y en políticas G5; GSC y Ads son un reporte no reconsultado con descuadres Q01–Q13 y una sola tanda de SERP.

**codex:** Alta: alta para corregir la documentación y priorizar verificaciones; media para la arquitectura y baja para el rendimiento futuro.

**evidencia:** Adenda §1 (reporte aportado, sin respuestas API); Q01–Q13; F4 (un snapshot y un solo par escritorio/móvil).

**resolucion:** Confianza global media, con desglose: alta en errores de especificación y políticas, media en arquitectura y priorización, baja en rendimiento comercial y proyecciones. Las dos respuestas dan el mismo desglose; difieren solo en la etiqueta agregada.


**punto:** Desviaciones de proceso declaradas por los pares

**claude:** Declara que el modo plan pedía archivo y herramientas, que prevalece el contrato sin herramientas y que no escribió ningún archivo.

**codex:** Declara un artefacto «created» (codex-B.json en una carpeta temporal fuera del repositorio) y una «validación mecánica del esquema tras escritura»; deviations vacío.

**evidencia:** Restricción del paquete: «No herramientas ni escritura por el par. El anfitrión solo guarda nuevos artefactos de revisión fuera del repositorio».

**resolucion:** Según su propio informe, Codex escribió y validó, y no lo declaró como desviación. Desde aquí no se puede comprobar si fue el anfitrión. No invalida el contenido ni consta cambio en los originales, pero el anfitrión debe registrar quién escribió el artefacto. Claude cumple.


### recomendacion


DICTAMEN CONSOLIDADO (4 nov 2026; las fuentes conservan sus cortes del 01 y 03 nov)
- Fase 5 cierra el diagnóstico documental con reservas.
- Está bien fundada la protección del legado, la medición de contactos reales y la claridad de la oferta en cobertura, streaming/podcast y catering.
- Los errores demostrados son documentales o de especificación (00, 07, 11). Se corrigen en un registro nuevo de vigencia, sin editar los originales.
- No se aprueba publicar, activar Ads ni pasar a fase 6.
- Reservas: canónica elegida por Google y acceso de Googlebot; causa del vacío de 237 días; entrega de Ads y configuración distinta del plan; medición sin probar; oferta, modalidades y permisos; GSC y Ads como reporte documental no reconsultado (Q01–Q13).

PRESUPUESTO VIGENTE (actualización del usuario, posterior a ambas derivaciones)
- Objetivo de unos S/100 al mes; máximo S/110.
- Los totales nominales del doc 11 cumplen: noviembre S/100,80 si se activa el 10 nov, diciembre S/99,70 y enero S/102,30.
- La configuración observada de S/7,77 al día (S/233 en 30 días), con Perú y PRESENCE_OR_INTEREST, sigue sin cuadrar con el plan. Se contrasta con vista previa y aprobación antes de cualquier cambio.
- Si se activa antes del 10 nov, el presupuesto diario se recalcula para no superar S/110.
- Los cálculos nominales no son facturación; el límite efectivo se comprueba en la cuenta.

PLAN PRIORIZADO (responsable · momento → cierre verificable)

P0 antes de publicar o activar
1. Inspección de URL de la home, /show.html y /index.html en ambos hosts. Dueño ejecuta, consultor interpreta → capturas fechadas de la canónica elegida y de la prueba en vivo.
2. Conciliar la campaña 23352035016 con el plan: techo de S/110, Lima y Callao, URL finales correctas. Diagnosticar la falta de entrega desde el 1 mar sin inferir causa. Dueño y especialista de Ads → captura igual al plan aprobado; causa documentada o declarada desconocida.
3. Medición: PAGE_VIEW como secundaria; formulario aceptado y recibido como conversión principal; WhatsApp, teléfono y brochure como interacciones mientras no acrediten contacto. Analítica y dueño → envío real recibido y contado una vez; recargar /gracias/ no genera evento.
4. Show: equivalencia de contenido con L07, un solo H1, 301 directo. Más el mapa completo de 301 (video, fotografía, marketing, web, index.html, host), Brochure.pdf con 200 en la misma ruta y 404 real. Desarrollo y QA → peticiones HTTP reales y comparación del texto con L07.
5. La compilación bloquea datos de prueba y [COMPLETAR]/[VALIDAR]; el noindex de staging es legible o el staging está protegido por acceso. Desarrollo → la compilación falla con un caso de prueba y la cabecera se verifica.
6. Show en Ads: corte el 15 nov reformulado. Solo se anuncia si antes hay entrega verificable, medición de contactos probada y destino funcional (11 días desde hoy). Decide Marco.

P1 antes de cerrar contenido o documentación
7. Registro de vigencia de 00/07/11 que reetiquete cada afirmación como hecho, reporte o hipótesis, con fecha. Incluye las listas de sobreafirmaciones de ambos pares, el estado de Ads sin «No apta», el techo de S/110, la medición, las expectativas de FAQ/Review/LocalBusiness, el show en public, los 12 servicios, el fragmento de redirecciones y el horario de lunes a sábado no validado.
8. Roles diferenciados de home, hub y pilar; revisar las keywords principales de fotografía, organización, video corporativo y web/marketing con SERP complementarias, en móvil y en otra fecha.
9. Fichas de oferta reales para cobertura, streaming/podcast y catering. Marco y responsables de servicio; nada copiado de CP01–CP08.
10. Ficha de Google y dirección del estudio, si atiende allí; después, destino de /fotografia.html según equivalencia de contenido. LocalBusiness solo con dirección real.
11. Vigilancia diaria de impresiones en GSC mientras siga el hosting antiguo (continua, solo lectura).

P2 posterior, con evidencia
12. Tanda B, /precios/, /blog/, S5, S6, ajustes por dispositivo u horario y recalibración de proyecciones con 30 contactos o 60 días de datos propios. S045 se mantiene como un fallo, no como una SERP vacía.

DECISIONES PARA MARCO
- Compartir la Inspección de URL.
- Decidir si se concilia la campaña o se mantiene sin entrega con su configuración actual.
- Decidir sobre el show antes del 15 nov.
- Confirmar oferta y set de podcast, y la atención presencial del estudio.
- Aportar datos y permisos reales.
- Autorizar el registro de vigencia sin tocar los originales.
- Visual y hosting siguen siendo decisión suya.

### riesgos


- Si la campaña empieza a entregar con la configuración observada (S/7,77 al día, Perú, PRESENCE_OR_INTEREST), el gasto nominal superaría el máximo de S/110 y llegaría a público fuera de Lima. Es una sospecha: hoy no hay entrega demostrada.

- Activar antes del 10 nov con S/4,80 al día sin recalcular supera S/110 (activando el 5 nov serían S/124,80 nominales). Reasignar al show o a C2 sin recalcular también puede superarlo.

- Mientras la web siga en el hosting antiguo puede repetirse un vacío de causa desconocida en plena temporada del show.

- Fijar el host antes de la Inspección de URL puede contradecir la canónica que eligió Google.

- Tomar clics de WhatsApp o teléfono, cargas de /gracias/ o PAGE_VIEW como leads inflaría el rendimiento aparente y llevaría a ajustes de puja, horario o dispositivo sin base.

- Seguir usando las sobreafirmaciones de 00/11 (competencia débil, volúmenes sumados, «rentable», «validado», 2.900 del estudio) puede desviar prioridades. También puede excluir oportunidades si se leen los null o 0 como falta de demanda.

- GSC y Ads son un reporte documental con descuadres Q01–Q13 y W1 quizá no definitivo; las decisiones finas requieren las exportaciones originales.

- Process: Codex informa haber escrito un artefacto pese a la restricción; Claude pudo superar el objetivo de 2.200 palabras (no medido aquí). Ninguno de los dos altera las conclusiones.

- Confundir un dictamen documental con implementación probada o con permiso de activar: los gates de publicación y de activación siguen sin ejecutarse.

### confianza


- **nivel:** media
- **motivo:** Alta en los errores de especificación y documentación (07, 11, 00), que se demuestran contra el propio texto y contra fuentes oficiales G5 del 03 nov, y en la aritmética del presupuesto con el techo nuevo. Media en arquitectura y priorización: una sola tanda de SERP y GSC/Ads como reporte documental no reconsultado, con descuadres. Baja en rendimiento comercial y proyecciones. La canónica, el acceso de Googlebot, la causa de los vacíos y la falta de entrega en Ads siguen sin verificar.
