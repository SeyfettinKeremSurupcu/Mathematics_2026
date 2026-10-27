### Exercise 6. Solving a System Using the Inverse

Solve

$$
Ax=b,
$$

where

$$
A=
\begin{pmatrix}
2 & 1 \\
1 & 3 \\
\end{pmatrix},
\qquad 
b=
\begin{pmatrix}
5 \\
7 \\
\end{pmatrix},
$$

using $x=A^{-1}b$. Then substitute the resulting vector back into the equation and check the result.

**Solution**

Find the determinant of $A$:

$$
\det A = 2(3) - 1(1) = 5
$$

Find $A^{-1}$:

$$
A^{-1}=
\frac{1}{5}
\begin{pmatrix}
3 & -1 \\
-1 & 2 \\
\end{pmatrix}
$$

Compute $x$:

$$
\begin{aligned}
x &= A^{-1}b \\
&= 
\frac{1}{5}
\begin{pmatrix}
3 & -1 \\
-1 & 2 \\
\end{pmatrix}
\begin{pmatrix}
5 \\
7 \\
\end{pmatrix} \\
&=
\frac{1}{5}
\begin{pmatrix}
15 - 7 \\
-5 + 14 \\
\end{pmatrix} \\
&=
\begin{pmatrix}
8/5 \\
9/5 \\
\end{pmatrix}
\end{aligned}
$$

Substitute $x$ back to check:

$$
\begin{aligned}
Ax &= 
\begin{pmatrix}
2 & 1 \\
1 & 3 \\
\end{pmatrix}
\begin{pmatrix}
8/5 \\
9/5 \\
\end{pmatrix} \\
&=
\begin{pmatrix}
16/5 + 9/5 \\
8/5 + 27/5 \\
\end{pmatrix} \\
&=
\begin{pmatrix}
25/5 \\
35/5 \\
\end{pmatrix} \\
&=
\begin{pmatrix}
5 \\
7 \\
\end{pmatrix}
\end{aligned}
$$

The result matches $b$.
