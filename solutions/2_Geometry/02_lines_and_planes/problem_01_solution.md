### Exercise 1. Line Through Two Points

Find the equation of the line through $A=(1,2)$ and $B=(4,-1)$ in parametric and general form. Identify a direction vector and an example of a normal vector. Check that both points satisfy the equation you obtain.

> **Why this exercise:** teaches how to move between equivalent descriptions of a line and connect them with the appropriate vectors.

**Answer 1**

First, construct a direction vector $v$ by subtracting the coordinates of $A$ from $B$:

$$
v = B - A = (4-1, -1-2) = (3, -3)
$$

We can scale this vector to $(1,-1)$ for simplicity. Using $A$ as the base point, the parametric form is:

$$
(x,y) = (1,2) + t(1,-1)
$$

To find a normal vector $n$, it must be perpendicular to the direction vector $(1,-1)$. A simple choice is $n=(1,1)$ since the dot product is $1(1) + 1(-1) = 0$.

The general equation of the line takes the form $Ax + By + C = 0$. Using the normal vector $(1,1)$ and point $A(1,2)$:

$$
\begin{aligned}
1(x-1) + 1(y-2) &= 0 \\
x + y - 3 &= 0
\end{aligned}
$$

Verification for point $A(1,2)$:

$$
1 + 2 - 3 = 0
$$

Verification for point $B(4,-1)$:

$$
4 - 1 - 3 = 0
$$

Both points satisfy the general equation.

---
