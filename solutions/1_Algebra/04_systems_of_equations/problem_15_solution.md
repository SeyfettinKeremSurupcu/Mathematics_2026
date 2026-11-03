### Exercise 15. Classifying Three Systems

For each of the following systems, perform only as much elimination as necessary to recognize its type:

**System 1**

$$
\begin{cases}
x+y=2, \\
x-y=0,
\end{cases}
$$

**System 2**

$$
\begin{cases}
x+y=2, \\
2x+2y=4,
\end{cases}
$$

**System 3**

$$
\begin{cases}
x+y=2, \\
2x+2y=5.
\end{cases}
$$

For each, justify the classification: one solution, infinitely many solutions, or no solution.

> **Why this exercise:** brings together the three basic cases and requires recognizing them from the structure after elimination. 

**Solution:**

**System 1**

$$
\begin{pmatrix}
1 & 1 & \mid & 2 \\
1 & -1 & \mid & 0 \\
\end{pmatrix}
$$

Row 2 minus Row 1:

$$
\begin{pmatrix}
1 & 1 & \mid & 2 \\
0 & -2 & \mid & -2 \\
\end{pmatrix}
$$

The lower triangle is zeros, and we have a non-zero entry (pivot) for both $x$ and $y$. This means there is exactly one solution.

**System 2**

$$
\begin{pmatrix}
1 & 1 & \mid & 2 \\
2 & 2 & \mid & 4 \\
\end{pmatrix}
$$

Row 2 minus $2 \times$ Row 1:

$$
\begin{pmatrix}
1 & 1 & \mid & 2 \\
0 & 0 & \mid & 0 \\
\end{pmatrix}
$$

The entire second row is zero. We have one pivot and one free variable. This means there are infinitely many solutions.

**System 3**

$$
\begin{pmatrix}
1 & 1 & \mid & 2 \\
2 & 2 & \mid & 5 \\
\end{pmatrix}
$$

Row 2 minus $2 \times$ Row 1:

$$
\begin{pmatrix}
1 & 1 & \mid & 2 \\
0 & 0 & \mid & 1 \\
\end{pmatrix}
$$

The second row represents $0=1$, which is a contradiction. This means there is no solution.
