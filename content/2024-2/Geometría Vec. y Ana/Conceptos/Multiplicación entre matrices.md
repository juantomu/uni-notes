# Multiplicación entre matrices
***
Sea A una matriz de orden $m \times n$ y B una matriz de orden $n \times p$. Cada entrada de la matriz AB es el producto escalar entre la i-ésima fila de A y la j-ésima columna de B.

Básicamente, la multiplicación solo es posible si el número de columnas de A es el mismo número de filas en B. Además, el orden de la matriz del resultado corresponde al número de filas de A x el numero de columnas de B.

$AB$ y $BA$ **no** siempre son iguales.
### Ejemplos
***
Ej 1:
	![[20240820_152629.jpg]]
Ej 2:
	![[20240820_153510.jpg]]
Ej 3:
$$B_{2x3}A_{3x3}=\begin{bmatrix}3&-1&4\\-2&5&1\end{bmatrix}\begin{bmatrix}-2&1&-3\\0&2&-1\\4&2&-5\end{bmatrix}=\begin{bmatrix}10&9&-28\\8&10&-4\end{bmatrix} $$
## Multiplicación de una matriz por una matriz identidad
***
Queda como la matriz original.

Ejemplo:
$$B_{2x3} Id_{3x3}=\begin{bmatrix}3&-1&4\\-2&5&1\end{bmatrix}\begin{bmatrix}1&0&0\\0&1&0\\0&0&1\end{bmatrix}=\begin{bmatrix}3&-1&4\\-2&5&1\end{bmatrix}=B$$
