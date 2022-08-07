## Notes  
Foundations of Sports Analytics
---

#### Week 1:  
**Pythagorian Expectation**: *wpc = T<sub>F</sub><sup>2</sup> / ( T<sub>F</sub><sup>2</sup> + T<sub>A</sub><sup>2</sup> )*  
The percentage of games won will be proportional to the square of total runs/points/goals scored by the team *squared* **divided** by the sum of total runs/points/goals scored by the team *squared* plus total runs/points/goals conceded by the team *squared*.  
**_Case of basketball_**: only need points scored and points conceded.

**Standard error**:  
Gives an idea of the precision of the estimate.

**t statistic**: *coef / std_err*  
Statistical significance

**p-value**: *P > |t|*  
Probability that we would observe *coef* by chance, if the true value was actually 0.  
By convention, cannot be confident that value of *coef* is **not** zero if p-value > 0.05.

**R-squared**:  
Percentage of variation in the y-variables which can be accounted by the variation in x-variables.  
_eg._ if R-squared = 0.894, Pythagorean Expectation can account for 89.4% of the variation in win percentage.
