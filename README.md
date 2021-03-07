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
      <a href="https://github.com/carlosepb/Solar_system/blob/main/images/animationSol.gif">Ver Demo</a>
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
Aplicación que simula un sistema solar con solo cinco planetas (Mercurio, Venus, La Tierra, Marte y Júpiter) y tres lunas (La Luna, Europa e IO).  Al empezar el programa vemos todos los planetas empezar en la misma posición del eje X pero ya que todos llevan una velocidad de orbita distinta se separarán.
</p>
<p align="center"><img src="images/planeta.JPG" alt="draw planeta" width="600" height="425"></br>imagen_1.0(Planetas)</p>
<p align="justify">
A modo de preparación para la siguiente practica se a añadido un cubo el cual podemos desplazar por la interfaz con las flechas del teclado para moverlo por los ejes X e Y, además de poder desplazarlo por el eje Z usando las teclas W (alejar) y S(acercar).(imagen_2.0).
</p>
<p align="center"><img src="images/nave.JPG" alt="cubo" width="600" height="425"></br>imagen_2.0(Cubo)</p>
<p align="justify">
En el gif inferior podemos ver los planetas orbitando a distintas distancias del sol, además de cada cuerpo con su nombre que no varía en su posición ni en su orientación. También cada cuerpo rotando sobre si mismo.(imagen_3.0).
</p>
<p align="center"><img src="images/animationSol.gif" alt="rotate" width="600" height="425"></br>imagen_3.0(Orbitando)</p>

## Trabajo Realizado
<p align="justify">
Para el uso de los cuerpos celestes se crea un objeto PShape para almacenar su tamaño y textura, para cada elemento tendremos un ángulo de rotación distinto que permitirá que los planetas tengan una velocidad de orbita diferente.
</p>
<p align="justify">
Para el fondo ser carga una imagen y se posiciona contiguas y se van desplazando a la izquierda para dar la sensación de movimiento.
</p>
<p align="justify">
Para posicionar los elementos por la interfaz se usa el método translade(), y para conseguir las orbitas y que los cuerpos giren el método rotate().
</p>
<p align="justify">
Como preparación para la siguiente práctica se ha añadido un cubo el cual podremos desplazar por la interfaz haciendo uso de los eventos de tecla pulsada y liberada. 
</p>

## Herramientas de Desarrollo

* [Processing3](https://processing.org/download/)

<!-- GETTING STARTED -->
## Empezando

<p align="justify">
Para modificar la aplicación necesitará instalar el entorno de desarrollo Processing3. En caso de que solo quiera ejecutar la versión release no será necesario que instale nada y puede pasar directamente al paso Ejecutar->Release.
</p>

### Prerrequisitos

* Descargar y descomprimir Processing3, lo puedes encontrar [aquí](https://processing.org/download/).

### Instalación
1. Para exportar a un archivo con formato gif animado es necesario instalar GifAnimation, lo puede encontrar [aquí](https://github.com/extrapixel/gif-animation).
   
### Ejecutar

1. Release.
    * Descomprimir rar.
    * Entrar a la versión correspondiente a nuestro windows.
    * Lanzar sistema_solar.exe.
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

Enlace al proyecto: [https://github.com/carlosepb/Solar_system](https://github.com/carlosepb/Solar_system)

<!-- ACKNOWLEDGEMENTS -->
## Agradecimientos
* [Processing](https://processing.org/)
* [Gif-animation](https://github.com/extrapixel/gif-animation)
* [Funprogramming](https://funprogramming.org/)
* [Text](https://processing.org/reference/text_.html)
* [Texturas](https://pixabay.com/es/images/search/planeta/)
