### Exercise 3. When Can Matrices Be Multiplied?
The matrix sizes are

$$
A_{2\times3},\qquad B_{3\times4},\qquad C_{4\times2},\qquad D_{2\times2}.
$$

For the products

$$
AB,\ BA,\ BC,\ CB,\ AC,\ CA,\ AD,\ DA
$$

determine whether they are defined. If so, state the size of the result. Justify each decision using the dimension compatibility condition.

### Solution 3
The product $XY$ is defined if and only if the number of columns in $X$ equals the number of rows in $Y$. The resulting matrix will have the number of rows of $X$ and the number of columns of $Y$.
- $AB$: $(2\times3) \times (3\times4)$. $3=3$, defined. Result size: $2\times4$.
- $BA$: $(3\times4) \times (2\times3)$. $4\neq 2$, undefined.
- $BC$: $(3\times4) \times (4\times2)$. $4=4$, defined. Result size: $3\times2$.
- $CB$: $(4\times2) \times (3\times4)$. $2\neq 3$, undefined.
- $AC$: $(2\times3) \times (4\times2)$. $3\neq 4$, undefined.
- $CA$: $(4\times2) \times (2\times3)$. $2=2$, defined. Result size: $4\times3$.
- $AD$: $(2\times3) \times (2\times2)$. $3\neq 2$, undefined.
- $DA$: $(2\times2) \times (2\times3)$. $2=2$, defined. Result size: $2\times3$.
