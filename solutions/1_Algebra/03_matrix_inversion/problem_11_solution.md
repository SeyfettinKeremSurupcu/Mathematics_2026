### Exercise 11. Parameter and Invertibility

For

$$
A(t)=
\begin{pmatrix}
1 & t \\
t & 1 \\
\end{pmatrix}
$$

find all $t$ for which the matrix is invertible, and then give a formula for $A(t)^{-1}$. Explain what happens to this formula at the excluded values.

**Solution**

Calculate the determinant:

$$
\det A(t) = 1(1) - (t)(t) = 1 - t^2
$$

The matrix is invertible when the determinant is nonzero:

$$
1 - t^2 \neq 0
$$

The matrix is invertible for all $t \neq 1$ and $t \neq -1$.

The formula for the inverse is:

$$
A(t)^{-1} = 
\frac{1}{1 - t^2}
\begin{pmatrix}
1 & -t \\
-t & 1 \\
\end{pmatrix}
$$

At the excluded values $t = 1$ and $t = -1$, the determinant becomes zero, making the fraction $\frac{1}{0}$ undefined. This reflects the algebraic fact that the matrix becomes singular and cannot be inverted.
