### Exercise 12. A Normal Vector to a Plane

Given $A=(1,0,2)$, $B=(2,1,0)$, and $C=(0,3,1)$. Construct two vectors lying in the plane, find a vector perpendicular to both, and check the perpendicularity using dot products.

**Answer 12**

Vectors within the plane:

$$
\begin{aligned}
\overrightarrow{AB} &= (1,1,-2) \\
\overrightarrow{AC} &= (-1,3,-1)
\end{aligned}
$$

Normal vector ($n$):

$$
n = \overrightarrow{AB}\times\overrightarrow{AC} =
\begin{pmatrix}
i & j & k \\
1 & 1 & -2 \\
-1 & 3 & -1 \\
\end{pmatrix}
= i(-1+6) - j(-1-2) + k(3+1) = (5, 3, 4)
$$

Verification (dot product check):

$$
\begin{aligned}
(5,3,4)\cdot(1,1,-2) &= 5+3-8 = 0 \\
(5,3,4)\cdot(-1,3,-1) &= -5+9-4 = 0
\end{aligned}
$$

---
