## Quantity discount model anomaly

- posted by: [Andrey Adamovich](https://stackexchange.com/users/-1/618-andrey-adamovich) on 2012-01-24
- tagged: `microeconomics`, `price`, `models`
- score: 1

I have discovered a weird anomaly when defining quantity based discounts for a training course based on number of students.

 - For less than 5 students we charge $200 per student per day 
 - For 5 and less than 50 there is 5% discount per student per day 
 - For 50 and less than 100 there is 8% discount per student per day 
 - For 100 or more there is 10% discount per student per day

My problem is that for 49 students we get `($200*95%)*49 = $9310`, but for 50 students we get `($200*92%)*50 = $9200`. And that's a bit unlogical, because we theoritically spend more effort to teach 50 students than 49, but discount model puts it differently. Same problem appears for 99 and 100 students.

I have tried different student numbers, more discount levels and different discount persentages, but the problem appears at some point anyway.

Any conditions or other models that can be used here to avoid this anomaly?


## Answer 880

- posted by: [EnergyNumbers](https://stackexchange.com/users/-1/104-energynumbers) on 2012-01-24
- score: 1

Yes, there are other models that avoid this anomaly, and I set out one at the bottom of this answer.

However, first some notes about such anomalies, which aren't unusual. Nor are they deal-breakers - plenty of successful commercial operators offer this sort of staggered discount scheme without harm.

There are a couple of potential advantages to a company that offers them:

1) they're relatively easy to understand; and that increases sales.

2) Particularly astute people who spot the anomalies feel that they can get one over the company by ordering just above the threshold. But once they've psychologically broken that threshold, they may go higher still. c.f. the seemingly illogical pricing of some web & print publications, that offer, say, web-only subscription £50, print-only subscription £150, web & print subscription £150. Now, that seems illogical, right? Why would anyone go for a print-only subscription at £150 when they can get web & print for the same price? Well, for the publisher, this is a pricing trick, that converts **web** sales into web & print sales, boosting their revenue: people spot the anomaly, and change their preference from a web-only subscription to a web & print one, because they feel that the "illogical" pricing gives them extra value.


Still, that's just a couple of reasons why seemingly-illogical pricing structures can be a desirable thing.

There are indeed discount structures that remove such anomalies. Here's one - it doesn't try to match the discount curve outlined in the question as closely as possible, but it's not far off:

For any given block-order of students:

 - first five students named pay $200
 - the next 45 students named pay $190
 - the next 100 students named pay $185
 - all students named thereafter pay $180

But that's more complex, and it looks unfair; and those are two potential deterrents to a potential purchaser.



---

All content is licensed under [CC BY-SA 3.0](https://creativecommons.org/licenses/by-sa/3.0/).
