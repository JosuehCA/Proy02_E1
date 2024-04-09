# Proy02_E1
Repo del Proyecto #2 de Teoría de Lenguajes de Programación, Equipo 1

## Integrantes:

* Aguilar Pérez Johan Ricardo
* Alcocer Herrera Julio César
* Cabrera Alcocer Herberth Josueh
* Córdova Martínez Ricardo

## Descripción de la actividad

Recopilación de 10 ejercicios de programación funcional utlizando funciones recursivas en el lenguaje de Racket, implementados en un Jupyter Notebook con ayuda del kernel iRacket para el mismo. Para cada ejercicio se definió una función específica que retorna el resultado correspondiente.

## Proceso de instalación: Jupyter Notebook

Primero debemos asegurarnos de tener instalado Jupyter Notebook. En la terminal del dispositivo (cmd para Windows), debemos asegurarnos de tener instalado Python, preferiblemente la versión más estable. Para ello, el comando `python --version`, o `python3 --version` debe devolvernos la versión de Python actualmente instalada y accesible desde el PATH. De no contar con Python, descargarlo directamente desde la [página oficial](https://www.python.org/downloads/) y seguir los pasos correspondientes. 

Seguidamente, debemos asegurarnos de tener pip instalado. Para corroborarlo, nos apoyamos del comando `pip --version` o `pip3 --version` y, de no contar con una versión instalada, lo instalamos con `python get-pip.py`, o `python3 get-pip.py`.

El siguiente paso consiste en instalar Jupyter Notebook, con lo cual nos apoyaremos del administrador de paquetes de Python "pip" que recién mencionamos. Basta con escribir el comando `pip install jupyter` o `pip3 install jupyter` y se iniciará la descarga e instalación del mismo. Podremos seguidamente corroborar la versión instalada con `jupyer --version`.

Para poder ejecutar los bloques de código, es necesario tener instalado el kernel de iRacket, diseñado para soportar el lenguaje Racket dentro del Jupyter Notebook. Para ello, debemos descargar Racket en primer lugar, lo cual puede realizarse [desde su página oficial](https://download.racket-lang.org/), donde solo debemos descargar el ejecutable y seguir las instrucciones de instalación. Seguidamente, nos dirigiremos a la carpeta donde realizamos la instalación, y en la barra de búsqueda escribiremos `cmd`, para poder acceder a todos los archivos dentro de la carpeta de Racket desde el la línea de comandos. A continuación, escribiremos `raco pkg install iracket` para descargar el paquete de iRacket, escribiendo `Y` donde corresponda para instalar las dependencias necesarias, y al finalizar la descarga, el comando `raco iracket install` nos instalará el kernel directamente en la carpeta de Racket. Ahora para poder acceder a él con el jupyter notebook, bastará con utilizar la misma ventana cmd que abrimos hace un momento, la cual tiene acceso a los archivos dentro de la carpeta Racket. De desearlo, podemos también agregar los archivos de Racket directamente al PATH para poder acceder a ellos desde cualquier ubicación de la computadora.

Ahora, ingresando el comando `jupyter notebook` directamente en la terminal/cmd, podremos acceder al mismo a través de un servidor local que se abre para nosotros. Es aquí donde procederemos a hacer click en el botón `upload` y seleccionar el archivo `Proy02_E1.ipynb` para acceder a su contenido e interactuar con los bloques de código, seleccionando el kernel de iRacket. 

## Ejecución de los problemas

La estructura de cada problema es descripción -> definición de la función -> prueba de funcionamiento. La última línea de cada bloque de código corresponde a la prueba de la función. El usuario es libre de cambiar los parámetros de esta para observar su funcionamiento, y ejecutarla con `ctrl` o `cmd` + `enter`, asegurándose de tener seleccionado el bloque correspondiente.
