### Exercise 5. Row Echelon Form and Number of Solutions

For the augmented matrix

$$
\begin{pmatrix}
1 & 2 & -1 & \mid & 3 \\
0 & 1 & 2 & \mid & 1 \\
0 & 0 & 0 & \mid & 0 \\
\end{pmatrix}
$$

determine the number of solutions and write them in parametric form. Explain how you know how many variables may be chosen freely.

> **Why this exercise:** teaches how to read information about solutions directly from row echelon form.

**Solution:**

The system from the augmented matrix is:

$$
\begin{cases}
x + 2y - z = 3, \\
y + 2z = 1, \\
0 = 0.
\end{cases}
$$

There are three variables ($x, y, z$) and two non-zero rows (two pivot elements). The number of free variables is $3 - 2 = 1$. The variable $z$ does not correspond to a pivot column, so it is the free variable. Let $z=t$.

From the second row:

$$
y = 1 - 2t
$$

Substitute into the first row:

$$
\begin{aligned}
x + 2(1 - 2t) - t &= 3 \\
x + 2 - 4t - t &= 3 \\
x &= 1 + 5t
\end{aligned}
$$

There are infinitely many solutions, given in parametric form as:

$$
\begin{pmatrix}
x \\
y \\
z \\
\end{pmatrix} = \begin{pmatrix}
1 + 5t \\
1 - 2t \\
t \\
\end{pmatrix}
$$
