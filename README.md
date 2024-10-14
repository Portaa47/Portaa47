# Recursividad 
----
fun numerosDesc(n= int) {
  if (n<=0)
  {
  print(n)
  numerosDesc(n-1)
}
fun main()
{
 val num=5
 numerosDesc(num)
}
----
Caso Base
 
El caso base en recursividad es el caso más simple de un problema que se puede resolver directamente, sin necesidad de llamar a la función recursiva nuevamente. Es el punto de parada de la recursividad, donde la función deja de llamarse a sí misma.

El caso base es importante porque:

◈ Evita la recursividad infinita: sin un caso base, la función recursiva seguiría llamándose a sí misma indefinidamente, lo que provocaría un error de stack overflow.

◈ Proporciona una solución trivial: el caso base proporciona una solución directa para el problema más simple, lo que permite que la función recursiva se construya sobre esta solución.

◈ Permite la descomposición del problema: el caso base ayuda a descomponer el problema en subproblemas más pequeños, que se pueden resolver de manera recursiva.

Un buen caso base debe cumplir con las siguientes características:

◈ Ser lo suficientemente simple como para ser resuelto directamente.

◈ Ser una instancia trivial del problema original.

◈ No requerir llamadas recursivas adicionales.

Llamada recursiva

La llamada recursiva es el proceso por el cual una función se llama a sí misma, ya sea directa o indirectamente, para resolver un problema. En otras palabras, una función recursiva es aquella que se invoca a sí misma durante su ejecución.

La llamada recursiva se caracteriza por:

◈ La función se llama a sí misma: La función recursiva se invoca a sí misma, lo que significa que se ejecuta nuevamente dentro de su propia ejecución.

◈ Parámetros diferentes: Cada llamada recursiva tiene parámetros diferentes, lo que permite que la función avance hacia la solución del problema.

◈ Condiciones de parada: La función recursiva debe tener condiciones de parada claras para evitar la recursividad infinita.

El proceso de llamada recursiva se puede describir de la siguiente manera:

◈ La función se llama a sí misma con parámetros iniciales.

◈ La función se ejecuta con los parámetros actuales y produce un resultado parcial.

◈ La función se llama a sí misma nuevamente con parámetros actualizados.

◈ El proceso se repite hasta que se alcanza la condición de parada.


La llamada recursiva es útil para resolver problemas que tienen las siguientes características:

◈ Se pueden descomponer en subproblemas más pequeños.

◈ Los subproblemas son similares al problema original.

◈ La solución del problema se puede construir a partir de las soluciones de los subproblemas.
