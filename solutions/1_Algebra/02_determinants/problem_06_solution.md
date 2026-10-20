### Exercise 6. Parameter and Invertibility
For

$$
A(t)=
\begin{pmatrix}
t & 1 \\
2 & t \\
\end{pmatrix}
$$

find all values of $t$ for which the matrix is not invertible. Explain how your answer is related to the determinant being zero.

### Solution 6

**Step 1: Compute the determinant in terms of $t$**

$$
\begin{aligned}
\det A(t) &= (t)(t) - (1)(2) \\
&= t^2 - 2
\end{aligned}
$$

**Step 2: Find values of $t$ where the matrix is not invertible**

A matrix is not invertible when its determinant is equal to zero. 

$$
\begin{aligned}
t^2 - 2 &= 0 \\
t^2 &= 2 \\
t &= \pm\sqrt{2}
\end{aligned}
$$

The matrix is not invertible for $t = \sqrt{2}$ and $t = -\sqrt{2}$ because these are the precise values that make the determinant zero, indicating that the rows (and columns) are linearly dependent.
