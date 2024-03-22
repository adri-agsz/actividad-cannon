# Juego de Objetivos con Turtle

Este es un programa de Python que utiliza el módulo `turtle` y `freegames` para crear un juego interactivo. En este juego, se generan objetivos 
aleatorios en la pantalla y el jugador debe hacer clic en la pantalla para lanzar una bola hacia los objetivos.

## Funciones

El programa consta de varias funciones:

- `tap(x, y)`: Responde al clic del usuario en la pantalla. Si la bola no está en la pantalla, establece la posición inicial de la bola y 
la velocidad en función de la posición del clic.
- `inside(xy)`: Verifica si el objetivo esta dentro de la pantalla.
- `draw()`: Dibuja la bola y los objetivos en la pantalla.
- `move()`: Mueve la bola y los objetivos. Genera nuevos objetivos aleatoriamente y elimina los objetivos que han sido golpeados por la bola.

## Uso

Para usar este programa, simplemente ejecútalo en un entorno de Python que tenga los módulos `turtle` y `freegames` instalados. 
Puedes interactuar con el programa haciendo clic en la pantalla para lanzar la bola hacia los objetivos.

¡Diviértete jugando con Turtle!
