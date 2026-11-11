### Exercise 7. A Line Relative to a Plane

For

$$
L:(x,y,z)=(1,1,0)+t(1,-1,0), \qquad \Pi:x+y+z=2,
$$

determine whether the line intersects the plane at one point, is parallel to it, or lies in it. Explain the role of the dot product of the direction vector and the normal vector.

> **Why this exercise:** builds a universal test for the relative position of a line and a plane.

**Answer 7**

The line's direction vector is $v=(1,-1,0)$ and the plane's normal vector is $n=(1,1,1)$. 

First, compute their dot product:

$$
v \cdot n = 1(1) + (-1)(1) + 0(1) = 0
$$

Since the dot product is zero, the line is perpendicular to the normal, which means the line is either strictly parallel to the plane or entirely contained within it.

To distinguish between these two cases, test if the line's anchor point $(1,1,0)$ satisfies the plane's equation:

$$
1 + 1 + 0 = 2
$$

The equation holds true. Because the line shares a point with the plane and its direction is completely parallel to the plane, the line **lies entirely within** the plane.

---
