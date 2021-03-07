# Solar_system
Simulación de un sistema solar con figuras 3D y texturas utilizando imágenes.
<!-- PROJECT LOGO -->
<br />
<p align="center">
  <h3 align="center">Simulación del sistema solar</h3>

  <p align="center">
    ¡Sistema solar en 3D!
    <br />
      <a href="https://github.com/carlosepb/Solar_system"><strong>Explorar repositorio»</strong></a>
    <br />
    <br />
      <a href="https://github.com/carlosepb/Solar_system/blob/main/images/animation.gif">Ver Demo</a>
      ·
      <a href="https://github.com/carlosepb/Solar_system/issues">Reportar Error</a>
      ·
      <a href="https://github.com/carlosepb/Solar_system/issues">Solicitar Colaboración</a>
    </p>
  </p>



<!-- TABLE OF CONTENTS -->
<details open="open">
  <summary>Tabla de Contenido</summary>
  <ol>
    <li>
      <a href="#sobre-el-proyecto">Sobre el Proyecto</a>
      <ul>
        <li><a href="#herramientas-de-desarrollo">Herramientas de Desarrollo</a></li>
      </ul>
    </li>
    <li><a href="#trabajo-realizado">Trabajo Realizado</a></li>
    <li>
      <a href="#empezando">Empezando</a>
      <ul>
        <li><a href="#prerrequisitos">Prerrequisitos</a></li>
        <li><a href="#instalación">Instalación</a></li>
        <li><a href="#ejecutar">Ejecutar</a></li>
      </ul>
    </li>
    <li><a href="#hoja-de-ruta">Hoja de Ruta</a></li>
    <li><a href="#licencia">Licencia</a></li>
    <li><a href="#contacto">Contacto</a></li>
    <li><a href="#agradecimientos">Agradecimientos</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## Sobre el Proyecto
<p align="justify">
Pequeña aplicación para convertir una figura en 2D en 3D proyectando sus vértices a través del eje z consiguiendo así darle profundidad generando una figura simétrica.
Para esto al ejecutar tendremos una primera pantalla dividida por una línea blanca en dos mitades en la que podremos dibujar la figura que queremos proyectar en el lado izquierdo terminando el modo edición al crear un vértice en el lado izquierdo, pudiendo borrar la figura dibujada en cualquier momento pulsando la tecla espacio(imagen_1.0).
</p>
<p align="center"><img src="images/planeta.JPG" alt="draw interface" width="400" height="425"></br>imagen_1.0(Pause)</p>
<p align="justify">
Una vez hacemos clic en la parte izquierda de la primera pantalla del programa se generará la figura en 3D, pudiendo borrarla y volver a la zona de dibujo pulsando la tecla espacio(imagen_2.0).
</p>
<p align="center"><img src="images/nave.JPG" alt="figure generated" width="400" height="425"></br>imagen_2.0(Jugando)</p>
<p align="justify">
Como podemos ver en el gif inferior podemos dibujar haciendo clic en distintos puntos de la zona de dibujo y dejando que esta se una automáticamente. También podemos ver unas cuantas figuras generadas y como con solo pulsar espacio borramos la figura actual y podemos proceder a dibujar otra sin ningún problema(imagen_3.0).
</p>
<p align="center"><img src="images/animationSol.gif" alt="draw and generate" width="400" height="425"></br>imagen_3.0(Saque)</p>

## Trabajo Realizado
<p align="justify">
En cada una de las pantallas tendremos un mensaje en la parte superior izquierda en la que podemos ver el comando de borrado que consiste únicamente en pulsar la tecla espacio.
</p>
<p align="justify">
Para dibujar las líneas que unen los vértices de la pantalla de dibujo se utilizan la variables mousePressed, mouseX y mouseY para saber cuando se interactúa usando el ratón y las coordenada en las que se ha hecho clic, además de si se encuentra en la de finalizar dibujo.
</p>
<p align="justify">
Se ha creado una pequeña clase con solo dos variables y un constructor para guardar las coordenadas de cada vértice y almacenarlas en un arraylist para el momento de dibujar la figura y rotar los vértices hacerlo con mayor facilidad independientemente del número de estos que haya.
</p>
<p align="justify">
Se utiliza la función translate para mover la figura ya generada por la interfaz a modo de poder visualizarla desde distintos puntos, esta seguirá el puntero del ratón.
</p>
<p align="justify">
Para rotar los vértices se ha creado una función a la que se le pasan el vértice actual y el inmediatamente inferior además del ángulo el cual definirá el número de polígonos que tendrá la figura al rotar(a mayor ángulo mas cuadrada será y menor ángulo mas suavizado será el resultado).
</p>
<p align="justify">
La grabación de gif está disponible pero para una ejecución mas optima se encuentra comentada en el código, en caso de querer usarla descomentar las líneas 20, 21, 80 y 92. Para parar la grabación haremos un clic sobre la pantalla ya que esta se encuentra en un evento de ratón pulsado.
</p>

## Herramientas de Desarrollo

* [Processing3](https://processing.org/download/)

<!-- GETTING STARTED -->
## Empezando

<p align="justify">
Para modificar la aplicación necesitará instalar el entorno de desarrollo Processing3 y la herramienta GifAnimation si desea generar imagenes en formato ".gif". En caso de que solo quiera ejecutar la versión release no será necesario que instale nada y puede pasar directamente al paso Ejecutar->Release.
</p>

### Prerrequisitos

* Descargar y descomprimir Processing3, lo puedes encontrar [aquí](https://processing.org/download/).

### Instalación
1. Para exportar a un archivo con formato gif animado es necesario instalar GifAnimation, lo puede encontrar [aquí](https://github.com/extrapixel/gif-animation).
   
### Ejecutar

1. Release.
    * Descomprimir rar.
    * Entrar a la versión correspondiente a nuestro windows.
    * Lanzar SolidOfRevolution.exe.
2. Proyecto.
    * Descomprimir rar.
    * Ejecutar Processin3.
    * Archivo->Abrir...

<!-- ROADMAP -->
## Hoja de Ruta

En este momento no hay planes de mejorar la aplicación.

<!-- LICENSE -->
## Licencia

Software completamente libre para copiar o distribuir.

<!-- CONTACT -->
## Contacto

Autor: Carlos Eduardo Pacichana Bastidas

Email: carlos.eduardo.pacichana@gmail.com  carlos.pacichana101@alu.ulpgc.es

Enlace al proyecto: [https://github.com/carlosepb/Figure2DTo3DUsingSolidOfRevolution](https://github.com/carlosepb/Figure2DTo3DUsingSolidOfRevolution)

<!-- ACKNOWLEDGEMENTS -->
## Agradecimientos
* [Processing](https://processing.org/)
* [Gif-animation](https://github.com/extrapixel/gif-animation)
* [Funprogramming](https://funprogramming.org/)
* [Text](https://processing.org/reference/text_.html)
