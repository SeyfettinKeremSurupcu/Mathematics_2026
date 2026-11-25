### Exercise 11. Two Similar Surfaces

Compare

$$x^2+y^2-z^2=1$$

and

$$x^2+y^2-z^2=-1.$$

For several values $z=c$, check whether the cross-section exists and what its radius is. Based on this, describe qualitatively the difference between the surfaces and make sketches.

#### Solution 11

**Surface 1:** $x^2+y^2-z^2=1 \iff x^2+y^2 = 1+c^2$

- $c=0$: circle, $r=1$.
- $c=\pm 1$: circle, $r=\sqrt{2}$.
- $c=\pm 2$: circle, $r=\sqrt{5}$.

Every horizontal plane intersects the surface in a circle. It is a single connected surface (one-sheeted hyperboloid) with minimum radius $1$ at $z=0$.

**Surface 2:** $x^2+y^2-z^2=-1 \iff x^2+y^2 = c^2-1$

- $c=0$: empty ($x^2+y^2=-1$).
- $c=\pm 1$: single point $(0,0,\pm 1)$, $r=0$.
- $c=\pm 2$: circle, $r=\sqrt{3}$.

No points exist for $\vert{}c\vert{}<1$. The surface consists of two disconnected sheets (two-sheeted hyperboloid) in $z \ge 1$ and $z \le -1$.

```text
   One-sheeted (x^2+y^2-z^2 = 1)        Two-sheeted (x^2+y^2-z^2 = -1)

            z                                      z
            ^                                      ^
         \  |  /                                \  |  /
          ) | (                                  \_|_/   z = 1
          | | |   r_min = 1
          ) | (                                   ___    z = -1
         /  |  \                                 / | \
                                                /  |  \
```

---
