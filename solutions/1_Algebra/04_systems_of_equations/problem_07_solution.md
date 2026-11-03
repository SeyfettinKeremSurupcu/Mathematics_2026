### Exercise 7. Choosing a Method Deliberately

Do not solve all of the following systems completely. For each situation, choose the method that best uses its structure and justify your choice:

1. one system with a triangular coefficient matrix

$$
\begin{cases}
2x-y=3, \\
4y=8;
\end{cases}
$$

2. three systems $Ax=b_i$ with the same invertible matrix $A$, when $A^{-1}$ is already known;
3. one $3\times3$ system for which the inverse matrix is not given and the goal is only to find one solution vector.

For case 1, carry out the chosen method completely. For cases 2 and 3, describe the plan and indicate which part of the computation would be reusable or unnecessary. Do not judge a method by its name alone — refer to the number of right-hand sides and the structure of the matrix.

> **Why this exercise:** practices choosing a method based on the structure of the problem instead of solving another small system by two methods.

**Solution:**

1. **System with a triangular coefficient matrix:** Back-substitution is the best method because the second equation already gives $y$ directly.
   
$$
4y = 8 \implies y = 2
$$

Substitute into the first:

$$
\begin{aligned}
2x - 2 &= 3 \\
2x &= 5 \\
x &= 2.5
\end{aligned}
$$

2. **Three systems with the same invertible matrix $A$ and known $A^{-1}$:** Matrix multiplication $x_i = A^{-1} b_i$ is optimal. The expensive step (finding $A^{-1}$) is already done, so we only need to perform three matrix-vector products, completely avoiding Gaussian elimination.

3. **One $3\times3$ system for a single solution:** Gaussian elimination on the augmented matrix is optimal. Computing the entire inverse matrix $A^{-1}$ takes more operations than finding a single solution via row reduction. The work to find the full inverse would be largely unnecessary.

---
