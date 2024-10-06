# Inversa por Determinantes 
***
Solo aplica para matrices cuadradas.

## Matrices 2x2
***
**Forma general**
$$A=\begin{bmatrix}a&b\\c&d\end{bmatrix}, A^{-1}=\frac{1}{ad-bc}\begin{bmatrix}d&-b\\-c&a\end{bmatrix}=\frac{1}{det(A)}\begin{bmatrix}d&-b\\-c&a\end{bmatrix}$$
**Ejemplo**
$$
A=\begin{bmatrix}3&-1\\4&5\end{bmatrix}, \space A^{-1}=\frac{1}{15-(-4)}\begin{bmatrix}5&1\\-4&3\end{bmatrix}=\frac{1}{19}\begin{bmatrix}5&1\\-4&3\end{bmatrix}
$$

**Paso 1:** Escribir la división $\frac{1}{}$ entre el [[Determinante |determinante de la matriz]]. ^ab72c9

**Paso 2:** La diagonal principal en la matriz se intercambia y a los números de la secundaria se cambian de signo.

## Matrices 3x3 | Método Cofactores - Adjunta
***
**Paso 1:** Hallar el [[Determinante|determinante]] ya sea por [[Determinante#Matrices 3x3 - Cofactores|cofactores]] o [[Determinante#Matrices 3x3 - Regla de Sarrus|Sarrus]]. 
*El determinante también se puede hallar multiplicando término a término cualquier fila o columna escogida de la matriz original y la de cofactores (aplicable a partir del [[#^f8d9d6|paso 3]]).*  ^0f725d

**Paso 2:** Crear una matriz de signos que corresponda a los 1 elevados a la posición del método de [[Determinante#Matrices 3x3 - Cofactores|cofactores]].
$$signo=\begin{bmatrix}+&-&+\\-&+&-\\+&-&+\end{bmatrix}$$

**Paso 3:** aplicar el método de [[Determinante#Matrices 3x3 - Cofactores|cofactores]] cubriendo la fila y columna correspondientes a cada posición evaluada, sacando el [[Determinante#Matrices 2x2|determinante de las matrices 2x2]] restantes y realizar las operaciones necesarias.
$$A=\begin{bmatrix}2&3&4\\4&3&2\\0&2&0\end{bmatrix}\quad C =\begin{bmatrix}+(0-4)&-(0-0)&+(8-0)\\-(0-8)&+(0-0)&-(4-0)\\+(6-12)&-(4-16)&+(6-12)\end{bmatrix}$$
$$C=\begin{bmatrix}-4&0&8\\8&0&-4\\-6&12&-6\end{bmatrix}$$ ^f8d9d6

**Paso 4:** Hallar la matriz adjunta transponiendo la matriz de cofactores.
$$A^{-1}=\frac{1}{det\left(A\right)} \space Adj(A)=\frac{1}{24}\begin{bmatrix}-4&&8&&-6\\0&&0&&12\\8&&-4&&-6\end{bmatrix}$$

**Paso 5:** Multiplicar la Matriz adjunta por el determinante encontrado en el [[#^0f725d|paso 1]].
$$A^{-1}=\begin{bmatrix}-4/24&8/24&-6/24\\0&0&12/24\\8/24&-4/24&-6/24\end{bmatrix}=\begin{bmatrix}-1/6&1/3&-1/4\\0&0&1/2\\1/3&-1/6&-1/4\end{bmatrix}$$ ^2f813b
