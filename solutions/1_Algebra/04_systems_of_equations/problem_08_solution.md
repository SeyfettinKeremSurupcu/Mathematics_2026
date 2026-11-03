### Exercise 8. Two Systems with the Same Coefficient Matrix

Solve by elimination the two systems

$$
\begin{cases}
2x+y=5, \\
x-y=1,
\end{cases}
$$

$$
\begin{cases}
2x+y=1, \\
x-y=4.
\end{cases}
$$

Compare the successive elimination steps. Which part of the calculation is the same in both cases, and why?

> **Why this exercise:** shows the role of the coefficient matrix independently of the right-hand side.

**Solution:**

**System 1:**

$$
\begin{pmatrix}
2 & 1 & \mid & 5 \\
1 & -1 & \mid & 1 \\
\end{pmatrix}
$$

Row 1 minus $2 \times$ Row 2:

$$
\begin{pmatrix}
0 & 3 & \mid & 3 \\
1 & -1 & \mid & 1 \\
\end{pmatrix}
$$

This gives $3y=3 \implies y=1$, and $x-1=1 \implies x=2$.

**System 2:**

$$
\begin{pmatrix}
2 & 1 & \mid & 1 \\
1 & -1 & \mid & 4 \\
\end{pmatrix}
$$

Row 1 minus $2 \times$ Row 2:

$$
\begin{pmatrix}
0 & 3 & \mid & -7 \\
1 & -1 & \mid & 4 \\
\end{pmatrix}
$$

This gives $3y=-7 \implies y=-7/3$, and $x - (-7/3) = 4 \implies x=5/3$.

The row operations on the left side (the coefficient matrix) are identical. The coefficient matrix dictates the elimination steps regardless of the values on the right-hand side.

---
