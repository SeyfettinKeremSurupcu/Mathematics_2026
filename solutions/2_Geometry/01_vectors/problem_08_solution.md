### Exercise 8. Linear Combination and Checking the Result

Check whether $w=(5,1)$ can be written as $w=au+bv$, where $u=(1,1)$ and $v=(2,-1)$. If so, find $a,b$, reconstruct $w$ from them, and explain the geometric meaning of the existence of such coefficients.

**Answer 8**

Linear combination equation:

$$
(5,1) = a(1,1) + b(2,-1)
$$

Resulting system:

$$
\begin{cases}
a+2b = 5, \\
a-b = 1.
\end{cases}
$$

From the second equation, $a = b+1$. Substituting this into the first equation:

$$
\begin{aligned}
(b+1) + 2b &= 5 \\
3b &= 4 \\
b &= \frac{4}{3}
\end{aligned}
$$

Thus, $a = \frac{7}{3}$.

Reconstruction and verification:

$$
\frac{7}{3}(1,1) + \frac{4}{3}(2,-1) = \left(\frac{7+8}{3}, \frac{7-4}{3}\right) = (5,1)
$$

**Geometric Meaning:** Two non-parallel vectors form a basis spanning their plane. These coefficients indicate exactly how far to move in the direction of each basis vector to reach the target point.

---
