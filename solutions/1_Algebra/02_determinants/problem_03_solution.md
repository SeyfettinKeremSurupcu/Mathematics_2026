### Exercise 3. Swapping Two Rows
For

$$
A=
\begin{pmatrix}
1 & 2 & 0 \cr
0 & 3 & 1 \cr
2 & 1 & 1 \cr
\end{pmatrix}
$$

compute $\det A$. Then form a matrix $B$ by swapping the first and second rows of $A$.

First predict $\det B$ using a determinant property, and then verify your prediction by calculation.

### Solution 3

**Step 1: Compute the determinant of matrix $A$**
To find $\det A$, we can use the cofactor expansion method. It is usually easiest to expand along a row or column with a zero. Let's expand along the first column:

$$
\det(A) = 1 \cdot \det \begin{pmatrix} 3 & 1 \cr 1 & 1 \end{pmatrix} - 0 \cdot \det \begin{pmatrix} 2 & 0 \cr 1 & 1 \end{pmatrix} + 2 \cdot \det \begin{pmatrix} 2 & 0 \cr 3 & 1 \end{pmatrix}
$$

Now, we calculate the smaller determinants:

First term determinant:

$$
\det \begin{pmatrix} 3 & 1 \cr 1 & 1 \end{pmatrix} = (3)(1) - (1)(1) = 3 - 1 = 2
$$

The second term is multiplied by 0, so we ignore it.

Third term determinant:

$$
\det \begin{pmatrix} 2 & 0 \cr 3 & 1 \end{pmatrix} = (2)(1) - (0)(3) = 2 - 0 = 2
$$

Putting it all together:

$$
\det(A) = 1(2) - 0 + 2(2) = 2 + 4 = 6
$$

**Step 2: Form matrix $B$ by swapping the first and second rows**
By taking row 1 and row 2 of matrix $A$ and swapping their positions, we get:

$$
B=
\begin{pmatrix}
0 & 3 & 1 \cr
1 & 2 & 0 \cr
2 & 1 & 1 \cr
\end{pmatrix}
$$

**Step 3: Predict the determinant of matrix $B$**
A fundamental property of determinants states that swapping any two rows (or columns) of a square matrix multiplies its determinant by -1. Since we performed exactly one row swap on $A$ to get $B$, we predict:

$$
\det(B) = -\det(A) = -6
$$

**Step 4: Verify the prediction by calculation**
Let's compute $\det B$ directly. We can expand along the second row because it contains a zero:

$$
\det(B) = -1 \cdot \det \begin{pmatrix} 3 & 1 \cr 1 & 1 \end{pmatrix} + 2 \cdot \det \begin{pmatrix} 0 & 1 \cr 2 & 1 \end{pmatrix} - 0 \cdot \det \begin{pmatrix} 0 & 3 \cr 2 & 1 \end{pmatrix}
$$

*(Note the alternating signs for the second row expansion: -, +, -)*

Calculate the smaller determinants:

First term determinant:

$$
\det \begin{pmatrix} 3 & 1 \cr 1 & 1 \end{pmatrix} = (3)(1) - (1)(1) = 2
$$

Second term determinant:

$$
\det \begin{pmatrix} 0 & 1 \cr 2 & 1 \end{pmatrix} = (0)(1) - (1)(2) = -2
$$

Substitute these back:

$$
\det(B) = -1(2) + 2(-2) - 0 = -2 - 4 = -6
$$

The calculated result perfectly matches our prediction, verifying the row-swap property.
