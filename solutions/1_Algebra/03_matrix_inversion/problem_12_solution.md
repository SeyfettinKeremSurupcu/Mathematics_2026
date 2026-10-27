### Exercise 12. Finding Inverses Without Starting from Scratch

It is known that

$$
A^{-1}=
\begin{pmatrix}
2 & -1 \\
-3 & 2 \\
\end{pmatrix}.
$$

Without finding $A$, compute $(3A)^{-1}$, $(A^T)^{-1}$, and $(A^2)^{-1}$. Justify each result using the appropriate property.

**Solution**

Using the property $(cA)^{-1} = \frac{1}{c} A^{-1}$:

$$
(3A)^{-1} = \frac{1}{3} A^{-1} = 
\begin{pmatrix}
2/3 & -1/3 \\
-1 & 2/3 \\
\end{pmatrix}
$$

Using the property $(A^T)^{-1} = (A^{-1})^T$:

$$
(A^T)^{-1} = 
\begin{pmatrix}
2 & -3 \\
-1 & 2 \\
\end{pmatrix}
$$

Using the property $(A^2)^{-1} = (A^{-1})^2$:

$$
\begin{aligned}
(A^2)^{-1} &= 
\begin{pmatrix}
2 & -1 \\
-3 & 2 \\
\end{pmatrix}
\begin{pmatrix}
2 & -1 \\
-3 & 2 \\
\end{pmatrix} \\
&=
\begin{pmatrix}
4 + 3 & -2 - 2 \\
-6 - 6 & 3 + 4 \\
\end{pmatrix} \\
&=
\begin{pmatrix}
7 & -4 \\
-12 & 7 \\
\end{pmatrix}
\end{aligned}
$$
