## Calculate a discount rate given a PV at some point in the future

- posted by: [user548084](https://stackexchange.com/users/-1/916-user548084) on 2012-04-25
- tagged: `inflation`, `finance`, `interest`
- score: 0

Repost from CrossValidated and Quantitative Finance...No one thinks this question is on topic for them. Giving Economics a try! 

I am trying to calculate a 24-month Customer Lifetime Value for a hypothetical magazine subscription service. CLV is typically calculated as the summation of the present value of future cash fows from the subscription, so if the subscription costs \$1.00 per month, that is the summation of \$1/(1+r)^n where $r$ is the discount rate and $n$ is the number of periods, taking $n$ from 0...23.

By looking at the data for my subscribers, I see that the actual survival rate is equal to 0.22 at 24 months (or, for a given 100 people who subscribe to my magazine, 22 remain after 24 months).

I want to specify the CLV equation from this data, but I'm not sure how to calculate $r$, given only this data point of 22% remaining after 24 months and the outline of the CLV equation above. $r$ should be the discount rate that gets me to .22 on month 24?

Just to clarify, the discount rate typically includes the cost of capital and\or inflation, but for this example I'm simplifying by assuming that the cost of capital and inflation is 0.

Any assistance would be greatly appreciated...


## Answer 1307

- posted by: [Dimitriy V. Masterov](https://stackexchange.com/users/-1/407-dimitriy-v-masterov) on 2012-04-26
- score: 0

I am not sure why solving that equations makes sense, but both $r=4.5455$ and $r=-1.985$ are possible solutions (non-complex ones). 



---

All content is licensed under [CC BY-SA 3.0](https://creativecommons.org/licenses/by-sa/3.0/).
