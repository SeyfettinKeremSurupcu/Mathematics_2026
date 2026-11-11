### Exercise 6. Angle Between Planes

Given

$$
\Pi_1:x+y+z=1, \qquad \Pi_2:x-y=2.
$$

First use the normal vectors to decide whether the planes are parallel. If not, compute the angle between them and explain why the normal vectors alone are enough for this calculation.

> **Why this exercise:** focuses attention on one mechanism—using normals to analyze position and angle—without also introducing the construction of the intersection line.

**Answer 6**

The normal vectors are:

$$
\begin{aligned}
n_1 &= (1,1,1) \\
n_2 &= (1,-1,0)
\end{aligned}
$$

The planes are not parallel because $n_1$ is not a scalar multiple of $n_2$. 

The angle $\theta$ between the planes is given by the cosine formula:

$$
\cos\theta = \frac{|n_1 \cdot n_2|}{\|n_1\|\,\|n_2\|} = \frac{|1(1) + 1(-1) + 1(0)|}{\sqrt{1^2+1^2+1^2} \sqrt{1^2+(-1)^2+0^2}} = \frac{0}{\sqrt{3}\sqrt{2}} = 0
$$

Since $\cos\theta = 0$, the angle is $90^\circ$ (or $\frac{\pi}{2}$ radians). 

**Explanation:** The angle between two planes in space is exactly equal to the acute angle between their normal vectors. The normals entirely define the orientation of the planes, making the lines of intersection and specific coordinate points unnecessary for determining the angular relationship.

---
