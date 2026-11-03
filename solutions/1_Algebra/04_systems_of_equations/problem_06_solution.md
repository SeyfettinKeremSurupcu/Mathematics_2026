### Exercise 6. A System with a Parameter — Which Cases Actually Occur?

Analyze, depending on the parameter $a$, the system

$$
\begin{cases}
x+y=2, \\
ax+ay=4.
\end{cases}
$$

Among the three possibilities — exactly one solution, infinitely many solutions, no solution — determine which actually occur and for which values of $a$. If one type cannot occur, explain why.

> **Why this exercise:** teaches how to analyze a parameter without assuming in advance that all theoretically possible cases must occur in a specific system.

**Solution:**

Subtracting $a \times$ Equation 1 from Equation 2:

$$
\begin{aligned}
(ax+ay) - a(x+y) &= 4 - a(2) \\
0 &= 4 - 2a
\end{aligned}
$$

If $a = 2$, the equation becomes $0=0$. The system reduces to the single equation $x+y=2$, which has infinitely many solutions.
---

If $a \neq 2$, the equation $0 = 4 - 2a$ is a contradiction (e.g., if $a=0$, we get $0=4$). The system has no solution.

The case of exactly one solution never occurs because the determinant of the coefficient matrix is $a - a = 0$ for all values of $a$. The two lines are always parallel or coincident; they never intersect at exactly one point.
