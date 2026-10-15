### Exercise 9. Composing Transformations
Let

$$
S=
\begin{pmatrix}
2 & 0 \\\\
0 & 1 \\\\
\end{pmatrix},\qquad R=
\begin{pmatrix}
0 & -1 \\\\
1 & 0 \\\\
\end{pmatrix}.
$$

The matrix $S$ describes nonuniform scaling, while $R$ describes a $90^\circ$ counterclockwise rotation.
For

$$
x=
\begin{pmatrix}
1 \\\\
2 \\\\
\end{pmatrix}
$$

compute $RSx$ and $SRx$. Compare the results and explain geometrically why the order of these transformations matters.

### Solution 9

$$
Sx = \begin{pmatrix} 2 & 0 \\\\ 0 & 1 \end{pmatrix} \begin{pmatrix} 1 \\\\ 2 \end{pmatrix} = \begin{pmatrix} 2 \\\\ 2 \end{pmatrix}
$$

$$
RSx = R(Sx) = \begin{pmatrix} 0 & -1 \\\\ 1 & 0 \end{pmatrix} \begin{pmatrix} 2 \\\\ 2 \end{pmatrix} = \begin{pmatrix} -2 \\\\ 2 \end{pmatrix}
$$

$$
Rx = \begin{pmatrix} 0 & -1 \\\\ 1 & 0 \end{pmatrix} \begin{pmatrix} 1 \\\\ 2 \end{pmatrix} = \begin{pmatrix} -2 \\\\ 1 \end{pmatrix}
$$

$$
SRx = S(Rx) = \begin{pmatrix} 2 & 0 \\\\ 0 & 1 \end{pmatrix} \begin{pmatrix} -2 \\\\ 1 \end{pmatrix} = \begin{pmatrix} -4 \\\\ 1 \end{pmatrix}
$$

Results comparison: $RSx \neq SRx$. 
Geometrically, $RSx$ means stretching the x-axis by 2 first, then rotating $90^\circ$. $SRx$ means rotating $90^\circ$ first (so the original x-component is now on the y-axis), and then stretching along the x-axis. Because scaling happens specifically along the coordinate axes, rotating before or after scaling affects completely different components of the original vector.
