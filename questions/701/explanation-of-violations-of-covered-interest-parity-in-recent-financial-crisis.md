## Explanation of violations of covered interest parity in recent financial crisis

- posted by: [Tim](https://stackexchange.com/users/-1/204-tim) on 2011-12-07
- tagged: `currency`, `crisis`, `finance`
- score: 3

> During the recent financial crisis, there were violations of [covered interest
> parity][1] because foreign banks were desperate for US dollars.

The covered interest parity says that $    S_t (1 + i_\$) = F_t (1 + i_c) $, where
$F_t$ and $S_t$ are the forward exchange rate at time $t$ and the exchange rate, and $i_\$$ and $i_c$ are the interest rates in US and in the foreign country.

I was wondering 

 1. why the foreign banks ("foreign" is with respect to US) were
    desperate for dollars in the financial crisis?
 2. why the foreign banks were desperate for US dollars is the reason of
    violations of covered interest parity?

Thanks and regards!


  [1]: http://en.wikipedia.org/wiki/Interest_rate_parity


## Answer 709

- posted by: [Muro](https://stackexchange.com/users/-1/165-muro) on 2011-12-08
- score: 4

> Why the foreign banks ("foreign" is with respect to US) were desperate
> for dollars in the financial crisis?

The US Dollar (USD) is considered one of safest and most liquid currencies in the world.  During the crisis banks were scrambling for cash to meet customer demands for cash.  Customers were liquidating their securities and money market accounts for cash.  Foreign banks wanted USDs because they are the most liquid and therefore can be used in almost any type of currency swap, repurchase agreement, or currency exchange giving the bank strength to obtain more foreign currency through any one of these arrangements as well as giving the bank the ability to provide its customers with USDs which were in high demand during the crisis.

> Why the foreign banks were desperate for US dollars is the reason of
> violations of covered interest parity?

Covered interest parity is a way to hedge against a "carry trade" transaction going against an investor.  

As an example, let's say the current exchange rate is 1 USD = 100 Yen and the current 1 year interest rate is 10% in US and 20% in Japan.  If I save 100 USDs, at the end of 1 year I'll have 110 USDs (100 USD * 1.10).  If instead, I exchanged my 100 USDs for 10,000 yen and saved in yen I would have 12,000 yen (10,000 * 1.20).  If the exchange rate is still 1 USD = 100 yen then when I exchange my 12,000 yen back to USDs I will have 120 USDs.  I effectively had a 20% return on my USDs.  

But what if the exchange rate changes during the year?  

What if the exchange rate at the end of the year is 1 USD = 200 Yen.  When I exchange back to USDs I will now only have 60 USDs.  I would experience a loss of 40 USDs on my initial investment of 100 USDs.  To hedge against this I enter into a forward currency exchange contract for the end of the year at a predetermined exchange rate to hedge against changes in the exchange rate.  For the above case I would purchase a futures contract to exchange yen to USDs at a rate of 1 USD = 109.09 yen at the end of one year.  This way at the end of the year when I exchange my yen back to USD I will be guaranteed an exchange rate of 109.09 which yields me 12,000 / 109.09 = 110 which is what I would have made had I invested the USDs at home.

A violation of the hedge would be to enter into a futures contract for the currency where the investor, even with the contract as a hedge, could experience a loss with the current exchange rates and interest rates.  This was occurring because of the high demand for USDs.  Investors were entering into currency contracts that violated the covered interest parity formulas because investors were desperate for USDs.



---

All content is licensed under [CC BY-SA 3.0](https://creativecommons.org/licenses/by-sa/3.0/).
