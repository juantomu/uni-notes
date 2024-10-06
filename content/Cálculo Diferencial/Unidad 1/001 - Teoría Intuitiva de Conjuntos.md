# Teoría Intuitiva de Conjuntos
***

> [!danger]  **Recursos**
> Notas del profesor: [[Notas - Clase 1 (Cálculo).pdf]]
> Material Bibliográfico: [[Logica y Conjuntos (Extra).pdf|Capítulo I. Lógica y Conjuntos.]]
> Diapositivas: [[Diapos. - Clase 1 (Cálculo).pdf]]
> Taller: [[Taller 1 - Calculo 1.pdf]]
## Conceptos
***
- [[Conjunto]]
- [[Objetos]]
- [[Unión de conjuntos]]
- [[Intersección de conjuntos]]
- [[Conjuntos disyuntos]]
## Simbología
***
> [!Help] Simbología
> $\in$ = pertenece
> $\notin$ = no pertenece
> | = tal que
> $\subseteq$ = contenido en
> $\supseteq$ = contiene a
> $\cup$ = unión
> $\cap$ = intersección
> $\setminus$ = diferencia de conjuntos
> $\times$ = producto conjunto
## Notación de conjuntos
***
### Por extensión 
Consiste en nombrar cada uno de los elementos (enumerar/listar).
	Ejemplo: $A=\{1, 2, 3, 4,5\}$ `los naturales menores a 6`
### Por comprensión
Consiste en indicar la  característica o propiedad común de todos los elementos del conjunto.
	Forma: $V=\{x \space|\space p(x)\}$
	Ejemplo: $V=\{x|x\in \mathbb{N},x<6\}$
	`Eso se lee: todos los números naturales menores que 6.`
## Subconjuntos
***
`Pag. 8`
Sean A y B conjuntos. Se dice que A es un subconjunto de B, si todo elemento en A está en B.
### Notación
Se escribe matemáticamente así:
	$A\subseteq B$ : A está contenido en B.
	$A\supseteq B$ : B contiene a A.

Se escribe simbólicamente así:
	$A\subseteq B \Leftrightarrow (\forall x)[x \in A \Rightarrow x \in B]$ 
	`Se lee: "para todo x perteneciente a A, entonces x pertenece a B".`
## Operaciones con Conjuntos
***
### Diferencia de Conjuntos
***
Sean A y B conjuntos. La diferencia de A y B, denotada por $A \backslash B$ ó $A-B$, es el conjunto de todos los elementos que están en A pero que NO están en B.

En símbolos:
$A \backslash B =\{x|x \in A \land x \notin B \}$

En otras palabras:
$x \in A \backslash B \iff x \in A \land x \notin B$

Ejemplos en página 19 y 20: [[Diapos. - Clase 1 (Cálculo).pdf]]
### Producto Cartesiano
***
Sean A y B conjutos no vacíos. El producto cartesiano de A y B, denotado por $A \times B$, es el conjunto de todos los pares ordenados (a,b) con $a \in A$ y $b \in B$.

En símbolos:
$A \times B = \{(a,b)|a \in A \land b \in B \}$

En otras palabras:
$(a,b) \in A \times B \iff a \in A \land b \in B \}$

Ejemplos en página 21 y 22: [[Diapos. - Clase 1 (Cálculo).pdf]]