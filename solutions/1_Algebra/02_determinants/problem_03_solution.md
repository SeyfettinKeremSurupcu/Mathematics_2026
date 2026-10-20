### Exercise 3. Swapping Two Rows
For

$$
A=
\begin{pmatrix}
1 & 2 & 0 \\
0 & 3 & 1 \\
2 & 1 & 1 \\
\end{pmatrix}
$$

compute $\det A$. Then form a matrix $B$ by swapping the first and second rows of $A$.

First predict $\det B$ using a determinant property, and then verify your prediction by calculation.

### Solution 3

**Step 1: Compute $\det A$**

Expanding along the first column:

$$
\begin{aligned}
\det A &= 1 \cdot \det
\begin{pmatrix}
3 & 1 \\
1 & 1 \\
\end{pmatrix}
- 0 + 2 \cdot \det
\begin{pmatrix}
2 & 0 \\
3 & 1 \\
\end{pmatrix} \\
&= 1(3 - 1) + 2(2 - 0) \\
&= 2 + 4 \\
&= 6
\end{aligned}
$$

**Step 2: Form matrix $B$ and predict its determinant**

Swapping the first and second rows of $A$ yields:

$$
B=
\begin{pmatrix}
0 & 3 & 1 \\
1 & 2 & 0 \\
2 & 1 & 1 \\
\end{pmatrix}
$$

A fundamental property states that swapping two rows multiplies the determinant by $-1$. Therefore, the prediction is:

$$
\det B = -6
$$

**Step 3: Verify by calculation**

Expanding $B$ along the first column:

$$
\begin{aligned}
\det B &= -1 \cdot \det
\begin{pmatrix}
3 & 1 \\
1 & 1 \\
\end{pmatrix}
+ 2 \cdot \det
\begin{pmatrix}
3 & 1 \\
2 & 0 \\
\end{pmatrix} \\
&= -1(3 - 1) + 2(0 - 2) \\
&= -2 - 4 \\
&= -6
\end{aligned}
$$

The calculation verifies the prediction.
