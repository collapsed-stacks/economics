## Long Run Average cost and equality between Short Run MC and Long Run MC

- posted by: [InterestedGuest](https://stackexchange.com/users/-1/171-interestedguest) on 2011-10-25
- tagged: `cost-curves`
- score: 4

I am working through my book for intermediate micro theory, and I am puzzled by the picture below: ![LAC curve][1]


  [1]: http://s16.radikal.ru/i191/1110/5e/4e1bd8a6aee4.jpg

ATC=Average Total Cost, SMC = Short Run Marginal Cost, LMC = Long Run Marginal Cost.

Author calls the LAC an "envelope" of individual ATCs -- presumably one plots many ATC curves and then pulls a string to mold the outside contour. The author also states that at the quantities of tangencies between ATCs and LAC, SMC equals to LMC. So my two questions are:

1) What quite does LAC represent? For each $Q_i$, does it show the optimal capital/labor combo (since capital can be varied) and thus the lowest price?

2) Why is it the case that at the quantities of tangency between ATCs and LAC, SMC = LMC? This is what I know of LMC and SMC -- SMC is the slope of the short run total cost curve at a given point, while LMC is the slope of the long run total cost curve at a given point. To get the total cost from an average cost graph, we jut multiply by $Q;$ at the points of tangencies between LAC and ATC, thus total costs are the same. But is this sufficient to imply that the derivatives of total cost curves (short and long run) at this point are equal, and that thus SMC and LMC at this point are equal?


## Answer 316

- posted by: [Jason B](https://stackexchange.com/users/-1/26-jason-b) on 2011-10-25
- score: 4

Think of the LAC curve as an average cost curve for a single firm in the long run.  Now, the individual ATC curves are short run average cost curves for different levels of output.  

Firms are more constrained in the short run, so therefore may be forced to produce a non-optimal output. For any given level of output, the lowest possible cost is that which is achievable in the long run. So, to produce $Q_1$ in the short run, the firm will find itself on $ATC_1$.  The lowest possible (minimum) average cost in the short run provides one point on the long run curve.

Given an infinity of output quantities, we can trace a continuous LAC curve by tracing these minimum points on the ATC curves (only three such points are shown in the chart).  So, LAC is showing the lowest cost for each level of output, not input ratios.

To see why the LRMC curve intersects LAC at it's minimum, consider that $LAC = C(Q)/Q$ so that at its minimum we have (by taking the derivative and setting it equal to zero): $$C'(Q)/Q=C(Q)/Q^2 \implies C'(Q)=C(Q)/Q ~ or ~ MC=AC$$

This leaves a final question:  why don't the individual SMC curves intersect the corresponding ATC curves at their minimums?  I assume the idea is that at least one input is fixed in the short run.  Then,

$$TC=C(Q)+F ~
so ~ that ~MC=C'(Q) ~ and ~ AC=C(Q)/Q+F/Q.
Then, ~ SMC=C'(Q)$$
and we don't have the long-run equivalence of MC and AC at the optimal point.  Finding the intersection of an SMC curve with its corresponding ATC curve, we have:  $$C'(Q)=C(Q)/Q+F/Q \implies MC=AC+F \implies MC-F=AC$$ so that the SMC curves do not fall on the minimum of the corresponding ATC curves.



---

All content is licensed under [CC BY-SA 3.0](https://creativecommons.org/licenses/by-sa/3.0/).
