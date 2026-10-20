### Exercise 15. Combining Determinant Properties
Let $A$ and $B$ be invertible $2\times2 matrices with

$$
\det A=-2,\qquad \det B=3.
$$

Without finding the entries of the matrices, compute

$$
\det\left(B^{-1}A^TB\right).
$$

State the determinant properties you use in order and explain why the factors involving $B$ eventually cancel.

### Solution 15

**Step 1: Apply properties to expand the determinant**

We use the multiplicative property of determinants, $\det(XYZ) = \det X \det Y \det Z$:

$$
\begin{aligned}
\det\left(B^{-1}A^TB\right) &= \det(B^{-1}) \cdot \det(A^T) \cdot \det(B)
\end{aligned}
$$

**Step 2: Apply specific matrix properties**

We know that $\det(B^{-1}) = \frac{1}{\det B}$ and $\det(A^T) = \det A$. Substituting these gives:

$$
\begin{aligned}
\det\left(B^{-1}A^TB\right) &= \left(\frac{1}{\det B}\right) \cdot \det A \cdot \det B \\
&= \left(\frac{1}{3}\right) \cdot (-2) \cdot (3)
\end{aligned}
$$

**Step 3: Explain cancellation and compute final value**

Since determinants are scalar numbers, their multiplication is commutative. The factors $\frac{1}{\det B}$ and $\det B$ multiply to $1$, effectively canceling each other out regardless of the actual entries of $B$.

$$
\begin{aligned}
\det\left(B^{-1}A^TB\right) &= (-2) \cdot \left(\frac{1}{3} \cdot 3\right) \\
&= -2
\end{aligned}
$$
