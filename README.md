# Fundamentos de Biodiseño - Biomecánica
## Integrantes - Roles
* PALMA ARAUJO GLORIA CECILIA - Coordinadora general, modelado 2D
* GAMARRA LEYVA ALEJANDRA IVONNE - Coordinadora de Investigación y Redacción, Electrónica
* ARANGO ESCALANTE NICOLAS THOMAS - Programación, manejo del GitHub
* ABANTO TRUJILLO ADRIANA TAYLI - Coordinadora de Programación, electrónica
* TELLO OCAÑA MIGUEL ANGEL - Modelado e Impresión 3D
* GORBEÑA GALARZA RODRIGO JOAQUIN - Coordinador diseño 3D

## Buscamos poder devolver utilidad mecánica a la mano

###### Dentro del caso clinico estudiado decidimos enfocarnos en la amputación transmetacarpiana del pulgar, en específico por la necesidad del usuario de recuperar su EMPLEO, lo cual también implica su propia sustentabilidad.

### Caso Clínico:

###### El paciente es un técnico electricista reparador de torres de alta tensión. Sufrió quemaduras de 3° grado en MMSS derecho (mano) y quemadura de 4° grado en MMII derecho, debido al alto riesgo de infección y complicaciones presentó amputación transmetacarpiana y desarticulación interfalángica proximal del dedo medio, por otro lado, presentó amputación transtibial en MMII, adicionalmente presentó trastorno sensorial táctil actualmente se encuentra desempleado y busca inserción laboral adaptada. 

#### En contexto

###### Sobre las amputaciones en el Perú, se encontró que, en una revisión de 1290 casos de pacientes con alguna amputación, 108 fueron por accidentes laborales dando un 8,4% del total. Además, se señalan las zonas más afectadas, siendo la más frecuente en la zona debajo de la rodilla abarcando 27,3% de afectados del total de personas censadas. Por otro lado, en el rubro de manufactura fue en donde ocurrieron más accidentes con un 37,9% de casos. Por último, los hombres fueron los más afectados con un 98,2% y un 40,7% se encontraron en el rango de 21 a 30 años. (1) Según cifras del Ministerio de Trabajo se reportan 40 casos al mes de lesión de mano por causas laborales, cifra que representa el 30% del mercado laboral, puesto que más del 70% se encuentra en la informalidad. (2) Las lesiones digitales son extremadamente frecuentes y cuando estas involucran al pulgar pueden comprometer importantemente la función de la mano, tanto así que su amputación afecta hasta un 50% la función global de la mano y disminuye la fuerza de agarre hasta en un 20%. (3). En cuanto al tipo de agarre tenemos los siguientes: 

#### Tabla 1: Descripción de agarres de la clasificación utilizada  
| Tipo de Agarre | Descripción |
| ----- | ---- |
| Agarre cilíndrico | Interviene la palma. El pulgar está en oposición directa a los dedos (en abducción o posición neutra | 
| Agarre palmar oblicuo  | Variante del cilíndrico. Interviene la palma, pero el pulgar está en aducción. | 
| Agarre de gancho | No intervienen ni el pulgar ni la palma. El peso del objeto lo soportan los dedos |
| Agarre lumbrical | Interviene el pulgar y la parte más proximal de los dedos (hasta la base de los nudillos), pero no interviene la palma |
| Pinza lateral | Se utiliza la parte lateral de los dedos (uno o varios) y normalmente también el pulgar. | 
| Pinza | Se utiliza el pulgar y las yemas de los dedos (uno o varios) | 
| Agarre intermedio de potencia-precisión | Interviene algo la palma pero tanto el pulgar como el índice estabilizan el agarre |

###### La tabla 1 nos muestra los tipos de agarre que se dan a nivel de la mano donde se puede ver que en todos el uso del pulgar es indispensable.

###### Figura 1: Frecuencias del uso diario de cada tipo de agarre totales
![Figura1](https://github.com/T0mmyoo4/FunBioIB/blob/main/Figura1.jpg)

###### La figura 1 muestra los porcentajes de tiempo de forma global y para cada agarre. Casi todos los agarres se utilizan con ambas manos aunque, en algunos casos, el porcentaje cambia considerablemente. Considerando a una persona diestra  el agarre de pinza especial es un agarre que requiere más destreza por lo que se utiliza fundamentalmente con la mano derecha, siendo este el de mayor frecuencia (4). Entonces una amputación tiene un impacto significativo en la capacidad de una persona, si sucede principalmente en el pulgar generando una mano disfuncional. 

### Estado del arte científico

#### Tabla 2: Estudios  
| Estudios | Descripción | Imagen |
| ----- | ---- | ---- |
| Prótesis diseñadas a medida impresas en 3D para la amputación parcial de la mano: todavía existen desafíos mecánicos | Modelo A: diseño de apertura voluntaria con posicionamiento típico del cable en el dedo dorsal. Modelo B: diseño de cierre voluntario con cables para dedos radiales ubicados lateralmente y dedos cubitales medialmente. Ambos dispositivos impresos en 3D tenían muy poca fuerza de agarre y pellizco, pero una destreza comparable a la de la prótesis mioeléctrica. El participante estaba más satisfecho con el peso y los atributos térmicos de los dispositivos impresos en 3D. (10) | ![EA1](https://github.com/T0mmyoo4/FunBioIB/blob/main/Imagenes/EA1.jpg) |
| Prótesis impresa en 3D para la rehabilitación de amputaciones digitales: presentación de un diseño mecánico | Este diseño fue adaptado para las medidas específicas del paciente e impreso en la Fundación Materialización 3D quienes realizaron como modificación más importante el cambio en la palanca, cambiándola de la muñeca a un dispositivo ortésico ajustado a nivel del dorso de la mano y sujeto por dos velcros en forma circular hacia la palma. Esto genera mayor estabilidad y disminuye la fuerza y tensión en la palanca al realizar la flexión. Para la impresión de esta prótesis el gasto fue de 12.72 USD. (11) | ![EA2](https://github.com/T0mmyoo4/FunBioIB/blob/main/Imagenes/EA2.jpg) | 
| Una prótesis de mano robótica de bajo coste con aparente sentido háptico controlado por señales electroencefalográficas | Este tipo de prótesis es una alternativa viable a las que utilizan señales electromiográficas (EMG). Estas a su vez cuentan con un sistema de retroalimentación háptica, que simula la función de los mecanorreceptores de la piel, proporcionando al usuario una sensación de tacto al utilizar la prótesis. Por otro lado, el uso de servomotores y controladores de fácil acceso en el mercado y además la impresión 3D permite bajar los costos para que sean accesibles para los usuarios. Por último, los resultados de la prótesis arrojan un 86.67 % de tasa de éxito en promedio de realizar las tareas proporcionadas.(12) | ![EA3](https://github.com/T0mmyoo4/FunBioIB/blob/main/Imagenes/EA3.jpg) |

###### Además,la mayoría de las veces los costos de las prótesis disponibles en el mercado superan el presupuesto de los pacientes y sus familias (6). En el mercado peruano se pueden adquirir prótesis mecánicas, eléctricas, mioeléctricas y cosméticas. Una prótesis eléctrica tiene costos alrededor de 53 000 soles, mientras que una mioeléctrica puede llegar a los 200 000. En el caso de las prótesis mecánicas, solo el dispositivo terminal (mano) de estas están costando aproximadamente S/3,800 y la fabricación del encaje protésico para que se adapte al tipo de amputación del paciente es un costo aparte. 

### Problemática:

###### Las personas que presentan una amputación funcional transmetacarpiana entre 20 a 30 años de edad con una ocupación laboral que implica un cierto esfuerzo físico no logran tener fuerza suficiente para agarrar. (Nos centraremos en el agarre pinza)
##### ¿Cómo podríamos mejorar el agarre pinza de las personas con amputaciones trans metacarpianas entre 20 a 30 años en Lima- Perú que desean obtener una cierta fuerza de agarre pinza?

### Estado del Arte comercial
#### Tabla 3: Productos disponibles en el mercado  
| Nombre | Descripción | Imagen |
| ----- | ---- | ---- |
| Dedo TITAN flex | Ligero y resistente hecho de titanio con funcionamiento mecánico que puede soportar hasta cargas de 68 kilos, cuesta como 2900 dólares americanos sin considerar costos de impuesto ni envío. La distribución de carga sobre la prótesis recae sobre un único socket colocado en la palma del paciente. El dedo no puede ser expuesto a sustancias corrosivas como agua salada. La flexión de la prótesis no está controlada por la propia mano en la que está colocada. (13)| ![EC1](https://github.com/T0mmyoo4/FunBioIB/blob/main/Imagenes/EC1.jpg) |
| Titan thumb / M-thumb | Prótesis específica para amputaciones a nivel transmetacarpiana de los pulgares, su soporte cubre a toda la palma de la mano para la distribución del peso, pero la flexión de esta no es dependiente al movimiento de la mano que sufrió la amputación. La prótesis es de mayor utilidad en situaciones donde se requiere trabajo de carga pesada con poca movilidad. Por otro lado, si se necesitase dexteridad, una alternativa es M-Thumb que tiene un mayor rango de movimiento y resistencia regulable (variar la intensidad del agarre) para la comodidad del usuario; a diferencia del Titan Flex, el dispositivo no se puede emplear en casos de carga pesada. (14) | ![EC2](https://github.com/T0mmyoo4/FunBioIB/blob/main/Imagenes/EC2.jpg) | 
| Point Thumb | Se trata de una prótesis del dedo pulgar diseñada para ser lo más liviana posible, pero a la vez resistente, con la ventaja de poder realizar 11 posiciones únicas de flexión. Así pues, este producto está diseñado para personas que requieran de un dispositivo con alta durabilidad que sea capaz de realizar distintos movimientos característicos del pulgar, por lo que la misma está hecha de titanio y acero inoxidable. Cabe destacar que tiene una capacidad de carga de 68 kg y pesa alrededor de unos 28 a 38 g. (15) | ![EC3](https://github.com/T0mmyoo4/FunBioIB/blob/main/Imagenes/EC3.jpg) |

### Patentes:
###### Dentro de las patentes encontradas las primeras dos son de innovación y la última de utilidad
#### Tabla 4: Productos disponibles en el mercado  
| Kind Code | Nombre | Descripción | Imagen |
| ---- | ----- | ---- | ---- |
| US20210085490 | BIOMEDICAL FINGER ASSEMBLY WITH RATCHETING LOCK | Proporciona sistemas, aparatos y dispositivos para un dedo protésico que puede ser utilizado en amputaciones en la articulación metacarpofalángica. El dispositivo restaura el agarre de una persona a la que le faltan  dedos o un pulgar aplicando fuerzas opuestas en la dirección de extensión a través de un trinquete cargado por resorte y un mecanismo de trinquete de cremallera de bloqueo, lo que permite a una persona manipular o estabilizar objetos. El dedo puede estar cargado por resorte en la dirección de extensión mediante un muelle de torsión u otro miembro de presión. El trinquete puede desengancharse automáticamente de la cremallera cuando el dedo alcanza la flexión completa, y el tope de desenganche de flexión completa puede ser ajustable. (16)| ![PAT1](https://github.com/T0mmyoo4/FunBioIB/blob/main/Imagenes/PAT1.jpg) |
| US8343234B2 | Prótesis de mano compuesta por 2 dispositivos de conducción | Se trata de una prótesis capaz de reemplazar 3 dedos de la mano (dedo índice, dedo medio y pulgar). Se caracteriza por estar compuesta por un chasis y 2 accionamientos capaces de permitirle al usuario realizar movimientos relativamente complejos. El primer accionamiento se ubica en la zona del chasis en el centro de la mano, del cual se generan la mayor parte de movimientos en torno a un eje de giro conectado al resto de dedos. Así pues, el segundo accionamiento se encuentra en el extremo que une a la prótesis separada para cada dedo, permitiendo que los dedos realicen movimientos en torno a un segundo eje, que sumado al primer accionamiento, el paciente es capaz de tener movimientos más fluidos y precisos, así como complejos. Por otro lado, también presenta un transmisor de fuerza, en la zona del segundo accionamiento que se encarga de retransmitir las fuerzas de tensión hacia toda la mano, permitiendo al usuario deshacerse de cargas innecesarias y viceversa. (17) | ![PAT2](https://github.com/T0mmyoo4/FunBioIB/blob/main/Imagenes/PAT2.jpg) | 
|16650357| Dispositivo háptico portátil con actuadores intercambiables para prótesis de extremidad | El wearable inventado por Enzo Romero, egresado de Ingeniería Mecatrónica PUCP, es un caso en el que la tecnología apunta mucho más lejos a beneficio del usuario colocado en el antebrazo como un brazalete, logra replicar la sensación del tacto en una persona que utiliza una prótesis de extremidad superior cuando el usuario presiona el objeto con los dedos de la  prótesis. (18) | ![EC3](https://github.com/T0mmyoo4/FunBioIB/blob/main/Imagenes/PAT3.jpg) |

### Lista de Requerimientos:
![LRF](https://github.com/T0mmyoo4/FunBioIB/blob/main/Imagenes/LRF.jpg) 
![LRF](https://github.com/T0mmyoo4/FunBioIB/blob/main/Imagenes/LRNF.jpg) 

### Proppuesta de Solución:
#### Desarrollo de una prótesis de pulgar para personas con amputación transmetacarpiana enfocada en la fuerza del agarre pinza de bajo costo impresa en 3D. 

#### Bibliografía:

###### 1 - Camacho-Conchucos HT. Pacientes amputados por accidentes de trabajo: características y años acumulados de vida productiva potencial perdidos. An Fac Med (Lima, Perú ) [Internet]. 2010 [citado el 27 de agosto de 2023];71(4):271–5. Disponible en:ht<span>tp://ww<span>w.<span>sci<span>elo.org.pe/s<span>cielo.php?script=sci_arttext&pid=S1025-55832010000400011
###### 2 - Varela Bohórquez AF, Charles D, Guzmán N, Gutiérrez AI, Lola C, Carpio A, et al. Ministro de Trabajo y Promoción del Empleo. Anuario Estadístico Sectorial 2022.  [Internet]. Gob.pe. [citado el 28 de agosto de 2023]. Disponible en: ht<span>tps://<span>cdn.w<span>ww.go<span>b.pe/uploads/documen<span>t/file/4930317/Anuar<span>io%202022.pdf?v=1691004485
###### 3 - Ruiz-Riquelme P, Urrutia-Hoppe E. Cobertura de partes blandas del Pulgar. Guía en la toma de decisiones. Rev Colomb Ortop Traumatol [Internet]. 2021 [citado el 10 de septiembre de 2023];35(1):67–73. Disponible en: ht<span>tps://w<span>ww.<span>else<span>vier.es/es<span>-revista-revista-colombiana-ortopedia-traumatologia-380-articulo-cobertu<span>ra-partes-blandas-del-pulgar--S0120884521000110 
###### 4 - Asociación AAA, Vergara M, Cabedo JS, Cervantes PJR, Pérez González A. Resultados de un trabajo de campo sobre agarres Resultados de un trabajo de campo sobre agarres utilizados en tareas cotidianas utilizados en tareas cotidianas [Internet]. Uji.es. [citado el 10 de septiembre de 2023]. Disponible en: ht<span>tp://www<span>.xixcnim.uji.es/CDActas/Documentos/Co<span>municacionesPosters/01-06.pdf
###### 5 - Stokosa JJ. Opciones para las prótesis de los miembros [Internet]. Manual MSD versión para profesionales. [citado el 11 de septiembre de 2023]. Disponible en: ht<span>tps://www<span>.msdmanuals.com/es-pe/professi<span>onal/temas-e<span>speciales/miembro-prot%C3%A9s<span>ico/opciones-para-las-pr%C3%B3tesis-de-los-miembros
###### 6 - Universidad Autónoma del Estado de Hidalgo. Vista de El impacto de la impresión 3D en la construcción de una prótesis de mano [Internet]. Edu.mx. [citado el 11 de septiembre de 2023]. Disponible en: ht<span>tps://repository.u<span>aeh.edu.mx/revistas/index.php/icbi/<span>article/view/4167/6524
###### 7 - Bustamante Carvallo MM. Malky : diseño e implementación de una prótesis parcial de mano personalizada. [citado el 11 de septiembre de 2023]; Disponible en: ht<span>tps://tesis.pucp.e<span>du.pe/repositorio//handl<span>e/20.500.12404/12164
###### 8 - Investigadores de la PUCP fabrican prótesis de mano para mejorar calidad de vida de personas con discapacidad [Internet]. Noticias - Consejo Nacional de Ciencia, Tecnología e Innovación Tecnológica - Plataforma del Estado Peruano. Disponible en: ht<span>tps://<span>ww<span>w.gob.pe<span>/institu<span>cion/concytec/noticias/341401-invest<span>igadore<span>s-de-la-pucp-fabrican-protesis-de-man<span>o-para-mejorar-calidad-de-vida-de-p<span>ersonas-con-discapacidad
###### 9 - Universidad Autónoma del Estado de Hidalgo. Vista de El impacto de la impresión 3D en la construcción de una prótesis de mano [Internet]. Edu.mx. [Consultado el 14 de septiembre de 2023]. Disponible en: ht<span>tps://<span>reposi<span>tory.uaeh.edu.mx/revistas<span>/inde<span>x.php/icbi/article/view/4<span>167/6524
###### 10 - O’Brien L, Cho E, Khara A, Lavranos J, Lommerse L, Chen C. 3D-printed custom-designed prostheses for partial hand amputation: Mechanical challenges still exist. J Hand Ther [Internet]. 2021;34(4):539–42. Disponible en: ht<span>tps://<span>ww<span>w.s<span>cienced<span>irect.com/science/article<span>/pii/S0894113020300867
###### 11 - Ricardo GS, María JVR. Prótesis impresa en 3D para la rehabilitación de amputaciones digitales: presentación de un diseño mecánico. Revista Colombiana de Cirugía Plástica y Reconstructiva [Internet]. 2019 [citado el 15 de septiembre de 2023];25(2). Disponible en: ht<span>tps://<span>ww<span>w.c<span>ip<span>la<span>stic<span>a.com/ojs/index.php/rccp/article<span>/view/113
###### 12 - Cutipa-Puma DR, Coaguila-Quispe CG, Yanyachi PR. A low-cost robotic hand prosthesis with apparent haptic sense controlled by electroencephalographic signals. HardwareX [Internet]. 2023 [citado el 15 de septiembre de 2023];14(e00439):e00439. Disponible en: ht<span>tp://dx.doi.org/10.1016/j.ohx.2023.e00439
###### 13 - College-park.com. [citado el 14 de septiembre de 2023]. Disponible en: ht<span>tps://www<span>.college-p<span>ark.com/titan<span>-flex
###### 14 - College-park.com. [citado el 14 de septiembre de 2023]. Disponible en: http<span>s://w<span>ww.college-p<span>ark.com/m-thumb<span>-black
###### 15 - Point Thumb [Internet]. Pointdesignsllc.com. [citado el 14 de septiembre de 2023]. Disponible en: htt<span>ps://w<span>ww.pointdesignsl<span>lc.com/pr<span>oducts/thumb-pr<span>osthesis
###### 16 - WIPO - search international and national patent collections [Internet]. Wipo.int. [citado el 14 de septiembre de 2023]. Disponible en: https:<span>//pa<span>tentscope.wi<span>po.int/sea<span>rch/<span>en/de<span>tail.jsf?docId=US320885759&_cid=P11-LM<span>88HA-24444-1
###### 17 - Puchhammer G. Hand prosthesis comprising two drive devices. US Patent. 8343234, 2013. [citado el 14 de septiembre de 2023]. Disponible en: ht<span>tps://patents<span>.google.com/patent<span>/US83432<span>34B2/en?q=(<span>finger+prosthesis)&oq=finger+prosthesis
###### 18 - Design of a non-invasive haptic feedback device for transradial myoelectric upper limb prosthesis [Internet]. IEEE ANDESCON. [citado el 14 de septiembre de 2023]. Disponible en: htt<span>ps://ie<span>eexplore-ieee-org.ezproxybib.<span>pucp.edu.pe/docu<span>ment/7836230
