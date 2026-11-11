### Exercise 4. Plane Through Three Points

Find the equation of the plane through

$$
A=(1,0,0), \quad B=(0,1,0), \quad C=(0,0,1).
$$

First construct two vectors lying in the plane, and then use the cross product. Check the resulting equation on all three points.

> **Why this exercise:** connects earlier vector tools with constructing the equation of a plane.

**Answer 4**

Construct two vectors lying in the plane:

$$
\begin{aligned}
\overrightarrow{AB} &= B - A = (-1, 1, 0) \\
\overrightarrow{AC} &= C - A = (-1, 0, 1)
\end{aligned}
$$

Compute the normal vector using the cross product:

$$
n = \overrightarrow{AB} \times \overrightarrow{AC} =
\begin{pmatrix}
1(1) - 0(0) \\
0(-1) - (-1)(1) \\
(-1)(0) - 1(-1) \\
\end{pmatrix}
= (1, 1, 1)
$$

Using $A(1,0,0)$ as the point and $n=(1,1,1)$ as the normal vector, the plane equation is:

$$
\begin{aligned}
1(x-1) + 1(y-0) + 1(z-0) &= 0 \\
x + y + z &= 1
\end{aligned}
$$

Verification for all points:
For $A(1,0,0)$: $1+0+0 = 1$
For $B(0,1,0)$: $0+1+0 = 1$
For $C(0,0,1)$: $0+0+1 = 1$

---
