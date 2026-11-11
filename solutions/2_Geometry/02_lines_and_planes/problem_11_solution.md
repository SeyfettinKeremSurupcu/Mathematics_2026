### Exercise 11. Plane Containing a Line and a Point

Find the equation of the plane containing

$$
(x,y,z)=(1,0,2)+t(1,1,-1)
$$

and the point $P=(0,2,1)$. Check that both the entire line and the point lie in the plane you obtain.

> **Why this exercise:** requires independently constructing two linearly independent directions in the plane.

**Answer 11**

From the line, we have an anchor point $P_0=(1,0,2)$ and a direction vector $v_1=(1,1,-1)$. 
A second direction vector $v_2$ can be formed from $P_0$ to $P$:

$$
v_2 = P - P_0 = (0-1, 2-0, 1-2) = (-1, 2, -1)
$$

The normal vector to the plane is the cross product of $v_1$ and $v_2$:

$$
n = v_1 \times v_2 =
\begin{pmatrix}
1(-1) - (-1)2 \\
(-1)(-1) - 1(-1) \\
1(2) - 1(-1) \\
\end{pmatrix}
= (1, 2, 3)
$$

Using $P=(0,2,1)$ and normal $n=(1,2,3)$, the plane equation is:

$$
\begin{aligned}
1(x-0) + 2(y-2) + 3(z-1) &= 0 \\
x + 2y + 3z - 7 &= 0
\end{aligned}
$$

Verification for point $P(0,2,1)$:

$$
0 + 2(2) + 3(1) - 7 = 0
$$

Verification for the line by substituting its parametric variables:

$$
\begin{aligned}
(1+t) + 2(t) + 3(2-t) - 7 &= 0 \\
1 + t + 2t + 6 - 3t - 7 &= 0 \\
(1+6-7) + (t+2t-3t) &= 0 \\
0 &= 0
\end{aligned}
$$

---
