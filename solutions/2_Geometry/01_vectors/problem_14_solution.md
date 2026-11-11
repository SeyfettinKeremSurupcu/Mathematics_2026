### Exercise 14. Closest Point on a Line

Given a point $P=(4,1)$ and a line through the origin with direction $v=(1,2)$. Using projection, find the closest point on the line, the distance from $P$ to the line, and verify that the appropriate vector is perpendicular to the direction of the line.

**Answer 14**

Closest point (projection):

$$
\mathrm{proj}_v\,P = \frac{(4)(1)+(1)(2)}{1^2+2^2}(1,2) = \frac{6}{5}(1,2) = \left(\frac{6}{5}, \frac{12}{5}\right)
$$

Distance vector ($r$):

$$
r = (4,1) - \left(\frac{6}{5}, \frac{12}{5}\right) = \left(\frac{14}{5}, -\frac{7}{5}\right)
$$

Distance:

$$
\|r\| = \sqrt{\left(\frac{14}{5}\right)^2 + \left(-\frac{7}{5}\right)^2} = \sqrt{\frac{196}{25} + \frac{49}{25}} = \sqrt{\frac{245}{25}} = \frac{7\sqrt{5}}{5}
$$

Verification (perpendicularity):

$$
\left(\frac{14}{5}, -\frac{7}{5}\right)\cdot(1,2) = \frac{14}{5} - \frac{14}{5} = 0
$$

The shortest distance from a point to a line is always measured along a path that is perpendicular to that line.

---
