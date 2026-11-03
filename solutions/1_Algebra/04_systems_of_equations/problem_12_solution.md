### Exercise 12. Homogeneous System

Solve

$$
\begin{cases}
x+2y-z=0, \\
2x+4y-2z=0, \\
x-y+2z=0.
\end{cases}
$$

Give all solutions in parametric form and explain why $(0,0,0)$ always satisfies a homogeneous system.

> **Why this exercise:** shows the special case of a system with a zero right-hand side without introducing additional theory.

**Solution:**

The augmented matrix is:

$$
\begin{pmatrix}
1 & 2 & -1 & \mid & 0 \\
2 & 4 & -2 & \mid & 0 \\
1 & -1 & 2 & \mid & 0 \\
\end{pmatrix}
$$

Subtract $2 \times$ Row 1 from Row 2, and Row 1 from Row 3:

$$
\begin{pmatrix}
1 & 2 & -1 & \mid & 0 \\
0 & 0 & 0 & \mid & 0 \\
0 & -3 & 3 & \mid & 0 \\
\end{pmatrix}
$$

The third row gives $-3y + 3z = 0$, so $y = z$. Let $z = t$, then $y = t$.
Substitute into the first row:

$$
\begin{aligned}
x + 2t - t &= 0 \\
x + t &= 0 \\
x &= -t
\end{aligned}
$$

The parametric solutions are $(-t, t, t)$.

The point $(0,0,0)$ always satisfies a homogeneous system because multiplying the zero vector by any matrix always yields the zero vector. Every term contains a variable, so if all variables are zero, their sum is inherently zero.

---
