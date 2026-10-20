### Exercise 9. Area and the Determinant
The vectors

$$
u=
\begin{pmatrix}
3 \\
1 \\
\end{pmatrix},\qquad v=
\begin{pmatrix}
1 \\
4 \\
\end{pmatrix}
$$

span a parallelogram. Compute its area using a determinant. Then reverse the order of the vectors and explain what changes in the determinant and what does not change in the area.

### Solution 9

**Step 1: Compute the area using the determinant**

The area of the spanned parallelogram is the absolute value of the determinant of the matrix formed by placing the vectors as columns.

$$
M =
\begin{pmatrix}
3 & 1 \\
1 & 4 \\
\end{pmatrix}
$$

$$
\begin{aligned}
\det M &= (3)(4) - (1)(1) \\
&= 12 - 1 \\
&= 11
\end{aligned}
$$

The area is $11$.

**Step 2: Reverse the order and explain**

Reversing the order of the vectors yields the matrix:

$$
N =
\begin{pmatrix}
1 & 3 \\
4 & 1 \\
\end{pmatrix}
$$

$$
\begin{aligned}
\det N &= (1)(1) - (3)(4) \\
&= 1 - 12 \\
&= -11
\end{aligned}
$$

When the order of the vectors is reversed (a column swap), the sign of the determinant changes from positive to negative. However, the geometric area is always positive (the absolute value of the determinant). Therefore, the area remains $11$ because $|11| = |-11|$.
