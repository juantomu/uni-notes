# Propiedades de las Matrices Elementales
***
## Propiedad 1
***
$$\det(F_{ij})=-1$$
El determinante de la matriz elemental cada que se realice una permutación, siempre será $-1$.
![[prop1 elemental matrix.png]]

## Propiedad 2
***
$$\det(F_{i}(k))=k \neq 0$$

El determinante de la matriz elemental al multiplicar una fila por un número, será el mismo número.

## Propiedad 3
***
$$\det(F_{ij}(k))=1$$

El determinante al multiplicar por un número y sumarle otra fila siempre será $1$ por una propiedad de los determinantes ([[Propiedades de Determinantes#^913259|ver aquí]]).
![[Layer 5.png]] ^26c601

## Propiedad 4
***
Por las propiedades anteriores se concluye que TODA matriz elemental es invertible puesto que el $\det \neq 0$.

## Propiedad 5
***
$$A{^{-1}}=F_{p}F_{p-1}F_{p-2}\dots F_{1}$$
La inversa de una matriz es igual al producto de las matrices elementales en el orden contrario a como estas aparecieron.

## Propiedad 6
***
$$\det(A)=\frac{\det(T)}{\det(F_{1})\det(F_{2})\dots\det(F_{p})}$$

El determinante de una matriz es el resultado de dividir el determinante de la matriz triangular superior resultante de la [[Eliminación Gaussiana]] entre la multiplicación de todas las matrices elementales que hayan resultado en el proceso para obtener la matriz triangular superior.

Ejemplo:
	![[prop6.png]]


## Extra
***
Realizar una [[005 - Eliminación Gaussiana y Gauss-Jordan|operación elemental]] a una matriz es igual a pre-multiplicar la matriz elemental por la matriz original.![[enchan.png]]*(Falta el ejemplo de la [[#^26c601|propiedad 3]], pero también se cumple).*