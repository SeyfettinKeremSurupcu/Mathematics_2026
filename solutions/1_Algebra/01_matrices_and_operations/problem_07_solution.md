### Exercise 7. Identity Matrix, Zero Matrix, and Powers
For

$$
A=
\begin{pmatrix}
2 & 1 \cr
0 & 2 \cr
\end{pmatrix}
$$

compute

$$
AI,\qquad IA,\qquad A+0,\qquad A^2,\qquad A^3.
$$

Explain the roles of the matrices $I$ and $0$, and describe the pattern you observe in successive powers of $A$.

### Solution 7

$$
AI = \begin{pmatrix} 2 & 1 \cr 0 & 2 \end{pmatrix} \begin{pmatrix} 1 & 0 \cr 0 & 1 \end{pmatrix} = \begin{pmatrix} 2 & 1 \cr 0 & 2 \end{pmatrix} = A
$$

$$
IA = \begin{pmatrix} 1 & 0 \cr 0 & 1 \end{pmatrix} \begin{pmatrix} 2 & 1 \cr 0 & 2 \end{pmatrix} = \begin{pmatrix} 2 & 1 \cr 0 & 2 \end{pmatrix} = A
$$

$$
A+0 = \begin{pmatrix} 2 & 1 \cr 0 & 2 \end{pmatrix} + \begin{pmatrix} 0 & 0 \cr 0 & 0 \end{pmatrix} = \begin{pmatrix} 2 & 1 \cr 0 & 2 \end{pmatrix} = A
$$

$$
A^2 = \begin{pmatrix} 2 & 1 \cr 0 & 2 \end{pmatrix} \begin{pmatrix} 2 & 1 \cr 0 & 2 \end{pmatrix} = \begin{pmatrix} 4 & 4 \cr 0 & 4 \end{pmatrix}
$$

$$
A^3 = A^2 A = \begin{pmatrix} 4 & 4 \cr 0 & 4 \end{pmatrix} \begin{pmatrix} 2 & 1 \cr 0 & 2 \end{pmatrix} = \begin{pmatrix} 8 & 12 \cr 0 & 8 \end{pmatrix}
$$

The identity matrix $I$ serves as the multiplicative neutral element ($AI=IA=A$). The zero matrix $0$ serves as the additive neutral element ($A+0=A$). 
Pattern observed in successive powers of $A$:

$$
A^k = \begin{pmatrix} 2^k & k \cdot 2^{k-1} \cr 0 & 2^k \end{pmatrix}
$$
