## Advantages to exotic financial instruments and microsecond trading

- posted by: [Joe](https://stackexchange.com/users/-1/488-joe) on 2011-12-14
- tagged: `macroeconomics`, `investment`, `speculation`
- score: 5

I often hear that exotic financial instruments like naked short selling and mortgage-back securities make the market less stable, and do little to improve the economy as one would do if they invested money in a good company, or engaged in normal consumer banking.

Likewise, there seems to be little advantage to microsecond trading as the market doesn't need to be corrected at that time scale.  It seems like a waste of intellectual capital at best and at worst it also destabilizes the market as the trading software does not have human judgement and might have bugs.

However, I wonder if there is another side to this discussion.  How do advocates of microsecond trading and exotic instruments defend their position?


## Answer 737

- posted by: [David](https://stackexchange.com/users/-1/114-david) on 2011-12-15
- score: 4

The advantage of microsecond trading is that it makes an asset more liquid. If an asset is liquid, it means that any buyer of the asset, long-term or short-term, will know that they are likely to be able to sell this asset whenever they would need to. This is certainly an advantage, because it means that there is less risk of getting stuck with an asset one does not want to own. If lots of assets have a high level of liquidity, it means that capital can be allocated more efficiently. 

One example is if I was the CEO of an airline company. I identify the volatility of the price of aviation fuel as the biggest risk for the company. In order to hedge this risk, I want to buy aviation fuel futures, which might be what one would call an exotic asset. The problem is that there is not enough liquidity in this market, so I cannot buy any such futures at a decent price. Any trading of aviation fuel futures, including microsecond trading, would help increase its liquidity. However, since the liquidity of the airline fuel market is too low, I would be forced to buy oil futures instead. The oil price and the aviation fuel prices are likely to correlate, so this is quite suitable for hedging my risk. However, in the event of a sudden reduction in refinery capacity (for example because of a war), then my risk would maybe not be hedged, so the airline might get in trouble because of the sudden rise in aviation fuel prices. 

I would argue that any increase in the number of assets available (including exotic assets), would in general enable more efficient allocation of capital, as one can find the asset that exactly matches ones needs. This could for example be the need for hedging. I have, however, not discussed any negative effects of such assets or microsecond trading.


## Answer 753

- posted by: [Cor_Blimey](https://stackexchange.com/users/-1/494-cor-blimey) on 2011-12-17
- score: 2

**Naked short selling** (i.e. going short a call option without owning the underlying) can provide a valuable price discovery mechanism, and are valuable as a means of altering risk profiles of a portfolio above the risk free market rate. 

However, by their nature, a large short position can (often is) market changing. Because of their leveraged nature an uncovered position permits large positions for a given upfront capital, allowing larger market influences. What perhaps needs to change is legislation regarding the legality of purposefully using concentrated short positions as a market manipulator.

**Rapid automated trading** (algo-trading) is often used to 'scalp' any microinefficiencies from a market. They are therefore valuable to the market and between markets as a means of rapidly 'ironing' out pricing irregularities, and ensuring parity between different markets. However, a darker side of automated trading is to market manipulate to trigger price caps/ceilings/collars of investor positions, then mopping up the resulting puts/calls.

**MBS** do not inherently make the market less stable. The issues over the past few years are not over the products, but from mis-understanding the products. Risk-pooling is effective and completely valid. However, by treating MBS as independent to one another and as spreading risk from individual mortgage consumers (through risk pooling) pricing of MBS failed to account for the - now understood - element of covariance between mortgage defaults. Furthermore, unlike previous Building society type mortgages, the risk is passed on to the MBS holders thus the bank / mortgage lender becomes a broker, disincentivising proper due diligence and incentivising accepting lower-quality debt. As a result of commanding a too small risk premium, MBS were overvalued.



## Answer 736

- posted by: [EnergyNumbers](https://stackexchange.com/users/-1/104-energynumbers) on 2011-12-15
- score: 1

Trading Strategies, such as devising and selling derivatives, or rapid automated trading, do not get justified or defended on the basis of their contribution to greater social welfare. They are private-sector instruments, and as such, their raison d'etre is to turn a profit.

The invention and selling of MBSs, and innovations in rapid automated trading, did, for quite a while, turn a significant profit, and so, by their own yardstick, they were succesful.

Within a market mechanism, any further defence is unnecessary and not meaningful. However, from a policy perspective, that does not mean that these things are desirable, however. There are plenty of potential and realised drawbacks there. To a degree, there is an agency problem here: that the ones making the profits, are not necessarily the ones incurring all the penalties when things go wrong. There is also a black-swan risk: that these trading strategies may make lots of very small incremental profits almost all the time, meaning that they attract a lot of investment and copying, but occasionally they experience a long-tail event that wipes out all the profit accumulated to date, and puts the strategy as a whole into a net loss.


## Answer 806

- posted by: [Tal Fishman](https://stackexchange.com/users/-1/89-tal-fishman) on 2012-01-03
- score: 1

<p>The second part of your question, regarding high frequency trading, has already been addressed on quantitative finance SE in the following question:</p>

<blockquote>
  <p><a href="http://quant.stackexchange.com/q/1658/1106">Has high frequency trading (HFT) been a net benefit or cost to society?</a></p>
</blockquote>

<p>There, I wrote:</p>

<blockquote>
  <p><a href="http://www.dauphine.fr/cereg/UserFiles/File/WFMQ2008_7.pdf" rel="nofollow">Does Algorithmic Trading Improve Liquidity?</a> This paper claims <em>yes</em>. Nevertheless, it does not answer <a href="http://www.economist.com/node/21525456" rel="nofollow">Buttonwood</a>'s concern that the improved liquidity is illusory.</p>
</blockquote>

<p>As for exotic financial instruments, you may be interested in reading some of the answers to <a href="http://quant.stackexchange.com/q/1572/1106">Why are exotic options most popular in FX?</a>  In short, these instruments help certain specialized clients, such as pension funds and insurance firms, hedge their unique risks and exposures in a cost-effective manner.  Remember, there are two sides to every trade, and even after the fact you will often not find either party regretting the trade, particularly those that are still going on today.</p>

<p>MBS, by the way, are not considered exotic, and naked short selling is neither exotic (in fact, it is illegal) nor a security.  <em>Some</em> new types of MBS may be considered exotic, and certainly many exotic derivatives <em>based on</em> MBS were created in the mid 2000s, but MBS themselves, particularly prime residential MBS, are about as vanilla a product as one can get.</p>



## Answer 811

- posted by: [Tom Au](https://stackexchange.com/users/-1/178-tom-au) on 2012-01-04
- score: 1

Microsecond trading is the ultimate exposition of "continuous time" trading, by which "continuous martingales" are reduced to Brownian motion.

http://arxiv.org/abs/0712.1275

That is to say that such trading helps create the "randomness" that is the hallmark of the efficient markets hypothesis. 

Such algorithms also lead to the "completion" of (time) "space," thereby reducing the potential for market inefficiencies.



---

All content is licensed under [CC BY-SA 3.0](https://creativecommons.org/licenses/by-sa/3.0/).
