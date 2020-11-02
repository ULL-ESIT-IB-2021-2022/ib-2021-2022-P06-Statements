# Práctica 05. Sentencias en C++. Declaraciones, Expresiones, Asignaciones, Sentencias de control de flujo. 

### Objetivos
Los objetivos de esta práctica son que el alumnado:

* Desarrolle programas sencillos en C++ que utilicen los diferentes tipos de sentencias estudiadas
* Conozca los tipos básicos de datos en C++, así como los fundamentos de su representación en memoria
* Sea capaz de automatizar el proceso de compilación utilizando la herramienta `make`

### Rúbrica de evaluacion de esta práctica
Se señalan a continuación los aspectos más relevantes (la lista no es exhaustiva)
que se tendrán en cuenta a la hora de evaluar esta práctica:
* El alumnado ha de acreditar que es capaz de realizar programas simples en C++ similares a los que se
  proponen en este documento.
* El alumnado ha de acreditar que ha realizado todos los ejercicios propuestos, así como ser capaz de
  desarrollar otros similares
* Ha de acreditar que es capaz de escribir un fichero Makefile para automatizar el proceso de compilación de
  sus programas
* El alumnado ha de acreditar conocer los conceptos expuestos en el material de referencia de esta práctica

### Trabajo previo
1. Estudie en el tutorial "Fundamentos de Informática" todo el material correspondiente a los capítulos 2, 3,
4 y 5:
[Expresiones](http://www.minidosis.org/#/temas/Cpp.Expresiones)
[Expresiones Booleanas](http://www.minidosis.org/#/temas/Cpp.ExpresionesBooleanas)
[Alternativas](http://www.minidosis.org/#/temas/Cpp.Alternativas)
[Iteraciones](http://www.minidosis.org/#/temas/Cpp.Iteraciones)


### Ejercicios 
1. 

2. 

3. 

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
n: 18
18 9 28 14 7 22 11 34 17 52 26 13 40 20 10 5 16 8 4 2 1
```
```
n: 19
19 58 29 88 44 22 11 34 17 52 26 13 40 20 10 5 16 8 4 2 1
```
n: 20
20 10 5 16 8 4 2 1
```

### Referencias
* [Tutorial Fundamentos de Informática](http://www.minidosis.org/#/cursos/FI)
* [Google C++ Style Guide](https://google.github.io/styleguide/cppguide.html)

