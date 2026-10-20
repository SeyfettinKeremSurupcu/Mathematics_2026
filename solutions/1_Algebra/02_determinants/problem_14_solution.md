### Exercise 14. A System of Equations and the Determinant
Consider the system $Ax=b$, where

$$
A=
\begin{pmatrix}
1 & 2 \\
k & 4 \\
\end{pmatrix}.
$$

For which values of $k$ does the system have exactly one solution for every $b$? For the remaining value, give an example of a right-hand side $b$ for which the system has infinitely many solutions, and an example for which it has no solution.

### Solution 14

**Step 1: Find values for exactly one solution**

A system $Ax=b$ has exactly one solution for every $b$ if and only if the matrix $A$ is invertible, which means $\det A \neq 0$.

$$
\begin{aligned}
\det A &= (1)(4) - (2)(k) \\
&= 4 - 2k
\end{aligned}
$$

Setting the determinant not equal to zero:

$$
\begin{aligned}
4 - 2k &\neq 0 \\
2k &\neq 4 \\
k &\neq 2
\end{aligned}
$$

The system has exactly one solution for all $k \neq 2$.

**Step 2: Examine the remaining value $k = 2$**

If $k = 2$, the matrix is:

$$
A =
\begin{pmatrix}
1 & 2 \\
2 & 4 \\
\end{pmatrix}
$$

The system $Ax=b$ becomes:

$$
\begin{aligned}
x_1 + 2x_2 &= b_1 \\
2x_1 + 4x_2 &= b_2
\end{aligned}
$$

Notice that the left side of the second equation is exactly twice the left side of the first equation.

- **Infinitely many solutions:** Choose $b$ such that the second equation is twice the first, making them consistent. For example, let $b_1 = 1$ and $b_2 = 2$. The vector $b$ is:

$$
b =
\begin{pmatrix}
1 \\
2 \\
\end{pmatrix}
$$

- **No solution:** Choose $b$ such that the equations contradict each other. For example, let $b_1 = 1$ and $b_2 = 0$. The vector $b$ is:

$$
b =
\begin{pmatrix}
1 \\
0 \\
\end{pmatrix}
$$
