## Why does the marginal revenue curve slope downward at twice the rate of demand in a monopoly?

- posted by: [Aarthi](https://stackexchange.com/users/-1/1-aarthi) on 2011-10-11
- tagged: `theory`, `demand`, `models`
- score: 7

The monopolist's view of the market usually looks as follows:

![enter image description here][1]

Why does the marginal revenue/benefit line always hit the Y-axis (Q) at the halfway point of the demand curve?

  [1]: http://i.stack.imgur.com/ZQCEy.png


## Answer 24

- posted by: [Ryan](https://stackexchange.com/users/-1/41-ryan) on 2011-10-11
- score: 12

That particular result (MR = double slope of D) only holds when demand is linear. Here's a mathematical argument for it:

Total revenue is the product of Price and Quantity:

    TR = P*Q

Price is a function of Quantity, so the above can be more accurately written as:

<pre>TR = P(Q)*Q</pre>

In the case of linear demand, we can write P(Q) as:

<pre>P(Q) = a - b*Q</pre>

Plugging this into our expression for total revenue:

<pre>TR = (a - b*Q)*Q</pre>

Which can be simplified to:

<pre>TR = aQ - b*Q<sup>2</sup></pre>

Taking the first derivative in Q of total revenue yields:

<pre>dTR/dQ = a - 2*b*Q</pre>

Using the definition of marginal revenue (which is the first derivative of total revenue in quantity), we can say:

<pre>MR = a - 2*b*Q</pre>

Which is what we wanted to show.

More intuitively, the reason is this: for a monopolist (or any firm facing a downward-sloping demand curve), a change in price leads to a change in total revenue in two components: first, lowering the price increases the quantity demanded. Since only one price may exist in a market at a given time (unless we allow for price discrimination) lowering the price means we must reevaluate the revenue from all of the _previous_ units as well.

The monopolist's marginal decision is therefore: is the increase in quantity demanded brought about by the decrease in price worth the reduction in revenue on all of the previous units? The monopolist requires a marginal cost curve to answer that question accurately.



---

All content is licensed under [CC BY-SA 3.0](https://creativecommons.org/licenses/by-sa/3.0/).
