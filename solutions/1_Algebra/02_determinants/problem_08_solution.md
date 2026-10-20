### Exercise 8. Determinant of a Product
Let $A,B$ be square matrices such that $\det A=3$ and $\det B=-5$. Compute $\det(AB)$, $\det(BA)$ and, if it exists, $\det(A^{-1}B)$. Explain why the first two results are equal even though usually $AB\neq BA$.

### Solution 8

**Step 1: Compute the determinants**

Using the multiplicative property of determinants, $\det(XY) = \det X \det Y$:

$$
\begin{aligned}
\det(AB) &= \det A \cdot \det B \\
&= (3)(-5) \\
&= -15
\end{aligned}
$$

$$
\begin{aligned}
\det(BA) &= \det B \cdot \det A \\
&= (-5)(3) \\
&= -15
\end{aligned}
$$

Since $\det A = 3 \neq 0$, $A$ is invertible, and $\det(A^{-1}) = \frac{1}{\det A}$.

$$
\begin{aligned}
\det(A^{-1}B) &= \det(A^{-1}) \cdot \det B \\
&= \left(\frac{1}{3}\right)(-5) \\
&= -\frac{5}{3}
\end{aligned}
$$

**Step 2: Explain equality**

Although matrix multiplication is not commutative ($AB \neq BA$), determinants yield scalar real numbers. Scalar multiplication is commutative, so $\det A \cdot \det B = \det B \cdot \det A$, resulting in $\det(AB) = \det(BA)$.
