## How do I show decreasing absolute risk aversion?

- posted by: [Patience](https://stackexchange.com/users/-1/14-patience) on 2011-12-04
- tagged: `risk`
- score: 1

I do not know the specific felicity function, so let it be a general form of u(x). 

Ok, so absolute risk aversion = - $u_x$$_x$ / $u_x$

How can I show that this is decreasing over x?


## Answer 686

- posted by: [Zermelo](https://stackexchange.com/users/-1/68-zermelo) on 2011-12-04
- score: 3

Let $r=-u_{xx}/u_{x}$. You need to show that this is decreasing in $x$, or that $\frac{dr}{dx}<0$. Since $r$ is a function of $u$, this can be further solved out in terms of $u$ by using the chain rule on the expression for $r$.

Of course, not every utility function exhibits decreasing absolute risk aversion, so you'll need to know something more about the utility function to show that $\frac{dr}{dx}<0$ is true.



---

All content is licensed under [CC BY-SA 3.0](https://creativecommons.org/licenses/by-sa/3.0/).
