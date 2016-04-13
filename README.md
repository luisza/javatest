# Java test of Solvo 

Fork this repository for do your work.

# Statement 

Cree un servicio SOAP en java que reciba una lista de números y operaciones matemáticas en orden y devuelva el resultado de operarlas respetando el orden de precedencia.  Esta lista está construida por una aplicación web (no debe implementarla) que permite al usuario insertar los números sin ninguna validación.

La aplicación solo tendrá operaciones básicas (Suma, Resta, Multiplicación y División) para números enteros y con decimales.

Para la representación de los números de millares puede utilizar comas “,” o espacio por ejemplo 10,000 o 5,000,321 que se pueden
combinar con puntos de tal forma que un número válido es 10,592.76. Debe tener cuidado con la posición de la coma, ya que 100,02 no es válido, así como tampoco 10,0000, ni tampoco ,302.

Algunos ejemplos de entrada pueden ser (uso [] para denotar lista):

    [10,592.76, '+', '780', '+', 10000, '*', 200.76]
    [1, '/', 323, '-', 765]
    [1, '+', 2]

En caso existir algún error debe devolver un mensaje de error.
