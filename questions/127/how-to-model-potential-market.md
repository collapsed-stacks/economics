## How to model potential market?

- posted by: [mpiktas](https://stackexchange.com/users/-1/95-mpiktas) on 2011-10-13
- tagged: `models`, `markets`
- score: 1

Suppose you have the data on volume sales of existing product, or volume sales of all products in one particular market. Take for example sales of shampoo of some particular brand and sales of all brands of shampoo. The question which a firm selling particular product would find interesting is what is a potential market for the product. The most simple understanding of potential market is how much more can you sell if "nobody holds you back". Suppose you want to put a number to this concept? How should one proceed?

My own idea is to develop a model for existing sales, say `y=f(X)`, where `y` are the sales of the product and `X` are the factors determining the sales. Then I would determine potential market via Monte-Carlo simulation. This means assuming some distribution for `X` and looking at the resulting distribution for `y`. Potential market could be say 95%'th quantile.

Will this idea work? Did anybody already tried it? What should be correct way to address this problem?


## Answer 132

- posted by: [Turukawa](https://stackexchange.com/users/-1/48-turukawa) on 2011-10-13
- score: 1

<p>Monte-Carlo simulation would be useful if you had some decision model on how individual consumers may make a purchasing decision.  Alternatives are related to <a href="http://en.wikipedia.org/wiki/Regression_analysis" rel="nofollow">Regression Analysis</a>.</p>

<p>I tend to use Ordinary Least Squares, selecting exogenous (independent) data series which can be used to model that "nobody holds you back" scenario.  For something like shampoo, you might use (at the highest level) GDP/capita and population growth (with an age profile) and then you can tighten it up with proxy data which may be of use (depending on what local statistics are available).</p>

<p>An alternative is nonparametric <a href="http://en.wikipedia.org/wiki/Vector_autoregression" rel="nofollow">Vector autoregression</a>, "used to capture the linear interdependencies among multiple time series" and is the approach that won Christopher Sims his economics gong in 2011. Bayesian VAR will take this model even further. However, all of this depends on the quality and consistency of the data you wish to apply.</p>

<p>You can model this in <a href="http://www.r-project.org/" rel="nofollow">R</a> (a purely statistics package) and I use <a href="http://numpy.scipy.org/" rel="nofollow">numpy</a> in Python.</p>



## Answer 522

- posted by: [Zermelo](https://stackexchange.com/users/-1/68-zermelo) on 2011-11-12
- score: 1

Usually **multinomial logit/probit** models are used to simulate situations where the demand for two or more products is related. Using this approach, you would have to posit a relationship between your new product and existing products in the market (from example, shampoos A and B are close substitutes, shampoo A and conditioner B are weak complements, etc.) and then use data on the demand for existing products to predict demand for the new product.


## Answer 523

- posted by: [Owe Jessen](https://stackexchange.com/users/-1/81-owe-jessen) on 2011-11-12
- score: 1

I tried something similar for the speed of adaption in a market with network effects, and got believable results. The problem was a lack of real world data to calibrate the model to. As Turukawa said, the crucial point is modeling the decision process of the agents. 

I think the problem in your case would be to identify and quantify relevant factors, for which you might want to look at the logit/probit approach mentioned above. 



---

All content is licensed under [CC BY-SA 3.0](https://creativecommons.org/licenses/by-sa/3.0/).
