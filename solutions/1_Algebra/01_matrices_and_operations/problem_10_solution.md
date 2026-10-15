### Exercise 10. Columns of a Matrix Product
Given

$$
A=
\begin{pmatrix}
1 & 2 & 0 \\\\
0 & 1 & 1 \\\\
\end{pmatrix},\qquad B=
\begin{pmatrix}
1 & 2 \\\\
-1 & 0 \\\\
3 & 1 \\\\
\end{pmatrix}.
$$

Denote the columns of $B$ by $b_1,b_2$.

1. Compute $Ab_1$ and $Ab_2$.
2. Compute the matrix $AB$.
3. Compare the results and explain why the columns of $AB$ are exactly the vectors $Ab_1$ and $Ab_2$.

### Solution 10
1. 

$$
b_1 = \begin{pmatrix} 1 \\\\ -1 \\\\ 3 \end{pmatrix}, \qquad b_2 = \begin{pmatrix} 2 \\\\ 0 \\\\ 1 \end{pmatrix}
$$

$$
Ab_1 = \begin{pmatrix} 1 & 2 & 0 \\\\ 0 & 1 & 1 \end{pmatrix} \begin{pmatrix} 1 \\\\ -1 \\\\ 3 \end{pmatrix} = \begin{pmatrix} 1(1)+2(-1)+0(3) \\\\ 0(1)+1(-1)+1(3) \end{pmatrix} = \begin{pmatrix} -1 \\\\ 2 \end{pmatrix}
$$

$$
Ab_2 = \begin{pmatrix} 1 & 2 & 0 \\\\ 0 & 1 & 1 \end{pmatrix} \begin{pmatrix} 2 \\\\ 0 \\\\ 1 \end{pmatrix} = \begin{pmatrix} 1(2)+2(0)+0(1) \\\\ 0(2)+1(0)+1(1) \end{pmatrix} = \begin{pmatrix} 2 \\\\ 1 \end{pmatrix}
$$

2. 

$$
AB = \begin{pmatrix} 1 & 2 & 0 \\\\ 0 & 1 & 1 \end{pmatrix} \begin{pmatrix} 1 & 2 \\\\ -1 & 0 \\\\ 3 & 1 \end{pmatrix} = \begin{pmatrix} (1)(1)+(2)(-1)+(0)(3) & (1)(2)+(2)(0)+(0)(1) \\\\ (0)(1)+(1)(-1)+(1)(3) & (0)(2)+(1)(0)+(1)(1) \end{pmatrix} = \begin{pmatrix} -1 & 2 \\\\ 2 & 1 \end{pmatrix}
$$

3. Comparing results: The first column of $AB$ is 

$$
\begin{pmatrix} -1 \\\\ 2 \end{pmatrix}
$$

which is $Ab_1$. The second column of $AB$ is 

$$
\begin{pmatrix} 2 \\\\ 1 \end{pmatrix}
$$

which is $Ab_2$. 

Explanation: Matrix multiplication $AB$ can be viewed as applying the transformation matrix $A$ to each column vector of $B$ independently. Thus, the $j$-th column of the product $AB$ is always equal to the matrix $A$ multiplied by the $j$-th column of matrix $B$.
