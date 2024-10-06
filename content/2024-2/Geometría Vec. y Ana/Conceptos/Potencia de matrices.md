# Potencia de matrices
***
La restricción más importante es cumplir el requerimiento de la [[Multiplicación entre matrices|multiplicación entre matrices]], se debe comprobar que son compatibles. Esta propiedad la cumplen exclusivamente las **matrices cuadradas**. Para resolver se hace lo mismo que en la [[Multiplicación entre matrices|multiplicación]].

$A^{2}=A_{3x3} \space A_{3x3}$ = Se puede hacer.
$B^{2}=B_{2x3} \space B_{2x3}$ = No son compatibles.

Ejemplo:
$$A^2=A_{3x3}A_{3x3}=\begin{bmatrix}-2&1&-3\\0&2&-1\\4&2&-5\end{bmatrix}\begin{bmatrix}-2&1&-3\\0&2&-1\\4&2&-5\end{bmatrix}=\begin{bmatrix}-8&-6&20\\-4&2&3\\-28&-2&11\end{bmatrix}$$

Si se tienen potencias de grado mayor a 2 se puede hacer lo siguiente:
$$A^3=AAA=A^2\times A=A\times A^2$$
## Potencia de matrices diagonales
***
Solo se deben elevar los elementos de la diagonal a lo que se requiera.

Ejemplo 1:
$$D=\begin{bmatrix}-2&0&0\\0&5&0\\0&0&4\end{bmatrix},D^2=\begin{bmatrix}-2&0&0\\0&5&0\\0&0&4\end{bmatrix}\begin{bmatrix}-2&0&0\\0&5&0\\0&0&4\end{bmatrix}=\begin{bmatrix}4&0&0\\0&25&0\\0&0&16\end{bmatrix}$$

Ejemplo 2:
$$D^8=\begin{bmatrix}\left(-2\right)^8&0&0\\0&5^8&0\\0&0&4^8\end{bmatrix}= \text{elevas la diag a la 8}$$
