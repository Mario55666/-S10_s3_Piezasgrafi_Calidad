# Operación Gran Formato · Revisión de artes y ficha técnica

Página web de un solo archivo para la actividad **«Operación Gran Formato: diagnóstico y rescate de una producción gráfica para retail»**. La página:

- carga tres artes de una producción rechazada con los valores con que se fabricaron;
- compara esos valores con las especificaciones del proyecto y muestra una vista previa técnica de cada pieza;
- incluye una infografía interactiva que relaciona la distancia del observador con la resolución de la imagen en 12 productos de publicidad exterior e interior;
- incluye un asistente con audio, un glosario de 44 términos y ayudas de redacción en el campo de observaciones;
- asigna insignias y XP por misión superada;
- genera la ficha técnica de producción en PDF por estudiante.

- Asignatura: Producción y publicación de piezas gráficas
- Unidad temática: producción gráfica de gran formato
- Fase del aprendizaje experiencial: conceptualización abstracta (Kolb)
- Modalidad: individual · evaluación formativa gamificada · 35–45 min · 1000 XP
- Autor: Mg. Mario Quiroz Martínez, 2026
- Archivo: `Operacion_Gran_Formato_revision_ficha.html` (≈ 1,3 MB). Lleva incrustados el logotipo del IDC y los tres artes en JPEG de calidad 90, con su tamaño en píxeles original.

---

## Cambios en `Operacion_Gran_Formato_revision_ficha2.html` (2026-11-06)

La resolución requerida ya no se calcula con ppi = 3438 ÷ distancia: sigue una tabla de cinco tramos de distancia. Estas notas prevalecen sobre las secciones 2, 3 y 4.4 de este documento, que describen la versión anterior. `ficha1` se conserva sin cambios.

| Distancia de visualización | Recomendado (ppi) | Mínimo aceptable (ppi) |
|---|---|---|
| Menos de 0,6 m | 200–300 | 150 |
| 0,6–1,5 m | 150–200 | 100 |
| 1,5–3,0 m | 100–150 | 75 |
| 3,0–6,0 m | 75–100 | 50 |
| Más de 6,0 m | 25–50 | 18–24 |

- **Control M01:** Desviación bajo el mínimo, Observación entre el mínimo y lo recomendado, Conforme desde lo recomendado. El archivo a escala 1:10 usa los mismos valores por 10. En los límites compartidos (1,5, 3 y 6 m) rige el tramo más exigente, y en «18–24» se toma 18 para aprobar.
- **Sección 03:** un banco óptico interactivo reemplaza la escena, la curva y la tabla comparativa. Muestra las 15 piezas de la tabla y sigue a la pieza seleccionada en la revisión, incluido el original solicitado.
- **Otros cambios:** parámetros de referencia, ayuda del campo de distancia, paso del asistente, nota del PDF y glosario, que suma «Resolución recomendada» y «Mínimo aceptable» (46 términos). Los números se escriben con coma decimal.
- **Guía del estudiante (nueva):** vista general al inicio y siete pasos dentro de las secciones, que suman 40 minutos. Cada paso indica qué hacer, cómo saber que terminó, qué hacer si se atasca, sus ayudas, su audio, el acceso al asistente y sus términos del glosario, que abren la definición. El asistente usa los mismos pasos. El esquema de observaciones agrega «Hipótesis de la fase OR» y «Contraste con la nomenclatura». El glosario suma ocho términos más (54 en total), entre ellos los que pide la sesión 10.
- **Mini-caso (sección 05, nueva):** cuatro reportes de instalación con opción múltiple, uno por concepto: resolución efectiva, escala de trabajo, línea de corte, y ojales con margen de refuerzo. Se requieren 3 de 4 aciertos para pasar a la experimentación activa, como indica la sesión 10. Las preguntas acertadas se bloquean con su fundamento y las erradas muestran una pista y se pueden reintentar. No suma XP. La ficha PDF registra el último resultado, el primer intento y el número de intentos. Las secciones Progreso y Ficha técnica pasan a ser la 06 y la 07.
- **Sesión 10:** esta tabla es la que rige. Ya la incorporan `sesion-10-arte-final-gran-formato-pop_v2.docx`, la diapositiva 5 de `Semana 10 Large_Format_Technical_Blueprint_v2` (.pptx y .pdf) y `Semana 10 Arte_Final_Gran_Formato_v2.mp4`. En ese video, la tabla de 2:21 muestra los cinco tramos y se quitaron las frases que decían los valores anteriores, por lo que dura 14 s menos (7:54); la narración no menciona los valores nuevos.
- **Por confirmar:** la tabla no cita fuente. Los formatos de las piezas son estimación didáctica. Las cuatro preguntas son una propuesta nueva, porque el documento de la sesión no las redacta; deben revisarse antes de aplicarlas.
- **Código fuente:** `outputs/2026-11-05-banco-optico-distancia/` en el proyecto; `node build-activity.mjs` genera esta versión a partir de `ficha1`.

---

## 1. Secciones

| N.° | Sección | Contenido |
|---|---|---|
| — | Portada | Narrativa del caso y datos de la actividad |
| 01 | Misiones | M01 Resolución · M02 Corte · M03 Tensión · M04 Tintas |
| 02 | Parámetros de referencia | Valores del dossier con fuente y misión |
| 03 | Infografía interactiva | Distancia del observador y resolución de la imagen |
| 04 | Revisión | Diagnóstico por pieza: vista previa con capas, formulario de corrección, tabla de controles y dictamen |
| 05 | Progreso | Cuatro insignias, puntaje XP y rango |
| 06 | Ficha técnica | Formulario del estudiante y generación del PDF |

---

## 2. Parámetros de referencia

| Parámetro | Valor | Fuente |
|---|---|---|
| Resolución requerida a tamaño final | ppi = 3438 ÷ distancia en pulgadas | Cálculo: agudeza visual de 1′ de arco |
| Escala de trabajo | 1:10 (ppi del archivo = ppi final × 10) | Proyecto |
| Línea de corte | Trazo vectorial independiente (p. ej. CutContour) | Proyecto |
| Demasía película adhesiva | 3 mm por lado | Proyecto |
| Demasía panel plástico | 2 mm por lado | Proyecto |
| Tolerancia de corte | ±1 mm | Proyecto |
| Lona PVC | Refuerzo perimetral 50 mm · ojales a 250 mm entre centros · 25 mm del centro al borde | Proyecto |
| SEG | Cordón perimetral de 12 mm compatible con la ranura del perfil; sin ojales | Proyecto (medida no universal: usar la ficha del perfil) |
| Material SEG | Textil de poliéster sublimable | Proyecto |
| Sublimación / UV | Transferencia por calor sobre poliéster / curado por radiación UV sobre soportes compatibles | Dossier, recurso 02 |
| Cobertura total de tinta | Referencia ≤ 300 %, estimada desde RGB sin perfil | Práctica general |

Las demasías de 2 y 3 mm, la tolerancia de ±1 mm y el cordón de 12 mm son especificaciones del escenario didáctico, no valores universales de la industria.

---

## 3. Infografía: distancia del observador y resolución

**Fundamento.** El ojo distingue detalles separados por un ángulo de alrededor de 1 minuto de arco. Ese detalle mide 0,29 mm a 1 m y 2,9 mm a 10 m. La resolución requerida a tamaño final es 3438 ÷ distancia en pulgadas.

**Componentes:**
- **Selector de productos:** 12 productos (tabla siguiente).
- **Escena anatómica animada:**
  - ojo del observador en corte con córnea, iris, cristalino, humor vítreo, retina, fóvea y nervio óptico, y los dos rayos que convergen en la fóvea;
  - observador de 1,70 m y pieza dibujados con la misma escala vertical (1 px = 10 mm); las piezas más grandes que el área de dibujo se reducen y se rotulan «dibujo reducido»; los habladores, las piezas de señalización y los colgantes se dibujan a su altura de montaje aproximada;
  - cono visual desde el ojo hasta la pieza y cota de distancia;
  - leyenda con el detalle mínimo distinguible y la altura angular de la pieza (2 · atan(alto ÷ 2 ÷ distancia));
  - distancia en escala logarítmica de 0,3 a 100 m;
  - el arte seleccionado en la revisión se imprime sobre la cara de la pieza;
  - al elegir un producto, la pieza se desplaza en 0,7 s hasta su distancia típica; con `prefers-reduced-motion` el cambio es inmediato.
- **Deslizador de distancia:** escala logarítmica de 0,3 a 100 m.
- **Curva de ppi requeridos:**
  - ejes logarítmicos: distancia de 0,3 a 100 m y resolución de 0,5 a 400 ppi;
  - la curva se dibuja al entrar en pantalla;
  - cada producto aparece como un tramo de color entre su distancia mínima y máxima;
  - una línea horizontal marca los ppi del arte actual en el formato del producto, y su cruce con la curva indica la distancia desde la que el arte se ve sin pixelado.
- **Indicadores:**
  - ppi requeridos y detalle mínimo distinguible;
  - píxeles necesarios para el formato, megapíxeles y peso estimado en CMYK de 8 bits;
  - resolución del archivo a escala: 1:10 en piezas de 3 m de ancho o más, 1:1 en las demás;
  - ppi del arte actual en ese formato, con estado suficiente o insuficiente.
- **Vista del observador:**
  - fragmento del arte con 24 detalles visibles de ancho;
  - dos cuadrículas: píxeles del archivo (azul) y detalles que distingue el ojo (magenta);
  - si el píxel del archivo es mayor que el detalle visible, el fragmento se dibuja sin suavizado y se ven los bloques.
- **Tabla comparativa:** formato, rango de distancia, ppi requeridos, píxeles a distancia típica, soporte y sistema de cada producto. Al hacer clic en una fila se selecciona el producto.

**Productos** (formatos y distancias típicas: estimación didáctica; ajustar al brief de cada instalación):

| Producto | Formato típico | Distancia (típica) | ppi requeridos (a la típica) |
|---|---|---|---|
| Banner en lona con ojales | 3000 × 1000 mm | 3–15 m (5 m) | 5,8–29 (17) |
| Roll-up / parante con base retráctil | 850 × 2000 mm | 0,8–4 m (1,5 m) | 22–109 (58) |
| Gigantografía hasta 5 m de ancho | 5000 × 2500 mm | 8–40 m (15 m) | 2,2–11 (5,8) |
| Vinil adhesivo para vidrios, paredes y vehículos | 2000 × 800 mm | 2–15 m (5 m) | 5,8–44 (17) |
| Autoadhesivos de señalización interior | 300 × 200 mm | 1–6 m (2 m) | 15–87 (44) |
| Lona para fachada outdoor | 10 000 × 6000 mm | 15–100 m (30 m) | 0,9–5,8 (2,9) |
| Carteles y afiches | 594 × 841 mm | 0,6–3 m (1,2 m) | 29–146 (73) |
| Banner / pendón interior | 600 × 1600 mm | 1–5 m (2 m) | 17–87 (44) |
| Exhibidores y displays de mostrador | 300 × 400 mm | 0,4–1,5 m (0,6 m) | 58–218 (146) |
| Habladores y señalización de góndola | 100 × 70 mm | 0,3–1,2 m (0,5 m) | 73–291 (175) |
| Móviles y colgantes | 500 × 500 mm | 2–8 m (3,5 m) | 11–44 (25) |
| Vinilos decorativos para vitrinas y paredes | 2000 × 1500 mm | 0,8–5 m (2 m) | 17–109 (44) |

«Roll-ups ejecutivos» y «Parantes tipo roll-up» comparten una entrada. «Banners en lona con ojales» (exterior) y «Banners» (pendón interior) tienen entradas separadas.

La resolución requerida es el límite de la agudeza visual. No incluye la resolución de salida del equipo (dpi), que es independiente de los ppi del archivo.

---

## 4. Revisión por pieza

### 4.1 Artes y valores recibidos

Los tres artes son PNG RGB de 8 bits, sin perfil ICC y sin resolución declarada.

| Pieza | Arte | Píxeles | Valores recibidos (producción rechazada) |
|---|---|---|---|
| 1 · Streaming de música | `arte_01_streaming.png` | 1672 × 941 | Gigantografía de fachada 6000 × 3000 mm · distancia 8 m · lona PVC · eco-solvente · **fijación con cordón SEG** · demasía 0 mm |
| 2 · Automotriz | `arte_02_automotriz.png` | 1536 × 1024 | Gráfico textil SEG 3000 × 2000 mm · distancia 3 m · **impresión UV** · **fijación con ojales** · demasía 0 mm |
| 3 · Producto veterinario | `arte_03_veterinario.png` | 1536 × 1024 | Panel de exhibidor 1500 × 1000 mm · distancia 1,5 m · panel PVC espumado · UV · adhesivo · **demasía 0 mm** |

En las tres piezas la línea de corte coincide con el límite visual.

### 4.2 Formulario de corrección

- **Pieza:** descripción, ancho y alto finales y ajuste del arte (recortar para cubrir, o encajar y extender el fondo).
  - La distancia de visualización es un dato del brief y no se edita, para que la resolución no pueda «aprobarse» alejando al observador.
  - La posición del recorte se ajusta con un deslizador.
  - El campo «ancho del original solicitado al cliente (px)» permite corregir la resolución; el control queda como observación hasta recibir ese archivo.
- **Producción:** soporte, sistema de impresión, fijación y demasía por lado.
- **Confirmaciones del estudiante:**
  - línea de corte vectorial independiente;
  - zona perimetral sin textos ni logotipos;
  - logotipos vectoriales del manual de marca;
  - textos revisados contra el texto aprobado.
- **Observaciones del revisor:** texto libre que pasa a la ficha.
- **«Restablecer valores recibidos»:** vuelve la pieza a los valores de la producción rechazada.
- **«Reemplazar arte (PNG o JPEG)»:** carga otro arte en la pieza seleccionada.

### 4.3 Vista previa

Lienzo a escala con capas que se pueden activar y desactivar:

- demasía;
- línea de corte (trazo discontinuo magenta);
- zona de refuerzo (50 mm) o del cordón (12 mm);
- ojales a 250 mm entre centros y 25 mm del borde;
- área recortada del arte.

### 4.4 Controles

| Misión | Control | Criterio |
|---|---|---|
| M01 | Resolución efectiva a tamaño final | ppi efectivos ≥ 3438 ÷ distancia (pulgadas); si no se cumple, indica los píxeles necesarios |
| M01 | Archivo a escala 1:10 | ppi del archivo ≥ ppi requeridos × 10 |
| M01 | Proporción del arte | Igual a la del formato; recorte o extensión ≤ 15 % = observación; mayor = desviación |
| M02 | Demasía por lado | 3 mm película adhesiva · 2 mm panel · lona: no definida (refuerzo dentro del formato) · SEG: según ficha del perfil |
| M02 | Línea de corte | Trazo vectorial independiente; tolerancia ±1 mm |
| M03 | Sistema de fijación | Lona → ojales con refuerzo; SEG → cordón perimetral; película y panel → adhesivo o montaje directo. Cuenta los ojales por lado |
| M03 | Zona de refuerzo o del cordón | Sin textos ni logotipos en la franja perimetral |
| M04 | Sistema de impresión y soporte | Matriz de compatibilidad (4.5) |
| M04 | Modo de color y perfil | Conversión con el perfil ICC del soporte en el RIP |
| M04 | Cobertura de tinta estimada | Media, percentil 99 y porcentaje del área en sombras; > 300 % = desviación; > 50 % del área en sombras = observación |
| — | Logotipos y textos | Vectoriales del manual de marca y texto aprobado |

Dictamen por pieza:

- **NO APTO: CORREGIR** si queda al menos una desviación;
- **APTO CON OBSERVACIONES** si solo quedan observaciones;
- **APTO PARA FABRICAR** si todos los controles son conformes.

Las pestañas de pieza muestran el estado con un punto de color.

### 4.5 Compatibilidad sistema de impresión × soporte

| Soporte | UV | Sublimación | Látex | Eco-solvente |
|---|---|---|---|---|
| Lona PVC | Conforme | Desviación | Conforme | Conforme |
| Textil SEG (poliéster sublimable) | Desviación | Conforme | Observación | Observación |
| Película adhesiva | Conforme | Desviación | Conforme | Conforme |
| Panel plástico | Conforme (UV plana) | Desviación | Observación (imprimir en vinil y montar) | Observación (imprimir en vinil y montar) |

La compatibilidad depende de la formulación de la tinta, del recubrimiento y del sustrato. La matriz sigue las especificaciones del escenario y no afirma que toda impresión UV o látex sea incompatible con textiles.

### 4.6 Revisión visual del arte

Las observaciones de contenido de cada arte son del revisor y están rotuladas como tales en la página y en la ficha. Se confirman con el archivo original del cliente.

- **Pieza 1:**
  - el texto «Meodo» en la tarjeta «Mood»;
  - tarjetas que tocan el borde derecho;
  - un botón de interfaz digital en una pieza impresa;
  - proporción 16:9 frente a 2:1.
- **Pieza 2:**
  - proporción 3:2 coincidente con el formato;
  - degradado de cielo con riesgo de bandeo;
  - textos de cuerpo pequeño;
  - elemento en el borde superior derecho.
- **Pieza 3:**
  - fondo negro dominante;
  - textos legales y del envase de cuerpo pequeño;
  - símbolo ® repetido;
  - caracteres irregulares en la pipeta.

---

## 5. Insignias y puntaje

Una misión se supera cuando ninguno de sus controles tiene desviación en las tres piezas. Cada misión superada suma 250 XP.

| Misión | Insignia |
|---|---|
| M01 | Detective de píxeles |
| M02 | Maestro de preprensa |
| M03 | Ingeniero de montaje |
| M04 | Experto en color |

Rangos: 900–1000 Maestro de producción gráfica · 750–899 Especialista en gran formato · 500–749 Técnico en formación · 0–499 Aprendiz de preprensa.

---

## 6. Asistente con audio, glosario y ayudas de redacción

La voz usa la síntesis del navegador (Web Speech API) y elige una voz en español, en este orden: es-PE, es-419, es-MX, es-US, es-ES. Antes de leer convierte los símbolos a palabras (mm → milímetros, ± → más o menos, × → por, 1:10 → uno a diez). Si el navegador no tiene síntesis de voz, aparece un aviso y el resto de las ayudas funciona sin audio.

- **Botones «Escuchar»:**
  - en la portada (narrativa de la misión);
  - en el encabezado de cada sección;
  - en las tarjetas de misión;
  - en cada ayuda de campo, en cada término del glosario y en las observaciones del estudiante;
  - un segundo clic en el mismo botón detiene la lectura, igual que la tecla Escape.
- **Asistente** (botón flotante abajo a la izquierda):
  - muestra la pieza seleccionada con su dictamen y el número de controles conformes;
  - «Escuchar el diagnóstico pendiente» lee cada control no conforme con su misión, su estado y la corrección;
  - incluye seis pasos guiados (leer la misión, revisar los parámetros, usar la infografía, diagnosticar cada pieza, redactar el fundamento, generar la ficha), cada uno con audio y un botón «Ir» a la sección;
  - permite elegir la voz, ajustar la velocidad (0,7–1,3) y detener la lectura.
  - El botón «Escuchar diagnóstico de la pieza» también está en el formulario de revisión.
- **Ayudas de campo:** un botón «?» en 13 campos (los del formulario y el correo de la ficha) despliega la explicación técnica del campo con su audio.
- **Glosario:**
  - diálogo con 44 términos (botón «Glosario», «Abrir glosario» o Alt+G);
  - buscador sin acentos y filtro por misión;
  - cada término trae definición, misión, audio y el botón «Insertar en observaciones», que lo coloca donde estaba el cursor.
- **Ayudas en «Observaciones del revisor»:**
  - «Insertar esquema de diagnóstico» agrega los encabezados Falla observada · Causa técnica · Corrección aplicada · Fundamento; no redacta el contenido.
  - Autocompletado: al escribir tres letras aparecen términos del glosario; Tab inserta el primero.
  - Las mayúsculas del término se ajustan a la posición en la frase; siglas como SEG o CutContour se mantienen.
  - Fichas de términos por misión (cinco por misión), ordenadas con las misiones pendientes de la pieza primero; un clic inserta el término.
  - Contador de términos técnicos detectados y cobertura por misión. La misión se marca en verde con dos o más términos y en ámbar si tiene controles pendientes.
- **Ficha PDF:** debajo de las observaciones de cada pieza, la ficha lista los términos técnicos detectados en el texto.

---

## 7. Ficha técnica en PDF

- **Datos obligatorios:** nombres, apellidos y correo electrónico institucional. El correo se valida en formato.
- **Contenido** (jsPDF 2.5.1 + jsPDF-AutoTable 3.8.2, A4):
  1. Portada: estudiante, correo, asignatura, fase, dictamen de cada pieza, XP y rango.
  2. Una página por pieza:
     - vista previa con demasía, línea de corte y fijación;
     - tabla con misión, parámetro, valor recibido, valor corregido, referencia, estado y corrección o fundamento;
     - datos de producción;
     - revisión visual, observaciones del estudiante y dictamen.
  3. Firmas del estudiante revisor, del jefe de producción y del docente responsable, con una nota de fuentes.
  4. Pie institucional y numeración en todas las páginas.
- **Nombre del archivo:** `Ficha_tecnica_GF_<Apellidos>_<Nombres>_<AAAA-MM-DD>.pdf`.
- **Descarga:** dentro de claude.ai usa la capacidad `downloads`; fuera de claude.ai, la descarga directa del navegador.
- **Conexión:** las bibliotecas de PDF se cargan desde cdnjs al generar la ficha, así que hace falta conexión a internet.

---

## 8. Estructura del proyecto

```
og/
├── src.html         marcado, estilos y script principal (revisión, controles, insignias, ficha PDF)
├── ig.js            infografía distancia–resolución
├── assist.js        asistente con audio, glosario y ayudas de redacción
├── build.py         incrusta el logotipo y los tres artes (JPEG, calidad 90) e inserta ig.js y assist.js
├── index.html       salida de build.py
└── Operacion_Gran_Formato_revision_ficha.html   copia de entrega
```

```bash
python3 build.py      # genera index.html
cp index.html Operacion_Gran_Formato_revision_ficha.html
```

Tecnología: HTML, CSS y JavaScript sin dependencias en la página. Web Speech API para la voz. Canvas para la vista previa y la vista del observador, SVG para la escena y la curva. Fuentes IBM Plex Sans e IBM Plex Mono (Google Fonts).

---

## 9. Pruebas realizadas

Pruebas en Playwright con Chromium, a 1366 × 900 y 390 × 800 px:

- **Valores de partida:** dictamen NO APTO en las tres piezas.
- **Pieza 1 corregida:** con fijación con ojales (72 ojales: 25 por lado largo y 13 por lado corto), línea de corte, zona perimetral verificada y original solicitado de 5000 px, pasa a APTO CON OBSERVACIONES.
- **Navegación:** el cambio de pieza actualiza la infografía.
- **Infografía:** selección de producto, deslizador de distancia y cuadrículas de la vista del observador.
- **Ficha PDF:** generada y descargada (8 páginas) con la descarga directa del navegador.
- **Asistente y ayudas** (con síntesis de voz simulada): lectura de la misión y del diagnóstico pendiente; ayuda de campo desplegada; esquema de diagnóstico; autocompletado con Tab; cobertura por misión; inserción desde el glosario en la posición del cursor; lista de términos en la ficha PDF.
- **Consola:** sin errores.

---

## 10. Limitaciones

- La cobertura de tinta es una estimación desde RGB sin perfil. El TAC real lo define el perfil de salida del RIP.
- El «original solicitado» simula un archivo de mayor resolución; el control queda como observación hasta recibirlo.
- La zona perimetral, los logotipos y los textos no se miden automáticamente; dependen de las confirmaciones del estudiante.
- Los formatos y distancias de la infografía son estimaciones didácticas.
- Los artes incluyen marcas registradas de sus titulares, usadas como caso de estudio; por eso la página se distribuye como archivo y no como página publicada.
- La calidad y disponibilidad de la voz dependen del navegador y del sistema operativo; algunos equipos no tienen voces en español instaladas.
- La detección de términos busca coincidencias de palabras y alias; no evalúa si el término está bien usado.
- Las cuatro preguntas de opción múltiple no están incluidas en `ficha` ni en `ficha1`; `ficha2` las agrega en su sección 05.

---

Mg. Mario Quiroz Martínez 2026 — Unidad didáctica de Producción y publicación de piezas gráficas
