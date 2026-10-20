### Exercise 5. Row Operations
For

$$
A=
\begin{pmatrix}
1 & 2 & 3 \\
2 & 1 & 0 \\
-1 & 4 & 2 \\
\end{pmatrix}
$$

find $\det A$ by simplifying the matrix with row operations. At each step, indicate whether and how the determinant changes.

### Solution 5

**Step 1: Perform row operations to create zeros below the first pivot**

Operation $R_2 \leftarrow R_2 - 2R_1$:

$$
\begin{pmatrix}
1 & 2 & 3 \\
0 & -3 & -6 \\
-1 & 4 & 2 \\
\end{pmatrix}
$$

Operation $R_3 \leftarrow R_3 + R_1$:

$$
\begin{pmatrix}
1 & 2 & 3 \\
0 & -3 & -6 \\
0 & 6 & 5 \\
\end{pmatrix}
$$

Adding a multiple of one row to another does not change the determinant.

**Step 2: Perform a row operation to create a zero below the second pivot**

Operation $R_3 \leftarrow R_3 + 2R_2$:

$$
\begin{pmatrix}
1 & 2 & 3 \\
0 & -3 & -6 \\
0 & 0 & -7 \\
\end{pmatrix}
$$

This operation does not change the determinant.

**Step 3: Compute the determinant of the resulting triangular matrix**

$$
\begin{aligned}
\det A &= 1 \cdot (-3) \cdot (-7) \\
&= 21
\end{aligned}
$$
