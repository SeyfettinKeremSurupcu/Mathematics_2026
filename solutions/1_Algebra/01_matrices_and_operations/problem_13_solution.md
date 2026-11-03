### Exercise 13. A Recurrence Written in Matrix Form

Let

$$
F=
\begin{pmatrix}
1 & 1 \\
1 & 0 \\
\end{pmatrix}.
$$

Compute $F^2$, $F^3$, $F^4$, and $F^5$. Compare the numbers obtained with the sequence

$$
0,1,1,2,3,5,8,\ldots
$$

and describe the relationship you observe. Then compute

$$
F
\begin{pmatrix}
a \\
b \\
\end{pmatrix}
$$

and explain how this multiplication performs one recurrence step: it creates the sum of two consecutive terms and keeps one of them for the next step.

> **Why this exercise:** shows the connection between matrix powers and a simple numerical recurrence.

**Solution:**

Compute the powers of $F$:

$$
F^2 =
\begin{pmatrix}
1 & 1 \\
1 & 0 \\
\end{pmatrix}
\begin{pmatrix}
1 & 1 \\
1 & 0 \\
\end{pmatrix} =
\begin{pmatrix}
2 & 1 \\
1 & 1 \\
\end{pmatrix}
$$

$$
F^3 = F^2 F =
\begin{pmatrix}
2 & 1 \\
1 & 1 \\
\end{pmatrix}
\begin{pmatrix}
1 & 1 \\
1 & 0 \\
\end{pmatrix} =
\begin{pmatrix}
3 & 2 \\
2 & 1 \\
\end{pmatrix}
$$

$$
F^4 = F^3 F =
\begin{pmatrix}
3 & 2 \\
2 & 1 \\
\end{pmatrix}
\begin{pmatrix}
1 & 1 \\
1 & 0 \\
\end{pmatrix} =
\begin{pmatrix}
5 & 3 \\
3 & 2 \\
\end{pmatrix}
$$

$$
F^5 = F^4 F =
\begin{pmatrix}
5 & 3 \\
3 & 2 \\
\end{pmatrix}
\begin{pmatrix}
1 & 1 \\
1 & 0 \\
\end{pmatrix} =
\begin{pmatrix}
8 & 5 \\
5 & 3 \\
\end{pmatrix}
$$

The numbers appearing in the matrices $(1, 1, 2, 3, 5, 8)$ are successive terms of the given Fibonacci sequence. Specifically, the entries shift positions, with the largest Fibonacci number appearing in the top-left corner.

Now, apply $F$ to a general column vector:

$$
F
\begin{pmatrix}
a \\
b \\
\end{pmatrix} =
\begin{pmatrix}
1 & 1 \\
1 & 0 \\
\end{pmatrix}
\begin{pmatrix}
a \\
b \\
\end{pmatrix} =
\begin{pmatrix}
a+b \\
a \\
\end{pmatrix}
$$

This multiplication performs one step of the Fibonacci recurrence. The new top entry is the sum of the previous two numbers ($a+b$), calculating the next term in the sequence. The new bottom entry simply stores the previous top entry ($a$), ensuring both values are available for the subsequent iteration.

---
