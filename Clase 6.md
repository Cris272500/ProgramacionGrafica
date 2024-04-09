## <h1 style="text-align: center;">Imágenes Ráster</h1>
Un **raster** es una estructura de datos formada por una matriz de pixeles. Posee las siguientes caracteristicas:
* Se organizan en columnas y filas
* Dan lugar a una cuadricula de celdas
* Presentan el valor que representa la informacion en cuestion

Con un raster se generan imagenes mediante una cuadricula rectangular de pixeles. A cada uno de los pixeles se les asigna un valor de color y una ubicacion

* A la imagen rasterizada se le conoce como **mapa de bits** o bitmap.

* La calidad de un raster se mide por la profundidad de:
	* Color
	* Ancho
	* Altura
		> Estas caracteristicas determinan cuantos colores diferentes para guardar cada pixel

* Los raster son fotogramas aereos digitales o incluso mapas escaneados

#### <u>Ventajas de almacenar datos en forma de raster</u>
1. Estructura de datos simples
2. Formato patente para análisis espacial y estadístico avanzado
3. Capacidad de representar surpeficies continuas y llevar a cabo analisis de superficie
4. Capacidad de almacenar
	* Puntos
	* Lineas
	* Poligionos
	* Superficies
	de manera uniforme
5. Capacidad de llevar a cabo superposiciones rapidas con datasets mas complejas.
***
#### <u>Caracteristicas generales de datos raster</u>
1. En los datasets raster, cada celda (pixel) posee un valor.
2. Los valores de cada celda pueden ser
	- Positivos o negativos
	- Enteros o de punto flotante
	#### <u>Positivos</u>
	Se utilizan para representar datos categoricos o discretos
	#### <u>Punto flotante</u>
	Representar las superficies continuas
3. El tamaño de celda determina el grosor o la delgadez con la que aparecerán los patrones o las entidades en el raster.
	> Cuando más pequeño sea el tamaño de la celda, más suave o más detallado será el ráster. Sin embargo, cuanto mayor sea el numero de celdas, mas tiempo tardara en procesar, aumentándose a su vez en la demanda de espacio de almacenamiento.

***
#### <u>Proyeccion universal transversal de Mercator (UTM)</u>
Es un sistema de proyeccion cartografico basado en cuadriculas con el cual se pueden referenciar puntos sobre la superficie terrestre

***
#### <u>Dispositivos raster</u>
* Impresora de Matriz
* Impresora Laser
 * Monitores
## <h1 style="text-align: center;">Pixeles</h1>
El termino "pixel" proviene de la contraccion de las palabras "picture" y "element" (elemento de imagen en ingles).

Cada pixel tiene una posicion especifica y esta asociado con un valor que determina su color y brillo. 

Estos valores pueden representarse en diferentes sistema de color, como RGB (rojo, verde, azul) o CMYK (cian, magenta, amarillo, negro), dependiendo del dispositivo o el contexto.

> Al combinar millones de pixeles en una matriz, se crea una representacion visual completa que los ojos humanos perciben como una imagen continua.

#### <u>Densidad de pixeles</u>
La densidad de pixeles, tambien conocida como **PPI** (pixeles por pulgada), se refiere a la cantidad de pixeles presentes en una pantalla por unidad de longitud, generalmente medida en pulgadas. 
* Indica la nitidez y la calidad visual que en una pantalla puede proporcionar.

En pantallas con una mayor densidad de pixeles, los pixeles individuales son mas pequeños y estan mas cerca unos de otros
* Lo que resulta en una mayor nitidez y una mayor capacidad para mostrar detalles finos. 
* En pantallas con una menor densidad de pixeles, los pixeles son mas grandes y estan mas espaciados
	* los detalles son menos nítidos y que los elementos de la imagen se ven mas grandes.
***
#### <u>Resolucion</u>
La resolucion de una imagen o pantalla se refiere a la cantidad de pixeles que la componen.
> Una mayor resolucion implica una mayor densidad de pixeles, y por lo tanto, una imagen mas detallada y nitida.

Por ejemplo, una pantalla de alta definicion puede tener una resolucion de 1920 x 1080 pixeles, lo que significa que hay 1920 pixeles en el eje horizontal y 1080 pixeles en el eje vertical.
#### <p style="color: blue;">Estandares de resolucion</p>
Existen varios estandares comunes de resolucion utilizados en imagenes digitales y pantallas.

Algunos de ellos incluyen:
* **VGA (640 x 480)**
	* Video Graphics Array, es un estandar de resolucion que se utiliza principalmente para pantallas y proyectores de menor calidad.
* **HD (High Definition)**
	* Se refiere a varias resoluciones de alta definicion, como 720p (1280 x )
	// Hasta aqui llegamos