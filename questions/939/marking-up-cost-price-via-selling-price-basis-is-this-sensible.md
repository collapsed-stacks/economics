## Marking up cost price via "selling price basis" - is this sensible?

- posted by: [Jake](https://stackexchange.com/users/-1/672-jake) on 2012-02-09
- tagged: `cost-curves`
- score: 1

I am a programmer working in a company that is currently losing money. Part of my job is to maintain software and formulas that calculate costs and selling prices. The way it is done now really bothers me. (I am not an economics expert, so please pardon me for abuse of terminologies.)

What happens is we generate a final cost value based on variable and fixed cost components. And then the company says "Ok, we want to take 25% of the selling price as profit" where profit retains the original definition of profit = revenue - cost. To compute the selling price, this formula is used: selling price = [final cost]/75*100.

A mathematical conseqeunce of this method is that if multiple profit sharing participants e.g. agent, sub-contractor etc. The total % cannot exceed 100% i.e. the significance of the 25% is merely a sell-price-split ratio. Furthermore, there seems not to be any scientific approach to determining how much % or ratio to allocate to cost, since it can arbitarily by 1%, 0.1%, 2.3% or anything left over after the split.

Furthermore, I cannot understand how cost analysis can be done if we calculate in this manner.

Anyone can advice whether this method of managing sales revenue is fine? If so, are there any references I can refer for analysis of this method? Thanks.


## Answer 954

- posted by: [mzuba](https://stackexchange.com/users/-1/219-mzuba) on 2012-02-12
- score: 1

I am not an expert, as this seems to be a business administration problem rather than an economics problem. But I’ll give it a try.

Is it wise to set $final price = final costs + markup * final costs$ ? An economist would say that the best price is the one your customer is still willing to pay (if you have a specific customer in mind), or the price which maximizes the profits you can make depending on the market and your production capacities. If you are facing a competitive market, arbitrarily decided fixed overhead will most definitely not maximize your profits. If this is what you are interested in, say so and I will elaborate. 

The legal form of your organisation, company strategy or custom in your industry might suggest other pricing strategies (this is business administration). Fixed overhead, for example, is common in academia.

Is this method mathematically unsound? I don’t think so.



---

All content is licensed under [CC BY-SA 3.0](https://creativecommons.org/licenses/by-sa/3.0/).
