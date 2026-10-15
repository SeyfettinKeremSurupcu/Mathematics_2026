### Exercise 2. Addition and Scalar Multiplication
For

$$
A=
\begin{pmatrix}
1 & 2 \cr
-1 & 3 \cr
\end{pmatrix},\qquad B=
\begin{pmatrix}
4 & -2 \cr
0 & 5 \cr
\end{pmatrix}
$$

compute

$$
A+B,\qquad A-B,\qquad 3A-2B.
$$

Explain why matrix addition is possible only for matrices of the same size.

### Solution 2

$$
A+B = \begin{pmatrix} 1+4 & 2+(-2) \cr -1+0 & 3+5 \end{pmatrix} = \begin{pmatrix} 5 & 0 \cr -1 & 8 \end{pmatrix}
$$

$$
A-B = \begin{pmatrix} 1-4 & 2-(-2) \cr -1-0 & 3-5 \end{pmatrix} = \begin{pmatrix} -3 & 4 \cr -1 & -2 \end{pmatrix}
$$

$$
3A-2B = \begin{pmatrix} 3(1) & 3(2) \cr 3(-1) & 3(3) \end{pmatrix} - \begin{pmatrix} 2(4) & 2(-2) \cr 2(0) & 2(5) \end{pmatrix} = \begin{pmatrix} 3 & 6 \cr -3 & 9 \end{pmatrix} - \begin{pmatrix} 8 & -4 \cr 0 & 10 \end{pmatrix} = \begin{pmatrix} -5 & 10 \cr -3 & -1 \end{pmatrix}
$$

Matrix addition is performed element-wise. Therefore, it is only possible for matrices of the same size because corresponding elements from each row and column index must exist in both matrices to be added together.
