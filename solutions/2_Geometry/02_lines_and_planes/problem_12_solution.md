### Exercise 12. Intersection Line of Two Planes

Find a parametric equation of the line that is the intersection of

$$
x+y+z=3, \qquad x-y+z=1.
$$

Find its direction vector in two ways: from the system of equations and from the cross product of the normal vectors. Compare the results.

> **Why this exercise:** shows the equivalence of the algebraic and geometric approaches to constructing an intersection line.

**Answer 12**

**Method 1: System of Equations**
Add the two equations together:

$$
\begin{aligned}
(x+y+z) + (x-y+z) &= 3 + 1 \\
2x + 2z &= 4 \\
x &= 2 - z
\end{aligned}
$$

Substitute $x = 2 - z$ into the first equation:

$$
\begin{aligned}
(2-z) + y + z &= 3 \\
y + 2 &= 3 \\
y &= 1
\end{aligned}
$$

Letting $z = t$, the parametric equations for the line are:

$$
(x,y,z) = (2-t, 1, t) = (2,1,0) + t(-1,0,1)
$$

The direction vector here is $v_a = (-1,0,1)$.

**Method 2: Cross Product of Normal Vectors**
The normal vectors of the planes are $n_1=(1,1,1)$ and $n_2=(1,-1,1)$. 

$$
v_b = n_1 \times n_2 =
\begin{pmatrix}
1(1) - 1(-1) \\
1(1) - 1(1) \\
1(-1) - 1(1) \\
\end{pmatrix}
= (2, 0, -2)
$$

**Comparison:** The vector $v_b = (2,0,-2)$ is simply a scalar multiple ($-2$ times) of $v_a = (-1,0,1)$. Both represent the exact same line direction in space.

---
