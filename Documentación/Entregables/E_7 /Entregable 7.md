# Cuadro de Retos, Limitaciones y mejoras 
|  | Retos | Limitaciones | Mejoras |
| ---- | ---- | ---- | ---- |
| Electrónica | Realizar el circuito con las correspondientes conexiones en la placa | El circuito esquematizado en EasyEDA no se ha podido trasladar de forma exacta al Arduino nano y a consecuencia, la placa que empleamos en nuestro prototipo. Esto debido a que el EasyEDA utiliza de dos a más capas, mientras que la placa que necesitamos, una.
 |   |
 
 | Software| Suavizar el movimiento del servomotor. Mejorar la velocidad de giro del servomotor. |El movimiento del servomotor se tornaba brusco debido a que se movía de acuerdo a solo un valor medido. El código de arduino funcionaba a una velocidad baja, debido a que el sensor y el arduino tardaban un tiempo relativamente largo en medir los valores. | Para suavizar el movimiento util izamos la  media móvil, con ayuda de un arreglo llamado “datosGuardados”, el cual almacena y guarda los datos medidos con anterioridad.Para mejorar la velocidad del movimiento se utilizó la función delayMicroseconds(). |
 

