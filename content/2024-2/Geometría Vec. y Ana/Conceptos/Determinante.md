# Determinantes
***
TBD. Se representa con $\det(A)=|A|=DET(A)$ 


## Matrices 2x2
***
$$A=\begin{bmatrix}a&b\\c&d\end{bmatrix}, A^{-1}=\frac{1}{ad-bc}\begin{bmatrix}d&-b\\-c&a\end{bmatrix}$$
$$
\det(A) =ad-bc
$$
El determinante corresponde a la multiplicación de los números de la diagonal principal $-$ la multiplicación de los números de la diagonal secundaria.

Si el $\det(A) \neq 0$, $A$ tiene inversa.
## Matrices 3x3 - Regla de Sarrus
***
El método a continuación es válido exclusivamente para matrices 3x3.

**Paso 1:** Aumentamos a la matriz dos columnas al lado derecho, en esos espacios duplicaremos las dos primeras columnas.

**Paso 2:** $\det(A)=+(\text{diagonales principales})-(\text{diagonales secundarias})$
![[det sarrus.png]]
## Matrices 3x3 - Cofactores
***
$$
A=\begin{bmatrix}-2 & 3 & 1\\ 5 & 0 & 2\\ -1 & -3 & 4\end{bmatrix}$$

**Ejemplo Fila 3**

$$\det\left(A\right)=\left(-1\right)^{3+1}\left(-1\right)\begin{vmatrix}3 & 1\\ 0 & 2\end{vmatrix}+\left(-1\right)^{3+2}\left(-3\right)\begin{vmatrix}-2 & 1\\ 5 & 2\end{vmatrix}+\left(-1\right)^{3+3}\left(4\right)\begin{vmatrix}-2 & 3\\ 5 & 0\end{vmatrix}$$

$$\begin{align}
\det(A)&=(-1) (6-0)-(-3) (-4-5)+4 (0-15) \\
\det(A)&=-6-27-60=-93
\end{align}
$$

**Paso 1:** Elegir una Fila o Columna cualquiera.

**Paso 2:** La suma de los dígitos de la posición del primer número de la fila o columna corresponde al primer exponente. El $-1$ del primer paréntesis hace parte de la receta.

**Paso 3:** En el segundo paréntesis va el **primer número** de la fila o columna escogida, multiplicado por una matriz de orden 2x2 que contiene a los números que quedan al eliminar de la matriz original la fila y columna que contienen a ese **primer número**. ^c38a21

**Paso 4:** Se suma por regla otro $-1$ elevado a la suma de los dígitos de la posición donde está el segundo número de la fila o columna escogida. ^c27b8f

**Paso 5:** Luego, en ese segundo paréntesis va el **segundo número** de la fila o columna escogida y se multiplica por una matriz 2x2 como en el [[#^c38a21|Paso 3]]. ^f8c65d

**Paso 6:** Se repiten los pasos [[#^c27b8f|4]] y [[#^f8c65d|5]] hasta completar todos los números de la fila o columna escogida.

**Paso 7:** Hallar los determinantes de las matrices 2x2 que resultaron de los pasos anteriores por el [[#Matrices 2x2|método general]].

**Paso 8:** Realizar todas las operaciones restantes.

*Como sugerencia general, trata de escoger la fila que más ceros tenga para que al momento de hacer las operaciones se cancelen algunas cosas y el proceso sea más ágil.*

