## How do models account for the existence of long-term and short-term utility functions?

- posted by: [Lev](https://stackexchange.com/users/-1/131-lev) on 2011-10-13
- tagged: `utility-function`
- score: 4

In the usual models, every person has a utility function and tries to maximize it.

Do any models account for the existence of different long- and short-term utility functions? For example, if I get drunk today, I'll increase my short-term utility function (feel good), but reduce my longer-term utility function (hangover next morning).

Or is the single utility function a weighted average of functions for different "terms"?


## Answer 152

- posted by: [Zermelo](https://stackexchange.com/users/-1/68-zermelo) on 2011-10-14
- score: 1

It might help to look for "time inconsistent preferences". Covers topics like addiction, procrastination. On the latter, the classic reference is "Procrastination and Obedience" by Akerlof in the American Economic Review.


## Answer 201

- posted by: [Paul Dexter](https://stackexchange.com/users/-1/152-paul-dexter) on 2011-10-15
- score: 1

[Discounted utility](http://en.wikipedia.org/wiki/Discounted_utility) is the usual way of modeling utility that is summed over time.  For example, assume tomorrow's utility should only be considered 90% as important as today's utility ([discount factor](http://en.wikipedia.org/wiki/Discount_factor) β=0.9), and the next day's utility should be considered 90% x 90% = 81% as important as today's utility, so that the sum over time is:

    U = ∑ β^t u(t)

For a more complex model, you could replace `β^t` by a [more precise function](http://en.wikipedia.org/wiki/Hyperbolic_discounting) reflecting people's actual preferences today for particular outcomes in the future.  On the other hand, [many economic models](http://www.google.com/search?q=two+stage+game+model) take a simpler approach by using only two time periods, ie `U = u(t=0)+βu(t=1)`.


## Answer 151

- posted by: [Sylvain Peyronnet](https://stackexchange.com/users/-1/82-sylvain-peyronnet) on 2011-10-13
- score: 0

It is addiction centered (the utility of a specific good at time t, depends on the comsumption of this good at previous times) but here is a reference : http://www.drugtext.org/Economics/a-theory-of-rational-addiction.html

Even if this is not exactly the kind of model you are asking for, something similar should to it to model long/short term utility.





---

All content is licensed under [CC BY-SA 3.0](https://creativecommons.org/licenses/by-sa/3.0/).
