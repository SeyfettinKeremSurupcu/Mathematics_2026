### Exercise 15. Associativity of Multiplication and Different Calculation Paths

Given

$$
A=
\begin{pmatrix}
1 & 2 & 0 \\
0 & 1 & 1 \\
\end{pmatrix},\quad B=
\begin{pmatrix}
1 & 0 \\
2 & 1 \\
-1 & 3 \\
\end{pmatrix},\quad C=
\begin{pmatrix}
2 & 1 \\
0 & -1 \\
\end{pmatrix}.
$$

Compute $(AB)C$ and $A(BC)$. Compare the results and the number of intermediate operations. Explain what associativity of matrix multiplication means in this example.

> **Why this exercise:** reinforces associativity by comparing two mathematically equivalent calculation paths.

**Solution:**

**Path 1: Compute $(AB)C$**

First, compute $AB$:

$$
AB =
\begin{pmatrix}
1 & 2 & 0 \\
0 & 1 & 1 \\
\end{pmatrix}
\begin{pmatrix}
1 & 0 \\
2 & 1 \\
-1 & 3 \\
\end{pmatrix} =
\begin{pmatrix}
1(1)+2(2)+0(-1) & 1(0)+2(1)+0(3) \\
0(1)+1(2)+1(-1) & 0(0)+1(1)+1(3) \\
\end{pmatrix} =
\begin{pmatrix}
5 & 2 \\
1 & 4 \\
\end{pmatrix}
$$

Next, multiply the result by $C$:

$$
(AB)C =
\begin{pmatrix}
5 & 2 \\
1 & 4 \\
\end{pmatrix}
\begin{pmatrix}
2 & 1 \\
0 & -1 \\
\end{pmatrix} =
\begin{pmatrix}
5(2)+2(0) & 5(1)+2(-1) \\
1(2)+4(0) & 1(1)+4(-1) \\
\end{pmatrix} =
\begin{pmatrix}
10 & 3 \\
2 & -3 \\
\end{pmatrix}
$$

**Path 2: Compute $A(BC)$**

First, compute $BC$:

$$
BC =
\begin{pmatrix}
1 & 0 \\
2 & 1 \\
-1 & 3 \\
\end{pmatrix}
\begin{pmatrix}
2 & 1 \\
0 & -1 \\
\end{pmatrix} =
\begin{pmatrix}
1(2)+0(0) & 1(1)+0(-1) \\
2(2)+1(0) & 2(1)+1(-1) \\
-1(2)+3(0) & -1(1)+3(-1) \\
\end{pmatrix} =
\begin{pmatrix}
2 & 1 \\
4 & 1 \\
-2 & -4 \\
\end{pmatrix}
$$

Next, multiply $A$ by this result:

$$
A(BC) =
\begin{pmatrix}
1 & 2 & 0 \\
0 & 1 & 1 \\
\end{pmatrix}
\begin{pmatrix}
2 & 1 \\
4 & 1 \\
-2 & -4 \\
\end{pmatrix} =
\begin{pmatrix}
1(2)+2(4)+0(-2) & 1(1)+2(1)+0(-4) \\
0(2)+1(4)+1(-2) & 0(1)+1(1)+1(-4) \\
\end{pmatrix} =
\begin{pmatrix}
10 & 3 \\
2 & -3 \\
\end{pmatrix}
$$

The results are identical. Associativity in this example means that the way the matrices are grouped for calculation—whether multiplying $A$ and $B$ first, or $B$ and $C$ first—does not change the final answer. However, the calculation paths differ fundamentally: $(AB)C$ required multiplying a $2\times3$ by a $3\times2$, then a $2\times2$ by a $2\times2$, while $A(BC)$ required multiplying a $3\times2$ by a $2\times2$, then a $2\times3$ by a $3\times2$.
