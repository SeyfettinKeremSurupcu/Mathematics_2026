### Exercise 11. A Parameter in a System of Three Equations

Analyze the number of solutions depending on $t$:

$$
\begin{cases}
x+y+z=1, \\
x+ty+z=2, \\
x+y+tz=3.
\end{cases}
$$

Use elimination and separately analyze the parameter values for which a standard calculation step ceases to be valid.

> **Why this exercise:** develops parametric analysis while still relying only on elimination.

**Solution:**

The augmented matrix is:

$$
\begin{pmatrix}
1 & 1 & 1 & \mid & 1 \\
1 & t & 1 & \mid & 2 \\
1 & 1 & t & \mid & 3 \\
\end{pmatrix}
$$

Subtract Row 1 from Row 2 and Row 3:

$$
\begin{pmatrix}
1 & 1 & 1 & \mid & 1 \\
0 & t-1 & 0 & \mid & 1 \\
0 & 0 & t-1 & \mid & 2 \\
\end{pmatrix}
$$

If $t=1$, the matrix becomes:

$$
\begin{pmatrix}
1 & 1 & 1 & \mid & 1 \\
0 & 0 & 0 & \mid & 1 \\
0 & 0 & 0 & \mid & 2 \\
\end{pmatrix}
$$

This indicates $0=1$ and $0=2$, which are contradictions. The system has no solution.

If $t \neq 1$, we can divide by $(t-1)$ to find exactly one solution:

$$
\begin{aligned}
y &= \frac{1}{t-1} \\
z &= \frac{2}{t-1}
\end{aligned}
$$

Substituting back into Row 1:

$$
\begin{aligned}
x + \frac{1}{t-1} + \frac{2}{t-1} &= 1 \\
x &= 1 - \frac{3}{t-1} \\
x &= \frac{t-4}{t-1}
\end{aligned}
$$

---
