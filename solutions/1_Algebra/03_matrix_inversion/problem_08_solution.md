### Exercise 8. Inverse of a Transformation

The matrix

$$
S=
\begin{pmatrix}
2 & 0 \\
0 & 1/2 \\
\end{pmatrix}
$$

describes a scaling of the plane. Find $S^{-1}$ and explain geometrically what the inverse transformation does. Check the action of the pair $S,S^{-1}$ on one simple vector.

**Solution**

Compute the inverse:

$$
S^{-1}=
\begin{pmatrix}
1/2 & 0 \\
0 & 2 \\
\end{pmatrix}
$$

Geometrically, the transformation $S$ stretches the plane by a factor of $2$ in the horizontal direction and compresses it by a factor of $2$ in the vertical direction. The inverse matrix $S^{-1}$ undoes this by compressing horizontally by $2$ and stretching vertically by $2$.

Choose a vector $v$:

$$
v=
\begin{pmatrix}
1 \\
1 \\
\end{pmatrix}
$$

Apply $S$:

$$
Sv=
\begin{pmatrix}
2 & 0 \\
0 & 1/2 \\
\end{pmatrix}
\begin{pmatrix}
1 \\
1 \\
\end{pmatrix}
=
\begin{pmatrix}
2 \\
1/2 \\
\end{pmatrix}
$$

Apply $S^{-1}$:

$$
S^{-1}(Sv)=
\begin{pmatrix}
1/2 & 0 \\
0 & 2 \\
\end{pmatrix}
\begin{pmatrix}
2 \\
1/2 \\
\end{pmatrix}
=
\begin{pmatrix}
1 \\
1 \\
\end{pmatrix}
$$

The vector returns to its original state.
