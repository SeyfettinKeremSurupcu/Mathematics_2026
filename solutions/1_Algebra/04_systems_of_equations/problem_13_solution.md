### Exercise 13. Does Every Equation Add New Information?

Consider the system:

$$
x_1+x_2=10, \qquad x_2+x_3=8, \qquad x_1-x_3=2.
$$

Solve it and check whether all three equations are independently necessary to describe the solution set. If one follows from the others, show this by calculation.

> **Why this exercise:** teaches how to recognize redundant equations within a system.

**Answer 13**

From the first equation, we get:

$$
x_1 = 10 - x_2
$$

From the second equation, we get:

$$
x_3 = 8 - x_2
$$

Substitute these into the third equation:

$$
\begin{aligned}
(10 - x_2) - (8 - x_2) &= 2 \\
2 &= 2
\end{aligned}
$$

This identity means the third equation is just a direct consequence of the first two (it can be obtained by subtracting the second equation from the first). Therefore, it adds no new information, and the system has infinitely many solutions based on a single parameter.

To finish solving, we set $x_2 = t$. Then we can write the other variables in terms of $t$:

$$
\begin{aligned}
x_1 &= 10 - t \\
x_3 &= 8 - t
\end{aligned}
$$

The full family of solutions is $(10-t, t, 8-t)$.
