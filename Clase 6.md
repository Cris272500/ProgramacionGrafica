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

#### <u>Caracteristicas generales de datos raster</u>
1. En los datasets raster, cada celda (pixel) posee un valor.
2. Los valores de cada celda pueden ser
	- Positivos o negativos
	- Enteros o de punto flotante
	#### <u>Positivos</u>
	Se utilizan para representar datos categoricos o discretos
	#### <u>Punto flotante</u>
	Representar las superficies continuas
	