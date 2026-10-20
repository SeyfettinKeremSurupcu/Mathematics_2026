### Exercise 5. Matrix Times Vector
Let

$$
A=
\begin{pmatrix}
2 & -1 \\
1 & 3 \\
\end{pmatrix},\qquad x=
\begin{pmatrix}
4 \\
2 \\
\end{pmatrix}.
$$

Compute $Ax$. Then express $Ax$ as a linear combination of the columns of $A$, with coefficients coming from the vector $x$.

### Solution 5

**Step 1: Compute $Ax$ using the standard matrix-vector rule**

We compute the product by taking the dot product of each row of $A$ with the vector $x$:

$$
\begin{aligned}
Ax &=
\begin{pmatrix}
(2)(4) + (-1)(2) \\
(1)(4) + (3)(2) \\
\end{pmatrix} \\
&=
\begin{pmatrix}
8 - 2 \\
4 + 6 \\
\end{pmatrix} \\
&=
\begin{pmatrix}
6 \\
10 \\
\end{pmatrix}
\end{aligned}
$$

**Step 2: Express $Ax$ as a linear combination of the columns of $A$**

By the definition of matrix-vector multiplication, the first entry of $x$ (which is $4$) multiplies every element in the first column of $A$, and the second entry of $x$ (which is $2$) multiplies every element in the second column of $A$. Regrouping the terms from the row-by-row multiplication directly shows that $Ax$ is exactly the linear combination of the columns of $A$ scaled by the corresponding entries of $x$:

$$
\begin{aligned}
Ax &= 4
\begin{pmatrix}
2 \\
1 \\
\end{pmatrix} + 2
\begin{pmatrix}
-1 \\
3 \\
\end{pmatrix} \\
&=
\begin{pmatrix}
8 \\
4 \\
\end{pmatrix} +
\begin{pmatrix}
-2 \\
6 \\
\end{pmatrix} \\
&=
\begin{pmatrix}
6 \\
10 \\
\end{pmatrix}
\end{aligned}
$$
