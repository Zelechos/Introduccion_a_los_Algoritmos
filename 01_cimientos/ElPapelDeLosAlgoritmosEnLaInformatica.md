# 1 El Papel de los Algoritmos en la Informatica

¿Qué son los algoritmos? ¿Por qué vale la pena estudiarlos? ¿Cuál es el papel
de los algoritmos en relación con otras tecnologías utilizadas en las computadoras? En este capítulo,
responderemos estas preguntas.

## 1.1 Algoritmos

De manera informal, un ***algoritmo*** es cualquier procedimiento computacional bien definido que toma
un valor o un conjunto de valores como ***entrada***  y produce un valor o un conjunto de valores como
***salida*** . Por lo tanto, un algoritmo es una secuencia de pasos computacionales que transforman la
entrada en la salida.
También podemos considerar un algoritmo como una herramienta para resolver un ***problema computacional***  bien especificado. 
El enunciado del problema especifica en términos generales la relación ***entrada/salida*** deseada. 
El algoritmo describe un procedimiento computacional específico para lograr esa relación entrada/salida.
Por ejemplo, podríamos necesitar ordenar una secuencia de números en un orden no decreciente. 
Este problema surge con frecuencia en la práctica y proporciona un terreno fértil para
introducir muchas técnicas de diseño y herramientas de análisis estándar. Así es como definimos formalmente el ***problema de ordenación (sorting problem)***:

Entrada: Una secuencia de $n$ numeros $\langle a_1, a_2,\dots, a_n \rangle$

Salida: Una permutación (reordenación) $\langle a'_1, a'_2, \dots, a'_n \rangle$ de la secuencia de entrada tal que  
$$a'_1 \leq a'_2 \leq \dots \leq a'_n.$$


Por ejemplo, dada la secuencia de entrada 
$$
\langle 31, 41, 59, 26, 41, 58 \rangle,
$$ 
un algoritmo de ordenamiento devuelve como salida la secuencia 
$$
\langle 26, 31, 41, 41, 58, 59 \rangle.
$$ 

Dicha secuencia de entrada se denomina una **instancia del problema de ordenamiento**.  
En general, una instancia de un problema consiste en la entrada (que satisface las restricciones impuestas en la definición del problema) 
necesaria para calcular una solución al problema.

-- TODO : Continuar en la pagina 6
