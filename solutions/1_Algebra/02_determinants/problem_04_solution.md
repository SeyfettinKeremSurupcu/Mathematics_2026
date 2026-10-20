### Exercise 4. Triangular Matrix
Without expanding the determinant, compute

$$
\det
\begin{pmatrix}
2 & 4 & 1 \\
0 & -3 & 5 \\
0 & 0 & 7 \\
\end{pmatrix}.
$$

State the rule for an arbitrary triangular matrix and explain it using this example.

### Solution 4

**Step 1: Compute the determinant**

$$
\begin{aligned}
\det
\begin{pmatrix}
2 & 4 & 1 \\
0 & -3 & 5 \\
0 & 0 & 7 \\
\end{pmatrix}
&= 2 \cdot (-3) \cdot 7 \\
&= -42
\end{aligned}
$$

**Step 2: State and explain the rule**

For an arbitrary upper (or lower) triangular matrix, the determinant is the product of the entries on its main diagonal. This occurs because expanding the determinant along the first column (which contains all zeros except the first entry) reduces the calculation to the product of the first entry and the determinant of the remaining smaller triangular matrix. Repeating this process isolates only the diagonal elements.
