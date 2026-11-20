### Exercise 11. Decomposition into Parallel and Perpendicular Components

Decompose $u=(3,4)$ into components parallel and perpendicular to $v=(1,2)$. Check $u=u_{\parallel}+u_{\perp}$ and $u_{\perp}\cdot v=0$. Explain why these are two independent checks of correctness.

**Answer 11**

Parallel component:

$$
u_{\parallel} = \mathrm{proj}_v\,u = \frac{3+8}{1+4}(1,2) = \frac{11}{5}(1,2) = \left(\frac{11}{5}, \frac{22}{5}\right)
$$

Perpendicular component:

$$
u_{\perp} = u - u_{\parallel} = (3,4) - \left(\frac{11}{5}, \frac{22}{5}\right) = \left(\frac{4}{5}, -\frac{2}{5}\right)
$$

Check 1 (Sum):

$$
u_{\parallel} + u_{\perp} = \left(\frac{11+4}{5}, \frac{22-2}{5}\right) = (3,4) = u
$$

Check 2 (Perpendicularity):

$$
u_{\perp}\cdot v = \left(\frac{4}{5}\right)(1) + \left(-\frac{2}{5}\right)(2) = \frac{4}{5} - \frac{4}{5} = 0
$$

**Explanation:** The first equality guarantees that no information is lost during the decomposition process, while the second equality tests whether the separated part truly satisfies the required geometric condition (perpendicularity).

---
