# Cuadro de Retos, Limitaciones y mejoras 
|  | Retos | Limitaciones | Mejoras |
| ---- | ---- | ---- | ---- |
| Electrónica | Realizar el circuito con las correspondientes conexiones en la placa | El circuito esquematizado en EasyEDA no se ha podido trasladar de forma exacta al Arduino nano y a consecuencia, la placa que empleamos en nuestro prototipo. Esto debido a que el EasyEDA utiliza de dos a más capas, mientras que la placa que necesitamos, una.
 |   |
| Software |Realizar el circuito con las correspondientes conexiones en la placa |El movimiento del servomotor se tornaba brusco debido a que se movía de acuerdo a solo un valor medido.


El código de arduino funcionaba a una velocidad baja, debido a que el sensor y el arduino tardaban un tiempo relativamente largo en medir los valores. 
 |Para suavizar el movimiento utilizamos la  media móvil, con ayuda de un arreglo llamado “datosGuardados”, el cual almacena y guarda los datos medidos con anterioridad.

Para mejorar la velocidad del movimiento se utilizó la función delayMicroseconds(). |

| Modelado 3D y Manufactura digital| Imprimir el modelado con los agujeros definidos.

Rehacer el modelado del socket, el case del servomotor y el de la muñequera.
|La calidad de impresión de cada capa no es tan alta debido al tamaño de los agujeros en el modelado.

Para modelar un socket adaptado a un muñón, se requieren medidas exactas.

La cantidad de material disponible para el equipo estaba limitada.|Para el case, se realizó un corte en la zona en la que se colocarán las correas, para que se ajuste a la muñeca con un ángulo de 150°. Además, se mejoró la forma de la muñequera: la parte más próxima a la mano tiene un diámetro menor y la zona que está en el brazo, uno mayor.  |
