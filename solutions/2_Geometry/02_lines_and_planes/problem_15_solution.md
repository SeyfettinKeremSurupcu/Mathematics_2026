### Exercise 15. Complete Classification of a Line Relative to a Plane

Let

$$
L:p+tv, \qquad \Pi:n\cdot x=d.
$$

State the conditions distinguishing the three cases: one intersection point, parallel with no common points, and the line contained in the plane. Then illustrate each case with your own simple numerical example.

> **Why this exercise:** requires formulating a general mathematical criterion instead of carrying out one isolated calculation.

**Answer 15**

**Case 1: One intersection point**
Condition: $n \cdot v \neq 0$ (the line direction is not perpendicular to the plane's normal).
Example: $L:(x,y,z) = (0,0,0) + t(0,0,1)$ and $\Pi: z=1$. 
The line travels along the z-axis and pierces the plane at exactly $(0,0,1)$.

**Case 2: Parallel with no common points**
Condition: $n \cdot v = 0$ AND $n \cdot p \neq d$ (the direction is parallel, but the anchor point is outside the plane).
Example: $L:(x,y,z) = (0,0,1) + t(1,0,0)$ and $\Pi: z=0$. 
The line travels along the x-axis, elevated at $z=1$, and will never touch the flat $z=0$ plane beneath it.

**Case 3: Line contained in the plane**
Condition: $n \cdot v = 0$ AND $n \cdot p = d$ (the direction is parallel, and the anchor point rests inside the plane).
Example: $L:(x,y,z) = (0,0,0) + t(1,0,0)$ and $\Pi: z=0$. 
The line begins at the origin (which is on the $z=0$ plane) and moves exclusively along the x-axis, remaining entirely within the plane.
