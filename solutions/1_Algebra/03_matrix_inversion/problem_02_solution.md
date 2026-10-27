### Exercise 2. Formula for a 2×2 Matrix

Find the inverse of

$$
A=
\begin{pmatrix}
3 & 2 \\
5 & 4 \\
\end{pmatrix}
$$

using the formula for a $2\times2$ matrix. At the end, check the result by computing one product with $A$.

**Solution**

Calculate the determinant of $A$:

$$
\det A = (3)(4) - (2)(5) = 12 - 10 = 2
$$

Apply the $2\times2$ inverse formula:

$$
\begin{aligned}
A^{-1} &= \frac{1}{\det A}
\begin{pmatrix}
4 & -2 \\
-5 & 3 \\
\end{pmatrix} \\
&=
\begin{pmatrix}
2 & -1 \\
-5/2 & 3/2 \\
\end{pmatrix}
\end{aligned}
$$

Check the result by computing $A A^{-1}$:

$$
\begin{aligned}
A A^{-1} &= 
\begin{pmatrix}
3 & 2 \\
5 & 4 \\
\end{pmatrix}
\begin{pmatrix}
2 & -1 \\
-5/2 & 3/2 \\
\end{pmatrix} \\
&=
\begin{pmatrix}
6 - 5 & -3 + 3 \\
10 - 10 & -5 + 6 \\
\end{pmatrix} \\
&=
\begin{pmatrix}
1 & 0 \\
0 & 1 \\
\end{pmatrix}
\end{aligned}
$$
