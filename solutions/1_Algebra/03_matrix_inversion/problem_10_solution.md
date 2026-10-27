### Exercise 10. Inverse of a Diagonal Matrix

Given

$$
D=
\begin{pmatrix}
2 & 0 & 0 \\
0 & -3 & 0 \\
0 & 0 & 5 \\
\end{pmatrix},
\qquad 
E=
\begin{pmatrix}
2 & 0 & 0 \\
0 & 0 & 0 \\
0 & 0 & 5 \\
\end{pmatrix}.
$$

Without using Gauss–Jordan elimination, decide which matrix is invertible. For the invertible matrix, give the inverse and check the result by multiplication.

**Solution**

A diagonal matrix is invertible if and only if all its diagonal entries are nonzero. Matrix $E$ has a zero on the main diagonal, so it is not invertible. Matrix $D$ has only nonzero elements on its main diagonal, so it is invertible.

The inverse is obtained by taking the reciprocal of each diagonal entry:

$$
D^{-1}=
\begin{pmatrix}
1/2 & 0 & 0 \\
0 & -1/3 & 0 \\
0 & 0 & 1/5 \\
\end{pmatrix}
$$

Check the result:

$$
\begin{aligned}
D D^{-1} &=
\begin{pmatrix}
2 & 0 & 0 \\
0 & -3 & 0 \\
0 & 0 & 5 \\
\end{pmatrix}
\begin{pmatrix}
1/2 & 0 & 0 \\
0 & -1/3 & 0 \\
0 & 0 & 1/5 \\
\end{pmatrix} \\
&=
\begin{pmatrix}
1 & 0 & 0 \\
0 & 1 & 0 \\
0 & 0 & 1 \\
\end{pmatrix}
\end{aligned}
$$
