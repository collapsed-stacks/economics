## Should trucks be allowed to take over on the highway?

- posted by: [bonifaz](https://stackexchange.com/users/-1/329-bonifaz) on 2011-12-05
- tagged: `damage-function`
- score: 1

In some European countries (e.g., Slovakia) trucks are strictly and generally forbidden to take over on the highway, whereas in several others it is allowed.

Appart from political issues that are related to this question, I'm interested in the economic implications of such measures. Please note that I'm talking about a typical two-lane highway.

Which factors do you consider?

Ones that come to my mind are:

- opportunity costs of truck X not taking over truck Y, and therefore truck X arriving z time units later, causing economic damage of d_X
- opportunity costs of w cars not being able to take over both trucks X and Y, because truck X is currently over taking truck Y, and therefore w cars arriving u minutes later, causing economic damage of d_w
- increased risk of accidents, causing economic damage of d_a

What else do you consider? Are you aware of any research that was elaborated on that topic?


## Answer 690

- posted by: [EnergyNumbers](https://stackexchange.com/users/-1/104-energynumbers) on 2011-12-05
- score: 4

Normally, this sort of analysis is done by linking dynamic micro-simulation modelling of the roads, with a full mode/destination choice model; and with an economic model.

The dynamic micro-sim translates the policy into a revised matrix of generalised costs of transport. That matrix then results in changes to mode choice (road vs rail vs water vs air), destination choice, and even origin (location of factory / distribution centre) choice. That provides a new distribution of costs and employment, which then goes into the top-level economic model, producing changes to economic activity.

And then that whole lot gets iterated around again and again, until it converges.

So,  the number of economic factors that go into your cost-benefit analysis can be pretty huge. It's not only changes to delay costs for freight and other traffic, and accident costs, but it can feed into distribution of employment, business location, and inter-sector competition, if the impacts are high enough.

Often, the impacts at the whole-economy level are very small, and the only modelling done is at the micro-sim level. That can easily give the wrong answer, not only getting the magnitude of the cost-benefit balance wrong, but even its sign: there are higher-level equilibriums at play than just the traffic flow on a particular route, that can give positive or negative feedbacks.



---

All content is licensed under [CC BY-SA 3.0](https://creativecommons.org/licenses/by-sa/3.0/).
