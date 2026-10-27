### Exercise 13. Undoing a Composite Transformation

The matrices

$$
S=
\begin{pmatrix}
2 & 0 \\
0 & 1 \\
\end{pmatrix},
\qquad 
H=
\begin{pmatrix}
1 & 1 \\
0 & 1 \\
\end{pmatrix}
$$

describe nonuniform scaling and shear. For $T=HS$, find $T^{-1}$ in two ways:

1. first compute $T$, then its inverse,
2. use $(HS)^{-1}=S^{-1}H^{-1}$.

Compare the results. Additionally compute $H^{-1}S^{-1}$ and verify that the incorrect order gives a different matrix. Explain the rule: “when undoing a composition of operations, we undo them from the end.”

**Solution**

Method 1:

$$
\begin{aligned}
T &= HS \\
&= 
\begin{pmatrix}
1 & 1 \\
0 & 1 \\
\end{pmatrix}
\begin{pmatrix}
2 & 0 \\
0 & 1 \\
\end{pmatrix} \\
&=
\begin{pmatrix}
2 & 1 \\
0 & 1 \\
\end{pmatrix}
\end{aligned}
$$

$$
\begin{aligned}
T^{-1} &= 
\frac{1}{2}
\begin{pmatrix}
1 & -1 \\
0 & 2 \\
\end{pmatrix} \\
&=
\begin{pmatrix}
1/2 & -1/2 \\
0 & 1 \\
\end{pmatrix}
\end{aligned}
$$

Method 2:

$$
S^{-1}=
\begin{pmatrix}
1/2 & 0 \\
0 & 1 \\
\end{pmatrix}
$$

$$
H^{-1}=
\begin{pmatrix}
1 & -1 \\
0 & 1 \\
\end{pmatrix}
$$

$$
\begin{aligned}
S^{-1}H^{-1} &= 
\begin{pmatrix}
1/2 & 0 \\
0 & 1 \\
\end{pmatrix}
\begin{pmatrix}
1 & -1 \\
0 & 1 \\
\end{pmatrix} \\
&=
\begin{pmatrix}
1/2 & -1/2 \\
0 & 1 \\
\end{pmatrix}
\end{aligned}
$$

The results are identical.

Now compute the incorrect order $H^{-1}S^{-1}$:

$$
\begin{aligned}
H^{-1}S^{-1} &= 
\begin{pmatrix}
1 & -1 \\
0 & 1 \\
\end{pmatrix}
\begin{pmatrix}
1/2 & 0 \\
0 & 1 \\
\end{pmatrix} \\
&=
\begin{pmatrix}
1/2 & -1 \\
0 & 1 \\
\end{pmatrix}
\end{aligned}
$$

This produces a different matrix. To accurately reverse a sequence of operations, the last operation applied must be the first one undone.
