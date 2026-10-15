### Exercise 4. Matrix Multiplication and Noncommutativity
For

$$
A=
\begin{pmatrix}
1 & 2 \cr
0 & 1 \cr
\end{pmatrix},\qquad B=
\begin{pmatrix}
2 & 0 \cr
3 & 1 \cr
\end{pmatrix}
$$

compute $AB$ and $BA$. Is $AB=BA$? Use this example to explain what noncommutativity of matrix multiplication means.

### Solution 4

$$
AB = \begin{pmatrix} (1)(2) + (2)(3) & (1)(0) + (2)(1) \cr (0)(2) + (1)(3) & (0)(0) + (1)(1) \end{pmatrix} = \begin{pmatrix} 8 & 2 \cr 3 & 1 \end{pmatrix}
$$

$$
BA = \begin{pmatrix} (2)(1) + (0)(0) & (2)(2) + (0)(1) \cr (3)(1) + (1)(0) & (3)(2) + (1)(1) \end{pmatrix} = \begin{pmatrix} 2 & 4 \cr 3 & 7 \end{pmatrix}
$$

$AB \neq BA$. Noncommutativity means that reversing the order of the matrices in the product generally yields a completely different result. Unlike real numbers where $x \cdot y = y \cdot x$, in matrix algebra, order strictly matters.
