## OLS regressions and total derivative of y

- posted by: [ben](https://stackexchange.com/users/-1/524-ben) on 2011-12-25
- tagged: `econometrics`
- score: 1

I was taught that in an OLS regression

$$y=\beta_0+\beta_1x_1+\beta_2x_2+...+\varepsilon$$

the $\beta$'s are the marginal effects of the respective $x$'s on $y$

In other words, the equation could be rewritten as the total derivative of $y$:

$$dy=\frac{dy}{dx_0}dx_0+\frac{dy}{dx_1}dx_1+\frac{dy}{dx_2}dx_2+...+\varepsilon$$

My question is do I have this right or did I misunderstand something?


Thanks


## Answer 790

- posted by: [Jason B](https://stackexchange.com/users/-1/26-jason-b) on 2011-12-29
- score: 2

I'm not entirely sure what you're asking.  You cannot "rewrite" the equation you've specified as a total derivative (in the sense that total derivative is not the equivalent of the OLS equation).

If you just want the total derivative of the "true" model, you're close.  It is (for k variables):

$$dy=\sum_{i=1}^{k}\frac{\partial y}{\partial x_i}dx_i\equiv\sum_{i=1}^{k}\beta_idx_i$$

 - There is no $x_0$, so it doesn't make sense to take it's derivative. Or, if you prefer, it is assumed constant in the specification you've written.
 - If you are interested in the fitted model, $d\hat{y}=\sum_{i=1}^{k}\hat{\beta_i}dx_i$.  If the OLS assumptions hold, $E[\varepsilon x]=0$.  If this doesn't hold (e.g. if $E[\varepsilon_j]\neq E[\varepsilon_m]\forall$ observations $j,m$), then there could be complex interactions between y and $\varepsilon$ (as in models that need autoregressive terms), but I don't think that's what you are after.




---

All content is licensed under [CC BY-SA 3.0](https://creativecommons.org/licenses/by-sa/3.0/).
