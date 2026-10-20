### Exercise 7. Using Properties Instead of Recomputing
Suppose that for a $3\times3$ matrix, $\det A=-4$. Compute

$$
\det(2A),\qquad \det(A^T),\qquad \det(A^2),\qquad \det(-A).
$$

Justify each answer using the appropriate property.

### Solution 7

**Step 1: Compute $\det(2A)$**

Multiplying an $n \times n$ matrix by a scalar $c$ multiplies the determinant by $c^n$. For a $3 \times 3$ matrix, $c = 2$ and $n = 3$.

$$
\begin{aligned}
\det(2A) &= 2^3 \det A \\
&= 8(-4) \\
&= -32
\end{aligned}
$$

**Step 2: Compute $\det(A^T)$**

The determinant of a matrix is equal to the determinant of its transpose.

$$
\begin{aligned}
\det(A^T) &= \det A \\
&= -4
\end{aligned}
$$

**Step 3: Compute $\det(A^2)$**

The determinant of a product is the product of the determinants.

$$
\begin{aligned}
\det(A^2) &= (\det A)^2 \\
&= (-4)^2 \\
&= 16
\end{aligned}
$$

**Step 4: Compute $\det(-A)$**

Multiplying a $3 \times 3$ matrix by $-1$ scales the determinant by $(-1)^3$.

$$
\begin{aligned}
\det(-A) &= (-1)^3 \det A \\
&= -1(-4) \\
&= 4
\end{aligned}
$$
