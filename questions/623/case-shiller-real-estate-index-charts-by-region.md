## Case-Shiller real-estate index charts by region?

- posted by: [Quant Guy](https://stackexchange.com/users/-1/501-quant-guy) on 2011-11-24
- tagged: `usa`, `housing-market`, `case-shiller`
- score: 2

Where online can I find charts for the Case-Shiller home price indices for each of the respective regional components? 




## Answer 625

- posted by: [Feral Oink](https://stackexchange.com/users/-1/130-feral-oink) on 2011-11-25
- score: 3

<p>I assume that you are referring to the S&amp;P/ Case-Shiller real-estate indices. They are available by geographic region on a monthly basis. The <strong><a href="http://www.standardandpoors.com/indices/articles/en/us/?articleType=PDF&amp;assetID=1245190941370" rel="nofollow" title="Case Shiller Index Methodology">Case-Shiller Index Methodology documentation</a></strong> describes the indices as follows:</p>

<blockquote>
  <p>Their purpose is to measure the average change in home prices in a
  <strong>particular geographic market</strong>. They are calculated monthly and cover <strong>20
  major metropolitan areas</strong> (Metropolitan Statistical Areas or MSAs)...and three price tiers – low, middle and high.</p>
</blockquote>

<p>Emphasis mine. Note that the methodology used to calculate the regional indices is separate from the nationwide index. The Case-Shiller National Index is</p>

<blockquote>
  <p>a composite of single-family home price indices for the nine U.S. Census
  divisions and calculated quarterly.</p>
</blockquote>

<p>To calculate the regional indices, data is collected for transactions of all residential properties. The main variable used for index calculation is the price change between two arms-length sales of the same single-family home. </p>

<p>The regional indices are calculated monthly, using a three-month moving average algorithm, and published with a two-month lag. This helps offset delays due to "clumping" in the flow of sales price data from county deed recorders. It should also help assure sufficient sample sizes for robust average price changes.</p>

<p>The following <strong><code>table*</code></strong> lists each of the twenty regional Case-Shiller real-estate indices, as well as the corresponding Bloomberg and Reuters ticker symbols:
<img src="http://i.stack.imgur.com/5g64f.png" alt="Case-Shiller regional real-estate indices"></p>

<p>Full details of the components of the 20 regions, at a county and city level are available from the Index Methodology documentation. Updates are published on the last Tuesday of each month at 09:00 AM Eastern Time. </p>

<p><strong><code>*</code></strong> The source for this chart was the <strong><a href="http://www.standardandpoors.com/indices/articles/en/us/?articleType=PDF&amp;assetID=1245302658617" rel="nofollow" title="Case-Shiller Regional and National Index FAQ, Dec 2010">Case-Shiller Real-estate Index FAQ</a></strong> which provides further practical details on available history and use cases. For example, </p>

<blockquote>
  <p>the monthly indices are not intended to measure recovery costs after
  disasters, construction or repair costs</p>
</blockquote>

<p>There are two other information sources for the regional Case-Shiller real-estate indices:</p>

<ul>
<li>The <strong><a href="http://www.standardandpoors.com/indices/sp-case-shiller-home-price-indices/en/us/?indexId=spusa-cashpidff--p-us----" rel="nofollow" title="S&amp;P website about Case-Shiller indices">S&amp;P Case-Shiller webpage</a></strong> includes links to studies based on the regional indices, as well as video and written comments by Yale University Professor Shiller etc.</li>
<li>Posts listed in the <strong><a href="http://www.housingviews.com/category/standard-poors-case-shiller-data/" rel="nofollow" title="Housing Views blog, Case-Shiller category">Case-Schiller category</a></strong> on the Housing Views blog offer current news stories and announcements about the national and regional indices. The domain is separate from the S&amp;P main website, which can be helpful for many reasons.</li>
</ul>

<p>Both sites offer a wide variety of <strong>historical and snapshot charts</strong> of the regional Case-Shiller home price indices.</p>




---

All content is licensed under [CC BY-SA 3.0](https://creativecommons.org/licenses/by-sa/3.0/).
