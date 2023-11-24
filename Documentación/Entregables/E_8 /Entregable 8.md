Tabla de verificación de diseño

Software

Dedo pulgar protésico enfocado en la fuerza de agarre y agarre pinza para amputaciones transmetacarpianas.

| Funcionalidad | Cumplimiento  | |
|----| ---- | ---- |
| | SÍ | NO |
| Medir |X| |
| Almacenar |X| |
| Procesar |X| |
| Flexionar |X| |
| Regular |X| |


## Medir: Mide el grado de flexión del dedo.

## Almacenar: El dispositivo almacena un tipo de dato, el grado de flexión y lo envía al motor.

## Procesar: Se procesa el ángulo de flexión y se traslada al servomotor mediante el arduino.

## Flexionar: La prótesis realiza la flexión necesaria de acuerdo a lo que procesa el sensor.

## Regular: Regular la potencia del servomotor dependiendo del ángulo de flexión.



Hardware

¿Cuánto peso debe tener la prótesis en conjunto?
La prótesis en conjunto debe tener alrededor de 600 g.
¿Cuánto peso debe tener la muñequeras en conjunto con la parte electrónica?
La muñequera en conjunto con la parte electrónica debe pesar alrededor de 300 g.
¿De qué material es la prótesis y muñequera?
Tanto la prótesis como la muñequera son de material PLA.
¿Qué dimensiones debe tener la prótesis?
La prótesis debe ser lo más cercana posible al tamaño del pulgar, en conjunto con una unión para soportar el servomotor adyacente y un socket adecuado para el muñón, es decir de una longitud de 14.5 cm x 7.2 cm x 16 cm aproximadamente.
¿Qué dimensiones debe tener la muñequera?
La muñequera debe tener 12.3 cm x 5 cm x 3.6 cm.


|Requerimiento de diseño | Resultado del test| 
|----| ---- | 
|La prótesis debe ser capaz de soportar y/o cargar más de un kilogramo sin ayuda de algún dedo externo a la prótesis.| Mediante la realización de las pruebas, se pudo observar que la prótesis fue capaz de cargar más de un kilogramo, así como ejercer un agarre con fuerza a superficies rugosas, ya que presentó una dificultad al momento de intentar sujetar superficies lisas debido a la característica lisa del PLA para el dedal de la prótesis.|
|La prótesis debe ser lo más estética posible para el usuario.|Después de realizar el ensamblado final de la prótesis, se llegó a la conclusión de que la prótesis no cumple con los estándares estéticos esperados, puesto que ocupa un espacio considerable y mayor al óptimo para poder soportar al servomotor encargado del movimiento.| 
|La prótesis en conjunto con la muñequera debe ser tan cómoda como sea posible y no debe dañar ni la zona del muñón del paciente, ni la zona del brazo en la que irá la muñequera.|Mediante el uso de la silicona médica para las zonas en contacto con la piel de la prótesis, se pudo observar un cierto grado de comodidad, anulando de manera significativa los posibles rasgos de dolor que podría crear el contacto de la piel con el material de PLA de la prótesis.| 
|La prótesis debe reaccionar correctamente al movimiento graduado del dedo índice para flexionar cada parte del dedo pulgar articulado.|Se observó un correcto funcionamiento y correlación entre la flexión del dedo índice y el grado de fuerza de agarre y flexión de la prótesis.| 
| La prótesis debe ser resistente cuando se la somete a un gran esfuerzo, es decir, no debe romperse o presentar algún posible tipo de fractura.|Al someter la prótesis a cargas desde 1 kilogramo a 4 kilogramos, se confirma que no llegó a presentarse alguna fractura en la misma; sin embargo, sí se observó que se deforma ante cargas muy pesadas, soltándolas y regresando el dedo a su estado inicial.| 
|La prótesis debe contener elementos de carácter accesible en términos económicos, así como un ensamblaje práctico y piezas replicables|Mediante el ensamblaje final de la prótesis se pudo concluir que los gastos económicos no superan los 1000 soles. Además, es resaltable el hecho de que la prótesis no presenta un ensamblaje de alta dificultad; sin embargo, debido a la replicación de la zona del muñón para el socket y la naturaleza de otras piezas únicas, la replicación de los planos sería altamente complicada. | 
