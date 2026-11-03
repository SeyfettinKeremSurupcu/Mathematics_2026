### Exercise 10. A Polynomial Through Three Points

Find a polynomial $p(x)=ax^2+bx+c$ whose graph passes through $(0,1)$, $(1,3)$, and $(2,9)$. Reduce the problem to a system of equations and check the result by substituting all three points.

> **Why this exercise:** shows that finding unknown coefficients can be reduced to solving a linear system.

**Solution:**

The general form is $p(x)=ax^2+bx+c$.
Substitute the points $(x, p(x))$:

$$
\begin{cases}
a(0)^2 + b(0) + c = 1, \\
a(1)^2 + b(1) + c = 3, \\
a(2)^2 + b(2) + c = 9.
\end{cases}
$$

This simplifies to:

$$
\begin{cases}
c = 1, \\
a + b + c = 3, \\
4a + 2b + c = 9.
\end{cases}
$$

Substitute $c=1$ into the other two:

$$
\begin{cases}
a + b = 2, \\
4a + 2b = 8.
\end{cases}
$$

Divide the second equation by 2: $2a + b = 4$.
Subtract the first equation from this new equation:

$$
(2a + b) - (a + b) = 4 - 2 \implies a = 2
$$

Then $2 + b = 2 \implies b = 0$. The polynomial is $p(x)=2x^2+1$.

Check:

- $p(0) = 2(0) + 1 = 1$
- $p(1) = 2(1) + 1 = 3$
- $p(2) = 2(4) + 1 = 9$

---
