### Exercise 2. Determinant of a 3×3 Matrix
For

$$
A=
\begin{pmatrix}
1 & 2 & -1 \\
0 & 3 & 4 \\
2 & 1 & 5 \\
\end{pmatrix}
$$

compute $\det A$ using Sarrus' rule. Then perform one simple check using a chosen property of the determinant.

### Solution 2

**Step 1: Compute the determinant using Sarrus' rule**

By copying the first two columns to the right of the matrix, the sum of the downward diagonal products is:

$$
(1)(3)(5) + (2)(4)(2) + (-1)(0)(1) = 15 + 16 + 0 = 31
$$

The sum of the upward diagonal products is:

$$
(2)(3)(-1) + (1)(4)(1) + (5)(0)(2) = -6 + 4 + 0 = -2
$$

Subtracting the upward sum from the downward sum yields the determinant:

$$
\begin{aligned}
\det A &= 31 - (-2) \\
&= 33
\end{aligned}
$$

**Step 2: Perform a simple check using cofactor expansion**

Expanding along the first column:

$$
\begin{aligned}
\det A &= 1 \cdot \det
\begin{pmatrix}
3 & 4 \\
1 & 5 \\
\end{pmatrix} \\
&\quad - 0 + 2 \cdot \det
\begin{pmatrix}
2 & -1 \\
3 & 4 \\
\end{pmatrix} \\
&= 1(15 - 4) + 2(8 - (-3)) \\
&= 11 + 2(11) \\
&= 33
\end{aligned}
$$

The result matches the calculation from Sarrus' rule.
