## Difference-in-difference estimator (panel data)

- posted by: [icobes123](https://stackexchange.com/users/-1/756-icobes123) on 2012-03-08
- tagged: `econometrics`, `homework`
- score: 1

Let's say we have two cities A and B. A increases spending on education to the point where earning levels increase to \$30,000 from \$20,000. Let's say B doesn't make any changes to spending and earning levels increase to \$25,000 from \$20,000. How could we use a difference-in-difference estimator to determine if City A's spending caused earnings to increase? Also, what are some assumptions that must be true for these results to be valid?

Thanks for the help! 


## Answer 1083

- posted by: [Dimitriy V. Masterov](https://stackexchange.com/users/-1/407-dimitriy-v-masterov) on 2012-03-09
- score: 1

You would calculate change for the treated group less the change for the untreated group: (30-20)-(25-20)=5K. You are assuming that in the absence of treatment (investment in education), city A would have experienced the same increase in wages as B of 5K. 


## Answer 1202

- posted by: [o.k.](https://stackexchange.com/users/-1/861-o-k) on 2012-04-10
- score: 1

<p>Usually just providing a Wikipedia link is not very helpful, but in your case, Wikipedia is just what you are looking for: <a href="http://en.wikipedia.org/wiki/Difference_in_differences" rel="nofollow">Difference in differences in Wikipedia</a>. </p>

<p>Loosely speaking, the identifying assumption in DID is that in absence of treatment, the change in outcome for the treated group would correspond to the change in outcome for the non-treated group. </p>




---

All content is licensed under [CC BY-SA 3.0](https://creativecommons.org/licenses/by-sa/3.0/).
