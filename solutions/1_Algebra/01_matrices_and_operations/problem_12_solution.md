### Exercise 12. Formula for a Matrix Power

Let

$$
A=
\begin{pmatrix}
1 & 1 \\
0 & 1 \\
\end{pmatrix}.
$$

Compute $A^2$, $A^3$, and $A^4$, and use them to formulate a conjecture for $A^n$. Then do not stop after checking one more case: assume the formula is true for $n$, multiply by $A$, and explain why you obtain exactly the formula for $n+1$.

> **Why this exercise:** teaches how to recognize a pattern and formulate a generalization from several computations.

**Solution:**

Compute the successive powers of $A$:

$$
A^2 =
\begin{pmatrix}
1 & 1 \\
0 & 1 \\
\end{pmatrix}
\begin{pmatrix}
1 & 1 \\
0 & 1 \\
\end{pmatrix} =
\begin{pmatrix}
1 & 2 \\
0 & 1 \\
\end{pmatrix}
$$

$$
A^3 = A^2 A =
\begin{pmatrix}
1 & 2 \\
0 & 1 \\
\end{pmatrix}
\begin{pmatrix}
1 & 1 \\
0 & 1 \\
\end{pmatrix} =
\begin{pmatrix}
1 & 3 \\
0 & 1 \\
\end{pmatrix}
$$

$$
A^4 = A^3 A =
\begin{pmatrix}
1 & 3 \\
0 & 1 \\
\end{pmatrix}
\begin{pmatrix}
1 & 1 \\
0 & 1 \\
\end{pmatrix} =
\begin{pmatrix}
1 & 4 \\
0 & 1 \\
\end{pmatrix}
$$

The top-right entry matches the exponent. The conjecture for $A^n$ is:

$$
A^n=
\begin{pmatrix}
1 & n \\
0 & 1 \\
\end{pmatrix}
$$

To prove this, assume the formula holds for $n$. Multiply $A^n$ by $A$ to find $A^{n+1}$:

$$
A^{n+1} = A^n A =
\begin{pmatrix}
1 & n \\
0 & 1 \\
\end{pmatrix}
\begin{pmatrix}
1 & 1 \\
0 & 1 \\
\end{pmatrix} =
\begin{pmatrix}
1(1)+n(0) & 1(1)+n(1) \\
0(1)+1(0) & 0(1)+1(1) \\
\end{pmatrix}
$$

Simplifying the entries gives:

$$
A^{n+1}=
\begin{pmatrix}
1 & n+1 \\
0 & 1 \\
\end{pmatrix}
$$

This matches the proposed formula exactly for $n+1$, demonstrating that adding one more factor of $A$ simply adds $1$ to the top-right entry.

---
