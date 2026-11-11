### Exercise 13. Closest Point on a Plane

Find the point on the plane $x+2y+2z=4$ closest to $P=(3,0,0)$. Give the distance and check that the segment joining the two points is perpendicular to the plane.

> **Why this exercise:** combines projection, distance, and the normal direction in one problem.

**Answer 13**

The plane's normal vector is $n=(1,2,2)$. The line passing through $P$ perpendicular to the plane is:

$$
(x,y,z) = (3+t, 2t, 2t)
$$

Substitute this into the plane equation to find the closest point $P'$:

$$
\begin{aligned}
(3+t) + 2(2t) + 2(2t) &= 4 \\
3 + 9t &= 4 \\
9t &= 1 \\
t &= \frac{1}{9}
\end{aligned}
$$

Evaluating at $t=\frac{1}{9}$ yields the closest point $P'$:

$$
P' = \left(3+\frac{1}{9}, \frac{2}{9}, \frac{2}{9}\right) = \left(\frac{28}{9}, \frac{2}{9}, \frac{2}{9}\right)
$$

Distance between $P$ and $P'$:

$$
d = \sqrt{\left(\frac{28}{9} - 3\right)^2 + \left(\frac{2}{9} - 0\right)^2 + \left(\frac{2}{9} - 0\right)^2} = \sqrt{\frac{1}{81} + \frac{4}{81} + \frac{4}{81}} = \sqrt{\frac{9}{81}} = \frac{3}{9} = \frac{1}{3}
$$

Verification of perpendicularity:
The segment vector is $P' - P = \left(\frac{1}{9}, \frac{2}{9}, \frac{2}{9}\right)$. This vector equals $\frac{1}{9}(1,2,2)$, which is a direct scalar multiple of the plane's normal vector $n$, proving it is perpendicular to the plane.

---
