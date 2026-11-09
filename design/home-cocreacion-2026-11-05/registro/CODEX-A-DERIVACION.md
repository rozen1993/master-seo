# Codex Astra Ultra — derivación independiente

5 de noviembre de 2026. Respuesta de `/root/astra_cocreacion_actual`, creado con `model=gpt-6-astra`, `reasoning_effort=ultra`, contexto limpio. Solo lectura; no generó imágenes ni modificó archivos. No recibió propuestas anteriores ni propuestas de Claude. Esta derivación no es un acuerdo conjunto ni una elección del dueño.

Paquete íntegro verificado por el par: SHA256 `0EAD2E7B1AF57F59DBE22299EB032C389181769AB3E5E8A3AA68AB2169AFF0C1`. Skill frontend-design leída íntegramente. Ocho imágenes abiertas realmente con view_image.

## Evaluación del contexto

El sujeto es Rhino Audiovisuales, en Lima. La audiencia son personas que necesitan contratar servicios audiovisuales o para eventos, con distintas necesidades y grados de preparación. La función de esta home es permitir reconocer al proveedor, entender sus prioridades y consultar un encargo.

La evidencia permite diseñar categorías, navegación y solicitud de propuesta. No permite demostrar experiencia mediante clientes, resultados o proyectos autorizados. La existencia de estudio propio sí está confirmada; sus instalaciones y modalidades no están documentadas aquí.

Propongo comparar las tres homes sobre un lienzo común de **1440 × 4000 px**, pendiente de confirmación operativa para la generación. Mismo contenido; distinta composición, tipografía, paleta y lenguaje de imágenes. Los nombres de las direcciones son internos.

## Examen visual real

| Archivo visto | Observación y criterio |
|---|---|
| `01-henry.jpg` | Automóvil lateral bajo nieve, imagen prácticamente completa y texto azul en la mitad inferior. La escena concentra la atención; el azul pierde contraste. Conservar concentración, separar texto de fondos difíciles. |
| `03-iconoclast.jpg` | Rostro desenfocado a la derecha, rectángulo turquesa a la izquierda y navegación minúscula arriba. Se percibe atmósfera antes que oferta. Rhino necesita comprensión inmediata, sin depender de una transición. |
| `04-division.jpg` | Gran estructura circular metálica, figura central y carro metálico en primer término; marca condensada arriba y título serif muy fino abajo. Funciona la tensión tipográfica; no trasladaría créditos de proyectos a imágenes conceptuales. |
| `05-velour.jpg` | Frase central monumental y condensada, imágenes pequeñas que entran desde los bordes, fondo casi negro y monograma rojo. La jerarquía es inequívoca. Evitaría imitar tanto su lema como su disposición periférica. |
| `09-lovesong-index.jpg` | Fondo rojo continuo, tabla central con números descendentes, autores, títulos y años; líneas negras finas. La estructura representa un archivo real. No existe evidencia equivalente para hacer un archivo de Rhino. |
| `11-stink.jpg` | Persona de polo rojo en un local de comida, asadores, subtítulo amarillo abajo y aviso de cookies arriba a la derecha. La escena comunica humanidad y contexto sin enseñar cámaras. No tomarla como referencia de interfaz limpia. |
| `12-mvsm.jpg` | Mucho espacio blanco antes de un mosaico de dos y luego tres imágenes; títulos blancos grandes dentro de cada pieza. El ritmo de proporciones es útil; su apariencia de portafolio acreditado no es trasladable. |
| `13-builders.jpg` | Declaración centrada sobre blanco, tres accesos arriba a la derecha y díptico inferior de escalera mecánica y ciudad nocturna. Tiene claridad y pausa. Rhino necesita además una salida explícita hacia consulta. |

Estas capturas acreditan únicamente lo visible, no comportamiento, animación o accesibilidad.

## Base de copy común propuesta

Usaría este mismo contenido en las tres imágenes, sujeto a cierre conjunto:

- **Navegación:** Servicios · Sobre Rhino · Contacto.
- **H1:** Productora audiovisual en Lima.
- **Introducción:** Elige el servicio que necesitas y cuéntanos qué tienes en mente.
- **Acciones iniciales:** Consultar proyecto · Ver servicios.
- **Bloque prioritario:** Empieza por tu encargo.
- **Cobertura de eventos:** Consulta foto o video para registrar tu evento. Cuéntanos la fecha, el lugar y qué necesitas cubrir.
- **Streaming y podcast:** Para una transmisión o un episodio. Describe tu proyecto y consulta las opciones.
- **Catering y coffee break:** Comparte la fecha, el lugar y el número de asistentes para consultar una propuesta.
- **Otros servicios:** Producción audiovisual · Fotografía y estudio · Servicios para eventos · Servicios digitales. Acción: Ver servicios.
- **Sobre Rhino:** Rhino Audiovisuales en Lima. Contamos con estudio propio. Conoce nuestros servicios audiovisuales, de fotografía y para eventos. Acción: Sobre Rhino.
- **Solicitud:** Para solicitar una propuesta. Cuéntanos qué necesitas, cuándo y dónde. Si ya tienes una idea, puedes incluir referencias.
- **Ayudas breves:** El encargo · Fecha y lugar · Necesidades y referencias.
- **CTA final:** Consultar proyecto.
- **Pie:** Rhino Audiovisuales · Lima · Servicios · Sobre Rhino · Contacto · Política de privacidad.
- **Identificación visual:** Imágenes ilustrativas.

Los títulos de servicios representan conceptualmente P05, P06 y P07; los CTA generales, P33. No se está certificando la disponibilidad de esos destinos. No incluiría un bloque titulado “Proyectos”, espacios vacíos para clientes ni botones de reproducción ficticios.

## Dirección A: Cine en tres planos

**Propuesta.** Una home cinematográfica, sobria y humana. El carácter procede del encuadre y la luz, mientras los textos viven en superficies legibles. No necesita una estética de equipos ni una falsa muestra de trabajos.

**Paleta, seis colores:**

- Azul de sala `#193344`: hero y cierre.
- Blanco frío `#F5F8FA`: superficie principal.
- Azul bruma `#CBD9E1`: transiciones.
- Tinta `#182730`: texto sobre claro.
- Rosa mineral `#DCAFA6`: acento pequeño y CTA sobre oscuro.
- Gris pizarra `#637782`: texto secundario sobre claro, sujeto a contraste final.

**Tipos.** Archivo SemiCondensed 600 para H1 y títulos: personalidad compacta sin imitar el cartel de Velour. Source Sans 3, pesos 400/600, para navegación y lectura. H1 88 px; H2 48; títulos de servicio 36; cuerpo 23–24; navegación y pies 18–20. Interlineado amplio en párrafos y compacto, sin colisiones, en titulares.

**Composición.** Cabecera tranquila. Hero asimétrico: texto sólido a la izquierda e imagen panorámica a la derecha. Después, tres grandes bandas de servicio; fotografía y texto intercambian posición. El contraste entre panorama y lectura produce el ritmo. Los módulos inferiores recuperan blanco y amplitud.

```text
┌ RHINO AUDIOVISUALES ─── Servicios / Sobre Rhino / Contacto ┐
│ H1 en azul profundo       │ Escena ilustrativa panorámica │
│ Introducción              │                              │
│ Consultar / Ver servicios │ Imágenes ilustrativas        │
├──────────────── Empieza por tu encargo ──────────────────┤
│ Imagen: encuentro         │ Cobertura + texto + acceso    │
│ Streaming + texto         │ Imagen: voz y escucha         │
│ Imagen: pausa             │ Catering + texto + acceso     │
├ Otros servicios / categorías / Ver servicios ────────────┤
│ Sobre Rhino                  │ Estudio propio / acceso    │
├ Para solicitar una propuesta ────────────────────────────┤
│ Introducción       El encargo / Fecha / Necesidades       │
│ Consultar proyecto                                       │
├ Marca / Lima / navegación / privacidad ───────────────────┤
└──────────────────────────────────────────────────────────┘
```

**Firma.** Tres encuadres panorámicos claramente separados que dan el mismo peso a las prioridades del negocio. Cada banda tiene una pregunta comercial concreta y su categoría: la proporción cinematográfica sirve a la selección del encargo.

**Imágenes.** Fotografía editorial generada, con color natural y grano muy leve: personas de espaldas en un encuentro sin marca; un gesto de conversación o escucha; manos acercando una taza sobre una mesa. Escenarios inventados, sin uniformes, señalética, equipamiento identificable ni interiores presentados como estudio de Rhino. Identificación legible junto a las imágenes.

**Autocrítica y cambio.** La primera idea de un fotograma a pantalla completa se parecía demasiado a una productora con reel acreditado. La sustituyo por hero dividido, CTA siempre sobre color sólido y categorías visibles. Descarto barras de tiempo, icono play y créditos cinematográficos: insinuarían piezas existentes.

**Riesgo y confianza.** Una fotografía demasiado espectacular podría seguir interpretándose como trabajo realizado. Conviene un tono editorial contenido y etiquetas cercanas. Confianza alta en comprensión; media-alta en singularidad, dependiente de una dirección fotográfica precisa.

## Dirección B: Mesa de montaje

**Propuesta.** Una identidad visual táctil, expresiva y cálida, construida con ilustración de papel. La home toma del montaje audiovisual la selección y relación entre fragmentos, sin simular una aplicación de edición.

**Paleta, seis colores:**

- Berenjena `#36204D`: textos y CTA.
- Lila papel `#D6C8ED`: hero y cierre.
- Coral mate `#F39D88`: una pieza principal del collage.
- Verde salvia `#B6CEC2`: bloque institucional.
- Blanco papel `#FBFAFC`: lectura.
- Ciruela gris `#6E607B`: detalles secundarios, sujetos a contraste.

**Tipos.** Bricolage Grotesque 700 en el H1 y titulares, con formas amplias y visibles; Figtree 400/600 en cuerpo y controles. H1 100–108 px; H2 52; títulos 36–40; cuerpo 24; navegación 19. No usar rotaciones para texto funcional.

**Composición.** H1 amplio en la mitad superior; debajo, una única composición de papel despliega las tres necesidades. Los servicios reaparecen como tres piezas abiertas y escalonadas, sin cajas de interfaz ni cuadrícula regular. El contenido institucional introduce un rectángulo salvia tranquilo. La solicitud final es tipográfica.

```text
┌ RHINO AUDIOVISUALES       Servicios / Sobre Rhino / Contacto ┐
│ PRODUCTORA AUDIOVISUAL                                    │
│ EN LIMA                                                  │
│ Introducción                    Consultar / Ver servicios │
│           Gran composición original de papel             │
│                     Imágenes ilustrativas                │
├ Empieza por tu encargo ───────────────────────────────────┤
│ Cobertura + texto      [escena de papel ancha]             │
│               [voz de papel]     Streaming + texto        │
│ [mesa de papel]                  Catering + texto         │
├ Otros servicios: categorías / Ver servicios ──────────────┤
│ Sobre Rhino / estudio propio / acceso                     │
├ Para solicitar una propuesta                             │
│ El encargo / Fecha y lugar / Necesidades y referencias    │
│                    Consultar proyecto                    │
├ Marca / Lima / navegación / privacidad ───────────────────┤
└───────────────────────────────────────────────────────────┘
```

**Firma.** Un montaje de tres escenarios de papel, de volumen poco profundo, unidos visualmente por el mismo material. No son paquetes ni etapas: cada pieza conserva su título y separación. La apuesta memorable está concentrada en ese montaje; el resto utiliza márgenes precisos y tipos limpios.

**Imágenes.** Ilustraciones manuales simuladas con bordes cortados, sombras físicas suaves y figuras simplificadas: encuentro de personas, conversación representada por dos perfiles y una mesa con una taza. No micrófonos de marca, pantallas con interfaces, menús, cámaras o decorados que parezcan inventario disponible.

**Autocrítica y cambio.** Un collage lleno de pegatinas, cinta adhesiva y textos inclinados sería decorativo y juvenil. El plan final elimina esos recursos: solo tres escenas, dos niveles de profundidad y una composición principal. Las ilustraciones acompañan a etiquetas comerciales literales; no sustituyen los nombres por “escena”, “voz” y “pausa”.

**Riesgo y confianza.** Puede percibirse más como estudio creativo que como proveedor para empresas si las figuras son demasiado infantiles. Mantener geometría sobria, proporciones adultas y poca caricatura. Confianza alta en diferenciación y honestidad visual; media-alta en adecuación comercial, que conviene contrastar con Marco.

## Dirección C: Luz de día

**Propuesta.** Una home luminosa, directa y de gran escala tipográfica. Frente a la inmersión de A y la materialidad de B, aquí el carácter nace del blanco, la verticalidad y fotografías de detalles cotidianos cuidadosamente encuadrados.

**Paleta, seis colores:**

- Blanco `#FFFFFF`: superficie dominante.
- Verde profundo `#174D45`: títulos y CTA.
- Azul agua `#D5EEF0`: zonas amplias de apoyo.
- Azul petróleo `#286C85`: enlaces y detalles.
- Amarillo lino `#E8CE78`: un acento pequeño, sin texto blanco.
- Grafito `#283C3D`: cuerpo.

**Tipos.** Archivo Narrow 600 en H1 y encabezados, usado a gran escala sin comprimir artificialmente; Instrument Sans 400/600 para texto y navegación. H1 126–136 px; H2 56; títulos 44; cuerpo 24; navegación 20. Titulares alineados a la izquierda, nunca en columnas densas.

**Composición.** Hero principalmente tipográfico, con un recorte vertical estrecho a la derecha. Las tres prioridades se presentan en bloques muy espaciosos: una columna continua de imágenes a la derecha y títulos grandes a la izquierda. Sin líneas divisorias, numeración ni apariencia de tabla. Después, “Otros servicios” y “Sobre Rhino” comparten una franja azul agua. El cierre vuelve a blanco.

```text
┌ RHINO AUDIOVISUALES       Servicios / Sobre Rhino / Contacto ┐
│ PRODUCTORA                                 │ detalle      │
│ AUDIOVISUAL                                │ fotográfico  │
│ EN LIMA                                    │ vertical     │
│ Introducción / Consultar / Ver servicios    │ ilustrativo  │
├ Empieza por tu encargo ────────────────────────────────────┤
│ COBERTURA DE EVENTOS                        │ personas     │
│ Texto / acceso                             │ y encuentro  │
│                                            │              │
│ STREAMING Y PODCAST                         │ gesto de     │
│ Texto / acceso                             │ conversación │
│                                            │              │
│ CATERING Y COFFEE BREAK                     │ taza y       │
│ Texto / acceso                             │ manos        │
├ Otros servicios              │ Sobre Rhino                │
│ Categorías / Ver servicios   │ Estudio propio / acceso     │
├ Para solicitar una propuesta ─────────────────────────────┤
│ Introducción / El encargo / Fecha / Necesidades            │
│ Consultar proyecto                                        │
├ Marca / Lima / navegación / privacidad ────────────────────┤
└───────────────────────────────────────────────────────────┘
```

**Firma.** Una franja vertical de observaciones humanas acompaña el recorrido comercial. Los detalles muestran atención al encuadre, sin presentarse como una colección de proyectos. Su continuidad ordena la página; las fotografías permanecen separadas, sin sugerir un mismo evento o paquete conjunto.

**Imágenes.** Fotografía conceptual de luz diurna, fondos sencillos y encuadres cercanos. Priorizar gestos y relaciones espaciales: personas sentadas, conversación, manos y taza. Nada de retratos de supuesto personal, instalaciones propias o montajes multitudinarios. “Imágenes ilustrativas” acompaña la columna, con repetición discreta donde sea necesario.

**Autocrítica y cambio.** Una primera versión con tres columnas iguales habría resultado un catálogo genérico y cercano al mosaico de referencias. La sustituyo por una lectura vertical con espacio generoso, sin tarjetas. También elimino el gran eslogan: el propio H1 sostiene la apertura y evita competir con la búsqueda comercial.

**Riesgo y confianza.** La gran tipografía podría desplazar demasiado las prioridades. Limitar el hero a aproximadamente una quinta parte del lienzo y comprobar la lectura completa del H1. Confianza alta en claridad y legibilidad; media-alta en personalidad, dependiente del ritmo y los recortes.

## Hallazgos, alternativas y verificación

1. **Las prioridades deben gobernar la composición.** El catálogo amplio aparece después; no convertir las 37 fichas en una home exhaustiva.
2. **El portafolio requiere evidencia ausente.** Lo omito en las tres propuestas. Las imágenes explican categorías; no actúan como prueba de experiencia.
3. **El estudio propio aporta un dato real.** Lo incorporo en el texto institucional, sin inventar una fotografía del local o una modalidad de alquiler.
4. **Descartadas:** archivo numerado de proyectos, muro de logotipos, hero con reel ficticio, paneles de métricas, menú de catering inventado y estética de software audiovisual.
5. **Antes de generar:** fijar el copy común y confirmar dimensiones. Los tipos nombrados son intención de diseño; no se ha comprobado su disponibilidad en el mecanismo de generación.
6. **Después de generar:** abrir cada PNG, verificar dimensiones reales, continuidad de página, texto completo, ausencia de afirmaciones nuevas, contraste aparente y equivalencia de contenido. Revisar a escala legible y en vista completa. El PNG no acredita accesibilidad funcional.
7. **Límite de esta revisión:** la autocrítica corresponde al plan. La calidad visual final y la exactitud tipográfica siguen pendientes de los PNG.

Las tres rutas son comparables por contenido, pero plantean experiencias distintas: **cine horizontal**, **ilustración material** y **tipografía luminosa con fotografía vertical**. La elección estética permanece abierta.
