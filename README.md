# Simple-Looper
Simple Looper - Patch
“Simple Looper” – Aproximaciones conceptuales a los elementos del dispositivo a través de Pure Data. 
Al interior de mi trabajo como compositor e investigador me he dedicado a analizar y describir el fenómeno del loop al interior de la música experimental electrónica y específicamente como el loop se presenta como una herramienta fundamental para la creación  de atmosferas y ambientes sonoros. De aquí mi interés por indagar en los elementos constitutivos de un loop y los dispositivos que hacen posible la repetición (loop) del material sonoro seleccionado para la composición.

En medio de mi proceso compositivo decidí entender como es que funciona un loop en su forma mas básica. Para ello utilicé el software Pure Data para graficar y describir una simple cadena de repetición. Cree un patch llamado “Simple Looper” en cual se compone de los siguientes elementos:

1 – Un mensaje  que llama el archivo de audio (open atomssamplefinal.wav, 1)desde la carpeta contenedora y lo hace audible con el numero “1”
2 -  El objeto readsf que lee la señal de salida de un archivo de audio
3  - Un Bang que tiene  su entrada conectada a la salida del objeto readsf~ y su salida al objeto open atomssamplefinal.wav, 1 con esto genera el loop que se reproduce y  se repite  infinitamente.
4 – El objeto Dac~ que es la puerta por donde sale el sonido de Pure Data.
5 -  El Mensaje  0  que detiene el loop generado.
Si analizamos los distintos dispositivos que existen en el mercado para generar distintos tipos de repetición nos daremos cuenta que son muchos. La repetición es en si misma una función que se encuentra integrada en casi la mayoría de los dispositivos  de procesamiento de audio y es a su vez una herramienta estética para la generación de estructuras especificas al interior de la composición de música “electrónica experimental”. Softwares y Hardwares poseen herramientas de audio las cuales permiten procesos de repetición, sin embargo sus usos están determinados muchas veces por empresas las cuales distribuyen comercialmente estas herramientas.  Softwares libres como Pure Data, Super Collider y otros abren una posibilidad real y abierta para el entendimiento de la creación de estos dispositivos desde sus elementos mas básicos a través de comunidades colaborativas que creen en el desarrollo colectivo de estas  herramientas.

“Simple Looper” es un prototipo inicial que se pretende desarrollar con el tiempo. Se implementaran y especificaran distintas funciones de repetición con la intención de transformarlo en una herramienta de crossfading – loop la cual permitirá un ejercicio de repetición donde el punto de corte del sample que se esta repitiendo  no se manifieste (corte en el punto de fase X=0 Y=0) con al intención de generar una percepción auditiva de “continuidad”. Serian estas las primeras aproximaciones a la creación de sonidos continuos a partir de un sample para la creación de ambientes sonoros y atmosferas.

por PP Mtrx.
