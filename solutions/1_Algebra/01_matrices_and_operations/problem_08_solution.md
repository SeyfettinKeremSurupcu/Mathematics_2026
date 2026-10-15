### Exercise 8. Row Operations and Their Reversibility
For

$$
A=
\begin{pmatrix}
1 & 2 & -1 \\\\
2 & 4 & 1 \\\\
-1 & 1 & 3 \\\\
\end{pmatrix}
$$

perform, in order:

1. $R_2\leftarrow R_2-2R_1$,
2. $R_3\leftarrow R_3+R_1$,
3. interchange $R_2$ and $R_3$.

Write the matrix after each step. Then, for each of the three operations, state an operation that reverses it.

### Solution 8
Initial matrix: 

$$
A = \begin{pmatrix} 1 & 2 & -1 \\\\ 2 & 4 & 1 \\\\ -1 & 1 & 3 \end{pmatrix}
$$

1. $R_2\leftarrow R_2-2R_1$:

$$
\begin{pmatrix} 1 & 2 & -1 \\\\ 0 & 0 & 3 \\\\ -1 & 1 & 3 \end{pmatrix}
$$

Reversal operation: $R_2 \leftarrow R_2 + 2R_1$

2. $R_3\leftarrow R_3+R_1$:

$$
\begin{pmatrix} 1 & 2 & -1 \\\\ 0 & 0 & 3 \\\\ 0 & 3 & 2 \end{pmatrix}
$$

Reversal operation: $R_3 \leftarrow R_3 - R_1$

3. Interchange $R_2$ and $R_3$:

$$
\begin{pmatrix} 1 & 2 & -1 \\\\ 0 & 3 & 2 \\\\ 0 & 0 & 3 \end{pmatrix}
$$

Reversal operation: Interchange $R_2$ and $R_3$ again.
