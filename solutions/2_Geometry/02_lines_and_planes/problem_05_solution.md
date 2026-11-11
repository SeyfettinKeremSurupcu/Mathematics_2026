### Exercise 5. Relative Position of Two Lines

Analyze the position of

$$
L_1:(x,y,z)=(1,1,0)+t(1,2,1),
$$

$$
L_2:(x,y,z)=(2,0,1)+s(0,1,-1).
$$

If they intersect, give the intersection point. If not, determine whether they are parallel or skew. Justify the classification.

> **Why this exercise:** teaches how to distinguish qualitatively different relationships between lines in space.

**Answer 5**

First, check if the direction vectors $(1,2,1)$ and $(0,1,-1)$ are parallel. They are not scalar multiples of each other, so the lines are not parallel. They must either intersect or be skew.

Set the parametric equations equal to check for an intersection point:

$$
\begin{cases}
1+t = 2, \\
1+2t = s, \\
t = 1-s.
\end{cases}
$$

From the first equation, $t = 1$.
Substitute $t=1$ into the second equation:

$$
1 + 2(1) = s \implies s = 3
$$

Substitute both $t$ and $s$ into the third equation to check for consistency:

$$
1 = 1 - 3 \implies 1 = -2
$$

This is a contradiction. Therefore, the system has no solution, meaning the lines do not intersect. Since they are neither parallel nor intersecting, they are **skew** lines.

---
