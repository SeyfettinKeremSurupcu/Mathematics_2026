### Exercise 14. A Matrix That Is Its Own Inverse

Assume that a square matrix $A$ satisfies

$$
A^2=I.
$$

Show that

$$
A^{-1}=A.
$$

Then give an example of a $2\times2$ matrix different from $I$ and $-I$ that satisfies this condition, and verify it by multiplication.

**Solution**

The equation can be written as:

$$
A A = I
$$

By definition, the inverse of $A$ is the matrix that yields $I$ when multiplied by $A$. Since $A$ multiplied by itself yields $I$, the matrix $A$ is its own inverse. Therefore, $A^{-1} = A$.

Consider the matrix:

$$
A=
\begin{pmatrix}
0 & 1 \\
1 & 0 \\
\end{pmatrix}
$$

Check the condition:

$$
\begin{aligned}
A^2 &= 
\begin{pmatrix}
0 & 1 \\
1 & 0 \\
\end{pmatrix}
\begin{pmatrix}
0 & 1 \\
1 & 0 \\
\end{pmatrix} \\
&=
\begin{pmatrix}
0 + 1 & 0 + 0 \\
0 + 0 & 1 + 0 \\
\end{pmatrix} \\
&=
\begin{pmatrix}
1 & 0 \\
0 & 1 \\
\end{pmatrix}
\end{aligned}
$$

The condition $A^2 = I$ is satisfied.
