### Exercise 10. Triangle Area from Vectors

The points $A=(0,0,0)$, $B=(2,1,0)$, and $C=(1,3,2)$ form a triangle. Construct $\overrightarrow{AB}$ and $\overrightarrow{AC}$, compute the area of the parallelogram using the cross product, and then find the area of the triangle. Explain the factor $\frac{1}{2}$.

**Answer 10**

Difference vectors:

$$
\begin{aligned}
\overrightarrow{AB} &= (2,1,0) \\
\overrightarrow{AC} &= (1,3,2)
\end{aligned}
$$

Cross product:

$$
\overrightarrow{AB}\times\overrightarrow{AC} =
\begin{pmatrix}
i & j & k \\
2 & 1 & 0 \\
1 & 3 & 2 \\
\end{pmatrix}
= (2, -4, 5)
$$

Area of the parallelogram:

$$
\|(2, -4, 5)\| = \sqrt{4+16+25} = \sqrt{45} = 3\sqrt{5}
$$

Area of the triangle:

$$
\mathrm{Area} = \frac{3\sqrt{5}}{2}
$$

**Explanation:** The area of the parallelogram spanned by two vectors equals the length of their cross product vector. Since a triangle is exactly half of this parallelogram (split by the diagonal), the area is multiplied by the factor $\frac{1}{2}$.

---
