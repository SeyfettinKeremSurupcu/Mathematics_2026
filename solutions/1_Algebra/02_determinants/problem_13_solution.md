### Exercise 13. Determinant by Elimination
Compute the determinant

$$
A=
\begin{pmatrix}
1 & 2 & 3 \\
2 & 5 & 7 \\
1 & 0 & 2 \\
\end{pmatrix}
$$

using elimination. Record the effect of every row operation used on the value of the determinant.

### Solution 13

**Step 1: Eliminate entries below the first pivot**

Operation $R_2 \leftarrow R_2 - 2R_1$:

$$
\begin{pmatrix}
1 & 2 & 3 \\
0 & 1 & 1 \\
1 & 0 & 2 \\
\end{pmatrix}
$$

Operation $R_3 \leftarrow R_3 - R_1$:

$$
\begin{pmatrix}
1 & 2 & 3 \\
0 & 1 & 1 \\
0 & -2 & -1 \\
\end{pmatrix}
$$

These operations (adding a multiple of one row to another) do not change the determinant.

**Step 2: Eliminate the entry below the second pivot**

Operation $R_3 \leftarrow R_3 + 2R_2$:

$$
\begin{pmatrix}
1 & 2 & 3 \\
0 & 1 & 1 \\
0 & 0 & 1 \\
\end{pmatrix}
$$

This operation does not change the determinant.

**Step 3: Compute the determinant**

The resulting matrix is upper triangular, so the determinant is the product of its diagonal entries:

$$
\begin{aligned}
\det A &= (1)(1)(1) \\
&= 1
\end{aligned}
$$
