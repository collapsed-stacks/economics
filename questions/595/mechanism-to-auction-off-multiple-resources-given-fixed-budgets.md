## Mechanism to auction off multiple resources given fixed budgets

- posted by: [Andrew Cone](https://stackexchange.com/users/-1/416-andrew-cone) on 2011-11-20
- tagged: `game-theory`, `price`, `optimization`, `auctions`, `mechanism-design`
- score: 5

I am trying to sell ad time on a screen to a bunch of advertisers. The advertisers tell me (or a salesperson keys in) how much a given advertiser is willing to pay for time in a one hour block. Each one hour block may be subdivided arbitrarily among multiple advertisers.

To formalize, the inputs are:

 - A set of advertisers $a_i$, with their maximum budgets $D_i$ (positive integers or reals, whichever makes it easier)
 - For each advertiser $a$, for each hour $h$ in the upcoming month, an amount $d_{a,h}$ that $a$ is willing to pay **per hour** for time during $h$. So $a$ might pay $\frac{d_{a,h}}2$ for 30 minutes of $h$, or $\frac{d_{a,h}}3$ for 20 minutes of $h$.

The output I would like is a list of tuples $(i, h, t, p)$, which tells me that the $i$th advertiser should get $t \in [0,1]$ share of hour $h$, for which they should pay a per-hour rate of $p$.

 - Exhausts every advertiser's budget. For marketing reasons beyond the scope of mechanism design, that is actually important.
 - Given that constraint, maximizes my revenue. For this purpose we can consider my costs 0, so this is equivalent to maximizing profit.


What is the appropriate mechanism for this? Is there a way to get the output I want by solving some sort of LP, QP, or other convex optimization problem? I have no training in economics or optimization, just a bachelors' in computer science, so please go easy on me :-).

 

## No Answers

There were no answers to this question.


---

All content is licensed under [CC BY-SA 3.0](https://creativecommons.org/licenses/by-sa/3.0/).
