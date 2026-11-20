### Exercise 9. Cross Product as a Perpendicular Direction

For $u=(1,2,0)$ and $v=(0,1,3)$, compute $u\times v$. Use dot products to check perpendicularity to both vectors, compute $v\times u$, and compare the results.

**Answer 9**

Cross product:

$$
u\times v =
\begin{pmatrix}
i & j & k \\
1 & 2 & 0 \\
0 & 1 & 3 \\
\end{pmatrix}
= i(6-0) - j(3-0) + k(1-0) = (6, -3, 1)
$$

*(Note: standard determinant notation usually uses `vmatrix`, but following rule 4, `pmatrix` is used for matrices.)*

Verification (perpendicularity check):

$$
\begin{aligned}
(6,-3,1)\cdot(1,2,0) &= 6-6+0 = 0 \\
(6,-3,1)\cdot(0,1,3) &= 0-3+3 = 0
\end{aligned}
$$

Comparison for $v\times u$:

$$
v\times u = (-6, 3, -1) = -(u\times v)
$$

**Explanation:** Changing the order of the cross product preserves the magnitude of the resulting perpendicular vector but completely reverses its direction (according to the right-hand rule).

---
