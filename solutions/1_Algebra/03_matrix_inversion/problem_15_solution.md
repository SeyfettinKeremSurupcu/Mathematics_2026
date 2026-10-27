### Exercise 15. Two Methods for Solving the Same System

For

$$
A=
\begin{pmatrix}
2 & 1 \\
1 & 3 \\
\end{pmatrix},
\qquad 
b=
\begin{pmatrix}
7 \\
8 \\
\end{pmatrix}
$$

solve $Ax=b$ in two ways:

1. using $A^{-1}b$,
2. using Gaussian elimination.

Compare both solutions, the number of essential steps, and state which method was simpler in this example.

**Solution**

Method 1, using $A^{-1}b$:

$$
A^{-1}=
\frac{1}{5}
\begin{pmatrix}
3 & -1 \\
-1 & 2 \\
\end{pmatrix}
$$

$$
\begin{aligned}
x &= A^{-1}b \\
&= 
\frac{1}{5}
\begin{pmatrix}
3 & -1 \\
-1 & 2 \\
\end{pmatrix}
\begin{pmatrix}
7 \\
8 \\
\end{pmatrix} \\
&=
\frac{1}{5}
\begin{pmatrix}
21 - 8 \\
-7 + 16 \\
\end{pmatrix} \\
&=
\frac{1}{5}
\begin{pmatrix}
13 \\
9 \\
\end{pmatrix} \\
&=
\begin{pmatrix}
13/5 \\
9/5 \\
\end{pmatrix}
\end{aligned}
$$

Method 2, using Gaussian elimination:

$$
\begin{pmatrix}
2 & 1 & \mid & 7 \\
1 & 3 & \mid & 8 \\
\end{pmatrix}
$$

Swap row 1 and row 2:

$$
\begin{pmatrix}
1 & 3 & \mid & 8 \\
2 & 1 & \mid & 7 \\
\end{pmatrix}
$$

Subtract $2$ times row 1 from row 2:

$$
\begin{pmatrix}
1 & 3 & \mid & 8 \\
0 & -5 & \mid & -9 \\
\end{pmatrix}
$$

Divide row 2 by $-5$:

$$
\begin{pmatrix}
1 & 3 & \mid & 8 \\
0 & 1 & \mid & 9/5 \\
\end{pmatrix}
$$

Subtract $3$ times row 2 from row 1:

$$
\begin{pmatrix}
1 & 0 & \mid & 13/5 \\
0 & 1 & \mid & 9/5 \\
\end{pmatrix}
$$

Both solutions produce exactly $x_1 = 13/5$ and $x_2 = 9/5$. Gaussian elimination involves intermediate row operations and avoids the need to formally calculate the determinant and the adjugate matrix, making it generally simpler and computationally faster, especially because it handles the specific vector $b$ alongside the reduction of $A$.
