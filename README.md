# Informe-Trabajo-de-Investigación

### 1. PLANTEAMIENTO DEL PROBLEMA

En la rama de los circuitos digitales, los sistemas de numeración forman parte esencial en el desarrollo de varios procesos debido a que en el muestreo de una señal se pretende convertir su valor en un valor binario, sin embargo, este proceso suele ser complicado cuando se busca trabajar de forma rápida y sencilla.

Existen varios métodos para realizar conversiones de sistemas de numeración y junto con ello varias herramientas que permiten llevar a cabo soluciones por medio de librerías o códigos preestablecidos que se encuentran en internet o se las puede descargar de alguna plataforma en línea, pero actualmente es necesario suscribirse a una membresía para acceder a todos los beneficios o soportar publicidades a cada momento de la utilización.

Los inconvenientes mencionados presentan un impedimento en el aprendizaje y desarrollo efectivo en los estudiantes e incluso en profesionales que buscan acelerar el proceso de elaboración de funciones lógicas e implementación de diseños.
En base a todos los puntos planteados se pretende implementar un algoritmo que resuelva operaciones aritméticas binarias elementales: suma, resta, multiplicación y división

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

La relación existente entre el articulo y la calculadora de binarios es que ambas realizan la multiplicación de dos números en el sistema binario la diferencia está en que en el articulo generaron un nuevo algoritmo para multiplicar dos números binarios en la aplicación que se creó un código que permita hacer la multiplicación basándose en las reglas establecidas de la multiplicación de números binarios.

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

La calculadora de binarios se asemeja con este articulo que presenta un nuevo algoritmo en que ambas son aplicaciones para el sistema numérico binario cada una tiene sus caracteristicas y se diferencian debido a que el artículo utiliza las sumas para subconjuntos y hace aplicaciones más avanzadas.

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

Se relaciona con la calculadora de binarios implementada porque de forma similar realizan un sistema para hacer sumas y restas de códigos Binarios, creando un código propio basado en el complemento 2 y el complemento 10 lo que no hace parte de esta calculadora ya que se estableció condiciones, sin embargo, se diferencian porque esta calculadora realiza multiplicación y división. 

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
El procedimiento que debemos seguir para dividir dos números binarios se observa en el siguiente ejemplo: 10/5=2

![jfigura9](https://github.com/JorgeGallegos99/Informe-Trabajo-de-Investigacion/blob/master/Img/jfigura9.png)

**Figura 9.** Ejemplo de división binaria

a.	Al igual que con las divisiones decimales, se toma dos cifras del dividendo y si al compararlas con el divisor las dos cifras son mayores, se busca un número que multiplicado por el divisor entregue un número aproximado al dividendo y se resta.

![jfigura9a](https://github.com/JorgeGallegos99/Informe-Trabajo-de-Investigacion/blob/master/Img/jfigura9a.png)

**Figura 9a)**

b.	Posteriormente se procede a bajar la siguiente cifra del dividendo siguiente y se vuelve a comparar con el divisor.

![jfigura9b](https://github.com/JorgeGallegos99/Informe-Trabajo-de-Investigacion/blob/master/Img/jfigura9b.png)

**Figura 9b)**

c.	Como el divisor es mayor, se busca un número que multiplicado por el dividendo entregue un numero cercano al divisor y se resta.

![jfigura9c](https://github.com/JorgeGallegos99/Informe-Trabajo-de-Investigacion/blob/master/Img/jfigura9c.png)

**Figura 9c)**

Así se obtiene que el cociente es 11 y con un residuo de 1.

### 5. DIAGRAMAS

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

   **Figura 13:** Diagrama del algoritmo de la multiplicación.
   

### 6. LISTA DE COMPONENTES

Para el desarrollo de la calculadora de binarios con 3 bits se utilizo, unicamente una aplicación de software.

|                 **Herramientas de Software**      |                  **Descripción**                      |
|---------------------------------------------------|-------------------------------------------------------|
|            MIT APP INVENTOR                       | Es un entorno de desarrollo de software generado por Google Labs Google Labs para                                                      elaborar aplicaciones de tipo Android. Quién lo utilice accedera al programa                                                            creado de una forma visual y se enlazara con bloques. Para trabajar en ella se                                                          necesita crear una cuenta y se realiza el procesamiento de la aplicacion en linea                                                        y para probar se usa su emulador propio en linea o con un sistema operativo                                                              andoid.|

   **Tabla 1:** HERRAMIENTAS DE SOFTWARE UTILIZADAS

![CFImg1](https://github.com/JorgeGallegos99/Informe-Trabajo-de-Investigacion/blob/master/Img/CFImg1.png)

   **Figura 14:** Herramienta MIT App Inventor

### 7. MAPA DE VARIABLES

**Tabla 2:** Mapa de Variables.

|        Variable                      |     Tipo            |                       Descripción                 |
|--------------------------------------|---------------------|---------------------------------------------------|
|acarreo                               |Entera               |Variable en la que se asigna un 1 de acarreo cuando se realiza una                                                                       operación suma binaria.                             |
|D0A,D0B,D1A,D1B,D2A,D2B              |String                |Variables que reciben correspondientemente un bit para realizar las                                                                     operaciones binarias.                               |
|R0,R1,R2,R3,R4,R5                    |String                |Variables en las cuales se asigna correspondientemente el resultado de las                                                               operaciones binarias                                |
|Acarreo2                              |Entera               |Variable en la que se asigna un 1 cuando se tiene un acarreo en la                                                                       multiplicación binaria.                             | 
|Acarreo3                              |Entera               |Variable en la que se le asigna un valor de 1 cuando se tienen un doble                                                                acarreo en la multiplicación binaria.                |
|Dividendo                             |Entera               | Variable que nos permite transformar numeros decimales a su                                                                              representacion binaria                             |
|numero                                |Entera               |Variable de estructura la cual itera para poder realizar comparaciones y                                                                 evaluarlas                                           |               


### 8. EXPLICACIÓN DEL CÓDIGO FUENTE

App Inventor presenta la aplicación por bloques, que permite programar mediante el uso de conexiones gráficas (bloques).
El algoritmo implementado está configurado con las siguientes restricciones:

* Se realizan las operaciones con dos números binarios ingresados: A (minuendo) y B (sustraendo).
* Los números binarios ingresados deben tener una magnitud máxima de 3 bits de magnitud.
* No está diseñada para reflejar bits de signo.
* En relación con el punto anterior, la operación resta se realiza sólo cuando A≥B, es decir, solo cuando el primer número ingresado: minuendo es mayor al segundo número: sustraendo. 

La pantalla principal de la aplicación llamada “Calculadora Binaria” se presenta de la siguiente manera, mostrando los dos números de magnitud 3 bits para ingresar, el resultado de la operación deseada y los botones de cada operación a realizar
Para todas las operaciones se creó una variable global llamada “global acarreo”

![m1PantallaApp.PNG](https://github.com/JorgeGallegos99/Informe-Trabajo-de-Investigacion/blob/master/Img/m1PantallaApp.PNG)

**Figura 15:** Pantalla de la Calculadora Binaria 

**Restricción:**
La restricción del programa es A≥B, para esto se realizó una transformación de sistema binario a decimal para realizar la comparación y cuando ese proceso sea verdadero se ejecutarán los procedimientos designados a cada botón.

![m2Restriccion.PNG](https://github.com/JorgeGallegos99/Informe-Trabajo-de-Investigacion/blob/master/Img/m2Restriccion.PNG)

**Figura 16:** Restricción

**Suma:**

1. La operación suma se realizará cuando el botón con el signo “+” sea seleccionado, llamando así al procedimiento definido como “OperacionSuma”

![m3BotonSuma.PNG](https://github.com/JorgeGallegos99/Informe-Trabajo-de-Investigacion/blob/master/Img/m3BotonSuma.PNG)

**Figura 17:** Boton Suma

2. Se implementaron tres procedimientos, suma0, suma1 y suma2, los cuales realizan la suma bit a bit de cada número ingresado desde el menos significativo al más significativo, es decir, de derecha a izquierda como se lo haría en una suma binaria normal.

![m4ProcesoSuma.PNG](https://github.com/JorgeGallegos99/Informe-Trabajo-de-Investigacion/blob/master/Img/m4ProcesoSuma.PNG)

**Figura 18:** Proceso Suma

3. La suma de cada bit fue realizada en forma decimal y con ayuda del bloque condicional if, se designó un valor correspondiente a la respuesta del bit sumado, según los siguientes casos:
* Sumando 2 se coloca cero en el bit de respuesta y se lleva 1 acarreo.
* Sumando 1 se coloca 1 en el bit de respuesta y se lleva 0 de acarreo.
* Sumando 0 se coloca 0 en el bit de respuesta y se lleva 0 de acarreo.

![m5OperacionSuma.PNG](https://github.com/JorgeGallegos99/Informe-Trabajo-de-Investigacion/blob/master/Img/m5OperacionSuma.PNG)

**Figura 19:** Operación Suma

4. Aplicando así la lógica binaria en la operación suma.

**Resta:**

1. La operación resta se realizará cuando el botón con el signo “-” sea seleccionado, llamando así al procedimiento definido como “OperacionResta”
![m6BotonResta.PNG](https://github.com/JorgeGallegos99/Informe-Trabajo-de-Investigacion/blob/master/Img/m6BotonResta.PNG)

**Figura 20:** Boton Resta

2. Se implementaron tres procedimientos, resta0, resta1 y resta2, los cuales realizan la resta bit a bit de cada número ingresado desde el menos significativo al más significativo, es decir, de derecha a izquierda como se lo haría en una resta binaria normal.

![m7ProcesoResta.PNG](https://github.com/JorgeGallegos99/Informe-Trabajo-de-Investigacion/blob/master/Img/m7ProcesoResta.PNG)

**Figura 21:** Proceso Resta

3. Debido a las restricciones del programa planteadas inicialmente la operación resta solo se realizará cuando A>B, es decir, solo cuando el minuendo es mayor al sustraendo. 

![m8OperacionResta.PNG](https://github.com/JorgeGallegos99/Informe-Trabajo-de-Investigacion/blob/master/Img/m8OperacionResta.PNG)

**Figura 22:** Operacion Resta

4. Aplicando así la lógica binaria en la operación resta.

**Multiplicación:**

1. La operación multiplicación se realizará cuando el botón con el signo “*” sea seleccionado, llamando así al procedimiento definido como “OperacionMultiplicacion”

![m9BotonMultiplicacion.PNG](https://github.com/JorgeGallegos99/Informe-Trabajo-de-Investigacion/blob/master/Img/m9BotonMultiplicacion.PNG)

**Figura 23:** Boton Multiplicación

La operación multiplicación se divide en dos procesos, el primero realiza el proceso de multiplicación de bit a bit y el segundo realiza la suma de dichas multiplicaciones.
2. La multiplicación de bit a bit se realiza con las reglas básicas de la multiplicación binaria.

![m10Multiplicaciones.PNG](https://github.com/JorgeGallegos99/Informe-Trabajo-de-Investigacion/blob/master/Img/m10Multiplicaciones.PNG)

**Figura 24:** Multiplicaciones

3. La suma de multiplicaciones se realiza con la misma estructura utilizada en la “OperacionSuma”.

![m11ProcesoMultiplicaciones.PNG](https://github.com/JorgeGallegos99/Informe-Trabajo-de-Investigacion/blob/master/Img/m11ProcesoMultiplicaciones.PNG)

**Figura 25:** Proceso Multiplicaciones

4. Finalmente se llama al proceso de “OperacionMultiplicacion” que realiza la suma binaria correspondiente de los procesos anteriores.

![m12OperacionMultiplicacion.PNG](https://github.com/JorgeGallegos99/Informe-Trabajo-de-Investigacion/blob/master/Img/m12OperacionMultiplicacion.PNG)

**Figura 26:** Operacion Multiplicar

5. Aplicando así la lógica binaria en la multiplicación.

**División:**

a.	La operación división se realiza cuando presionamos el botón que tiene el símbolo la división(slash) realizando el llamado al procedimiento denominado “División”.

![jEjecuciondivisionbinaria.png](https://github.com/JorgeGallegos99/Informe-Trabajo-de-Investigacion/blob/master/Img/jEjecuciondivisionbinaria.png)

**Figura 27.** Ejecución de la división binaria 

b.	EL algoritmo utilizado para realizar la división binaria se divide en do partes, la primera parte consiste en transformar las cantidades ingresadas en su representación decimal para determinar con mayor facilidad debido a que se ha establecido que A>B. posterior a esta comparación se procede a realizar las operaciones correspondientes para obtener el resultado de la división, esto se realizo a través de varias comparaciones con el objetivo de evaluar los dos números y conseguir un número divisible entero.

c.	Se creo una variable global denominada divisor la cual nos ayuda a transformar los números decimales a binarios con el algoritmo de las divisiones sucesivas y poder operar con dichas cantidades.

![jfragmentocodigo]( https://github.com/JorgeGallegos99/Informe-Trabajo-de-Investigacion/blob/master/Img/jfragmentocodigo.png)

**Figura 28.** Fragmento del código

d.	la segunda parte consiste en mostrar el resultado obtenido, esto lo haremos con un procedimiento denominado “division2”
Luego de haber ingresado el numero A y B obtendremos el resultado esperado.

**Borrar:**

1.El botón borrar elimina todos los valores de ingreso y de entrada para comenzar un nuevo proceso

![m13BotonBorrar.PNG](https://github.com/JorgeGallegos99/Informe-Trabajo-de-Investigacion/blob/master/Img/m13BotonBorrar.PNG)

**Figura 29:** Boton Borrar
 
### 9. DESCRIPCIÓN DE PRERREQUISITOS Y CONFIGURACIÓN

Cuando la calculadora de binarios con 3 bits ya está listo para probarlo se utiliza un emulador que la de la aplicación como se muestra en la  siguiente tabla.

**Tabla 3:** Herramientas Secundarias Utilizadas.
|                 **Herramientas de Software**       |                  **Descripción**                      |
|----------------------------------------------------|-------------------------------------------------------|
|    Emulador de MIT App Inventor para computadores. | La aplicación MIT App Inventor te da directamente el emulador para probar el                                                          programa que estas creando.                             |
|Emulador de MIT App Inventor para sistemas Android. | Se puede descargar directamente de una tienda de aplicaciones. Ejemplo: Play                                                          Store                                                   |
|                       BLUESTACKS                    | Es un emulador de Android que se utiliza en la computadora y permite descargarse                                                      el MIT App Inventor para probar el programa creado.      |                          
### 10. APORTACIONES
**BlueStacks.**
- Emulador de Android el cual se usó para descargar la aplicación de appinventor en el ordenador y poder realizar las pruebas del programa realizado.

![BLUESTACKS1](https://github.com/JorgeGallegos99/Informe-Trabajo-de-Investigacion/blob/master/Img/BLUESTACKS.png)

**Figura 30**  BlueStacks

### 11. CONCLUSIONES
+ Se realizó la calculadora Binaria para 3 Bits, con un diseño amigable al usuario con el funcionamiento de las 4 operaciones aritméticas  mediante la aplicación appinventor.
+ Se conoció acerca de las características del Mit App Inventor, su funcionamiento y como trabajar en ella para crear un nuevo programa disponible para el Sistema Operativo Android.
+ Se Utilizó los conceptos de operaciones binarias: suma, resta y multiplicacion para crear la calculadora binaria.
+ Mediante la investigacion de la división de números binarios se pudo implementar el algoritmo para la 4 operación de numeros binarios.
+ Se creó la calculadora con las 4 operaciones para números binarios de 3 bits.
+ Se ImplementÓ código propio para la aplicación sin ninguna de las librerías preestablecidas.

### 12. RECOMENDACIONES
+ La calculadora Binaria admite solo números de 3 bits.
+ El número que se ingrese en el casillero A debe ser mayor al casillero B.
+ Una vez ingresado los datos se puede realizar cualquiera de las 4 operaciones sin necesidad de borrar.

### 13. CRONOGRAMA

![CR1.png](https://github.com/JorgeGallegos99/Informe-Trabajo-de-Investigacion/blob/master/Img/CR1.png)

**Figura 31** Cronograma creado en Monday.


### 14. BIBLIOGRAFÍA
* Franco Mariscal, A. J. (19 de Enero de 2008). Educación Matemática. Obtenido de http://www.scielo.org.mx/scielo.php?pid=S1665-58262008000200006&script=sci_arttext
* Matemática para Programadores. (3 de Septiembre de 2015). Obtenido de Sistemas de Numeración y Aritmética Binaria: https://d1wqtxts1xzle7.cloudfront.net/38651460/matematicas-para-programadores.pdf?1441246752=&response-content-disposition=inline%3B+filename%3DMatematicas-para-programadores.pdf&Expires=1592023716&Signature=Bkpu0LBX6wSab4OsdSqjkX9c85Sd2qBuhKvhI2-4tEXTUhM
* Redondo Galván, A. (16 de MArzo de 2016). Universidad Autónoma del Estado de México. Obtenido de Lógica Secuencial y Combinatoria: http://ri.uaemex.mx/oca/bitstream/20.500.11799/32726/1/secme-35753.pdf
* Villa Martínez, H. A. (2008). Universidad de Sonora. Obtenido de Programa de Ciencias de la Computación: https://www.researchgate.net/profile/Hector_Villa-Martinez/publication/291335556_Sistemas_numericos/links/56a0276b08ae2c638eb7f34a.pdf
* https://appinventor.mit.edu/
* https://monday.com/lang/es/?utm_source=adwordsbrand&utm_campaign=spanish_en-rlsa-remarketing-brand b&aw_keyword=%2Bmonday&aw_match_type=b&gclid=Cj0KCQjwuJz3BRDTARIsAMgHxWgIz2tuLReevEnLf5flffgemHcL11Dwy5Y1i2a4CnXgftvufdy_4gaAvb8EALw_wcB

### 15. ANEXOS

## 15.1. MANUAL DE USUARIO
**Manual de usuario:** 

Calculadora Binaria es una aplicación para Android que permitirá realizar operaciones binarias elementales entre dos números de 3 bits de una manera fácil y sencilla.

1. Ingresar los números con los que se desea trabajar en cada casillero correspondiente. Hay que recordar que el número mayor va en A.

![m14Paso1Manual.PNG](https://github.com/JorgeGallegos99/Informe-Trabajo-de-Investigacion/blob/master/Img/m14Paso1Manual.PNG)

**Figura 32**  Paso 1 del Manual

2. Presionar el botón correspondiente a la operación que desee realizar.

![m15Paso2Manual.PNG](https://github.com/JorgeGallegos99/Informe-Trabajo-de-Investigacion/blob/master/Img/m15Paso2Manual.PNG)

**Figura 33**  Paso 2 del Manual

3. La respuesta de la operación se reflejará automáticamente en el campo de texto “Resultado”.

![m16Paso3Manual.PNG](https://github.com/JorgeGallegos99/Informe-Trabajo-de-Investigacion/blob/master/Img/m16Paso3Manual.PNG)

**Figura 34**  Paso 3 del Manual

¡Listo! Obtienes el resultado

4. Pulsar el botón “Borrar para limpiar la pantalla e ingresar nuevos valores para operar.

[m17Paso4Manual.PNG](https://github.com/JorgeGallegos99/Informe-Trabajo-de-Investigacion/blob/master/Img/m17Paso4Manual.P

**Figura 35**  Paso 4 del Manual



