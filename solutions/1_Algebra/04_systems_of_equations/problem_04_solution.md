### Exercise 4. Infinitely Many Solutions

Solve

$$
\begin{cases}
x+y+z=2, \\
2x+2y+2z=4, \\
x-y+z=0.
\end{cases}
$$

Give the solution in parametric form, identify a free variable, and for one chosen parameter value check that the resulting point really satisfies the system.

> **Why this exercise:** shows the case of multiple solutions and teaches a simple parametric description.

**Solution:**

The augmented matrix is:

$$
\begin{pmatrix}
1 & 1 & 1 & \mid & 2 \\
2 & 2 & 2 & \mid & 4 \\
1 & -1 & 1 & \mid & 0 \\
\end{pmatrix}
$$

Subtract $2 \times$ Row 1 from Row 2, and Row 1 from Row 3:

$$
\begin{pmatrix}
1 & 1 & 1 & \mid & 2 \\
0 & 0 & 0 & \mid & 0 \\
0 & -2 & 0 & \mid & -2 \\
\end{pmatrix}
$$

The third row simplifies to $-2y = -2$, which gives $y=1$.
The first row equation is $x + y + z = 2$. Substituting $y=1$ yields $x + 1 + z = 2$, or $x + z = 1$.

Since there is no condition restricting $z$, $z$ is a free variable. Let $z = t$. The parametric solution is:

$$
\begin{pmatrix}
x \\
y \\
z \\
\end{pmatrix}
=
\begin{pmatrix}
1 - t \\
1 \\
t \\
\end{pmatrix}
$$

Checking for a chosen parameter value, e.g., $t=0$: the point is $(1,1,0)$. Substituting into the original system:

- $1+1+0=2$
- $2(1)+2(1)+2(0)=4$
- $1-1+0=0$

The point satisfies the system.

---
