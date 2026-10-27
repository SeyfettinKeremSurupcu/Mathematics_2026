### Exercise 3. When Does the Inverse Not Exist?

For

$$
A=
\begin{pmatrix}
2 & 4 \\
1 & 2 \\
\end{pmatrix}
$$

explain in two ways why $A^{-1}$ does not exist: using the determinant and using dependence between the rows.

**Solution**

First method, using the determinant:

$$
\det A = (2)(2) - (4)(1) = 0
$$

A matrix is invertible if and only if its determinant is nonzero. Since the determinant is zero, $A^{-1}$ does not exist.

Second method, using row dependence:
The first row of the matrix is exactly twice the second row. Because one row is a scalar multiple of the other, the rows are linearly dependent, which means the matrix is singular and cannot be inverted.
