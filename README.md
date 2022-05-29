# **PROGRAMAS EN C++ DE MUSO CAMILY**

------------
#### *Aquí encontrarás toda la información que se necesita para manejar los programas elaborados y desarrollados en este directorio. Todos los programas a continuacion fueron desarrollados en lenguaje c++.*

------------
### Información sobre el Autor

------------

Creador por: Camily Fiorella Muso Díaz.

Correo Institucional: camily.muso.diaz@utelvt.edu.ec

Correo Personal: camiliitawdiazyt18@gmail.com

Video de Introducción sobre informática: https://www.youtube.com/watch?v=0vOxndYnAfk

## **Programas**
------------
## **Programa para comparar dos números**
- ###  Descripción del problema que soluciona

Este programa permite comparar dos números ingresados manualmente por el usuario y determinar cuándo los números son iguales o uno es mayor que el otro.
- ###  Funcionalidad

El programa comienza utilizando variables de tipo decimal, llamado "float".

El programa permite ingresar dos cantidades que deseamos comparar, las cuales se van almacenar en las dos variables CM_V1 y CM_V2.


Una vez ingresadas las variables, utilizaremos la función "if" para poder hacer una comparación lógica entre las cantidades ingresadas.

- ### **Salidas**

Una vez ya terminado el proceso lógico, se pueden imprimir el total de tres posibilidades:

- Primera posibilidad: Ambas cantidades son iguales.(Saldran iguales en caso de que los numeros ingresados sean iguales)

- La segunda: El número de la variable CM_V1 es menor que CM_V2(Esto ocurre si el primer número ingresado es menor que el segundo numero ingresado)

- La tercera: El número ingresado en la variable CM_V2 es menor que CM_V1(Esto pasa porque el segundo valor ingresado en la segunda variable es menor que la primer variable)
###### *Imagen de referencia:*
[![Imagen de Referencia:](https://pbs.twimg.com/media/FT0XBOOWIAAavHF?format=png&name=small "Imagen de Referencia:")](http://https://pbs.twimg.com/media/FT0XBOOWIAAavHF?format=png&name=small "Imagen de Referencia:")

------------

## **Programa para realizar una suma de varios números**

- ### Descripción del problema que soluciona

El programa permite sumar la cantidad de numeros que el usuario desee, ingresandolos todos de manera manual.

- ### Funcionalidad

En este programa vamos a usar dos tipos de datos; los enteros (int), y los decimales (float).

En este caso se dara el uso de un contador (CM_c que va a estar declarado como un entero) y el uso de un acumulador (CM_m que va a estar declarado como decimal).

El contador va a ir incrementando de uno en uno, en función del numero que ingrese el usuario (CM_D).

El acumulador va a ir almacenando la suma de las cantidades que ingrese el usuario (CM_s).

Para complementar este proceso, vamos a usar una estructura repetitiva do-while, que servirá para que el proceso anteiormente descrito, se repita mientras se cumpla una condición (CM_c < CM_D).
- ### Salidas

Una vez realizado todo el proceso que se indica, el programa comenzara a imprimir el valor del contador (CM_D) y el valor del acumulador (CM_m).

###### *Imagen de referencia:*
[![Imagen de referencia:](https://pbs.twimg.com/media/FT4Lo5tWQAA3nLx?format=png&name=small "Imagen de referencia:")](http://https://pbs.twimg.com/media/FT4Lo5tWQAA3nLx?format=png&name=small "Imagen de referencia:")

------------


## **Programa para para calcular el punto de venta**

------------
- ### **Descripción del problema que soluciona**

El programa permite ingresar el valor de las comprar que el usuario desee, calcula el valor del IVA de la compra, aplica un descuento a elección del usuario, para finalmente, mostrar el valor bruto de la compra, el valor del IVA, el valor del descuento, y el precio final a pagar.

- ### **Funcionalidad**

En este programa se usaran las variables de tipo entero (int), aunque tambien se puede usar las variables de tipo decimal que seria(float).

 Generalmente utilizamos una variable de control como contador que al llegar a un número predeterminado, vamos a utilizar una estructura repetitiva do-while, que servirá para que el proceso anteriormente descrito, se repita mientras se cumpla una condición (CM_i<=CM_a).

Una vez que hemos ingresado, sumado y almencenado el valor bruto de las compras (CM_vb), tenemos que aplicarle un descuento. Para ello, le pedimos al usuario que ingrese el descuento que desee aplicar (CM_AC).

Despues de los puntos ya establecidos, se realizan los siguientes procesos:

- CM_iv=CM_vb*0.15;(la variable CM_iv a almacenar el resultado del descuento que se le aplique a la compra).

- CM_TP=CM_vbi-CM_AC; (la variable CM_TP va a almacenar el resultado de la diferencia entre el valor acumulado de las compras, y el valor resultante del descuento).

- CM_AC=CM_vbi*0.10;(la variable CM_AC va a almacenar el calculo del IVA de la variable anterior CM_vbi).

- CM_TP=CM_vbi-CM_AC; (la variable CM_TP va a almacenar el resultado final, en el cual se va a aplicar el descuento, y añadir el IVA).

- ### Salidas

Una vez que se realiza todo este proceso, el programa nos va a imprimir los siguientes valores:

CM_vb (variable que representa el valor bruto de las compras).

CM_AC (variable que representa el valor de la compra, aplicandole el descuento).

CM_iv (variable que representa el valor de la compra, añadiendole el IVA).

CM_TP (variable que representa el valor final).

###### *Imagen de referencia:*
[![Imagen de referencia:](https://pbs.twimg.com/media/FT4V4s0XEAEehKv?format=png&name=small "Imagen de referencia:")](http://https://pbs.twimg.com/media/FT4V4s0XEAEehKv?format=png&name=small "Imagen de referencia:")

------------

## **Programa para saber la edad de una persona**

- ### **Descripción del problema que soluciona**

El programa permite calcular la edad exacta de una persona, mediante el ingreso de la fecha de nacimiento del usuario dia, mes y año, por otra parte mostrara el ingreso de la fecha actual dia, mes y año.

- ### **Funcionalidad**

En este programa, solo vamos a usar variables de tipo entero (int).

Para iniciar el programa, tenemos que ingresar el valor de las variables que van a representar la fecha actual, bajo el formato día/mes/año (CM_fechact, CM_mesact y CM_anioact respectivamente).

Progresivamente, se tiene que ingresar el valor de las variables que van a representar la fecha de nacimiento del usuario, bajo el formato día/mes/año (CM_fechnac, CM_mesnact, CM_anionac respectivamente).

Una vez que se ingresan esas variables, el programa va a realizar una operacion logica que es el restar las fechas actuales y las fechas de nacimiento.

##### 1. *CM_dia=CM_fechact-CM_fechnac; (Usamos la variable CM_dia, que va a almacenar la diferencia entre el día actual y el día de nacimiento).*

##### 2. *CM_mes=CM_mes+12; (Se suman 12 meses a la cantidad de meses actuales ingresados por el usuario).*

##### 3. C*M_edad=CM_anioact-CM_anionac; (Usamos la variable CM_edad, que va a almacenar la diferencia entre la cantidad de años actuales ingresados).*

##### 4. *CM_mes=CM_mesnact-CM_mesact; (Usamos la variable CM_mes, que va a almacenar la diferencia entre el mes actual y el mes de nacimiento).*

- ### **Salida**

Una vez que se realicen todos los procesos descritos antes, el programa imprime los siguientes resultados:

CM_edad (Esta variable almacena la diferencia entre el año actual y el año de nacimiento).

CM_mes (Esta varible almecena la diferencia entre el mes actual y el mes de nacimiento).

CM_dia (Esta variable almacea la diferencia entre el día actual y el día de nacimiento).

###### *Imagen de referencia:*
[![Imagen de referencia:](https://pbs.twimg.com/media/FT4ekIbXEAAblhp?format=png&name=small "Imagen de referencia:")](http://https://pbs.twimg.com/media/FT4ekIbXEAAblhp?format=png&name=small "Imagen de referencia:")

------------

## **Programa contador y clasificador de monedas**

- ###**Descripción del problema que soluciona**

El programa permite ingresar la cantidad de monedas que el usuario desee, repartidas en tres denominaciones (10 y 25 centavos). Una vez ingresadas las monedas, el programa debe clasificar cuantas monedas de cada tipo se han ingresado, imprimir ese dato e imprimir el valor total del dinero ingresado.

- ### Funcionalidad

En este programa vamos a usar dos tipos de datos; los enteros (int), y los decimales (float).

Para comenzar con la realización del programa, debemos de usar la variable CM_n para que el usuario ingrese la cantidad de monedas a ingresar. Esta misma variable va a ser usada para determinar el tamaño del vector num, que vamos a declarar después.

Una vez que hemos usado la variable CM_n, vamos a usar un vector de una dimensión, con el valor almacenado en la variable CM_n (num [CM_n]).

Posterior a ello, vamos a usar la variable CM_b, con la cual el usuario tiene que ingresar los valores, con los cuales va a rellenar el vector declarado anteriormente.

Adicional a esto, vamos a usar la condicion if y else_if para poder analizar los tipos de monedas ingresadas por el usuario; en caso de que la moneda ingresada sea de un valor de 10 centavos(num [CM_b]==10), vamos a usar un acumulador (CM_x1) que va a almacenar unicamente la cantidad de monedas de 10 centavos ingresadas.

Complementando el programa, vamos a añadir la función if y else_if para poder analizar los tipos de monedas ingresadas por el usuario; en caso de que la moneda ingresada sea de un valor de 10 centavos(num [CM_b]==10), vamos a usar un acumulador (CM_z1) que va a almacenar unicamente la cantidad de monedas de 10 centavos ingresadas.

En caso de que la condición anterior no se cumpla, usaremos un else_if, en donde, si el valor de la moneda ingresada es de 25 centavos (num [CM_b]==25), vamos a usar un acumulador (CM_z2) que va a almacenar unicamente la cantidad de monedas de 25 centavos.

También, vamos a usar una variable (CM_x) para almacenar la suma de todas las monedas ingresadas.

- ### Salidas

Una vez que se realicen los procesos descritos antes, el programa va a imprimr los siguientes resultados:

CM_x2 (Esta variable va a almacenar la cantidad de monedas de 25 centavos ingresadas).

CM_z1 (Esta variable va a almacenar la cantidad de monedas de 10 centavos ingresadas).

CM_x (Esta variable va a almacenar la sumatoria del valor de las monedas ingresadas).

###### *Imagen de referencia:*
[![Imagen de referencia:](https://pbs.twimg.com/media/FT4kVfKWAAAP7Kj?format=png&name=small "Imagen de referencia:")](http://https://pbs.twimg.com/media/FT4kVfKWAAAP7Kj?format=png&name=small "Imagen de referencia:")

------------

## Descargar e Instalar los Programas realizados

------------

##### *Para poder descargar el repositorio en el que se encuentran los programas descritos en este foro.*

------------


## Los siguientes dos pasos  que deberas realizar son:

### *1. Clonar el repositorio*

Para clonar el repositorio en tu entorno de trabajo, debes usar el comando git clone, seguido de la dirección del repositorio en donde se encuentra el trabajo.

##### git clone

https://github.com/CamiRusse/CamilyMuso/Actividad-E2.git

Una vez clonado en tu equipo, tienes que usar el comando git pull para poder descargar cualquier cambio que se haya podido realizar en el repositorio.

Usando el comando ls de termux, puedes verificar que se encuentran todos los archivos que acabas de descargar.

En caso de que necesites realizar y subir cambios en losp programas, recuerda usar los comandos git status (para ver que es lo que se somete a cambios), git add (para añadir esos cambios a la nube), git commit (para comentar esos cambios) y git push (para poder subir a github los cambios que introduciste).

### *2. Compilar los programas*

En caso de que desees compilar y correr los archivos .cpp, debes usar el comando g++ nombre_del_programa.cpp -o nombre_del_programa. 

##### Ejemplo

g++ MusoCamily_Compara.cpp -o MusoCamily_Compara

Muchas gracias por su atención. =)
Espero que haya sido de ayuda.
