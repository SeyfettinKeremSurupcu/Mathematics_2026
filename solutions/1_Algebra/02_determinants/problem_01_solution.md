### Exercise 1. Determinant of a 2×2 Matrix
Compute

$$
\det
\begin{pmatrix}
3 & -2 \cr
5 & 4 \cr
\end{pmatrix},\qquad \det
\begin{pmatrix}
1 & 7 \cr
2 & 14 \cr
\end{pmatrix}.
$$

Which matrix is invertible? Justify your answer.

### Solution 1
To compute the determinant of a $2 \times 2$ matrix $A = \begin{pmatrix} a & b \cr c & d \end{pmatrix}$, we use the standard formula:

$$
\det(A) = ad - bc
$$

This means we multiply the elements on the main diagonal ($a$ and $d$) and subtract the product of the elements on the other diagonal ($b$ and $c$).

**Step 1: Compute the determinant of the first matrix**
For the first matrix, we identify $a=3$, $b=-2$, $c=5$, and $d=4$. Applying the formula:

$$
\det \begin{pmatrix} 3 & -2 \cr 5 & 4 \end{pmatrix} = (3)(4) - (-2)(5)
$$

$$
= 12 - (-10) = 12 + 10 = 22
$$

**Step 2: Compute the determinant of the second matrix**
For the second matrix, we identify $a=1$, $b=7$, $c=2$, and $d=14$. Applying the formula:

$$
\det \begin{pmatrix} 1 & 7 \cr 2 & 14 \end{pmatrix} = (1)(14) - (7)(2)
$$

$$
= 14 - 14 = 0
$$

**Step 3: Determine invertibility**
A fundamental property in linear algebra states that a matrix is invertible if and only if its determinant is non-zero ($\det(A) \neq 0$). 
- The **first matrix is invertible** because its determinant is $22$ ($22 \neq 0$). 
- The **second matrix is not invertible** (it is a singular matrix) because its determinant is exactly $0$.
