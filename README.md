# Informe-Trabajo-de-Investigacion

### 1. PLANTEAMIENTO DEL PROBLEMA

### 2. OBJETIVOS
##### OBJETIVO GENERAL

Realizar una calculadora con características propias que sea capaz de resolver las 4 operaciones básicas en el sistema de numeración binario mediante la aplicación appinventor.

##### OBJETIVOS ESPECÍFICOS
- Conocer las características que brinda la aplicación appinventor para trabajar con esta y crear un nuevo programa.
- Utilizar los conceptos de operaciones binarias para realizar un código propio en nuestra calculadora.
- Investigar cómo se realiza una división en números binarios, e implementarla en la aplicación.
- Crear una calculadora para la resolución de suma, resta, multiplicación y división de números binarios de 3 bits.
- Implementar un código propio para la aplicación, sin usar librerías preestablecidas.

### 3. ESTADO DEL ARTE

**1.	Improved Multiplication Algorithm by Clearing Leading Zeros of Binary Numbers based on Big Data Analysis
Algoritmo de multiplicación mejorado al borrar los ceros iniciales de Números binarios basados en análisis de Big Data**

**Autores**

•	Donghoon Kim
Department of Computer Science, Arkansas State University, Jonesboro, USA
•	Jaehee Jung
Department of General Education, Hongik University, Seoul, South Korea

**Año de publicación**: 27-29 June 2018

**De que se trata**

Se trata de la creación de un nuevo algoritmo para realizar multiplicaciones de números binarios porque descubrieron que se puede reducir el número de iteraciones al eliminar los ceros iniciales innecesarios en el multiplicador. 
Mediante dos formas

   • Pre-front-based: pre-clear ceros iniciales con el algoritmo de multiplicación basado en front.
   • Post-booth: post-clearing ceros iniciales con la parte posterior algoritmo de multiplicación basado en algoritmo Booth.
    
Su algoritmo creado de multiplicación permite con un cambio mínimo para lidiar con la ingestión de grandes datos.
La relación existente entre el articulo y la calculadora de binarios de 3 bits es que ambas realizan la multiplicación de dos números en el sistema binario la diferencia está en que en el articulo generaron un nuevo algoritmo para multiplicar dos números binarios en la aplicación que se creó un código que permita hacer la multiplicación basándose en las reglas establecidas de la multiplicación de números binarios.

**Lugar de publicación**

**Se publicó en la conferencia:**  

Software Engineering, Artificial Intelligence, Networking, and Parallel/ Distributed Computing (SNPD), ACIS International 

**Lugar:** Busan, Corea del sur.


**2.	Parallel Algorithms for Solving Sparse Binary Subset Sums Using Random Mappings**

**Algoritmos paralelos para resolver sumas de subconjuntos binarios dispersos utilizando asignaciones aleatorias**

**Autores**

•	Nikita Rumenko

Moscow Technical University of Communications and Informatics, Moscow, Russian Federation

•	Alexander Kostyuck

Moscow Technical University of Communications and Informatics, Moscow, Russian Federation

**Fecha de publicación**:  21-25 Oct 2019

**De que se trata**

En este artículo se busca el uso de asignaciones aleatorias para resolver sumas de subconjuntos binarios dispersos a través de la búsqueda de colisiones. Con un mapeo que se adapta a nuestro propósito y se proponen dos algoritmos paralelos basados en técnicas conocidas de detección de colisiones. Con la finalidad de aprender paridades con ruido, decodificar códigos aleatorios y problemas relacionados.

La calculadora de binarios de 3 bits se asemeja con este nuevo algoritmo  creado ya que ambas son aplicaciones para el sistema numérico binario y se diferencian ya que en el artículo utiliza las sumas para subconjuntos y hace aplicaciones más avanzadas.

**Lugar de publicación**

**Se publicó en la conferencia:** 

- 2019 XVI International Symposium "Problems of Redundancy in Information and Control Systems" (REDUNDANCY).

**Lugar:** Moscow, Russia, Russia

**3.	Reconfigurable adders for Binary/BCD addition/subtraction**
      **Sumadores reconfigurables para suma / resta binaria / BCD**

**Autores**

•	Syed Ershad Ahmed

Department of Electrical Engineering, Birla Institute of Technology and Science - Pilani, Hyderabad Campus, Hyderabad - 500078, India

•	Sreehari Veeramanchaneni

Department of Electrical Engineering, Birla Institute of Technology and Science - Pilani, Hyderabad Campus, Hyderabad - 500078, India

•	N Moorthy Muthukrishnan

Department of Electrical Engineering, Birla Institute of Technology and Science - Pilani, Hyderabad Campus, Hyderabad - 500078, India

•	M. B Srinivas

Department of Electrical Engineering, Birla Institute of Technology and Science - Pilani, Hyderabad Campus, Hyderabad - 500078, India

**Fecha de publicación:** 6-7 oct. 2015

**De que se trata**

En este artículo se ha creado una arquitectura reconfigurable para sumar y restar números binarios del código BCD de forma eficiente. La arquitectura evita el uso de circuitos adicionales del complemento 2 y del complemento 10 para corregir los resultados en formato de magnitud de signo. Esta arquitectura permite reconfigurar en tiempo real y facilita las operaciones de BCD y Binario.

Se relaciona con la calculadora de binarios de 3 bits implementada porque de forma similar realizan un sistema para hacer sumas y restas de códigos Binarios, creando un código propio basado en el complemento 2 y el complemento 10 lo que no hace parte de esta calculadora ya que se estableció condiciones, sin embargo, se diferencian porque esta calculadora realiza multiplicación y división. 

**Lugar de publicación**

**Se publicó en la conferencia:**

* 2015 Asia Pacific Conference on Postgraduate Research in Microelectronics & Electronics

**Lugar**: Macao, China

### 4. MARCO TEÓRICO

El sistema de numeración binario es el más importante de los sistemas digitales, sin embargo, también existen otros sistemas que son igual de importantes, es el caso del sistema decimal que es el más usado en todo el mundo ya que a través del mismo podemos representar varias cantidades ya sean grandes o pequeñas y operar con las mismas para obtener distintos resultados, pero la capacidad de cálculo de los seres humanos tiene bastantes limitantes. Aquí es donde intervienen los sistemas digitales, los cuales son capaces de procesar una gran variedad de datos y realizar operaciones o cálculos de una manera rápida, eficiente; siempre y cuando estos datos sean binarios, esto quiere decir que tenemos que representar cantidades decimales en cantidades binarias para que los sistemas digitales manipulen toda la información que ingresemos según nuestras necesidades.
Para poder observar la importancia de los sistemas digitales implementaremos una calculadora de operaciones aritméticas básicas. El sistema binario está conformado por dos dígitos o elementos, estos son el “1” y el “0” conocido como el sistema de base 2 debido a podemos representar cualquier número decimal, hexadecimal, octal en base 2 elevado a alguna potencia. Al igual que con los decimales, las operaciones de suma, resta, multiplicación y división tienen mecanismos parecidos en el sistema binario, simplemente se debe tomar en cuanta ciertas reglas para poder operar con ellos para que el resultado sea el correcto, dichas reglas son relativamente fáciles de recordar (Franco Mariscal, 2008).

**SUMA**

Para poder sumar primero debemos saber las reglas que rigen esta operación.

![reglasSumaBinaria](https://github.com/JorgeGallegos99/Informe-Trabajo-de-Investigacion/blob/master/Img/ReglasSumaBinaria.png)

**Figura 1.** Reglas de la Suma Binaria

**Fuente:** (Villa Martínez, 2008)

En la suma Binaria se introduce el concepto de “acarreo” y este se presenta solamente cuando sumamos 1+1, como cuando sumamos dos números decimales cuyo resultado es mayor a 10 y llevamos a la siguiente cifra, de la misma manera cuando sumamos 1+1 debemos “llevar” un 1 al acarreo (Franco Mariscal, 2008). Ejemplo:
5 + 7 = 12

![figura2](https://github.com/JorgeGallegos99/Informe-Trabajo-de-Investigacion/blob/master/Img/FIgura2.png)

**Figura 2.** Suma binaria de tres bits

En la figura 2 se observa la operación de suma binaria, el proceso que debe realizarse para obtener su solución es el siguiente:

a. Se comienza a sumar de derecha a izquierda columna a columna, en el caso de la primera columna el resultado de sus sumandos es igual a 2, sin embargo, en el sistema binario no se admite el número 2, es aquí donde se debe hacer uso de las reglas que se presentan en la figura 2. Es decir, al resultado de esta suma se le asigna el valor de “0” y se lleva un acarreo de “1” en la siguiente columna. El acarreo está representado con el número 1 de color rojo.
b. En la segunda columna se debe operar los dos sumandos y adicionarle el acarreo que se generó en la operación de la primera columna.

![figura3](https://github.com/JorgeGallegos99/Informe-Trabajo-de-Investigacion/blob/master/Img/fugura3.png)

**Figura 3.** Suma de la segunda columna
Al realizar la operación en esta columna el resultado da 0 con un acarreo de 1, el cual se añade a la siguiente columna.

c. Para la tercera columna se debe operar de igual manera que en las anteriores columnas, pero en este caso cambiará un poco. Primero se suma el acarreo que se generó en la anterior operación con el sumando superior, dando como resultado 0 con acarreo 1.

![jfigura4](https://github.com/JorgeGallegos99/Informe-Trabajo-de-Investigacion/blob/master/Img/jfigura4.png)

**Figura 4.** Suma binaria
Se debe añadir a este resultado el siguiente sumando dando como resultado 1.
Tomando en cuenta las reglas y operando correctamente sin olvidar colocar el acarreo se obtiene el resultado esperado en la suma binaria.

**RESTA**

La resta de números binarios es similar a la resta decimal que se conoce, para la realización de este trabajo de investigación se estableció que el minuendo siempre será mayor que el sustraendo. A continuación, en la figura 5 se presentan las reglas que se deben tener en cuenta para poder restar números binarios.

![jreglarestabinaria](https://github.com/JorgeGallegos99/Informe-Trabajo-de-Investigacion/blob/master/Img/jreglarestabinaria.png)

**Figura 5.**  Reglas de la Resta Binaria
Existen dos métodos para restar números binarios y para poder entenderlos veamos el siguiente ejemplo: 

12-4=8

![jfigura6](https://github.com/JorgeGallegos99/Informe-Trabajo-de-Investigacion/blob/master/Img/jfigura6.png)

**Figura 6.** Ejemplo de Resta binaria

**Complemento a 1**
a. Primero se debe cambiar a todos los bits del sustraendo por su complemento, es decir, reemplazar a todos los ceros por unos y a todos los unos por ceros.

![jfigura6a](https://github.com/JorgeGallegos99/Informe-Trabajo-de-Investigacion/blob/master/Img/jfigura6a.png)
**Figura 6 a)**

b. Luego de haber complementado el sustraendo, se suma el minuendo con complemento del sustraendo como en la figura 6b).

![jfigura6b](https://github.com/JorgeGallegos99/Informe-Trabajo-de-Investigacion/blob/master/Img/jfigura6b.png)
**Figura 6 b)**

c.	Como el bit más significativo salió 1 se debe sumar este bit a la respuesta. Si el bit más significativo hubiese salido cero se debería que complementar el resultado y esa será nuestra respuesta.

![jfigura6c](https://github.com/JorgeGallegos99/Informe-Trabajo-de-Investigacion/blob/master/Img/jfigura6c.png)
**Figura 6c)**

d. El resultado que se obtenga de esta suma será la respuesta esperada.
![jfigura6d](https://github.com/JorgeGallegos99/Informe-Trabajo-de-Investigacion/blob/master/Img/jfigura6d.png)
**Figura 6d)** 
**Fuente** (Redondo Galván, 2016)

**Complemento a 2**

Para el complemento a 2 se usará el ejemplo anterior (véase fig. 6).
a.	Primero se debe complementar todos los bits a partir del primer 1 que se encuentre de derecha hacia izquierda

![jfigura6e](https://github.com/JorgeGallegos99/Informe-Trabajo-de-Investigacion/blob/master/Img/jfigura6e.png)
**Figura 6e)**

b. Se realiza una suma normal:
![jfigura6f](https://github.com/JorgeGallegos99/Informe-Trabajo-de-Investigacion/blob/master/Img/jfigura6f.png)
**Figura 6f)**

c.	En el caso del complemento 2 si el bit más significativo es 1 simplemente se lo elimina y esa será la respuesta.

![jfigura6g](https://github.com/JorgeGallegos99/Informe-Trabajo-de-Investigacion/blob/master/Img/jfigura6g.png)
**Figura 6g)**
**Fuente:(Redondo Galván, 2016)**

**MULTIPLICACIÓN**
Las reglas de las multiplicaciones binarias son iguales que en una multiplicación decimal (véase fig. 7)

![jfigura7](https://github.com/JorgeGallegos99/Informe-Trabajo-de-Investigacion/blob/master/Img/jreglamultiplicacion.png)
**Figura 7.** Reglas de la multiplicación binaria

El procedimiento que se debe seguir se visualiza con ayuda del siguiente ejemplo:
7x7=49

![jfigura8](https://github.com/JorgeGallegos99/Informe-Trabajo-de-Investigacion/blob/master/Img/jfigura8.png)
**Figura 8.** Ejemplo de multiplicación binaria

a. Se multiplica una a una las cifras del multiplicando por cada cifra del multiplicador (bit a bit)
![jfigura8a](https://github.com/JorgeGallegos99/Informe-Trabajo-de-Investigacion/blob/master/Img/jfigura8a.png)
**Figura 8a)**

b. A continuación, se realiza el proceso de suma normal
![jfigura8b](https://github.com/JorgeGallegos99/Informe-Trabajo-de-Investigacion/blob/master/Img/jfigura8b.png)
**Figura 8b)**

**DIVISIÓN**

La división binaria es relativamente más sencilla que la división decimal ya que solo hay dos posibles valores 0 si el divisor es menor que el dividendo o 1 si es el caso contrario (Matemática para Programadores, 2015).
El procedimiento que debemos seguir para dividir dos números binarios se observa en el siguiente ejemplo:
10/5=2

![jfigura9](https://github.com/JorgeGallegos99/Informe-Trabajo-de-Investigacion/blob/master/Img/jfigura9.png)
**Figura 9.** Ejemplo de división binaria

a.	Al igual que con las divisiones decimales, se toma dos cifras del dividendo y si al compararlas con el divisor las dos cifras son mayores, se busca un número que multiplicado por el divisor entregue un número aproximado al dividendo y se resta.
![jfigura9a]()\
Figura 9a)\
b.	Posteriormente se procede a bajar la siguiente cifra del dividendo siguiente y se vuelve a comparar con el divisor.
![jfigura9b]()\
Figura 9b)\
c.	Como el divisor es mayor, se busca un número que multiplicado por el dividendo entregue un numero cercano al divisor y se resta.
![jfigura9c]()\
Figura 9c)\
Así se obtiene que el cociente es 11 y con un residuo de 1.\
Mapa de variables
|Variable|Tipo |Descripción|
|acarreo|Entera|Variable en la que se asigna un 1 de acarreo cuando se realiza una operación suma binaria.|
|D0A,D0B,D1A,\D1B,D2A,D2B|String |Variables que reciben correspondientemente un bit para realizar las operaciones binarias.|
|R0,R1,R2,R3,\R4,R5|String|Variables en las cuales se asigna correspondientemente el resultado de las operaciones binarias|
|Acarreo2|Entera|Variable en la que se asigna un 1 cuando se tiene un acarreo en la multiplicación binaria.| 
|Acarreo3|Entera|Variable en la que se le asigna un valor de 1 cuando se tienen un doble acarreo en la multiplicación binaria.|

5. DIAGRAMAS
La  Calculadora Binaria de 3 bits funciona como se muestra en la figura 10.
##### Diagrama del funcionamiento

![CFImg2](https://github.com/JorgeGallegos99/Informe-Trabajo-de-Investigacion/blob/master/Img/CFImg2.png)

   **Figura 10:** Diagrama de Bloques del Funcionamiento de la aplicación Calculadora Binaria de 3 bits
   
 ##### Diagrama de la suma
 
 ![CFImg3](https://github.com/JorgeGallegos99/Informe-Trabajo-de-Investigacion/blob/master/Img/CFImg3.png)

   **Figura 11:** Diagrama del algoritmo de la suma
   
  ##### Diagrama de la Resta
 
 ![CFImg4](https://github.com/JorgeGallegos99/Informe-Trabajo-de-Investigacion/blob/master/Img/CFImg4.png)

   **Figura 12:** Diagrama del algoritmo de la resta
   
  ##### Diagrama de la multiplicación
  
  ![CFImg5](https://github.com/JorgeGallegos99/Informe-Trabajo-de-Investigacion/blob/master/Img/CFImg5.png)

   **Figura 12:** Diagrama del algoritmo de la multiplicación.
   

6. LISTA DE COMPONENTES

Para el desarrollo de la calculadora de binarios con 3 bits se utilizo, unicamente una aplicación de software.

|                 **Herramientas de Software**      |                  **Descripción**                      |
|---------------------------------------------------|-------------------------------------------------------|
|            MIT APP INVENTOR                       | Es un entorno de desarrollo de software generado por Google Labs Google Labs para                                                      elaborar aplicaciones de tipo Android. Quién lo utilice accedera al programa                                                            creado de una forma visual y se enlazara con bloques. Para trabajar en ella se                                                          necesita crear una cuenta y se realiza el procesamiento de la aplicacion en linea                                                        y para probar se usa su emulador propio en linea o con un sistema operativo                                                              andoid.|

   **Tabla 1:** HERRAMIENTAS DE SOFTWARE UTILIZADAS

![CFImg1](https://github.com/JorgeGallegos99/Informe-Trabajo-de-Investigacion/blob/master/Img/CFImg1.png)

   **Figura 13:** Herramienta MIT App Inventor

7. MAPA DE VARIABLES
Este punto hace referencia a las variables que se emplean dentro de un programa, las cuales deben ser indicadas en la captura de una pantalla si son componentes visuales o especificados en una taba sin no son visibles en una interface. Se debe hacer referencia al tipo y la función que desempeñan en la aplicación.

8. EXPLICACIÓN DEL CÓDIGO FUENTE
En este punto se debe explicar cómo funcionan la implementación del programa, explicando los valores que requiere y los valores que devuelve.

9. DESCRIPCIÓN DE PRERREQUISITOS Y CONFIGURACIÓN

Cuando la calculadora de binarios con 3 bits ya está listo para probarlo se utiliza un emulador que la de la aplicación como se muestra en la  siguiente tabla.

|                 **Herramientas de Software**       |                  **Descripción**                      |
|----------------------------------------------------|-------------------------------------------------------|
|    Emulador de MIT App Inventor para computadores. | La aplicación MIT App Inventor te da directamente el emulador para probar el                                                          programa que estas creando.                             |
|Emulador de MIT App Inventor para sistemas Android. | Se puede descargar directamente de una tienda de aplicaciones. Ejemplo: Play                                                          Store                                                   |
|                       BLUESTAKS                    | Es un emulador de Android que se utiliza en la computadora y permite descargarse                                                      el MIT App Inventor para probar el programa creado.      |                          

**Tabla 2:** HERRAMIENTAS SECUNDARIAS DE SOFTWARE UTILIZADAS
 
10. APORTACIONES
BLUESTAKS. - Emulador de Android el cual se usó para descargar la aplicación de appinventor en el ordenador y poder realizar las pruebas del programa realizado.\
CALCULADORAS DE NUMERO BINARIOS ONLINE. - usadas para comparar los resultados obtenidos en las pruebas realizadas del programa, además verificar si los resultados son los correctos.\
11. CONCLUSIONES
Se estable las conclusiones de cada asunto investigado, implicaciones para la teoría y resultados de las experiencias. Estos siempre estarán en relaciona los objetivos generales y específicos.

12. RECOMENDACIONES
Se establecen en función del proyecto y constituyen la base para un funcionamiento adecuado.

13. CRONOGRAMA
El estudiante detalla cada una de las tareas y actividades que va a ejecutar durante el desarrollo de su trabajo. Este cronograma debe representarse gráficamente mediante un “DIAGRAMA DE GANTT”, el cual de ser desarrollado con MICROSOFT PROJECT.

14. BIBLIOGRAFÍA
Emplear normas APA para el informe e IEEE para el artículo

15. ANEXOS
15.1. MANUAL DE USUARIO

Constituye un documento en el cual se ilustra con imágenes y un lenguaje claro cómo utilizar la aplicación, evitando mencionar código. Además debe presentar como armar, instalar o conectar la aplicación, evitando los esquemas circuitales.

15.2. HOJAS TÉCNICAS


