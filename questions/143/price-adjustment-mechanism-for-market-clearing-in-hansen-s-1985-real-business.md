## Price adjustment mechanism for market clearing in Hansen's (1985) Real Business Cycle model

- posted by: [Nate](https://stackexchange.com/users/-1/119-nate) on 2011-10-13
- tagged: `market-clearing`, `price-adjustment`
- score: 6

I am building a version of Hansen's (1985) divisible-labor RBC (Real Business Cycle) model with agents that form evolutionary expectations -- their "mental model" of the world can change as the model steps forward.

The model is a standard representative-agent neoclassical stochastic growth model; the household (HH) maximizes an infinite-horizon time-separable utility function with capital as a single investment asset.

Solving this "the regular way" is covered in a number of places. Instead of solving the model with something like Uhlig's (1997) log-linearization or Schmitt-Grohe and Uribe's (2004) approximation of the policy function (or any of the options I get with Dynare), I'd like to write up the agents in the model as objects in code, and step that code forward through time. There are three main obstacles:

 1. Agents need to have expectations. 
 2. Markets need to clear.
 3. The no-ponzi condition needs to be enforced.

(1) is simple enough. With one agent and one firm (or N identical agents/firms), the HH can form expectations over the true probability distribution of the future. The entire point of constructing this, however, is to allow for this expectations mechanism to be "swapped out" with others -- recursive OLS, for example, or Bayesian learning, or even some sort of "meta-model selection" as in LeBaron et al. (1999). Regardless, I have not problems here (yet).

(2) is where I currently have an issue. The tricky thing is that the basic RBC model has three markets -- consumption, labor, capital. The price of consumption is fixed in the original, which I retained, so that market is fine. For the other two markets, my first pass was to essentially create an auctioneer and have it do the tatonnement process. Come up with a price, hand it to agents, gather supply and demand, adjust the prices "in the right direction," and hand them back. This is repeated in a single period until markets clear (supply and demand in all markets are within some epsilon). My first-pass attempt at this was to have a blindingly simple adjustment rule:

  p' = rho*(XD/XS)*p

where p' is the next-period price for the market under consideration, p is price this period, XD and XS are excess demand and excess supply, respectively, and rho is a simple "control" to allow adjustment of the process. This is similar to price adjustment in LeBaron et al. (1999), but here is multiplicative, and my goal here is market clearing each period. 

I quickly ran into some trouble -- my little RBC economy would run to zero in one or other of the markets fairly quickly. This, of course, may be due to a number of things -- I strongly suspect that my expectations process (initially, simple adaptive expectations) and/or the fact that I don't have a no-ponzi condition implemented (...yeah...) are the major things affecting my results. (I suspect I may be "stepping off the convergent path," as it were. Perhaps not technically correct in a discrete-time model...)

Those, however, are questions for another post. Right now, I'm simply trying to think a little better about the market-clearing process. Does anyone have any suggestions?  I've recently stumbled across the WALRAS algorithm (Cheng and Wellman 1998), but am largely unfamiliar with computational tatonnement-style market clearing. 

Ah, and I should note -- the purpose of all this is a few reasons -- one is just reproducing classic results (if possible) in a new way, another is giving myself a framework in which I can easily switch out expectational mechanisms and (eventually) incorporate various forms of agent heterogeneity in a general-equilibrium setting. It's also a fantastic way to review basic models and learn some of the newer developments in agent learning in macro.


References: 

Cheng and Wellman (1998), "The WALRAS Algorithm: A Convergent Distributed Implementation of General Equilibrium Outcomes," Computational Economics, 12(1): 1-24.

Hansen (1985), "Indivisible Labor and the Business Cycle," Journal of Monetary Economics, 16: 309-27.

LeBaron, Arthur, Palmer (1999), "," Journal of Economic Dynamics and Control, 23: 1487-1516

Schmitt-Grohe and Uribe (2004), “Solving Dynamic General Equilibrium Models Using a Second-order Approximation to the Policy Function,” Journal of Economic Dynamics and Control, 28(4): 755–75.

Uhlig (1997), "A toolkit for analyzing nonlinear economic dynamic models easily," Working paper.


## Answer 854

- posted by: [Hoemr](https://stackexchange.com/users/-1/594-hoemr) on 2012-01-17
- score: 0

http://people.brandeis.edu/~ghall/econ303/

Go down to the link:

"Matlab code that solves Hansen's divisible labor model and Burnside, Eichenbaum, and Rebelo's labor hording model. "




---

All content is licensed under [CC BY-SA 3.0](https://creativecommons.org/licenses/by-sa/3.0/).
