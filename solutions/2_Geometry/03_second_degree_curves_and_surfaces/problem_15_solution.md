### Exercise 15. Recognition and Sketch Without a Given Name

Consider the two equations:

$$4x^2+9y^2-8x+36y+4=0,$$

$$4x^2+y^2=z^2.$$

For the first equation, reduce it to canonical form, recognize the curve, give its most important features, and make a sketch.

For the second equation, do not begin by using a ready-made name for the surface. First describe the cross-sections $z=c$ and the cross-sections by the planes $x=0$ and $y=0$, paying attention to the different scales along the axes. Only then identify the surface and make a sketch.

#### Solution 15

**Part 1:** $4x^2+9y^2-8x+36y+4=0$

Complete the square:

$$\begin{aligned} 4(x^2-2x) + 9(y^2+4y) &= -4 \\ 4((x-1)^2 - 1) + 9((y+2)^2 - 4) &= -4 \\ 4(x-1)^2 + 9(y+2)^2 &= 36 \end{aligned}$$

Divide by $36$:

$$\frac{(x-1)^2}{9} + \frac{(y+2)^2}{4} = 1$$

- **Curve type:** Ellipse.
- **Center:** $(1,-2)$.
- **Semiaxes:** $a=3$ along $x$, $b=2$ along $y$.
- **Vertices:** $(-2,-2)$, $(4,-2)$, $(1,-4)$, and $(1,0)$.

```text
            y
            ^
            | (1,0)
    --------+--+--------+---> x
            |  1        4
     (-2,-2)|   (1,-2)
       (----+---*-------+ )
            |   | (4,-2)
            | (1,-4)
```

**Part 2:** $4x^2+y^2=z^2$

- **Cross-sections $z=c$:**
  - $c=0$: $4x^2+y^2=0$, giving the single point $(0,0,0)$.
  - $c \neq 0$: dividing by $c^2$ yields

$$\frac{x^2}{(c/2)^2} + \frac{y^2}{c^2} = 1$$

Each cross-section is an ellipse centered at $(0,0,c)$ with semiaxis $\frac{\vert{}c\vert{}}{2}$ along $x$ and $\vert{}c\vert{}$ along $y$ (stretched twice as much along $y$ as along $x$).
- **Cross-section $x=0$:** $y^2=z^2 \iff z = \pm y$ (two intersecting lines with slopes $\pm 1$).
- **Cross-section $y=0$:** $4x^2=z^2 \iff z = \pm 2x$ (two steeper intersecting lines with slopes $\pm 2$).
- **Identification:** Because the horizontal cross-sections are ellipses whose dimensions scale linearly with $\vert{}z\vert{}$ and the vertical cross-sections through the $z$-axis are pairs of intersecting lines, the surface is an **elliptic cone** with vertex at $(0,0,0)$ and axis along the $z$-axis.

```text
             z
             ^
         \   |   /   z = +/- y (wider in y)
          \  |  /    z = +/- 2x (narrower in x)
           \ | /
            \|/
            /|\
           / | \
          /  |  \
         /   |   \
```
