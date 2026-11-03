### Exercise 2. Gaussian Elimination — One Solution

Solve using Gaussian elimination:

$$
\begin{cases}
x+y+z=6, \\
2x-y+z=3, \\
x+2y-z=2.
\end{cases}
$$

After solving, substitute the result into all equations and check consistency.

> **Why this exercise:** introduces the basic method for solving a system and builds the habit of checking the result.

**Solution:**

The augmented matrix for the system is:

$$
\begin{pmatrix}
1 & 1 & 1 & \mid & 6 \\
2 & -1 & 1 & \mid & 3 \\
1 & 2 & -1 & \mid & 2 \\
\end{pmatrix}
$$

Subtract $2 \times$ Row 1 from Row 2, and subtract Row 1 from Row 3:

$$
\begin{pmatrix}
1 & 1 & 1 & \mid & 6 \\
0 & -3 & -1 & \mid & -9 \\
0 & 1 & -2 & \mid & -4 \\
\end{pmatrix}
$$

Swap Row 2 and Row 3:

$$
\begin{pmatrix}
1 & 1 & 1 & \mid & 6 \\
0 & 1 & -2 & \mid & -4 \\
0 & -3 & -1 & \mid & -9 \\
\end{pmatrix}
$$

Add $3 \times$ Row 2 to Row 3:

$$
\begin{pmatrix}
1 & 1 & 1 & \mid & 6 \\
0 & 1 & -2 & \mid & -4 \\
0 & 0 & -7 & \mid & -21 \\
\end{pmatrix}
$$

From Row 3, we solve for $z$:

$$
-7z = -21 \implies z = 3
$$

Substitute $z=3$ into Row 2:

$$
\begin{aligned}
y - 2(3) &= -4 \\
y &= 2
\end{aligned}
$$

Substitute $y=2$ and $z=3$ into Row 1:

$$
\begin{aligned}
x + 2 + 3 &= 6 \\
x &= 1
\end{aligned}
$$

Checking consistency by substituting $(1,2,3)$ into the original equations:

- $1+2+3=6$
- $2(1)-2+3=3$
- $1+2(2)-3=2$

The point $(1,2,3)$ satisfies all equations.
