## price, demand, market equilibrium

- posted by: [Marie. P.](https://stackexchange.com/users/-1/730-marie-p) on 2012-02-26
- tagged: `homework`, `price`
- score: 0

I'm currently a little stuck on an exercise. We are given the marginal cost of an object, 100€, and the demand curve as Q=200,000-500P. The market is assumed to be perfectly competitive. Now the question arises, under what circumstances will the market equilibrium be efficient?
(First, I assume that in a perfect, frictionless market, the marginal cost will be the price of the TV?)
Isn't the answer to this included in the model of a perfectly competitive market? What else has to be fulfilled for the equilibrium to be efficient?

On another question, what if the sale is by government regulation limited to 100,000 units per year (before, people would buy 150,000). "Show the effect on price, social benefit, and cost". Well, I think that then the prices will be increased such that the demand will only be exactly 100,000. But what are the effects on social benefit and cost? Will not the cost be exactly the same, and how can we show social benefit?

I don't think this is very hard, but I'm just missing the foundations. Can somebody help me?


## Answer 1016

- posted by: [Kitsune Cavalry](https://stackexchange.com/users/-1/721-kitsune-cavalry) on 2012-02-26
- score: 2

**Edited:** Thanks for pointing out my gross error protoaster, this should be right now. Please let me know of any other errors!

In a perfectly competitive market where there is no market power for the firm selling TVs, he/she will try to maximize profit. We can measure profit as

$$\pi = p(q)q - c(q)$$
Where $\pi$ is profit, $p(q)$ is price in terms of quantity produced, and $c(q)$ is cost in terms of quantity produced. We have a market demand function that you gave
$$q(p)=200,000-500p$$
where $q(p)$ is a function of quantity demanded in terms of price. Since the firm is price taking in a competitive market, we can set $p(q)=p$. With this we create a profit equation, take the derivative, and set it equal to zero.
$$\pi = p*(200,000-500p) - c(q)$$
$$=200,000p-500p^2 - c(q)$$
$$\frac {d\pi} {dp} = 200,000 - 1,000p - 100 = 0$$
The derivative of $c(q)$ is marginal cost, which we know to be 100, and is why I put it into the equation. Solving for p we get $p = 199.9$. Substituting that back into the demand function you gave, we find $q=100,050$, which will be the number of TVs sold.

Now to find what happens if we limit the TVs sold to 100,000. Plugging this into the demand function you gave, selling 100,000 TVs would increase the price to 200.

We know that $c'(q)=100$, so taking the anti-derivative of this gives us $c(q)=100q$. The original cost of production would have thus been $100 * 100,050 = 10,005,000$. This falls down to $100*100,000 = 10,000,000$ for our new cost.

And for social benefit, we measure the change in profit for our producer.
$$New_\pi=200,000*200 - 500 * 200^2 - 10,000,000 = 10,000,000$$
$$Original_\pi = 200,000*199.5 - 500 * 119.5^2 - 10,005,000= 22,754,875$$

Which is a pretty large change in profit for such a small change in price! While producer surplus falls though, consumer surplus increases slightly, and total surplus (consumer sur. + producer surplus) falls. If you want to find consumer surplus for each scenario and then find the difference between total surplus, then you can take an integral:
$$\int_0^{quant. supp.} \! ((200,000 - 500p) - p) \, \mathrm{d} p$$
To which you insert each value of p that you need.
$$Original_{CS}= 20,039,675.25$$
$$New_{CS}=20,040,000$$



---

All content is licensed under [CC BY-SA 3.0](https://creativecommons.org/licenses/by-sa/3.0/).
