## How can one calculate critical mass for this market?

- posted by: [David](https://stackexchange.com/users/-1/114-david) on 2011-10-12
- tagged: `markets`, `trade`, `critical-mass`, `matching-problem`
- score: 3

I would like to create a new virtual market and I need to know how one can calculate the critical mass needed for this market to be successful. What I mean by successful, is that the trading volume will increase over time. The market is for buyers and sellers of mechanical devices, where someone needing a special mechanical device (maybe something as simple as a one-piece thing). 

At the moment, I am not able to guess anything about the critical mass for this market. Maybe one needs to have 1000 buying orders per day, or maybe just 1. Any estimate that is better than that, will get a huge cheer from me, but to answer this question, you do not need to come with a specific estimate, I am more after how to go about doing this.

The following are the characteristics of the market: 

 - A buyer will initiate the trade by stating interest in buying a device with a range of specifications
 - I believe that at least one seller should offer to sell the device within 24 hours (at least for simple devices) for the average buying-offer, for buyers to believe that the market is useful, and choose to return in the future
 - I believe that 80% of the buying offers need to get at least one bid, in order for the market to be successful
 - There will be an unknown number of specializations for the sellers. Some can only create in plastics, while others are specialized in titanium devices. Similar with forms and sizes, and specifications about accuracy. To simplify this, we can assume that there are 500 specializations. Some of these will be hugely more popular than other ones. Please make the assumptions you need to with regards to this.


## Answer 110

- posted by: [David Perry](https://stackexchange.com/users/-1/8-david-perry) on 2011-10-12
- score: 5

<p>Finding the critical mass point of a given market is very non-trivial and typically involves more sociology than economics, but you might find some good reading in Hugo Engelmann's <a href="http://en.wikipedia.org/wiki/One-third_hypothesis">one-third hypothesis</a>:</p>

<blockquote>
  <p>...we would expect that the most persistent subgroups in any group
  would be those which approximate one-third or, by similar reasoning, a
  multiple of [i.e., a power of] one-third of the total group. Being the
  most persistent, these groups also should be the ones most
  significantly implicated in ongoing sociocultural transformation. This
  does not mean that these groups need to be dominant, but they play
  prominent roles.</p>
</blockquote>

<p>It has also been hypothesized that adoption may follow a normal distribution more accurately and that the initial "tipping point" is to be found one standard deviation below the median, or about 15.8% of the total populous. </p>

<p>These are general theories, in any case. If you have a great deal of data about your specific market you may be able to attain a closer estimation: The critical mass point of any network-effect driven market is the point at which the value obtained from the good or service is greater than or equal to the price of the good or service. Since the value of the good/service is, in the case of markets, largely determined by the size of the user base, you can solve for the intersection of the two so long as you have a method of reliably determining value based on network size and a reasonable estimation of price.</p>



## Answer 902

- posted by: [PGR](https://stackexchange.com/users/-1/632-pgr) on 2012-01-31
- score: 1

This sounds like a matching problem to me, and I'm sure an expert on matching can provide you with an algebraic expression for what you're looking for. Varian had something along those lines appled to virtual markets.

But let me take a stab at it.

By critical mass I assume you mean the minimum number of bids per day to ensure that the overall number of transactions steadily increases over time. Each transaction is a match between what a buyer is looking for and what a seller has to offer. It seems to me that your uncertainty is whether enough buyers or bids will appear.

It also seems to me that your critical mass (minimum number of bids daily required to ensure that the total number of transactions rises over time) will be lower, the more you facilitate the existence of a successful match. So things like having an appealing shelf/database will not only captivate potential buyers and allow sellers to showcase their products, it will also lower your critical mass number. 

Another important factor is transaction costs; the lower they are the lower critical mass will be.



---

All content is licensed under [CC BY-SA 3.0](https://creativecommons.org/licenses/by-sa/3.0/).
