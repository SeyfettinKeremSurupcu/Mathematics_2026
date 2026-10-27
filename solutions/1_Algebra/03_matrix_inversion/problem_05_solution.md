### Exercise 5. A 3×3 Matrix

Use Gauss–Jordan elimination to find the inverse of

$$
A=
\begin{pmatrix}
1 & 1 & 0 \\
0 & 1 & 1 \\
1 & 0 & 1 \\
\end{pmatrix}.
$$

Check the result by multiplication.

**Solution**

Set up the augmented matrix:

$$
\begin{pmatrix}
1 & 1 & 0 & \mid & 1 & 0 & 0 \\
0 & 1 & 1 & \mid & 0 & 1 & 0 \\
1 & 0 & 1 & \mid & 0 & 0 & 1 \\
\end{pmatrix}
$$

Subtract row 1 from row 3:

$$
\begin{pmatrix}
1 & 1 & 0 & \mid & 1 & 0 & 0 \\
0 & 1 & 1 & \mid & 0 & 1 & 0 \\
0 & -1 & 1 & \mid & -1 & 0 & 1 \\
\end{pmatrix}
$$

Add row 2 to row 3:

$$
\begin{pmatrix}
1 & 1 & 0 & \mid & 1 & 0 & 0 \\
0 & 1 & 1 & \mid & 0 & 1 & 0 \\
0 & 0 & 2 & \mid & -1 & 1 & 1 \\
\end{pmatrix}
$$

Divide row 3 by $2$:

$$
\begin{pmatrix}
1 & 1 & 0 & \mid & 1 & 0 & 0 \\
0 & 1 & 1 & \mid & 0 & 1 & 0 \\
0 & 0 & 1 & \mid & -1/2 & 1/2 & 1/2 \\
\end{pmatrix}
$$

Subtract row 3 from row 2:

$$
\begin{pmatrix}
1 & 1 & 0 & \mid & 1 & 0 & 0 \\
0 & 1 & 0 & \mid & 1/2 & 1/2 & -1/2 \\
0 & 0 & 1 & \mid & -1/2 & 1/2 & 1/2 \\
\end{pmatrix}
$$

Subtract row 2 from row 1:

$$
\begin{pmatrix}
1 & 0 & 0 & \mid & 1/2 & -1/2 & 1/2 \\
0 & 1 & 0 & \mid & 1/2 & 1/2 & -1/2 \\
0 & 0 & 1 & \mid & -1/2 & 1/2 & 1/2 \\
\end{pmatrix}
$$

The inverse matrix is:

$$
A^{-1}=
\frac{1}{2}
\begin{pmatrix}
1 & -1 & 1 \\
1 & 1 & -1 \\
-1 & 1 & 1 \\
\end{pmatrix}
$$

Check the result:

$$
\begin{aligned}
A A^{-1} &= 
\frac{1}{2}
\begin{pmatrix}
1 & 1 & 0 \\
0 & 1 & 1 \\
1 & 0 & 1 \\
\end{pmatrix}
\begin{pmatrix}
1 & -1 & 1 \\
1 & 1 & -1 \\
-1 & 1 & 1 \\
\end{pmatrix} \\
&=
\frac{1}{2}
\begin{pmatrix}
2 & 0 & 0 \\
0 & 2 & 0 \\
0 & 0 & 2 \\
\end{pmatrix} \\
&=
\begin{pmatrix}
1 & 0 & 0 \\
0 & 1 & 0 \\
0 & 0 & 1 \\
\end{pmatrix}
\end{aligned}
$$
