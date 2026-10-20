### Exercise 1. Determinant of a 2×2 Matrix
Compute

$$
\det
\begin{pmatrix}
3 & -2 \\
5 & 4 \\
\end{pmatrix},\qquad \det
\begin{pmatrix}
1 & 7 \\
2 & 14 \\
\end{pmatrix}.
$$

Which matrix is invertible? Justify your answer.

### Solution 1

The determinant of a $2 \times 2$ matrix is computed as:

$$
\det
\begin{pmatrix}
a & b \\
c & d \\
\end{pmatrix}
= ad - bc
$$

**Step 1: Compute the determinant of the first matrix**

$$
\begin{aligned}
\det
\begin{pmatrix}
3 & -2 \\
5 & 4 \\
\end{pmatrix}
&= (3)(4) - (-2)(5) \\
&= 12 - (-10) \\
&= 22
\end{aligned}
$$

**Step 2: Compute the determinant of the second matrix**

$$
\begin{aligned}
\det
\begin{pmatrix}
1 & 7 \\
2 & 14 \\
\end{pmatrix}
&= (1)(14) - (7)(2) \\
&= 14 - 14 \\
&= 0
\end{aligned}
$$

**Step 3: Determine invertibility**

A matrix is invertible if and only if its determinant is non-zero ($\det A \neq 0$). 

- The first matrix is invertible because its determinant is $22 \neq 0$. 
- The second matrix is not invertible because its determinant is $0$.
