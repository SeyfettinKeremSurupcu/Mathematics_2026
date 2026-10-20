### Exercise 11. Shortening the Calculation with Row Operations
Compute

$$
\det
\begin{pmatrix}
1 & 2 & 3 \\
1 & 3 & 4 \\
1 & 4 & 6 \\
\end{pmatrix}
$$

by first performing row operations that create as many zeros as possible. State which operations do not change the determinant.

### Solution 11

**Step 1: Simplify using row operations**

Applying $R_2 \leftarrow R_2 - R_1$ and $R_3 \leftarrow R_3 - R_1$:

$$
\begin{pmatrix}
1 & 2 & 3 \\
0 & 1 & 1 \\
0 & 2 & 3 \\
\end{pmatrix}
$$

Applying $R_3 \leftarrow R_3 - 2R_2$:

$$
\begin{pmatrix}
1 & 2 & 3 \\
0 & 1 & 1 \\
0 & 0 & 1 \\
\end{pmatrix}
$$

**Step 2: Compute determinant and identify stable operations**

The resulting matrix is upper triangular. The determinant is the product of its diagonal entries:

$$
\begin{aligned}
\det A &= (1)(1)(1) \\
&= 1
\end{aligned}
$$

Adding or subtracting a scalar multiple of one row to another row never changes the determinant. Therefore, all operations performed above preserved the original determinant.
