# MI PRIMER PROYECTO TERMINADO

En este proyecto sencillo simularemos la pagina de netflix, especificamente donde se muestran los perfiles. Es una tarea propuesta por mi maestro de programación para observar los conocimientos adquiridos en HTML y CSS. 

## ¿Como lo hice?:
1.  Se creó un contenedor para integrar todos los elementos de la página, y para agregar algunas estilos que cumplan su función en toda la página en general por ejemplo: color de fondo de la pagina, posicionamiento (en una coordenada fija con respecto al navegador) y propiedades relacionadas al texto. 

1. Dentro del contenedor, se usa una clase llamada "ordenarContenedor" con el fin de crear algunas reglas de estilos y algunos ajustes de posicionamiento ya que esta clases contendrá los elementos: imágenes, nombre, avatar, y otros botones; hacemos que esta clase se convierta en un contenedor **"Caja flexible" ** de modo que los elementos integrados en ellas se puedan redimensionar según el ancho del navegador y según los márgenes, la alineación y  las dimensiones de los objetos que integramos. 

1. dentro del contenedor y de la clase "ordenarContenedor"(caja flexible) creamos otra clase "titulo_avatares" que llevará algunos estilos y reglas para: los titulos y los avatares. Esta clase la encerramos con la propiedad max-wight; (anchura y altura maxima de 78%) con el fin de que los elementos tanto avatar como nombre se mantengan en ese rango de ancho y de alto. 

1. El titulo principal está encerrado en una clase donde se colocaron sus reglas de estilos solo para  el titulo: tipo de letra, color, tamaño alineación, entre otros. 

1. En la página index de html creamos una lista no ordenada (ul) con la regla de estilos tipo clase(lista_avatar): cada itens de la lista(li) esta encerrado por una clase(decoracion_lista): que contiene tres clases:
- "Avatar": imágenes, tamaños, márgenes, decoración bordes, cursor, y más.
- "nombre":tipo y tamaño de fuente, color, alineacion y margenes.
- "candaito": imagen en forma de candando con estilos. 

6.. En otra clase llamada "boton" la usamos para colocar un boton que simule el boton de "administrar perfiles" de netflix. este boton lleva estilos: border, tipo de letra, tamaño, margen, disposicion del texto, color y mas. 

##### otros estilos: 
se uso la pseudo clase ":hover" la cual permite mostrar los estilos cuando el mouse se posicione en el objeto que contiene la pseudoclase. 

# link de la pagina creada

