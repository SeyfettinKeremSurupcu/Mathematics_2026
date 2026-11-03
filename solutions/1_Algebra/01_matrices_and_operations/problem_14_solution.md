### Exercise 14. Rotation Matrices

The matrix for a rotation through an angle $\theta$ is

$$
R(\theta)=
\begin{pmatrix}
\cos\theta & -\sin\theta \\
\sin\theta & \cos\theta \\
\end{pmatrix}.
$$

Compute $R(\alpha)R(\beta)$ and, using the angle-sum formulas for sine and cosine, show that

$$
R(\alpha)R(\beta)=R(\alpha+\beta).
$$

Explain the result geometrically.

> **Why this exercise:** shows the consistency between matrix algebra and the geometry of composing rotations.

**Solution:**

Multiply the two rotation matrices:

$$
R(\alpha)R(\beta) =
\begin{pmatrix}
\cos\alpha & -\sin\alpha \\
\sin\alpha & \cos\alpha \\
\end{pmatrix}
\begin{pmatrix}
\cos\beta & -\sin\beta \\
\sin\beta & \cos\beta \\
\end{pmatrix}
$$

Computing the dot products for the entries gives:

$$
R(\alpha)R(\beta) =
\begin{pmatrix}
\cos\alpha\cos\beta - \sin\alpha\sin\beta & -(\cos\alpha\sin\beta + \sin\alpha\cos\beta) \\
\sin\alpha\cos\beta + \cos\alpha\sin\beta & -\sin\alpha\sin\beta + \cos\alpha\cos\beta \\
\end{pmatrix}
$$

Apply the standard trigonometric angle-sum formulas, $\cos(\alpha+\beta) = \cos\alpha\cos\beta - \sin\alpha\sin\beta$ and $\sin(\alpha+\beta) = \sin\alpha\cos\beta + \cos\alpha\sin\beta$:

$$
R(\alpha)R(\beta) =
\begin{pmatrix}
\cos(\alpha+\beta) & -\sin(\alpha+\beta) \\
\sin(\alpha+\beta) & \cos(\alpha+\beta) \\
\end{pmatrix}
$$

This resulting matrix is identically $R(\alpha+\beta)$. 

Geometrically, applying $R(\beta)$ rotates a vector by the angle $\beta$, and subsequently applying $R(\alpha)$ rotates the new vector by the angle $\alpha$. The product $R(\alpha)R(\beta)$ proves that composing these two sequential rotations is algebraically equivalent to performing a single rotation by the total combined angle $\alpha+\beta$.

---
