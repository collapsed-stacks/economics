## Land trading model

- posted by: [Erel Segal Halevi](https://stackexchange.com/users/-1/732-erel-segal-halevi) on 2012-03-09
- tagged: `models`
- score: 0

I try to build a model of trading land plots. In my model:

 1. There are N citizens, and N different land plots.
 2. There is some initial division of the plots, for example, each plot belongs to a citizen at random.
 3. Citizens buy and sell land plots in a free market.
 4.  Eventually, I want to get some information about the distribution of lands - how many citizens will have no land? how many citizens will have many land plots? etc.

My question is in part 3: how do I model the buying and selling of land plots? 

Here is what I have so far:

 A. For each land plot and each citizen, I pick at a random number that stands for the subjective utility of that specific land to that specific citizen.

 B. Additionally, for each citizen, I calculate a global utility, that depends only on the number of plots he holds. I assume it is a concave function (such as: 1000*sqrt(num-of-plots)).

 C. The total utility of a citizen is the sum of subjective utilities for all the lands he holds (A), and the utility that depends on the number of plots (B).

 D. In each period, each citizen earns a constant net income. I assume that income and utility have the same units (e.g. both are measured in gold-ounces).

 E. In each period, each citizen picks a land plot at random. He compares his current utility with the utility he will have with this plot. This is the maximum number of gold-ounces he will give for this land.

 F. The current holder of that land also compares his current utility with the utility he will have without this plot. This is the minimum number of gold-ounces he will demand for selling this land.

 G. If E is greater than F, then there is a deal. The price is chosen at random between E and F. The buyer pays the gold-ounces to the seller.

Does this model makes sense?

Can you point me to papers with similar models?

## No Answers

There were no answers to this question.


---

All content is licensed under [CC BY-SA 3.0](https://creativecommons.org/licenses/by-sa/3.0/).
