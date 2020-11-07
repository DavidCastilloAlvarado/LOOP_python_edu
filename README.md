# **WHILE - FOR LOOP in Python**
### Qué es un LOOP?
Los loops pueden ejecutar un bloque de código, tantas veces como sea necesario hasta cumplir cierta condición, por lo que son ampliamente utilizados en programación.

### Qué es un FOR LOOP?
Es usado para iterar sobre elementos de una secuencia. Usualmente usado cuando tienes un pedazo de código que quieres correr "n" veces y donde "n" está definido.

### Qué es un WHILE LOOP?
Es usado para repetir un bloque de código. Ejecuta un bloque de código hasta que cierta condición se cumple o deja de cumplir.

# CÓMO USAR "WHILE LOOP"
While loop hace exactamente los mismos que "if else", pero en vez de correr el código una sola vez, este ejecuta y luego regresa al punto inicial de ejecución (manteniendo todas los cálculos en memoria) y lo repite todo el proceso nuevamente.

Sintaxis: 

    while <CONDICIÓN> :
        <CODIGO A EJECUTAR>

Ejemplo: 

![](/imagenes/whileexam.PNG)

* Linea 1: definimos la variable X con valor de 0
* Linea 2: El while loop verifica la condición x < 4. El valor actual es, entonces la condición es verdadera.

=> INGRESA AL BLOQUE DE CONTROL DEL WHILE LOOP

* Linea 3: Muestra en pantalla el valor actual de X. <br>
* Linea 4: X es incrementado en 1. El flujo de control regresa al inicio en la **línea 2**. Ahora el valor de x es 1, el cual es menor que 4 por lo que la condición es verdadera y vuelve a ejecutar el bloque de control. Esto continuará hasta que X se convierta en 4 y la condición WHILE se convierta en FALSA.

# CÓMO USAR "FOR LOOP"
En Python "FOR lOOP" son llamados iteradores.
Al igual que while loop, "FOR LOOP" se usa también para repetir bloques de código de programa. Pero a diferencia de while loop donde se dependía de una condición (VERDADERA, FALSA); "FOR LOOP" depende de elementos iterables.

![](/imagenes/forexam.PNG)

Este "FOR LOOP" itera con números declarados en el rango ( range(2,7) )

Cuando el código es ejecutado, imprimirá los números entre 2 y 7 sin incluir al 7, (2,3,4,5,6).

En general el FOR LOOP puede ser usado para iterar objetos, no necesariamente números.

![](/imagenes/forexam2.PNG)

* Línea 1: Almacenamos los string "jan", "FEB", etc ... dentro de la lista Months.<br>
* Línea 2: Iteramos el for loop en cada elemento de la lista Months.
Línea 3: Imprimimos el nombre del mes en cada iteración.
# CÓMO USAR EL COMANDO "break" EN "FOR LOOP"
Break es una función unica en for loop y while loop`s que permite terminar la ejecución del loop.

Ejemplo:

![](/imagenes/break.PNG)

En este ejemplo, nosotros preparamos el for loop para iterar los números del 10-20, pero queremos que termine las iteraciones cuando tome al número 15. Para ello, declaramos **break** cuando x==15. Entonces tan pronto cuando x sea igual a 15 la ejecución del loop terminará.

# CÓMO USAR EL COMANDO "continue" in FOR LOOP
La función "continue" como el nombre lo indica (continuar), terminará la iteración actual y pasará a la siguiente iteración para seguir ejecutando todas las iteraciones restantes del FOR LOOP.

![](/imagenes/continue.PNG)

El comando "continue" puede ser usado para capturar o evitar iterar ciertos valores, objetos o condiciones.
En nuestro ejemplo, tenemos declarado valores del 10-20, pero entre estos números nosotros solo queremos aquellos números que no son divisibles por 5 o entras palabras que divididos por 5 no nos de cero 0.

Entonces en nuestro rango range(10,20), solo hay 3 números divisibles por 5 (10,15,20), el resto no.

Finalmente el código exceptuará al 10,15,20.

* Línea 1: se declara el rango(10,20)
* Línea 2: se declara la condición de divisibilidad por 5 para ejecutar el "continue".
* Línea 3: se imprime el valor, el cual no es divisible entre 5

# QUÉ ES "enumerate()" EN PYTHON
Es una función integrada (built-in function) usado para asignar un índice para cada ítem del objeto iterable. Esta función agrega un índice a cada elemento del objeto iterable mientras llama uno a uno en cada iteración.

Ejemplo:<br>
La función enumerate es usada para enumerar o indexar los miembros de una lista u objeto iterable.

Supongamos que queremos enumerar los meses de la lista ( Jan, Feb, Marc, ….June), por lo que declaramos la variable i, esta enumerará los meses al mismo tiempo que avanza la ejecución del loop.

![](/imagenes/enumerate.PNG)

Cuando el código se ejecuta, la salida imprime el nombre del mes con su número de índice (0,Jan), (1,Feb), ...


# **EJEMPLO PRACTICO:**

    Escriba un programa en Python que lea dos números enteros [>0], el primer número debe ser menor que el segundo número, si esto no se cumple debe volver a ingresar los números.
    Luego el programa debe mostrar todos los números primos comprendidos entre estos números (ambos inclusive).

![](/imagenes/ejemplo.PNG)

* Línea 1 y 2: El programa solicita dos valores de entrada
* Linea 4 - 7: Inicia el proceso iterativo de verificación, donde n1 y n2 tienen que ser mayores a cero y además n2>n1
* Línea 9: Inicia el proceso de iteración entre los números n1 y n2, incluido el n2. Para determinar quien es número primo.
* Línea 10: inicializa el contador de divisores
* Línea 11: inicia una segunda iteración anidada la cual sirve para buscar divisores para cada número comprendido en la lista de la línea 9.
* Línea 12: Para cada posible divisor se consulta si existe divisibilidad, de ser el caso procese a aumentar la cantidad de divisores en la línea 13.
* Línea 14: Acabando la iteración con todos los posibles divisores, se consulta si es un número primo, de ser verdadero, se imprime en pantalla si el número es primo.
* REPETIR PARA CADA NÚMERO de la lista de la línea 9.


# CONCLUSIÓN
Como pudimos observar el uso de estas simples herramientas son la base de toda la programación. Las computadoras saben hacer a la perfección tareas repetitivas, las cuales podemos codificar en unas cuantas líneas.<br>
Con ejemplos sencillos no es posible visualizar la magnitud de su alcance en el desarrollo de software, pero mientras más se interiorice más interesantes se convertirán. <br>

Si estás aquí entonces estás iniciando tu camino en la programación, por lo que si te gustan estos temas, te recomiendo ver mi canal de YouTube en donde encontraras más contenido interesante. 

![](/imagenes/yt.png)
