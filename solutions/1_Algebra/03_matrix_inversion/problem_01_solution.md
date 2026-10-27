### Exercise 1. Definition of the Inverse

For

$$
A=
\begin{pmatrix}
2 & 1 \\
1 & 1 \\
\end{pmatrix},
\qquad 
B=
\begin{pmatrix}
1 & -1 \\
-1 & 2 \\
\end{pmatrix}
$$

check, without using a formula, whether $B=A^{-1}$. Compute $AB$ and $BA$ and relate the result to the definition of the inverse.

**Solution**

Compute the product $AB$:

$$
\begin{aligned}
AB &= 
\begin{pmatrix}
2 & 1 \\
1 & 1 \\
\end{pmatrix}
\begin{pmatrix}
1 & -1 \\
-1 & 2 \\
\end{pmatrix} \\
&=
\begin{pmatrix}
2(1) + 1(-1) & 2(-1) + 1(2) \\
1(1) + 1(-1) & 1(-1) + 1(2) \\
\end{pmatrix} \\
&=
\begin{pmatrix}
1 & 0 \\
0 & 1 \\
\end{pmatrix}
\end{aligned}
$$

Compute the product $BA$:

$$
\begin{aligned}
BA &= 
\begin{pmatrix}
1 & -1 \\
-1 & 2 \\
\end{pmatrix}
\begin{pmatrix}
2 & 1 \\
1 & 1 \\
\end{pmatrix} \\
&=
\begin{pmatrix}
1(2) + (-1)(1) & 1(1) + (-1)(1) \\
-1(2) + 2(1) & -1(1) + 2(1) \\
\end{pmatrix} \\
&=
\begin{pmatrix}
1 & 0 \\
0 & 1 \\
\end{pmatrix}
\end{aligned}
$$

Both products result in the identity matrix $I$. By definition, a matrix $B$ is the inverse of $A$ if and only if $AB = I$ and $BA = I$. Therefore, $B = A^{-1}$.
