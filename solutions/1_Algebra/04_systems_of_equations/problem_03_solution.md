### Exercise 3. Inconsistent System

Solve or show that the system is inconsistent:

$$
\begin{cases}
x+2y=3, \\
2x+4y=7.
\end{cases}
$$

Show how the contradiction appears in the matrix after elimination and interpret it in terms of equations.

> **Why this exercise:** teaches how to recognize that a system has no solution without guessing.

**Solution:**

The augmented matrix is:

$$
\begin{pmatrix}
1 & 2 & \mid & 3 \\
2 & 4 & \mid & 7 \\
\end{pmatrix}
$$

Subtract $2 \times$ Row 1 from Row 2:

$$
\begin{pmatrix}
1 & 2 & \mid & 3 \\
0 & 0 & \mid & 1 \\
\end{pmatrix}
$$

The second row represents the equation $0x + 0y = 1$, which simplifies to $0=1$. This is a mathematical contradiction, meaning no values of $x$ and $y$ can satisfy both equations simultaneously. The system has no solution.

---
