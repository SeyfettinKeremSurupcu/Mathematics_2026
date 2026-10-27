### Exercise 7. Inverse of a Product

For

$$
A=
\begin{pmatrix}
1 & 1 \\
0 & 1 \\
\end{pmatrix},
\qquad 
B=
\begin{pmatrix}
2 & 0 \\
0 & 3 \\
\end{pmatrix}
$$

compute $(AB)^{-1}$ and $B^{-1}A^{-1}$. Check that the results are the same and explain the meaning of the reversed order.

**Solution**

Compute the product $AB$:

$$
\begin{aligned}
AB &= 
\begin{pmatrix}
1 & 1 \\
0 & 1 \\
\end{pmatrix}
\begin{pmatrix}
2 & 0 \\
0 & 3 \\
\end{pmatrix} \\
&=
\begin{pmatrix}
2 & 3 \\
0 & 3 \\
\end{pmatrix}
\end{aligned}
$$

Find $(AB)^{-1}$:

$$
\begin{aligned}
(AB)^{-1} &= 
\frac{1}{6}
\begin{pmatrix}
3 & -3 \\
0 & 2 \\
\end{pmatrix} \\
&=
\begin{pmatrix}
1/2 & -1/2 \\
0 & 1/3 \\
\end{pmatrix}
\end{aligned}
$$

Find $A^{-1}$ and $B^{-1}$:

$$
A^{-1} = 
\begin{pmatrix}
1 & -1 \\
0 & 1 \\
\end{pmatrix}
$$

$$
B^{-1} = 
\begin{pmatrix}
1/2 & 0 \\
0 & 1/3 \\
\end{pmatrix}
$$

Compute $B^{-1}A^{-1}$:

$$
\begin{aligned}
B^{-1}A^{-1} &= 
\begin{pmatrix}
1/2 & 0 \\
0 & 1/3 \\
\end{pmatrix}
\begin{pmatrix}
1 & -1 \\
0 & 1 \\
\end{pmatrix} \\
&=
\begin{pmatrix}
1/2 & -1/2 \\
0 & 1/3 \\
\end{pmatrix}
\end{aligned}
$$

The results are identical. Reversing the order is necessary because undoing a sequence of operations requires undoing the most recently applied operation first.
