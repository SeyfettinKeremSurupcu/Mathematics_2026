### Exercise 15. Comparing Directions Using the Cosine of the Angle

Given:

$$
a=(1,2,1), \qquad b=(2,4,2), \qquad c=(2,0,3)
$$

For each pair, compute the formula:

$$
\frac{u\cdot v}{\|u\|\,\|v\|}
$$

Order the pairs by increasing angle between the vectors. Explain why for $a$ and $b$ the value is $1$ even though the vectors have different lengths.

**Answer 15**

Cosine calculations:

Pair $a$ and $b$:

$$
\frac{1(2)+2(4)+1(2)}{\sqrt{1+4+1}\sqrt{4+16+4}} = \frac{12}{\sqrt{6}\sqrt{24}} = \frac{12}{12} = 1
$$

Pair $a$ and $c$:

$$
\frac{1(2)+2(0)+1(3)}{\sqrt{6}\sqrt{4+0+9}} = \frac{5}{\sqrt{6}\sqrt{13}} = \frac{5}{\sqrt{78}} \approx 0.566
$$

Pair $b$ and $c$:

$$
\frac{2(2)+4(0)+2(3)}{\sqrt{24}\sqrt{13}} = \frac{10}{2\sqrt{78}} = \frac{5}{\sqrt{78}} \approx 0.566
$$

**Ordering (by increasing angle):** As the cosine value decreases, the angle increases. Therefore, the smallest angle is between $(a,b)$. Next are the $(a,c)$ and $(b,c)$ pairs (the angles for these two pairs are exactly equal).

**Explanation:** The result for $a$ and $b$ is $1$ because $b = 2a$. If two vectors point in exactly the same direction, the angle between them is $0^\circ$ ($\cos(0)=1$). In the angle formula, the lengths of the vectors in the denominator exactly cancel out the coefficient scaling in the numerator, so vector length has no effect on the calculation of the angle.
