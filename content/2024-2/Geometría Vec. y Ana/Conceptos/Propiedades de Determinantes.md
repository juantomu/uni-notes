# Propiedades de Determinantes
***
$$A=\begin{bmatrix}4&-2\\5&1\end{bmatrix}$$
> [!caution] Propiedad 1
> $\det(A) =\det (A{^T})$

Ejemplo:
$$A=\begin{bmatrix}4&-2\\5&1\end{bmatrix}, det\left(A\right)=\left(4\right)\left(1\right)-\left(5\right)\left(-2\right)=4-\left(-10\right)=14$$
$$A^T=\begin{bmatrix}4&5\\-2&1\end{bmatrix}, det\begin{pmatrix}A^T\end{pmatrix}=4-(-10)=14$$

> [!caution] Propiedad 2
> $\det(A{^{-1}}) = \frac{1}{\det(A)}$

Ejemplo:
$$A^{-1}=\frac{1}{14}\begin{bmatrix}1&2\\-5&4\end{bmatrix}=\begin{bmatrix}1/14&2/14\\-5/14&4/14\end{bmatrix}$$
$$\\det\left(A^{-1}\right)=\frac{1}{14}\times\frac{4}{14}-\frac{2}{14}\times\left(\frac{-5}{14}\right)=\frac{4}{14^{2}}+\frac{10}{14^{2}}=\frac{14}{14^{2}}=\frac{1}{14}$$

> [!caution] Propiedad 3
> $\det(kA) = k^n \times \det (A)$
> 
> $$\begin{align}\text{Si n es par }  &\det(-A)=(-1){{^{\text{par}}}}\det(A)=\det(A)\\\text{Si n es impar }&\det(-A)=(-1){{^{\text{impar}}}}\det(A)=-\det(A)\end{align}$$
> 
> $n$ = orden de la matriz

> [!caution] Propiedad 4
> $\det(AB) = \det(A)\det(B)$
 
> [!caution] Propiedad 5
> $\det(A{^n}) =[\det(A)]{^n}$

![[Ejemplo aplicación de propiedades.png]]
> [!caution] Propiedad 6
> $\det(-A) =(-1){^n}\det (A)$

> [!caution] Propiedad 7
> $det(Adj(A))=\left[det\left(A\right)\right]^{n-1}$

> [!caution] Propiedad 8
> $det(Adj(A)) \text{ es único}$

> [!caution] Propiedad 9
> $det(A{^n}) = [\det(A)]{^n}$

> [!caution] Propiedad 10
> El determinante de una matriz triangular superior, inferior, diagonal o escalar es la multiplicación de los elementos de la diagonal principal.

^913259

