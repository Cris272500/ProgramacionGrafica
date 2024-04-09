## <h1 style="text-align: center;">API: Application Programming Interface</h1>
Programa que para programar provee piezas de alto nivel (lenguaje, bibliotecas) que se ensamblan para armar una aplicacion.

Es una biblioteca de rutinas para interactuar con el hardware.
## <h1 style="text-align: center;">GUI: Graphical user Interface</h1>
Es una biblioteca para programar la interaccion del usuario con el programa mediante dispositivos de entrada y utilizando ventanas y otras metaforas graficas.

Proveen funciones tipo __callback__ para reaccionar a la entrada de datos a traves de:
- Teclado
- Mouse
- Menu
- Widgets
## <h1 style="text-align: center;">API'S Graficas</h1>
#### <u>OpenGL</u>
Provee funciones para casi todo el pipeline y es soportado por casi todos los sistemas operativos.

Esta implementado en hardware en casi todas las placas graficas (la GPU) se encarga de hacer las operaciones
***
#### <u>Direct 3D</u>
Es una herramienta que permite a los desarrolladores trabajar con gráficos tridimensionales en aplicaciones, pero solo para windows
***
#### <u>X11, PostScript, PDF</u>
Solo 2D y por Software
***
#### <u>HPGL</u>
Caido, casi no usado pero es un ejemplo de API vectorial
## <h1 style="text-align: center;">GUI'S gratuitas con ventana OpenGL</h1>
#### <u>AUX</u>
Para aprender OpenGL, excesivamente simple, ya no se utiliza
#### <u>GLUT</u>
Simple y estable, no cubre todas las necesidades
#### <u>QT, FLTK, wxWidgets</u>
Muy completas

## <h1 style="text-align: center;">OpenGL Utility Library (GLUT)</h1>
* Abre ventanas de OpenGL
* Callbacks para interaccion con hardware
	* Recibir input del teclado y mouse
	* Temporizador (idle callback)
	* Resize y redraw (render)
* Menus muy modestos
* Estable, sencillo y eficiente
* No posee widgets (sliders, cuadros de dialogo)
* No soporta selector de archivos
* No soporta la reduita del raton
* No se actualiza desde hace mucho tiempo
## <h1 style="text-align: center;">Lineamientos de un programa grafico</h1>
* Creacion de ventana de aplicacion
* Creacion de ventanas de dibujo e interaccion
### <u>GUI</u>
Usando declaraciones de callbacks
* Funciones del mouse
* Funciones de los menus
* Funciones del teclado
### <u>OpenGL</u>
* Variables de estado usuales
* Sistema de coordenadas estandar
* Iluminacion inicial
* Camara y sistema de Proyeccion usual
* Loop de ejecucion
	* Dibujar
	* Reaccionar a los eventos
	* Alterar el contenido o los metodos
