## Income Elasticity and Goods?

- posted by: [MathMathCookie](https://stackexchange.com/users/-1/181-mathmathcookie) on 2011-12-06
- tagged: `microeconomics`, `elasticity`
- score: 0

1. What is the correlation between elasticity and calling a good a "luxury" or inferior? Do we need to deal with price-demand or income elasticity?

2. Also, in what case (i.e. income elasticity = o?) can we call a good quasilinear? I recently answered a question in which the demand equation was: $x(p_x,p_y)= (4p_y/p_x)^2$ and asked to find the income elasticity of demand for x. I was a little baffled, but following the definition of income elasticity, I found it to be 0, so I concluded it was quasilinear, was I correct? If so, why?



## Answer 704

- posted by: [Michael Greinecker](https://stackexchange.com/users/-1/397-michael-greinecker) on 2011-12-07
- score: 2

<ol>
<li><p>If demand for a good $i$ can be represented as a function $x_i(\cdot)$ of income for some consumer, we say $i$ is a <em>luxury good</em> if for income levels $0&lt;m\leq m&#39;$, one has $\frac{x_i(m)}{m}\leq\frac{x_i(m&#39;)}{m&#39;}$, that is $\frac{x_i(\cdot)}{\cdot}$ is an increasing function. A sufficient condition for this is that $x_i$ is differentiable and $\bigg(\frac{x_i(m)}{m}\bigg)&#39;&gt;0$ for positive income levels $m$. Applying the quotient rule, this is equivalent to $$\frac{x&#39;_i(m)-mx_i(m)}{m^2}&gt;0$$
$$\frac{x&#39;_i(m)}{m^2}&gt;\frac{x_i(m)}{m}$$
$$\frac{x&#39;_i(m)}{m}&gt;x_i(m)$$
$$x&#39;_i(m)\frac{m}{x_i(m)}&gt;1.$$
The left side of the inequality is simply the income elasticity of demand for good $i$.</p></li>
<li><p>This is a bit more complicated, since quasi-linearity is a property of utility functions or preferences, not demand. Since the demand function you gave does not depend on  income, the income elasticity is indeed $0$. This holds true for quasi-linear utility functions at interior solutions. If you don't allow for $y$ to be negative, there are always boundary solutions for $m$ small enough. </p></li>
</ol>

<p>Another, more demaning question is, is whether preferences giving rise to constant interior demand for a good are quasi-linear (under some regularity conditions). I dont know the answer to this question, I guess one might obtain a positie nswer by using <a href="http://www.esr.ie/Vol34_2Neary.pdf" rel="nofollow">Gorman's theorem</a>.</p>




---

All content is licensed under [CC BY-SA 3.0](https://creativecommons.org/licenses/by-sa/3.0/).
