### Exercise 11. When Do Matrices Commute?

Given

$$
A=
\begin{pmatrix}
1 & 1 \\
0 & 1 \\
\end{pmatrix},\qquad B=
\begin{pmatrix}
a & b \\
c & d \\
\end{pmatrix}.
$$

Find the conditions on $a,b,c,d$ under which $AB=BA$. Describe the general form of all such matrices $B$.

> **Why this exercise:** deepens the idea of noncommutativity by finding the conditions under which commutativity does hold.

**Solution:**

First, compute the product $AB$:

$$
AB=
\begin{pmatrix}
1 & 1 \\
0 & 1 \\
\end{pmatrix}
\begin{pmatrix}
a & b \\
c & d \\
\end{pmatrix}
=
\begin{pmatrix}
a+c & b+d \\
c & d \\
\end{pmatrix}
$$

Next, compute the product $BA$:

$$
BA=
\begin{pmatrix}
a & b \\
c & d \\
\end{pmatrix}
\begin{pmatrix}
1 & 1 \\
0 & 1 \\
\end{pmatrix}
=
\begin{pmatrix}
a & a+b \\
c & c+d \\
\end{pmatrix}
$$

For $AB = BA$, corresponding entries must be equal, leading to a system of equations:

$$
\begin{cases}
a+c=a, \\
b+d=a+b, \\
c=c, \\
d=c+d.
\end{cases}
$$

From $a+c=a$ and $d=c+d$, it follows that $c=0$. 
From $b+d=a+b$, it follows that $d=a$.

The condition for commutativity is $c=0$ and $a=d$. The variables $a$ and $b$ can be any real numbers. The general form of all matrices $B$ that commute with $A$ is:

$$
B=
\begin{pmatrix}
a & b \\
0 & a \\
\end{pmatrix}
$$

---
