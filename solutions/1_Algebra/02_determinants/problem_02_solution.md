### Exercise 2. Determinant of a 3×3 Matrix
For

$$
A=
\begin{pmatrix}
1 & 2 & -1 \cr
0 & 3 & 4 \cr
2 & 1 & 5 \cr
\end{pmatrix}
$$

compute $\det A$ using Sarrus' rule. Then perform one simple check using a chosen property of the determinant.

### Solution 2
**Step 1: Understand and set up Sarrus' Rule**
Sarrus' rule is a visual method for calculating the determinant of a $3 \times 3$ matrix. To use it, we write out the matrix and then copy its first two columns to the right side:

$$
\begin{matrix}
1 & 2 & -1 & | & 1 & 2 \cr
0 & 3 & 4 & | & 0 & 3 \cr
2 & 1 & 5 & | & 2 & 1 \cr
\end{matrix}
$$

**Step 2: Multiply along the diagonals**
We calculate the sum of the products of the three main (downward-right) diagonals and subtract the sum of the products of the three anti-diagonals (upward-right).

*Downward diagonals (add these):*
1. $(1) \cdot (3) \cdot (5) = 15$
2. $(2) \cdot (4) \cdot (2) = 16$
3. $(-1) \cdot (0) \cdot (1) = 0$
*Sum of downward products* = $15 + 16 + 0 = 31$

*Upward diagonals (subtract these):*
1. $(2) \cdot (3) \cdot (-1) = -6$
2. $(1) \cdot (4) \cdot (1) = 4$
3. $(5) \cdot (0) \cdot (2) = 0$
*Sum of upward products* = $-6 + 4 + 0 = -2$

$$
\det(A) = 31 - (-2) = 31 + 2 = 33
$$

**Step 3: Perform a simple check**
To verify our result, we can use the **Laplace expansion (cofactor expansion)** property along any row or column. It is usually fastest to expand along a row or column that contains a zero. Let's expand along the first column:

$$
\det(A) = 1 \cdot \det \begin{pmatrix} 3 & 4 \cr 1 & 5 \end{pmatrix} - 0 \cdot \det \begin{pmatrix} 2 & -1 \cr 1 & 5 \end{pmatrix} + 2 \cdot \det \begin{pmatrix} 2 & -1 \cr 3 & 4 \end{pmatrix}
$$

Calculate the smaller $2 \times 2$ determinants:
- $\det \begin{pmatrix} 3 & 4 \cr 1 & 5 \end{pmatrix} = (3)(5) - (4)(1) = 15 - 4 = 11$
- $\det \begin{pmatrix} 2 & -1 \cr 3 & 4 \end{pmatrix} = (2)(4) - (-1)(3) = 8 + 3 = 11$

Substitute these back into the expansion equation:

$$
\det(A) = 1(11) - 0 + 2(11) = 11 + 22 = 33
$$

The results match perfectly, verifying that $\det(A) = 33$.
