## Calculate Interest rate on debt

- posted by: [J. Maes](https://stackexchange.com/users/-1/578-j-maes) on 2012-05-02
- tagged: `interest-rates`
- score: 1

I'm looking at [this][1] page, which explains the valuation of equity as a call option. I can calculate the value of the call and the value of the outstanding debt using the black and Scholes formula. I don't understand the formula to calculate the Interest rate on debt. 

It says:

($ 80 / $24.06)1/10 -1 = 12.77% 

but I do not see how this formula gets to 12.77%

This is in the source:

> The parameters of equity as a call option are as follows: 
> 
> Value of the underlying asset = S = Value of the firm = $ 100 million 
> 
> Exercise price = K = Face Value of outstanding debt = $ 80 million 
> 
> Life of the option = t = Life of zero-coupon debt = 10 years 
> 
> Variance in the value of the underlying asset = s2 = Variance in firm
> value = 0.16 
> 
> Riskless rate = r = Treasury bond rate corresponding to option life =
> 10%  Valuing Equity as a Call Option
> 
> Based upon these inputs, the Black-Scholes model provides the
> following value for the call: 
> 
> d1 = 1.5994 N(d1) = 0.9451 
> 
> d2 = 0.3345 N(d2) = 0.6310  Value of the call = 100 (0.9451) - 80
> exp(-0.10)(10) (0.6310) = $75.94 million
> 
> Value of the outstanding debt = $100 - $75.94 = $24.06 million
> 
> Interest rate on debt = ($ 80 / $24.06)1/10 -1 = 12.77%

  [1]: http://pages.stern.nyu.edu/~adamodar/New_Home_Page/lectures/opt.html

## No Answers

There were no answers to this question.


---

All content is licensed under [CC BY-SA 3.0](https://creativecommons.org/licenses/by-sa/3.0/).
