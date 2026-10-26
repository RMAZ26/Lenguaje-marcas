Prefiero Display Flex por que me permite que se organize de una manera mas automatica ya que no tienen encuenta los margin , padding etc.. por lo que no tienes que estar calculando nada

## APARTADO C
1 ¿qué diferencia hay entre margin y padding?
Margin o margen Es el espacio exterior de la caja. Sirve para separar el elemento de otros elementos que lo rodean o de los bordes del contenedor
Padding o relleno Es el espacio interior de la caja. Se encuentra entre el contenido (texto o imágenes) y el borde del propio elemento, haciendo que la caja sea más grande por dentro.

2 ¿Por qué saltaba la tercera tarjeta de línea?
Al usar display: inline-block, el navegador interpreta los saltos de línea y espacios en blanco del código HTML como un carácter de espacio real. Aunque las tres tarjetas sumaban exactamente 660px de ancho para un contenedor de 800px, al sumarle esos espacios  invisibles entre las etiquetas junto con los márgenes o bordes, el ancho total superaba el límite del contenedor, obligando a la tercera tarjeta a bajar de línea.

3 ¿Qué propiedades ignoraba el span y por qué?
El span es un elemento en línea inline, por lo que ignora el ancho width, el alto height y los márgenes/paddings verticales. Esto ocurre porque está diseñado para integrarse dentro de líneas de texto y solo ocupa el espacio estricto de su contenido.

4 ¿Qué hace display: none con el espacio que ocupaba la caja?
display: none elimina el elemento por completo del flujo visual de la página.  display: none hace que la caja desaparezca por completo y no deja ningún hueco, permitiendo que los elementos de su alrededor ocupen su sitio automáticamente.