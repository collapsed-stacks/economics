## Can misalignment in incentives within organisations be modelled using game theory?

- posted by: [Turukawa](https://stackexchange.com/users/-1/48-turukawa) on 2011-10-20
- tagged: `game-theory`, `perverse-incentives`, `organizational-economics`
- score: 7

Large organisations (be they public or private) often have **inherent contradictions** in the **incentives governing different independent functions** within that organisation.  These are relatively obvious when the parties have direct contact but much harder to deal with when the parties are connected only tangentially.

Simple interactions, poorly aligned, can have irrational results.  Call them **perverse incentives**.

By way of example:

 - A purchasing manager in a public hospital is incentivised to achieve the best prices on inputs the hospital requires (everything from tea and coffee for staff, to syringes and swabs, to specimen test kits, to big pieces of medical imaging kit);
 - Medical devices are covered by a range of regulatory compliance requirements but, within these measures, there is still a range of failure rates and support services;
 - A certain medical device could have a failure rate of 1 in 1,000, while another has a failure rate of 1 in 10,000 - if the device is sufficiently cheap and ubiquitous it may not matter, functionally, which kit is purchased;
 - Extending the example, a swab which every now and then fails to absorb cells from a test subject and this isn't picked up till the patient has left (happens, but at different rates, even when compliant);
 - The purchasing manager buys the cheaper one and achieves his efficiency target (and incentive);
 - The medical staff are incentivised to reduce waiting times but, when this device fails (although cheap) it results in a not-inconsequential impact on patient care time;
 - Retesting the patient has negligable costs, but retesting the same patient implies another patient was not tested and had to wait;
 - Long waiting lists result from efficiencies gained elsewhere.

I created a game I call [Contradiction][1] (unsurprisingly) to model this and it works quite well, but I'm curious as to whether there are other games (or analytical approaches) which can model these weakly connected actions which have an impact on overall organisation efficiency even as individual participants achieve their objectives.


  [1]: http://www.whythawk.com/ideas/contradiction-when-bad-systems-ruin-good-people.html


## Answer 348

- posted by: [MikeRand](https://stackexchange.com/users/-1/45-mikerand) on 2011-10-27
- score: 1

<p>System dynamics / agent-based modelling.</p>

<p>The classic setup in this kind of literature is a supply chain, where severe overstocking occurs despite each link in the chain having a reasonable objective function.</p>

<p>===Updated with links===</p>

<ul>
<li><a href="http://www.informs-sim.org/wsc06papers/008.pdf" rel="nofollow">A strong overview of ABM</a></li>
</ul>

<p>The key here is to understand the concept of emergent behavior: that individual agents following simple rules can produce surprising results.</p>



## Answer 970

- posted by: [Peutch](https://stackexchange.com/users/-1/674-peutch) on 2012-02-14
- score: 1

<p>The standard and ubiquitous framework to analyze those situations is the principal-agent model .</p>

<p>Typically, the principal is concerned with providing incentives for the agent to exert some effort towards some action. The premise is that the principal cannot exactly observe how much effort has been exerted, but can only observe say the (noisy) outcome of the action.</p>

<p>To go back to your example, the hospital manager would like the purchasing manager to invest effort in finding out the cheapest supplies of inputs, but can only observe how much was spent. The purchasing manager can always claim that this year was a bad year, and that it's not its fault.</p>

<p>The question then is for the principal to design a contract that will provide at least partial incentives for the agent to exert effort. Given the imperfect observability (or contractibility) of effort, the agent will then enjoy some informational rents. What this means is that <strong>it is in general impossible for the principal to devise a contract that will induce the agent to exert the first-best level of effort</strong>.</p>

<p>The problem becomes more acute when there are multiple tasks. (Look at <a href="http://jleo.oxfordjournals.org/content/7/special_issue/24.full.pdf+html" rel="nofollow">Holmström-Milgrom 1991 paper</a> in JLEO). <strong>When the results of tasks is not observed with the same precision in different tasks, incentive contracts will induce a distortion of effort towards more "visible" tasks, thereby also inducing sub-optimal allocation of effort.</strong></p>

<p>An extreme example is, say, if you reward class teachers on the basis how their students do in standardized tests. Then class teachers will have an incentive to exert more effort on training their students on those tests specifically, and less effort on stimulating general curiosity of the students (which is difficult to observe, or to contract on).</p>

<p>This should enable you to address the question, for example, of waiting time in hospitals versus quality of care. Waiting time can be very accurately measured, and rewarding that will distort effort away from less observable outcomes, such as quality of care.</p>




---

All content is licensed under [CC BY-SA 3.0](https://creativecommons.org/licenses/by-sa/3.0/).
