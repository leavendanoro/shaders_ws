# Taller de shaders

## Propósito

Estudiar los [patrones de diseño de shaders](http://visualcomputing.github.io/Shaders/#/4).

## Tarea

1. Hacer un _benchmark_ entre la implementación por software y la de shaders de varias máscaras de convolución aplicadas a imágenes y video.
2. Implementar un modelo de iluminación que combine luz ambiental con varias fuentes puntuales de luz especular y difusa. Tener presente _factores de atenuación_ para las fuentes de iluminación puntuales.
3. (grupos de dos o más) Implementar el [bump mapping](https://en.wikipedia.org/wiki/Bump_mapping).

## Integrantes

Complete la tabla:

| Integrante | github nick |
|------------|-------------|
|Leonardo Avendaño Rocha            |leavendanoro             |

## Informe

En el punto uno se tienen 3 carpetas, la carpeta _p1_ tiene la aplicacion de distintas máscaras de convolución, que se pueden cambiar con los número 1 al 5, en imagen y video sobre una figura de una lata con la medición de cuadros por segundo, en la carpeta _p1_frames_ se tiene la misma implementación pero solo para video en 2D, en la carpeta _video_frame_ se tiene la implementación por software para hacer la comparación.

Para el punto dos se tiene la implementación de distintos tipos de luz. Con la ayuda de la librería nub se puede interactuar con una fuente de luz para modificar la escena.

## Entrega

Fecha límite ~~Lunes 1/7/19~~ Domingo 7/7/19 a las 24h. Sustentaciones: 10/7/19 y 11/7/19.
