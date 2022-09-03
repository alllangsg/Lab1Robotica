# Laboratorio 1 de Robótica Industrial: Diseño de trayectorias con IRB 140 de ABB

## Miembros del equipo
Allan Giordy Serrato Gutiérrez  
Juan Fernando Ramírez Montes

## Resumen

En esta práctica se llevó a cabo la implementación de una ruta de trazado para un brazo robótico, teniendo por objetivo escribir en un tablero las iniciales de los nombres de los integrantes del equipo con un marcador.

Dentro de las actividades desarrolladas se encuentra el diseño de una herramienta capaz de sostener el marcador y ofrecer cierta flexibilidad en el desplazamiento con el fin de hacer los trazos sin dañar elementos cercanos, además se diseñó un tablero con la trayectoria a seguir para finalmente integrarlo todo en RobotStudio.

Una vez generado el código respectivo dentro de este entorno de desarrollo se ejecutó el programa en el robot real, obteniendo los resultados que se aprecian en los videos dentro del repositorio.

## Procedimiento

La primera tarea desarrollada consistió en el diseño de la herramienta encargada de sostener el marcador, esta contaba con la funcionalidad adicional de protección al marcador por medio de un sistema de amortiguación, haciendo que ante una aproximación acelerada del brazo al tablero no se vea afectado el marcador, basado en estas premisas, y teniendo en cuenta la geometría del portaherramientas se llegó al siguiente diseño:

<center> Imagen 1. Herramienta Impresa en 3D con PLA</center>

 ![HerramientaImagenEdit](https://user-images.githubusercontent.com/62154397/188254524-68327ef0-743f-4034-9f73-5154c1332d95.jpeg) 
 
Adicionalmente se le agregó una punta al portamarcadores dentro del diseño con el fin de contar con las distancias reales de la herramienta, adicional a esto se diseñó el tablero con las geometrías requeridas para dibujar las letras y el resultado fué el siguiente.

<center>  Imagen 2. Tablero para la trayetoria 1. </center>

![imagenTablero1Edit](https://user-images.githubusercontent.com/62154397/188254888-22171a92-4871-4f9c-ad77-c3b185bdb59d.png)

<center>  Imagen 3. Tablero para la trayetoria 2. </center>

![ImagenTablero2](https://user-images.githubusercontent.com/62154397/188254939-5064b949-cc0f-4bd8-8b6c-dc33a6f43961.png)


Finalmente se hicieron varios experimentos con el robot real, modificando el work object de orientación, implementando dos trazados distintos y probando posiciones del robot diferentes con el fin de explorar posibles limitaciones dentro del seguimiento de trayectorias, los resultados son mostrados en las siguientes imágenes.

<center>  Imagen 4. Robot realizando la trayectoria 1 en el laboratorio de robótica </center>

![ImagenRobotEdit](https://user-images.githubusercontent.com/62154397/188255033-7f0868cf-85c2-4ea6-8252-0a68b2540b24.png)

<center> Imagen 5.  Resultado prácica trayectoria 1.  </center>

![trayectoria1Edit](https://user-images.githubusercontent.com/62154397/188255180-d97d5d40-5c91-450d-a584-164ade551d1e.png)

<center>  Imagen 6. Resultado prácica trayectoria 2.  </center>

![FotoTrayectoria2Edit](https://user-images.githubusercontent.com/62154397/188255202-90a04482-e2d9-4cf8-b919-ebb183247c2b.jpeg)
