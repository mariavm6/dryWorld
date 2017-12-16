# dryWorld

# Procesado de contenido multimedia
En esta práctica hemos trabajado las diferentes modificaciones que se pueden hacer en contenido multimedia de imágenes, vídeo y audio.
Todo esto integrado en una página web. También hemos creado un banner publicitario.

## Edición de las imágenes

Todas las imágenes las he editado con la herramienta Gimp, cuentan con una marca de agua creada con la herramienta de texto que crea una capa a la que reducimos la opacidad [Proceso creación marca de agua](img/marca de agua.PNG). 
Dentro del proyecto están guardadas las imágenes originales y en los diferentes formatos requeridos en la rúbrica.
+ **Desierto** 
Con la herramienta de clonación, cogiendo como patrón la textura de la arena se consigue borrar a la persona que aparece en la imagen original.
[Proceso Edición](img/edicionDesierto.PNG)[Imagen Desierto](img/Desierto.jpg)
+ **Sequía1**
Para cambiar las nubes las seleccioné con la herramienta de selección difusa que selecciona una región contigua basándose en el color y después con la herramienta de balance de color, ajusté los niveles de color hasta conseguir un color rosa anaranjado.
Otra modificación fue quitar la vegetación de la imagen con la herramienta de clonado tomando como patrón la montaña, el suelo o el cielo. 
Al quitar la vegetación el puente había que alargarlo y para ello seleccioné uno de los arcos del puente y lo copié como una capa. Después subí la altura del terraplén de la derecha con la herramienta de clonado.
Para dar un poco de luminosidad a la imagen, puse un destello con degradado simulando el Sol.
[Proceso Edición 1](img/edicionEmbalse1.PNG) [Proceso Edición 2](img/edicionEmbalse2.PNG) [Proceso Edición 3](img/edicionEmbalse3.PNG)
[imagen Sequía1](img/sequía1.jpg)
+ **Sequía2**
Para poder seleccionar el curso del rio, activé la máscara y con la herramienta borrador seleccioné el curso del rio y lo borré con la tecla suprimir.
Después con la herramienta de selección invertí la imagen para seleccionar la parte del puente, montañas y cielo, la corté y la pegué en una nueva imagen como una nueva capa en una nueva imagen con el fondo transparente. 
Para poner la lava descargué una imagen con licencia para poder modificarla. La lava la formé con la misma imagen pero puesta en distintas capas y diferentes posiciones e inclinaciones. Una de las capas está formada por un recorte de la misma imagen.
El fondo de la imagen lo oscurecí con la herramienta Tono y saturación, modificando la luminosidad y  saturación. Seguí la misma técnica con la parte de la lava para que el contraste de color no fuese tan notorio y para conseguir un ambiente con humo.
Aun oscureciendo la parte de la lava el contraste seguía muy marcado. Por lo que utilicé la herramienta de desparasitar para suavizar más el corte entre las capas.
Para crear un ambiente con humo y unificar toda la imagen utilicé la herramienta de renderizado y creé unas nubes oscuras simulando humo. 
El detalle de la luna está hecho con uno de los pinceles del programa.
[Proceso Edición 1](img/edicionPuente0.PNG) [Proceso Edición 2](img/edicionPuente1.PNG) [Proceso Edición 3](img/edicionPuente2.PNG) [Proceso Edición 4](img/edicionPuente3.PNG) [Proceso Edición 5](img/edicionPuente4.PNG) [Proceso Edición 6](img/edicionPuente5.PNG) [Imagen de la lava](img/lava.jpg) 
[Imagen Sequía2](img/sequía2.jpg)

+ Reduccion del tamaño de las imágenes: Con el programa Adobe Photoshop he reducido el tamaño y la calidad de las imágenes para que ocuparan lo menos posible.[Proceso cambio de tamaño y calidad 1](img/calidad.JPG)[Proceso cambio de tamaño y calidad 2](img/tamaño.JPG)

+ Cambiar formato img: Para cambiar el formato de las imágenes lo hice de forma online en [https://www.aconvert.com](https://www.aconvert.com).

## Edición del vídeo:

Para poder utilizar la herramienta de edición movie maker he tenido que cambiar el formato del video, para ello he utilizado un [conversor de video online](https://video.online-convert.com/es/convertir-a-mp4). Para que ocupara menos también cambié el códec con la misma herramienta online a mpeg4.
Cortar el video para que empiece en 2017 y se corta con la herramienta Split.
En Edit aumento la velocidad a 1.75px para que se pueda visualizar la mayor parte del video y después vuelvo a utilizar la herramienta Split para que el video dure los 10s solicitados.
Para empezar el video he puesto la animación de flip. Otra modificación ha sido usar el efecto visual Hue - cycle entire colorspectrum y añadí audio al vídeo.
Después en el escaparate virtual dentro de la etiqueta <video> con el atributo poster puse una imágen que se muestra en el escaparate virtual antes de que se reproduzca el vídeo.
[Imagen poster](img/poster.jpg) [Vídeo](video/TemperaturaYprecepitaciónSigloXXI.mp4)

## Edición del audio:
Los audios utilizados en esta práctica incluído el del vídeo los descargué de la página [https://www.bensound.com](https://www.bensound.com).
Utilicé la herramienta audacity. Primero recorte el audio para que tuviera la duración requerida de un minuto.
Las modificaciones que he aplicado han sido las de aparecer y desvanecerse progresivamente y modificar los
graves y agudos.
[Proceso Edición 1](img/edicionAudio.PNG)

+ Cambiar formato de audio y video: Utilicé la herramienta Free Studio.

## Logo:
Lo cree en la página [https://es.freelogodesign.org](https://es.freelogodesign.org).

## Banner:
Para la creación del banner he utilizado la herramienta de Google Web Designer.
He creado el banner con unas dimensiones de 300x250 px.
El banner consta de dos páginas para poder crear la animación.

En la primera página he puesto una foto de fondo con dos textos.
El primer texto tiene una animación de entrada, que lo he hecho insertando en la 
línea de tiempo un fotograma clave y después arrastrando la caja de texto he dibujado el movimiento.
El segundo texto también tiene animación y he seguido la misma técnica que con el anterior, solo que
el fotograma clave empieza una vez que termina el anterior. En este texto también he añadido un componente
de área para tocar que nos redirige a la segunda página, esto lo explicaré más abajo.

En la segunda página también he puesto una foto de fondo con el texto fijo de volver con un componente
de área para tocar que nos redirige a la primera página y un texto con movimiento, he utilizado la 
misma técnica que en los textos animados anteriores.

Para crear la animación entre las dos páginas he añadido dos eventos uno que empieza en la primera página
cuando haces click en "HAZ CLICK" que te lleva a la segunda página con un efecto de transición.
En la segunda página he hecho lo mismo con el texto volver.
[Proceso creación del banner](img/creacion banner.PNG)[Imagen1 utilizada para el banner](img/cambio.jpg)[Imagen2 utilizada para el banner](img/futuro.jpg)