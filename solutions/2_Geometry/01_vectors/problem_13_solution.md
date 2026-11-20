### Exercise 13. Do Four Points Lie in One Plane?

Given the following points:

$$
A=(0,0,0), \qquad B=(1,2,0), \qquad C=(0,1,1), \qquad D=(2,5,1)
$$

1. Construct $\overrightarrow{AB}$ and $\overrightarrow{AC}$.
2. Find $n=\overrightarrow{AB}\times\overrightarrow{AC}$.
3. Construct $\overrightarrow{AD}$ and check whether $\overrightarrow{AD}\cdot n=0$.
4. Based on this, decide whether $D$ lies in the plane determined by $A,B,C$, and justify the criterion.

**Answer 13**

Vector construction and normal calculation:

$$
\begin{aligned}
\overrightarrow{AB} &= (1,2,0) \\
\overrightarrow{AC} &= (0,1,1)
\end{aligned}
$$

$$
n = \overrightarrow{AB}\times\overrightarrow{AC} = (2-0, 0-1, 1-0) = (2, -1, 1)
$$

Checking the third vector:

$$
\overrightarrow{AD} = (2,5,1)
$$

$$
\overrightarrow{AD}\cdot n = 2(2) + 5(-1) + 1(1) = 4 - 5 + 1 = 0
$$

**Result:** Point $D$ lies on the plane formed by $A,B,C$. Any vector lying on the plane must be exactly perpendicular to the normal vector of that plane. The dot product being zero satisfies this condition.

---
