## A question on the travel cost valuation method

- posted by: [Adam Bailey](https://stackexchange.com/users/-1/719-adam-bailey) on 2012-02-27
- tagged: `microeconomics`, `sustainability`
- score: 2

[As there has been no response to this question I have extensively edited it to address more clearly the guidance in FAQs.]

For the research component of my MSc I undertook a travel cost valuation of an urban park (I’ve now completed the MSc so this is not homework).  My estimated consumer surplus seemed low, and I’ve been considering why this might be.  This question relates to just one possible reason.

Where a valuation relates to a remote site, eg a national park (as many published studies do), it may be a reasonable assumption to treat the value of the site in isolation.  Where a park is one of many within a city, however, the interactions between the demands for visits to different parks can hardly be ignored.  The question therefore is what exactly is the meaning of the value of an urban park estimated by the travel cost method.  Is it:

a) The marginal value which that park contributes to the total value of all the city’s parks, as compared with a situation without that park but with all the other parks still present; or

b) A value which could, in principle, be added to the equivalent values for all the other parks to estimate the total value of all the city’s parks (I avoid “average value” since an assumption of homogeneous units is implausible for parks); or

c) Neither of the above; or

d) Does the meaning depend on the details of how the method is applied (eg the variables included in the trip-generating function)?

I don’t think the answer can be (a) since, if the park had not existed, some of its visitors would instead have visited other parks within the city, choosing to make higher-cost trips or to visit parks with inferior characteristics.  Thus some of the consumer surplus a travel cost study of one park measures is not additional, but merely transferred from other parks.

I also don’t think the answer can be (b).  Some people may have a strong desire to visit a park, and if no alternative were available, might be willing to travel say 20 km to visit a park.  But if they live in a city where everyone is within 2 km of a park, their willingness to travel 20 km is never revealed by their behaviour.  Of course they might make much more frequent trips, but there is no particular reason to think that this would have the same effect on measured consumer surplus.

My provisional thinking is that the answer is (c).

I have looked at many papers on the travel cost method but have not seen this issue addressed.  Some papers – eg Rosenthal D H 1987  The Necessity for Substitute Prices in Recreation Demand Analyses  American Journal of Agricultural Economics Vol 69 No 4 pp 828-837 – refer to the inclusion of variables for substitute sites in estimating a trip-generating function for a site. It is shown that omission of substitute price variables can result in a biased estimate of the trip-generating function and therefore of a site’s value.  But this seems to be a separate point.  It concerns how potential visitors behave given a choice between two or more existing sites.  It does not address how visitors would have behaved if one or more of the sites had not existed.

There are of course other important kinds of site value which the travel cost method does not capture (eg hedonic property value, the value of ecosystem services) - please ignore these for the purposes of this question.


## Answer 1045

- posted by: [EnergyNumbers](https://stackexchange.com/users/-1/104-energynumbers) on 2012-03-02
- score: 1

<p>I think that by measuring the travel cost, (I take it that this is some form of generalised cost, combining time, money and some elements to reflect journey quality), the only thing you can learn anything about, is the <strong>difference in utility between one park and another</strong>.</p>

<p>For example, let's say:</p>

<ul>
<li>£5 is my generalised cost of getting to Regent's Park (photo below), a large formal park with manicured gardens and magnificent blossoming avenues of trees;</li>
<li>£3 is my generalised cost of getting to Green Park, a large open space with virtually no flowers; and </li>
<li>£1 is my generalised cost of getting to Russell Square, an urban garden square with cafe, fountain and lots of traffic noise.</li>
</ul>

<p>If I choose Russell Square, then all we can say is that the utility value of it no less than £4 below Regent's Park, and no less than £2 below Green Park.</p>

<p>My choice is probably going to depend on how much time I'm going to spend in the park too: Russell Square is fine for 15 minutes; but if it's a couple of hours in the park I'm after, I'll choose one of the others. So the <strong>travel cost differential</strong> is probably telling me something about <strong>differential utility per unit time</strong>.</p>

<p>This whole subject is fraught with complexities and confounding features, though. In particular, parks are often primarily social spaces, which means that the choice of park will be influenced by, among other things, the distribution of travel costs of the people I'm planning to meet.</p>

<p>And that's before we get into the heap of confusion that arises as soon as we take into account that when people make trips to recreational distances, they'll sometimes choose a travel route that does not minimise cost, because the journey itself becomes part of the recreational activity.</p>

<p><img src="http://i.stack.imgur.com/CZZsO.jpg" alt="gratuitous photo of Regent's Park"></p>



## Answer 1266

- posted by: [Frank](https://stackexchange.com/users/-1/659-frank) on 2012-04-21
- score: 1

<p>I lean towards (a). It won't be possible to estimate the value of any arbitrary combination of parks, like</p>

<p>v({park #1}), v({park #1 and park #3 and park #5}), v({park #5}),...</p>

<p>without making some assumptions about how people choose which parks to go to. For example, you could assume that each person chooses which park to use -- if any -- based on its characteristics (distance from where they live, parking availability, shade, etc.) and run a probit regression on their decisions. To do this you might need to collect information on the characteristics of parks and also of potential users (like where they live or their wealth, which may proxy for car ownership, etc.).</p>

<p>If you do something like that, it is a relatively short step to ask "What would happen to public welfare without this park?" There is a strong tradition in Industrial Organization (or IO, a field of economics) of using decision models to ask questions like "What would happen to consumer welfare without <a href="http://scholar.google.com/scholar?cluster=11382843928443122124&amp;hl=en&amp;as_sdt=0,50" rel="nofollow">the minivan</a>?" and you could probably build on that. In fact, the literature started with Daniel McFadden, who wrote <a href="http://scholar.google.com/scholar?q=author%3a%22daniel%20mcfadden%22%20intitle%3a%22urban%20travel%20demand%22" rel="nofollow">a paper and a book</a> on "urban travel demand."</p>

<p>Oy, EnergyNumbers' answer reminded me of a serious confounding factor here, though: congestion. If a lot of people go to a park that I like a lot, it may become less appealing!</p>




---

All content is licensed under [CC BY-SA 3.0](https://creativecommons.org/licenses/by-sa/3.0/).
