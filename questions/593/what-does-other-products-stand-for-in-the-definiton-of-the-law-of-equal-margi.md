## What does 'Other products' stand for in the definiton of 'The law of equal marginal utilities'?

- posted by: [pencilCake](https://stackexchange.com/users/-1/403-pencilcake) on 2011-11-19
- tagged: `utility`, `marginal-utility`
- score: 1

I have seen this definiton of "The law of equal marginal utilities" in the book *The Complete Idiot's Guide To Economics*:

> The law of equal marginal utilities per dollar states that a consumer
> will buy  each product she wants until the marginal utility per dollar
> spent on it is exactly  the same as it is for any other product she
> buys.


I cannot understand what the "for any other product she buys" stands for? What would that 'other product' term mean?



## Answer 594

- posted by: [Jason B](https://stackexchange.com/users/-1/26-jason-b) on 2011-11-19
- score: 3

Suppose we have 2 goods, A and B.  

Consider the consumer's budget constraint, 

$P_A Q_A + P_B Q_B = W$

And the consumer's utility, $U(Q_A, Q_B)$

I want to maximize utility, subject to my budget constraint:

Max $L = U(Q_A, Q_B) + \lambda(W-P_AQ_A + P_BQ_B)$

and the first order conditions for an (interior) optimum are then:

$\partial L/\partial Q_A = U_A - P_A =0$

$\partial L/\partial Q_B = U_B - P_B=0$

$\partial L/\partial \lambda = W = P_AQ_A + P_BQ_B$

Here, $U_A$ is the marginal utility for good A, and $U_B$ is the marginal utility for good B.

So, we have:

$P_A/P_B = U_A/U_B$

Or, the price ratio equals the ratio of marginal utilities.

Rearranging:

$U_A/P_A = U_B/P_B$

**That is, the marginal utility per dollar for good A is equal to the marginal utility per dollar for good B.**

This result generalizes to N goods, so that:

$U_1/P_1 = U_2/P_2 = ... = U_N/P_N$

**That is, at an optimum, the marginal utility per dollar for ANY good is equal to the marginal utility per dollar for any other good.**


## Answer 597

- posted by: [gsk3](https://stackexchange.com/users/-1/21-gsk3) on 2011-11-21
- score: 2

@JasonB has given you the analytical answer for the two-good case, which is awesome.

Since your reference material is at a non-technical level, however, I'll try to give an intuitive understanding.

Suppose the consumer's purchasing decisions were such that Good A's marginal utility per dollar did not equal that of Good B at the quantities consumed.  Further suppose without loss of generality that Good A's MU/$ was higher than Good B's.  Then the consumer could spend one less dollar on Good B and one more dollar on Good A, still balance their budget, and have higher utility.  Therefore, the consumer could not have been at the optimum in the first place.

In other words, it's a bit of a tautology: If the consumer is optimizing (e.g. ensuring that they could not spend their last dollar any differently without reducing their total utility) then the marginal utilities over all goods must be equal.

Diminishing marginal utilities work nicely in this world, as they mean that you won't keep consuming more of Good A until your whole budget is exhausted--at some point the utility will drop below that of other goods and you'll stop spending money on A.

Finally, note that the book's sentence would be more clearly stated "for **every** product."  That takes us into a many-good world, and the results generalize.





---

All content is licensed under [CC BY-SA 3.0](https://creativecommons.org/licenses/by-sa/3.0/).
