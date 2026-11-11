### Exercise 8. Intersection Point of a Line and a Plane

Find the intersection point of

$$
(x,y,z)=(1,0,2)+t(1,2,-1)
$$

with the plane $x+y+z=4$. Check the result by substituting it into both descriptions.

> **Why this exercise:** practices the most important computational case of the line–plane relationship.

**Answer 8**

Substitute the parametric expressions for $x, y, z$ directly into the plane equation:

$$
\begin{aligned}
(1+t) + (2t) + (2-t) &= 4 \\
3 + 2t &= 4 \\
2t &= 1 \\
t &= \frac{1}{2}
\end{aligned}
$$

Substitute $t=\frac{1}{2}$ back into the line equation to find the intersection point:

$$
(x,y,z) = \left(1+\frac{1}{2}, 2\left(\frac{1}{2}\right), 2-\frac{1}{2}\right) = \left(\frac{3}{2}, 1, \frac{3}{2}\right)
$$

Verification in the plane equation:

$$
\frac{3}{2} + 1 + \frac{3}{2} = 4
$$

Verification in the line equation:

$$
(1,0,2) + \frac{1}{2}(1,2,-1) = \left(1+\frac{1}{2}, 0+1, 2-\frac{1}{2}\right) = \left(\frac{3}{2}, 1, \frac{3}{2}\right)
$$

---
