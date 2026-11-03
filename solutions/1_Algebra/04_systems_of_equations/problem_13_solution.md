### Exercise 13. Does Every Equation Add New Information?

Consider the system

$$
x_1+x_2=10,\qquad x_2+x_3=8,\qquad x_1-x_3=2.
$$

Solve it and check whether all three equations are independently necessary to describe the solution set. If one follows from the others, show this by calculation.

> **Why this exercise:** teaches how to recognize redundant equations within a system.

**Solution:**

From the first equation, $x_1 = 10 - x_2$.
From the second equation, $x_3 = 8 - x_2$.
Substitute these into the third equation:

$$
\begin{aligned}
(10 - x_2) - (8 - x_2) &= 2 \\
2 &= 2
\end{aligned}
$$

This identity means the third equation is just a direct consequence of the first two ($E_3 = E_1 - E_2$). Therefore, it adds no new information, and the system has infinitely many solutions based on a single parameter.

---
