hello.c es un codigo que imprime  "Hello World" en el terminal.

partes del codigo:
El archivo "stdio.h" es una cabecera estándar en el lenguaje de programación C. "stdio" es una abreviatura de "standard input/output" (entrada/salida estándar) y contiene las declaraciones necesarias para realizar operaciones básicas de entrada/salida, como leer desde el teclado o escribir en la pantalla. Por eso al inicio del codigo incluiremos esta cabecera estándar con "#include <stdio.h>".
luego, encontraremos la función main, que sera la funcion donde estarán las lineas encargadas de imprimir nuestro "Hello World". Para poder imprimir nuestra oración, utilizaremos la función printf, la cual imprimira nuestro "Hello World" en la terminal.
este codigo fue compilado con el estandard c11 escribiendo en la terminal gcc hello.c -std=gnu11 -o hello.
si queremos que en vez de imprimir en una terminal, la salida sea en un archivo txt, escribiremos en el terminal:
./hello > output.txt

