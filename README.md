CALCULADORA
HOJA HTML:

Creacion de clase "contenedor" que contiene a todos los elementos de la calculadora, sus hijos o subclases son "pantalla" y "teclado".

Clase "pantalla", es la que se encarga de mostrar las operaciones.

Clase "teclado", se encarga de contener a cada tecla de la calculadora, numeros, operadores, y mas.

Cada subclase de clase "teclado" es un contenedor de cada etiqueta 'button' que contiene el signo o numero de la calculadora, y en el caso de la subclase "tecla" que la segunda clase de cada boton es para dar un estilo personalizado.

La subclase de la clase "teclado", "operadores", contiene un enlace svg que es el estilo de icono de bootstrap. 

HOJA DE ESTILO CSS:

Definicion de variables 

En la clase "contenedor" trabajamos con el formato grid y dividimos la caja en dos, "pantalla" y "teclado".

A la clase "pantalla" le asignamos las propiedas de border radius y border con el valor solid para que tenga borde linea redondeado y que se vean de color blanco con un grosor de 1px.

En la clase "teclado" tambien trabajamos con el sistema de grillas, GRID. Lo dividimos en cuatro columnas y cinco filas.

Con la clase "tecla" le damos border radius con valor de 50% para que su borde sea un círculo.

A cada clase de buton le aignamos su ubicacion segun de como estaba cuadriculado en la clase "teclado".