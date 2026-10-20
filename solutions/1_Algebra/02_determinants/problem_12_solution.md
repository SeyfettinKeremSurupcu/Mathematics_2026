### Exercise 12. A Parameter Revealed by a Row Operation
For

$$
A(t)=
\begin{pmatrix}
1 & 2 & 3 \\
2 & 4 & t \\
0 & 1 & 1 \\
\end{pmatrix}
$$

find the values of $t$ for which the matrix is not invertible.

Before computing the determinant, perform the operation

$$
R_2\leftarrow R_2-2R_1
$$

and use the resulting structure. At the end, explain what special thing happens to the rows for the value of the parameter you found.

### Solution 12

**Step 1: Perform the specified row operation**

Applying $R_2 \leftarrow R_2 - 2R_1$:

$$
\begin{pmatrix}
1 & 2 & 3 \\
0 & 0 & t - 6 \\
0 & 1 & 1 \\
\end{pmatrix}
$$

**Step 2: Find values of $t$ for non-invertibility**

The matrix is not invertible when the determinant is zero. Expanding along the first column of the simplified matrix:

$$
\begin{aligned}
\det A(t) &= 1 \cdot \det
\begin{pmatrix}
0 & t - 6 \\
1 & 1 \\
\end{pmatrix} \\
&= (0)(1) - (t - 6)(1) \\
&= 6 - t
\end{aligned}
$$

Setting the determinant to zero yields:

$$
\begin{aligned}
6 - t &= 0 \\
t &= 6
\end{aligned}
$$

**Step 3: Explain the row behavior at $t = 6$**

If $t = 6$, substituting it into the row-reduced matrix results in the entire second row becoming zero:

$$
\begin{pmatrix}
1 & 2 & 3 \\
0 & 0 & 0 \\
0 & 1 & 1 \\
\end{pmatrix}
$$

In the original matrix, setting $t = 6$ makes the second row $(2, 4, 6)$, which is exactly twice the first row $(1, 2, 3)$. This linear dependence guarantees a zero row upon reduction, proving non-invertibility.
