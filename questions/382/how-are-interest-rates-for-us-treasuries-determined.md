## How are interest rates for US Treasuries determined?

- posted by: [user8077](https://stackexchange.com/users/-1/71-user8077) on 2011-10-31
- tagged: `interest-rates`
- score: 2

I am interested in learning how US treasuries receive their interest allotment. I know there are "auctions" and such but not much more. Is there a formula? How much control the the US government have over the process? 

[edit] Specifically the process of issuing new treasuries not after-market trading.


## Answer 610

- posted by: [EnergyNumbers](https://stackexchange.com/users/-1/104-energynumbers) on 2011-11-23
- score: 2

<p><strong>TL;DR - Interest rates at issue are determined by the market at auction</strong></p>

<p>A very similar question was asked over on money.SE, and got a very comprehensive answer from <a href="http://economics.stackexchange.com/users/165/muro">Muro</a>, who is also <a href="http://money.stackexchange.com/users/1229/muro">Muro on money.SE</a>; below is that answer (that I've edited slightly), and <a href="http://money.stackexchange.com/q/2907">this is the original</a></p>

<p><strong>How do treasury auctions work?</strong></p>

<p>First, the US government will issue a notice indicating how much money it would like to borrow. Below is an actual announcement issued by the treasury department that it will be having an auction to raise \$23 billion.
<img src="http://i.stack.imgur.com/Bq1j7.jpg" alt="enter image description here"></p>

<p>The announcement indicates the date of the auction (March 8th, 2011 in the example) as well as deadlines for competitive (11:30 AM) and noncompetitive (11:00 AM) bids. If you would like to participate in the auction then your bids must be submitted before these times.</p>

<p><strong>Competitive Bid</strong> - the bidder specifies the maximum price they will pay for the security. All treasuries are priced in \$100 so bids are submitted in terms of buying a security that will repay the owner \$100 when the security matures (\$100 is the face or par value).</p>

<p><strong>Noncompetitive Bid</strong> - the bidder does not specify any maximum price requirement. These bidders are first in line to be issued a bill but they will get whatever price is determined at auction.</p>

<p>There is a limit of \$5 million that can be submitted as a noncompetitive bid per bidder per auction.</p>

<p>For competitive bids any one customer can be awarded a maximum of 35% of the total offering.</p>

<p>In order to better illustrate the mechanics of the auction let's go back to the example. The table below is a hypothetical list of bids for the \$23 billion being issued. The bids include the total amount the bidder is willing to purchase as well as the maximum price the bidder will pay based on a \$100 par value note.</p>

<p>Bid 1: \$5 billion, max price: don't care (noncompete)<br>
Bid 2: \$10 billion, max price: don't care (noncompete)<br>
Bid 3: \$5 billion, max price: \$98<br>
Bid 4: \$5 billion, max price: \$95<br>
Bid 5: \$10 billion, max price: \$92<br>
Bid 6: \$5 billion, max price: \$90<br></p>

<p>Notice there is a total of \$40 billion in bids. The auction is only for \$23 billion. This means some bids will go unfilled. The ratio between bids and the amount of the auction is called the bid-to-cover ration. For our example it is 1.74 (\$40/\$23). A high bid-to-cover ratio indicates a strong demand for the bonds since there are a lot of bidders. A low ratio indicates weak demand. A ratio under 2.0 is considered weak.</p>

<p>The bids are filled in the following manner:</p>

<ol>
<li>All the noncompetitive bids are filled first. This means Bid 1 and Bid 2 will be filled first. This fills \$15 of the \$23 billion leaving \$8 billion left. </li>
<li>Once all the noncompetitive bids are filled then the competitive bids are filled next starting from the highest max price and proceeding to the lowest until the issue is completely fulfilled.  This means Bid 3 will be filled in full. The remaining \$3 billion will be issued to Bid 4. For this auction Bid 5 and Bid 6 will go unfilled.</li>
<li>Since Bid 4 was the last accepted competitive bid, its max price will be the price that <strong>all</strong> (both competitive and noncompetitive) bidders will receive. This price will also determine the yield for this auction which is 5.26% (100-95/95 * 100).</li>
</ol>

<p>Results of our example auction:</p>

<p>Bid 1: \$5 billion, max price: noncompetitive, <strong>All \$5 billion filled at \$95</strong><br>
Bid 2: \$10 billion, max price: noncompetitive, <strong>All \$10 billion filled at \$95</strong><br>
Bid 3: \$5 billion, max price: \$98, <strong>All \$5 billion filled at \$95</strong><br>
Bid 4: \$5 billion, max price: \$95, <strong>Only \$3 billion filled at \$95</strong><br>
Bid 5: \$10 billion, max price: \$92, <strong>Not filled</strong><br>
Bid 6: \$5 billion, max price: \$90, <strong>Not filled</strong><br></p>

<p>Once the auction is completed the treasury will post the results of the auction. Below is the actual results of the auction.
<img src="http://i.stack.imgur.com/Zl4Lp.jpg" alt="enter image description here"></p>

<p>There are some additional items that are reported from the auction:<br>
<strong>High Rate:</strong> This is the highest yield (or the lowest price) that was accepted at the auction. For our example this would be \$95.<br>
<strong>Allotted at High:</strong> This is the percentage of the total that was filled at the highest accepted yield (or lowest accepted price). For our example, the last \$3 billion we filled was at the lowest price so our allotment at high would be \$3/\$23 = 13%.<br>
<strong>Price:</strong> Price as determined by the auction.<br>
<strong>Median Rate:</strong> Half of the competitive bids were submitted below this rate while the other half were above.<br>
<strong>Low Rate:</strong> The lowest yield (or highest price) submitted for the competitive bids.</p>

<p>The announcement also shows the breakdown of the amount of bids submitted noncompetitively versus competitively and how much was rewarded for those same categories.</p>

<p>There is an entry in the middle of the results announcement listed as SOMA. This stands for System Open Market Account. This represents treasuries that are held by the Federal Reserve. If the Federal Reserve has treasuries that are maturing then it is expected that they will use the proceeds from those maturing treasuries to buy new treasuries. For our example auction the FED had no bills maturing at the time. If they did then the FED would also get the same price determined at the auction.</p>




---

All content is licensed under [CC BY-SA 3.0](https://creativecommons.org/licenses/by-sa/3.0/).
