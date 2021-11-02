# Práctica 06. Sentencias en C++. Declaraciones, Expresiones, Asignaciones, Sentencias de control de flujo. 

# Factor de ponderación: 5

### Objetivos
Los objetivos de esta práctica son que el alumnado:
* Desarrolle programas sencillos en C++ que utilicen los diferentes tipos de sentencias estudiadas

### Rúbrica de evaluacion de esta práctica
Se señalan a continuación los aspectos más relevantes (la lista no es exhaustiva)
que se tendrán en cuenta a la hora de evaluar esta práctica:
* El alumnado ha de acreditar conocer los conceptos expuestos en el material de referencia de esta práctica.
* El alumnado ha de acreditar que ha realizado todos los ejercicios propuestos, así como ser capaz de desarrollar otros similares.
* Ha de acreditar que es capaz de escribir un fichero Makefile para automatizar el proceso de compilación de sus programas.
* El código que escriba ha de estar escrito de acuerdo a los estándares definidos en la Guía de Estilo de Google para C++.
* Todos los identificadores que utilice en su programa (constantes, variables, etc.) deberán ser
  siempre significativos. No utilice nunca identificadores de una única letra, tal vez con la excepción de las
  variables que utilice para iterar en un bucle.
* Antes de su ejecución, todos los programas que desarrolle, deben imprimir en pantalla un
  mensaje indicando la finalidad del programa así como la información que precisará del usuario para su correcta ejecución.

### Trabajo previo
Estudie en el tutorial "Fundamentos de Informática" todo el material correspondiente a los capítulos 2, 3,
4 y 5:
[Expresiones](http://www.minidosis.org/#/temas/Cpp.Expresiones),
[Expresiones Booleanas](http://www.minidosis.org/#/temas/Cpp.ExpresionesBooleanas),
[Alternativas](http://www.minidosis.org/#/temas/Cpp.Alternativas)
e
[Iteraciones](http://www.minidosis.org/#/temas/Cpp.Iteraciones)

### Ejercicios 
1. Escriba un programa `dividers.cc` que solicite al usuario un número e imprima en pantalla todos los
divisores del número introducido:
```
Introduzca un número: 200
1 2 4 5 8 10 20 25 40 50 100 200
```

2. Escriba un programa que lea un número natural e imprima en pantalla un "cuadrado hecho de asteriscos" del tamaño indicado. 
Por ejemplo, este es el cuadrado de 5 asteriscos:
```
*****
*****
*****
*****
*****
```
3. Escriba un programa que lea un número natural e imprima como salida la suma de los dígitos del número en cuestión.
Por ejemplo, si el número introducido fuera el 2021, la salida debería ser 5

2. Desarrolle un programa `longest_shortest.cc` que se comporte como se describe a continuación:
* En primer lugar, se solicita al usuario que introduzca un número entero, `n` que indicará cuántas palabras introducirá a continuación;
* A continuación el usuario introducirá `n` palabras

    La salida del programa debe mostrar en pantalla la palabra más larga y la más corta introducidas por el usuario. El siguiente sería un ejemplo de la ejecución del programa:
```
Cantidad de palabras: 5
Palabra 1: negro
Palabra 2: amarillo
Palabra 3: naranjo
Palabra 4: azul
Palabra 5: blanco
La palabra mas larga es amarillo
La palabra mas corta es azul
```
    Para realizar este programa estudie los métodos (funciones) disponibles para los objetos de la clase
`std::string`.
Puede Ud. estudiarlos en [esta referencia](http://www.cplusplus.com/reference/string/string/) (por ejemplo).
En particular el método [length](http://www.cplusplus.com/reference/string/string/length/) devuelve la longitud de una cadena.

3. Realice un programa `statistics.cc` que declare un `std::vector` de tamaño `kVectorSize` y lo inicialice
con valores aleatorios en el rango [0.0, 10.0]. 
El programa imprimirá en pantalla el valor medio de los datos del vector así como los valores mínimo y máximo.
Para generar números aleatorios en C++ consulte la función `std::rand` por ejemplo en 
[esta referencia](https://en.cppreference.com/w/cpp/numeric/random/rand).

4. La secuencia de Collatz de un número entero se construye de la siguiente forma:
* si el número es par, se lo divide por dos;
* si es impar, se le multiplica tres y se le suma uno;
* la sucesión termina al llegar a uno

La [conjetura de Collatz](https://es.wikipedia.org/wiki/Conjetura_de_Collatz) 
afirma que, al partir desde cualquier número, la secuencia siempre llegará a 1. 
A pesar de ser un resultado a simple vista muy simple, no se ha podido demostrar si es cierta o no.

Usando ordenadores, se ha verificado que la sucesión efectivamente llega a 1 partiendo desde cualquier número natural menor que 2<sup>58</sup>.

Desarrolle un programa `collatz.cc` que entregue la secuencia de Collatz de un número entero.
Se muestran a continuación los resultados que debería entregar el programa para algunos valores del número N
de entrada.
Este valor (número de entrada) en su programa deberá estar representado por la constante `kInitialValue`.

```
kInitialValue: 18
18 9 28 14 7 22 11 34 17 52 26 13 40 20 10 5 16 8 4 2 1
```
```
kInitialValue: 19
19 58 29 88 44 22 11 34 17 52 26 13 40 20 10 5 16 8 4 2 1
```
```
kInitialValue: 20
20 10 5 16 8 4 2 1
```

### Referencias
* [Tutorial Fundamentos de Informática](http://www.minidosis.org/#/cursos/FI)
* [Google C++ Style Guide](https://google.github.io/styleguide/cppguide.html)
* [La función std::rand](https://en.cppreference.com/w/cpp/numeric/random/rand)
* [La conjetura de Collatz](https://es.wikipedia.org/wiki/Conjetura_de_Collatz) 
* [La clase std::string](http://www.cplusplus.com/reference/string/string/)

