## This is about a differentiating problem, see details in main box

- posted by: [Patience](https://stackexchange.com/users/-1/14-patience) on 2012-04-08
- tagged: `demand`
- score: 0

I don't see how to get from (9) to (10).

By differentiating wrt wi, I get the beta part, but i don't get the second part. Can someone explain this? Thanks.

![enter image description here][1]


  [1]: http://i.stack.imgur.com/8m54G.png


## Answer 1195

- posted by: [Adam Bailey](https://stackexchange.com/users/-1/719-adam-bailey) on 2012-04-09
- score: 2

I'm going to answer this as a mathematical question as the economic meaning of the variables is unclear without more context.

The second part of the differentiation is an application of the basic rule for differentiating powers: $d(ax^n)/dx  =  nax^{n-1}$

In this case:

$a = q[w_1w_2...w_m]^{1/m}$ where the product in square brackets includes all the w's ***except*** $w_i$.

$x = w_i$

$n = 1/m$

Differentiation of $w_i^{1/m}$ with respect to $w_i$ yields $(1/m)w_i^{(1/m)-1}$ which equals $w_i^{1/m}/mw_i$.

When this is multiplied by $q[w_1w_2...w_m]^{1/m}$, the $w_i$ term in the numerator can be included in the product in the square brackets producing the full set of w's $w_1$ to $w_m$.  Hence the differential can be expressed as $(q/mw_i)[w_1w_2...w_m]^{1/m}$.





---

All content is licensed under [CC BY-SA 3.0](https://creativecommons.org/licenses/by-sa/3.0/).
