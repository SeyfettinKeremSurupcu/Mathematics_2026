### Exercise 6. Shifted Ellipse

Reduce

$$4x^2+9y^2-16x+18y-11=0$$

to canonical form. Give the center and semiaxis lengths. Check that substituting the coordinates of the center into the left-hand side gives a value consistent with the form you obtained.

#### Solution 6

Complete the square:

$$\begin{aligned} 4(x^2-4x) + 9(y^2+2y) &= 11 \\ 4((x-2)^2 - 4) + 9((y+1)^2 - 1) &= 11 \\ 4(x-2)^2 + 9(y+1)^2 &= 36 \end{aligned}$$

Divide by $36$:

$$\frac{(x-2)^2}{9} + \frac{(y+1)^2}{4} = 1$$

- **Center:** $(2,-1)$.
- **Semiaxis lengths:** $a=3$ along $x$, $b=2$ along $y$.
- **Consistency check at $(2,-1)$:**

$$4(2)^2 + 9(-1)^2 - 16(2) + 18(-1) - 11 = 16 + 9 - 32 - 18 - 11 = -36$$

This matches $4(x-2)^2 + 9(y+1)^2 - 36$ evaluated at $(2,-1)$, where both squared terms vanish and leave $-36$.

---
