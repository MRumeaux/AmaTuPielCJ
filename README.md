# AmaTuPielCJ
Repositorio creado para generar web Ama Tu Piel - CJ
V1 (o V.0.0.1): Se genera estructura HTML (a validar que se encuentre OK a medida que se vaya cargando el CSS), se contemplan nombres de clases genéricas para poder implementar correctamente metodología BEM. Se inicializan variables en CSS básicas de colores y fuentes recurrentes. 
Se intenta en esta pasada tener en consideración el armado Mobile First, siendo que en casos anteriores se comenzó focalizando en Desktop.


proto-primer-ajuste-css-para-index: Se intenta dar formato inicial a versión mobile. Se generan boxes para estandarizar y reutilizar en otras páginas del sitio. Se intentan aplicar clases en función a metodología BEM, entendiendo clases genéricas e insertando múltiples clases dentro de un mismo div para no repetir CSS. No se aplican mediaquerys de momento.

proto-crear-css-tips-y-marcas: En un primer guardado dí formato css a marcas + tips y ajusté responsibidad a elementos para las versiones de ventana con bootstrap. 

proto-inicial-css-para-corpo-y-facial: Pensando en metodología BEM intento crear pocas clases pero que sean repetitivas. Cuesta un poco dimensionar cuales vale estandarizar, aunque viendo positivamente el asunto generé un wireframe estático muy similar entre categorías.
actV2: Tuve que ajustar partes del HTML al empezar a implementar algunas clases, me retrasó las cargas de imágenes (todavía pendientes algunas secciones)
No me agrada como está quedando el contenido CSS pero ya estoy muy justo de tiempos para corregir a cero todo, lo implementaré momentáneamente de esta manera sabiendo que tengo un esqueleto decente de HTML.


proto-ajuste-imgs-corpo-facial: Se agregan las imagenes, se comprueba una resposibidad del site. Se agregan mediaquerys pero no cumplen su función. Pensé todo como mobile first y salió absolutamente mal; no toma los cambios que serían necesarioas para la versión tablet + desk. En momentos así, solo se puede reír.

proto-adhiero-sass-a-proyecto: Se procede a adherir metodología de referencia a proyecto. A nivel de orden creo haber separado bien los contenidos como así intentar generar nesting de clases. No me convence la repetición del mediaquery dentro de las variables, me resulta incómodo sentir que poniendo las mismas líneas de código pero cambiando apenas algunos detalles. Se ingresan algunas animaciones para imágenes de index y productos plus se da una estilización a las etiquetas a.