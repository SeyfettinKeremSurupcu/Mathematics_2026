### Exercise 10. Detecting Dependence
Without carrying out a full determinant calculation, explain why

$$
\det
\begin{pmatrix}
1 & 2 & 3 \\
2 & 4 & 6 \\
0 & 1 & 5 \\
\end{pmatrix}=0.
$$

Identify a specific dependence between the rows and connect it with noninvertibility of the matrix.

### Solution 10

By inspecting the rows of the matrix, the second row is exactly a scalar multiple of the first row:

$$
R_2 = 2R_1
$$

This indicates that the rows are linearly dependent. When the rows of a square matrix are linearly dependent, the matrix maps space to a lower dimension and its volume scaling factor is zero. Consequently, the matrix is not invertible, which dictates by definition that its determinant must equal zero.
