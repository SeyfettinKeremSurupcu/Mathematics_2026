### Exercise 14. Contrast: Intersection and Parallelism

From the point $P=(0,0,1)$, two lines are drawn with direction vectors

$$
v_1=(2,1,-1), \qquad v_2=(2,1,0).
$$

For each line, analyze its position relative to the plane $z=0$.

For the line that intersects the plane, find the intersection point. For the other line, explain how you can recognize parallelism without solving an equation.

> **Why this exercise:** compares two very similar data sets that lead to different outcomes and forces recognition of the geometric condition before calculation.

**Answer 14**

The plane $z=0$ has a normal vector $n=(0,0,1)$.

For the first line with $v_1=(2,1,-1)$:

$$
v_1 \cdot n = 2(0) + 1(0) - 1(1) = -1
$$

Since the dot product is non-zero, this line intersects the plane. The parametric equation is $(x,y,z) = (2t, t, 1-t)$. Setting $z=0 \implies 1-t=0 \implies t=1$. The intersection point is $(2, 1, 0)$.

For the second line with $v_2=(2,1,0)$:

$$
v_2 \cdot n = 2(0) + 1(0) + 0(1) = 0
$$

Because the dot product is zero, the direction vector is orthogonal to the normal, which immediately indicates parallelism without having to solve an equation. Furthermore, since the starting point $P(0,0,1)$ does not lie on the plane $z=0$, the line is strictly parallel and never intersects.

---
