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

Adicionalmente se le agregó una punta al portamarcadores dentro del diseño con el fin de contar con las distancias reales de la herramienta, adicional a esto se diseñó el tablero con las geometrías requeridas para dibujar las letras y el resultado fué el siguiente.

Finalmente se hicieron varios experimentos con el robot real, modificando el work object de orientación, implementando dos trazados distintos y probando posiciones del robot diferentes con el fin de explorar posibles limitaciones dentro del seguimiento de trayectorias, los resultados son mostrados en las siguientes imágenes.

