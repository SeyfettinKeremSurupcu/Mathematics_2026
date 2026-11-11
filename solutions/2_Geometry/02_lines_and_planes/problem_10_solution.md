### Exercise 10. Projection of a Point onto a Plane

Find the orthogonal projection of $P=(2,1,3)$ onto the plane $x+y+z=3$, and then find the reflection of $P$ across this plane. Check that the midpoint of the segment joining the point and its reflection lies on the plane.

> **Why this exercise:** combines the normal, intersection, and distance into the construction of a projection and reflection.

**Answer 10**

The plane has normal vector $n=(1,1,1)$. A line passing through $P$ and perpendicular to the plane uses this normal as its direction vector:

$$
L:(x,y,z) = (2+t, 1+t, 3+t)
$$

Find the intersection of this line with the plane to get the projection point $P'$:

$$
\begin{aligned}
(2+t) + (1+t) + (3+t) &= 3 \\
6 + 3t &= 3 \\
3t &= -3 \\
t &= -1
\end{aligned}
$$

The orthogonal projection $P'$ is evaluated at $t=-1$:

$$
P' = (2-1, 1-1, 3-1) = (1,0,2)
$$

The reflection $P''$ requires traveling twice the distance along the normal, which corresponds to $t=-2$:

$$
P'' = (2-2, 1-2, 3-2) = (0,-1,1)
$$

Verification: The midpoint $M$ between $P(2,1,3)$ and $P''(0,-1,1)$ is:

$$
M = \left(\frac{2+0}{2}, \frac{1-1}{2}, \frac{3+1}{2}\right) = (1,0,2)
$$

This midpoint is exactly the projection point $P'$, and substituting it into the plane equation ($1+0+2=3$) confirms it lies perfectly on the plane.

---
