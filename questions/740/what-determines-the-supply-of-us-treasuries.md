## What determines the supply of US Treasuries

- posted by: [Pablitorun](https://stackexchange.com/users/-1/405-pablitorun) on 2011-12-15
- tagged: `treasuries`
- score: 2

Recently the Federal Reserve has sought to manage longer term interest rates by purchasing longer dated treasuries.  

My question is the following: what options does the treasury have in managing the interest rate curve by modifying the supply.  (IE in the extreme funding the government almost entirely in ultra short term T-bills and hardly selling any of the longer term bonds.)

Isn't the Federal Reserve pretty much obligated to purchase T-bills at an unlimited rate to hit their overnight rate targets?  Could the government be funded exclusively via the federal reserves overnight lending at the feds stated rates?

Note: I realize this isn't an especially appealing option, I am just curious as to how the supply of treasuries is determined.



## Answer 749

- posted by: [Quant Guy](https://stackexchange.com/users/-1/501-quant-guy) on 2011-12-16
- score: 2

<p>The issuance and hence total supply of treasury notes, bonds, and bills outstanding is determined by the Treasury. Bonds are outstanding until they are redeemed by the Treasury at par.</p>

<p>The Treasury handles bond issuance at all maturities -- so it does control the supply. It does not control the yield curve -- that is determined thru the interaction of buyers and sellers. In choosing maturities, they diversify duration risk, minimize interest rate risk, take into account funding commitments, all within debt ceiling constraints.</p>

<p>You would have to study the time-series composition of maturities and issuances to back-out a policy.</p>

<p>Now the Federal Reserve can introduce a zero-maturity, zero-interest perpetual liability of the Federal Reserve that is called currency (although technically this is printed by the Treasury as well). The Fed can also purchase Treasury bonds to influence the term structure. This currency liability is backed by the assets of the Federal Reserve which are traditionally US Treasury obligations (but now also include RMBS, Maiden Lane, etc.)</p>

<p>At the margin, an additional T-bill issued has no significant effect on the rate. However, large sales/purchases at a specific maturity do change rates indeed this is the premise of rate-targetting, QE1, etc.</p>

<p>You can see their <a href="http://treasurydirect.gov/RT/RTGateway?page=institHome" rel="nofollow">auction schedule here</a> which is clearly tilted towards shorter maturities. They are taking advantage of low-rates for an extended period of time:</p>

<p>However, the Fed is one of many players in the bond market. For example, T-bill buyers during times of severe financial distress investors have bid-up the price of T-bills so that they produce real negative returns (despite the Fed's intentions). The Fed can expand its balance sheet but its ability to do so is still constrained by the credibility holders of the currency have in the Fed and the value of the currency. Indeed, a substantial portion of Fed policy is implemented in messaging (for example the intended path of rates thru 2013) not just open-market operations which carry with it balance sheet and interest rate risk.</p>

<p>To accomplish what you propose, the Fed would need to match its purchases of T-bills with sales of notes and bonds at various maturities to neutralize their activity. If the Fed did not neutralize their actions then under ordinary circumstances this would create inflation (and ultimately increase the overnight lending rate). </p>

<p>Needless to say this activity would lead to a steepening of the yield-curve and amount to a tightening of monetary policy since long-term rates are going higher and short-term rates are at the zero-bound. Also, it would expose the Federal Reserve balance sheet to a tremendous amount of short-term interest rate risk including losses on its holdings of longer-dates Treasuries and RMBS. Since the liability of the Fed is backed by the asset-side of the Fed balance sheet, the value of the currency would diminish. If interest rates increased the Treasury would also find itself paying higher rates and perhaps fail to roll-over the large quantities of debt required.</p>

<p>Also the ability of the Federal Reserve to conduct monetary policy would be undermined by a loss of credibility in the value of the currency and the policy messaging from the institution.</p>



## Answer 750

- posted by: [Muro](https://stackexchange.com/users/-1/165-muro) on 2011-12-16
- score: 2

<p>The total amount of US Treasuries issued is indirectly determined by the US congress.  The US congress decides how much money it is going spend.  If they decide to spend more than is being received in taxes then the Treasury must issue bonds to cover the difference.</p>

<p>The Treasury determines the mix of bonds (e.g. 3 months, 1 year, 3 years, 30 years, etc) that will be issued.</p>

<p>The supply for a particular duration can be modified in two ways:</p>

<ol>
<li><strong>Increased/decreased borrowing by the US government</strong>.  This affects the overall supply of US Treasuries.  If the US government only spent money it received in taxes then the US government would not need to issue US Treasuries to borrow money.</li>
<li><strong>Bond mix.</strong>  The Treasury can change the mix of bonds issued to meet the borrowing needs of the US government.</li>
</ol>

<blockquote>
  <p>What options does the treasury have in managing the interest rate
  curve by modifying the supply?</p>
</blockquote>

<p>As mentioned above, the US Treasuries determines the mix of bonds that will be issued to meet the borrowing requirements of the US government.  Thus, the Treasury can affect the supply of different bonds by determining the mix of bonds to use to meet borrowing needs.</p>

<p>During the financial crisis there was a large demand for short term treasuries.  The US Treasury met this demand by financing most of the government borrowing over the last 3 years with short term bills (i.e. less than a year).  Chart below from <a href="https://customers.reuters.com/d/graphics/FEDERALDEBT.pdf" rel="nofollow">here</a>.</p>

<p><img src="http://i.stack.imgur.com/Af0SH.jpg" alt="enter image description here"></p>

<p>Although the US government has been able to take advantage of low borrowing costs on short term loans, US government borrowing is now financed through one giant, adjustable rate loan.  If rates start going up the US government will feel the effects immediately since they will be rolling over existing short term debt into new short term debt at a higher rate.</p>

<blockquote>
  <p>Isn't the Federal Reserve pretty much obligated to purchase T-bills at
  an unlimited rate to hit their overnight rate targets?</p>
</blockquote>

<p>The Federal Reserve is not obligated to purchase T-bills.  A bank that is identified as a "Primary Dealer" (e.g. JP Morgan, Goldman Sachs, etc.), however, is obligated to purchase US Treasuries at auction.  This guarantees there will always be a market for US government debt and there will never be a failed debt auction.</p>

<blockquote>
  <p>Could the government be funded exclusively via the federal reserves
  overnight lending at the feds stated rates?</p>
</blockquote>

<p>The US government cannot borrow directly from the Federal Reserve.  The Federal Reserve works with its primary dealers to purchase US debt.  A primary dealer could borrow from the FED and use the borrowed money to purchase US debt.</p>

<p>Indirectly the FED can print money to fund the US government.  The FED has increased its balance sheet of US debt of over \$600 billion over the last year.  In took the newly printed \$600 billion and used it to purchase US bonds from primary dealers.  Thus, the US government was primarily being financed by money printed by the FED.  This is what is called "monetization" in fancy economics lingo.</p>

<p><img src="http://i.stack.imgur.com/r3EKr.jpg" alt="enter image description here"></p>




---

All content is licensed under [CC BY-SA 3.0](https://creativecommons.org/licenses/by-sa/3.0/).
