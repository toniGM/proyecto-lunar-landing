# PROYECTO LUNAR LANDING (LMSGI 02)
### ARGUMENTACIÓN TÉCNICA Y ESTÉTICA

Al inciar el documento _principal.html_, en la etiquta **head** he relacionado todas las características de la página, como el tipo de caracteres utilizados, el enlace a la hoja de estilos, titulo, descripción y contenido. 
Para cumplir con lo solicitado en la tarea he decidido crear dos menús que harán las veces de panel de opciones y panel de enlaces.
Los menús los he creado en el documento _Html_ con la etiqueta **UL** (Lista desordenada).
La imagen de la nave y la luna la he insertado mediante la etiqueta ***img**.
También he creado dos nuevas hojas a las que he llamado _agradecimientos.html_ e _instrucciones.html_, a las que se llegará desde la página principal y que contendrán datos e información del juego.

En el documento de estilos css enlazado es donde se estructura y organizan todos los elementos anteriormente creados. De la siguiente manera:

1. Body. Aquí he dado formato al texto (tamaño y color) y he añadido el fondo de la página (background-image)
2. SelectorIZ (UL y LI A). Lo he utilizado para dimensionar y dar formato al menú que estará en el lado izquierdo de la pantalla, posicionándolo de forma absoluta y a la izquerda (**position y float**)
3. SelectorDE (UL y LI A). Como en el menú anterior se ha dado el mismo formato, posicionándolo también de forma absoluta, pero en el lado derecho de la pantalla (**position: absolute y float: right**).
4. Al menú derecho, como son enlaces a otras páginas, le he añadido un efecto para que cuando se pase el ratón sobre uno de ellos, cambie su color (**hover**).
5. Para ubicar el planeta se ha utilizado el identificador antes declarado y que lo define (**navediv**), alineándolo siempre en el centro de la pantalla (**text-align: center;**).

