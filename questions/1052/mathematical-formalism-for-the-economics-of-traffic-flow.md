## Mathematical formalism for the economics of traffic flow

- posted by: [tomasblog](https://stackexchange.com/users/-1/754-tomasblog) on 2012-03-05
- tagged: `theory`, `public-policy`, `models`
- score: 1

Cities often invest large amounts of money to improve traffic circulation (such as widening roads, performing expensive studies, etc.). While it is obvious that cities would perform very poorly economically if their roads were gridlock all the time, is there an accurate mathematical measure for the economic value of traffic flow in a city? When a city decides to perform major construction by either adding or widening roads, how to they quantify the cost/benefit ratio?


## Answer 1066

- posted by: [Mike M](https://stackexchange.com/users/-1/763-mike-m) on 2012-03-08
- score: 3

For a relatively simple approach, you need at least two things: a value-of-time for each individual and a way to calculate the delay that individuals are experiencing.  Now you can make assumptions about these measures to make your model as simple or complicated as you'd like.  To briefly explain how this works (I assume that the improvement will turn a congested roadway into a non-congested roadway):

 1. Calculate the delay of each individual (or aggregate to some degree) in the transportation network.  This is the difference between the non-congested travel time and the actual travel time.
 2. Determine a measure of the time valuation (value-of-time) of individuals (e.g. everyone has same valuation, businesspeople have greater valuation than commuters).
 3. Multiply each individual's delay by her value-of-time.  This gives you a measure of the time-cost of their trip (versus a non-congested trip)
 4. Sum the time-cost across the individuals in the area of interest.

With the total time-cost across the population, you now have the benefit in monetary terms.  To get the cost of the construction, you need to estimate this as well (probably from similar projects or perhaps a government entity has already calculated it).  Compare the construction cost to the total time-cost to determine the cost/benefit ratio.

The accuracy of your approach will depend on your assumptions, but this is the process in a nutshell.  Like a previous poster stated, people write books about the assumptions you could use and methods to use (Look at literature in transportation planning and travel demand modeling).


## Answer 1087

- posted by: [Dimitriy V. Masterov](https://stackexchange.com/users/-1/407-dimitriy-v-masterov) on 2012-03-09
- score: 1

<p>Researchers at the Texas Transportation Institute regularly estimate the costs of urban congestion. Their estimate of annual congestion costs per capita in 2001 for seventy-five large U.S. metropolitan areas was 520 dollars, representing twenty-six hours of delay and forty-two gallons of fuel. That adds up to 70 billion. Here's an <a href="http://mobility.tamu.edu/files/2011/09/appendix-a.pdf" rel="nofollow">a more recent example of their work</a></p>




---

All content is licensed under [CC BY-SA 3.0](https://creativecommons.org/licenses/by-sa/3.0/).
