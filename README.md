# BEcopter Informe Final
Informe de Proyecto Final de Carrera *  Ingeniería en Informática.


Correcciones realizadas en esta Versión 2: 

CORRECCIONES EMILIANO  
* El capítulo 1 debe llamarse: Introducción
* El cap 2 lo llamaría Análisis de requerimientos, se sobreentiende lo de obtención
* Cap3: Componentes y armado del cuadricóptero
* EN gral primero van las conclusiones y luego las propuestas de trabajos a futuro
* Los acrónimos se usan del siguiente modo: en la primera mención se utilizan las palabras que lo componen y entre paréntesis su acrónimo, a partir de ahí basta con utilizar solamente el acrónimo. Corregir pág. 4 con el uso de PFC.
* Siempre que exista el término en castellano, utilizarlo por sobre el inglés, por ejemplo open source -> código abierto. Y mantenerlo durante todo el texto, no usar uno y otro indistintamente.
* En vez de usar el término ordenador usar computadora o PC.(en 1.3.2 x ejemplo)
* pág. 8, en el 4to párrafo hay un *de* que está de mas. ... suma importancia elegir DE las indicadas...
* p8, error en item lenguaje python: soporta programación *orientación* a objetos,
* en p8 y p9 donde se mencionan las herramientas, sino hay una referencia a lo mencionado debe utilizarse un pié de página con la URL.
* Mencionar aquellas herramientas que son parte de la biblioteca estándar de python (login, socket).
* El término librería proviene de una mala traducción del inglés al castellano, la correcta tradución de library es biblioteca.
* En algún lado debería decir las versiones con las que se trabajó, python 2.7 o 3+ ? mas aun si es un proyecto FLOSS donde alguien lo podría replicar.
* En el cap.3 sería de ayuda al lector que una vez que menciona los componentes de hardware incluya un diagrama de bloques, algo sin demasiados detalles, que ayude a entender el rol de cada componente, sino uno debe irse armando mentalmente para qué y cómo interactuarán entre si. Un diagrama general ayudaría mucho a la comprensión por parte del lector del sistema global.
* p13, el acrónimo VANT debería mencionarse en esta página en vez de en el resumen.
* Todas las referencias a los pié de página tienen un espacio que no corresponde entre el término a referenciar, por ej, Router 1, debería ser Router1 (en super índice)
* 3.1.5.3 usar primero radio control y entre paréntesis (RC), no al revés como está.
* Las figuras se citan siempre usando la abreviación Fig. X. Ojo porque algunas veces usas Figura X y otras usas Imagen X.
* La Fig. 3.19 debe indicar qué es cada componente sobre la misma imagen o con alguna etiqueta y decirlo en el pié de la imagen. Uno quisiera leer un proyecto de manera mas fluida para no tener que estudiarlo y entender qué es cada componente ni el rol que juega. Es por eso que como dije anteriormente, hay que hacer uso de diagramas, ya sea en bloques o con los componentes para que uno pueda entender el flujo de las comunicaciones, la interacción de los componentes, etc. Por ejemplo, entiendo bien el drama de la conversión con arduino uno de PWM a SBUS, pero no me queda claro todavía quién lo entrega en un formato y quién lo debe recibir en el otro. Lo dejaré para releer, pero ese debería ser muy fácil de ver con un diagramita y todos estaríamos felices y contentos.
* La Fig. 3.22 no está citada/mencionada en ninguna parte del texto.
* p33, dice en la última oración tres veces la palabra proyecto!
* p33, dice *según Pressman* sin ninguna referencia!
* p35, menciona HUD sin que se sepa qsu significado ni qué es.
* p35, corregir en 4.2.1: interfaz gráfica de usuario (GUI, del inglés Graphical User Interface). En el último párrafo: nos basamos y basándonos en una misma oración.
* p35, la primera aparición del término mockups no explica qué es ni para qué.
* p36, en 4.2.2 falta un punto final al primer párrafo.
* p36, en 4.3 segundo párrafo empieza mal, dice Según y luego una coma. Dice: Exceptuando las librerías pertinentes? no se qué significa eso.
* p37. la figura 4.2 no está referenciada en el texto. ni la de las clases subsiguientes.
* p51, link en pié de pág. o referencia a openpyxl
* p58. Aclarar el significado de QA, o cuando se menciona aseguramiento de la calidad ponerlo entre paréntesis: QA, del inglés Quality Assurance...
* p62, la Fig. 5.4 no está mencionada o lo hace a posteriormente de su aparición, lo que es incorrecto. Tal vez en la misma figura se podría poner nombre a los componentes no obvios: 5, 3,etc.,
* la tabla 5.1 tampoco se menciona
* p65. Fig. 5.8 dice fuente de alimentación para navio2 cuando en realidad es de la raspy, al menos así la referencia en la página previa.
* p67, 5.3.2.6 hay una oración confusa, dice que corrobora con un tester que la corriente promedio de salida mantenga un valor aceptable de voltaje... eso no está bien, o medís corriente (mA) o medís voltaje (V), o no está claro.
* p69, 5.3.3: empieza mal el párrafo: por último y ya probado....
* p69, el código python que ahí figura esta mal, no existe la sangría que requiere el lenguaje.¿Por qué? Si es por cuestiones visuales entonces tampoco, si en el informe se presenta un código, ese debe ser correcto.
* p70, ¿la conexión por ssh es por puerto serial?
* p70, corregir palabra *domincilio*
* p71. mismo problema con el código previo, no está citado y el código está mal sangrado (indentado)
* p78, el resumen tiene un error, dice posteriores en vez de previas.
* p80, Gimbal?
* No tiene bibliografía!!! es imposible que un proyecto sea defendido sin esto! Seguramente se pasó, por favor agregala!
* El proyecto menciona que todo lo que se desarrollará será de código abierto, bajo qué licencia? en qué repositorio se lo encuentra?
* A veces el resumen del capítulo es muy reiterativo, no tiene sentido que nos diga el nombre del capítulo de nuevo, debería ser efectivamente un resumen útil al lector, sino parece forzado.
* Si las clases se relacionan entre sí entonces debe haber un diagrama de clases que muestre todas las clases con sus relaciones.
* En el índice figura un listado de acrónimos que no existe. Alguien debería haberse dado cuenta de esto antes que llegue a los jurados. No es tan grave, son errores subsanables, pero por favor revisala minuciosamente tanto vos como tus directores.
* p67: los códigos deberían tener menor tamaño de fuente, son mayores a la fuente del texto del informe. Además, los códigos deben estar referenciados también, como una figura o tabla. En latex se llaman listings. Si se complica podrías usar el paquete minted, tal vez te ayuda.
* Agregar en un apartado una lista de acrónimos
* p33, mejorar el último párrafo ya que hay errores conceptuales y lo encuentro algo confuso, los objetos son instancias de clases, se debe hablar siempre de clases. Las clases tiene atributos y métodos, no funciones. Los métodos son las diferentes funcionalidades de la clase que si son públicas son la interfaz usadas para interactuar con ella desde el programa principal si son públicas o únicamente desde otros métodos si son privadas.
* p21, dice que los componentes de la raspi no son los mismos a los ordenadores comerciales. la raspi es una computadora comercial. No aplicaría acá la diferenciación utilizando el término comercial, en todo caso sería computadora convencional para las PC y computadora de placa única para la raspi (single board computer) https://all3dp.com/1/single* board* computer* raspberry* pi* alternative/
* Muchas figuras no cuentan con la referencia en el texto o en algunos se muestra primero la figura y luego su referencia, esto no debe ser así. Hay muchos errores de puntuación y de tipeo.
* p20, clarificar/mejorar la escritura del primer párrafo (que viene de la página previa). Luego de un punto seguido empieza con *Pero*, lo que no es muy recomendable.

* p21, dice la distro que usa para la raspi de entre varias pero no justifica, sería bueno saber las razones/justificaciones para decantarse hacia emlid por sobre la raspbian. A mi me gustaría saberlo, yo la he probado con arch y raspian por ejemplo y no conocía emlid. Entiendo que es para drones, pero nunca lo aclara, uno se da cuenta leyendo mas adelante.
* p15, si se menciona de la ventaja de la raspi en términos de consumo energético e incluso comparandola con una pc convencional debe decirse cuánto es esto? watts? autonomía con una determinada batería? etc, etc

CORRECCIONES GUIDO
* Se agrega el nombre del director en portada.
* Se elimina la hoja con el escrito "Documento maquetado con TEXIS"
* Se modifica la información del Codirector
* Se quitan los espacios antes de las comas
* Se mejora la redacción de multirotores
* Ortografía en Bibliografía
* Corrección de ecuación 4.1
* Numeración de los apéndices
* Corrección de  sinc(i) 
* Unificación de siglas
* Se habla de GNSS en vez de GPS
* Se mejora la redacción de 3.2.5 Primeras pruebas.
* Se agregan los labes a los códigos
* Se quitan imágenes no referenciadas y de poca utilidad
* Corrección de los intervalos que se muestran, por ejemplo [-60, 60]
* Modificación del tamaño de las imágenes y espacios


En versión 2.1:
* Diagrama de clases en hoja A3.
* Capitulo 6: Corrección del orden (Conclusión - Trabajos futuros) y descripción detallada del trabajo realizado en las distintas fases.

