## Multiple solutions for optimal policy with forward looking variables: How to make sense of this?

- posted by: [Har](https://stackexchange.com/users/-1/62-har) on 2011-10-12
- tagged: `theory`, `monetary-policy`
- score: 7

In the paper [Indicator variables for optimal policy][1] by Svensson and Woodford, optimal policy in a linear-quadratic model with forward looking variables is discussed (for example, a forward looking variable can be inflation expectations).

The difficulty with optimal policy for forward looking variables is that the forward looking variables themselves are dependent on policy. For example, if the market thinks that the central bank will raise the interest rate in the future, inflation expectations today will be lowered and the market will be affected. To solve this, it is assumed that the private sector knows that the social planner will optimize at each time, and can thus form its expectations accordingly. Through some clever manipulations, Svensson and Woodford are able to reduce the problem of optimal policy to solving for the Kalman gain matrix.

They derive the formula $$K =PL'(LPL'+\Sigma_{vv})^{-1}$$ where P in turn can be solved for from $$P = H(P-PL'(LPL'+\Sigma_{vv})^{-1}LP)H'+\Sigma_{uu}$$

Never mind the exact expression (if you are interested, the definitions of all the symbols are all in the paper). However, it is not a priori obvious that the above equation has a unique solution (and I believe I know of cases when this does indeed have several legitimate solutions).

My question is as follows:
If it is true that the optimal policy problem has several solutions, and the private sector forms its opinions based on the assumption of optimal policy, how does the private sector know which optimal policy the central planner will pick?

Caveat: I am not a trained economist. This is all me trying to make sense of the paper, and if there are some things I say that are wrong, I would appreciate this being pointed out. Feel free to edit both title and tags.

  [1]: http://ideas.repec.org/a/eee/moneco/v50y2003i3p691-720.html


## Answer 170

- posted by: [EnergyNumbers](https://stackexchange.com/users/-1/104-energynumbers) on 2011-10-15
- score: 2

To reflect briefly on Svensson and Woodford's model of optimal-policy choice; as George Box said: all models are wrong - some models are useful. If their formulation of policy choice really does imply that there is always a unique, knowable solution, then their model is not useful for cases where we can demonstrate that there is *not* a unique knowable solution.

It's not difficult to construct a set of scenarios where the optimal policy problem has several solutions, or at least, one where the uncertainties swamp the expected welfare differences between solutions, so that there is no *significant* difference in total expected welfare between solutions. 

And so, to answer the direct question: in such cases as above, the private sector *cannot* know which optimal policy the central planner will pick. Private-sector players will have to make a differential diagnostic: they will have to analyse where policy trajectories would fork, for the different solutions, and watch policy announcements for those forks, and only then, invest accordingly (or, depending on the distribution of potential gains and losses, they might invest partially in all possible optimal outcomes, until a policy decision makes at least one outcome non-optimal).

Take, for example, the decarbonisation of electricity: it might be the case that in a current electricity market, neither PV, nor biomass, nor offshore wind, can compete with incumbents; but that with research funding and market reform, any one of them could be cheaper than either of the other two, and cheaper than the incumbents.  Let's say that the uncertainties around future costs, after economies of scale, mean that there is no significant difference in costs between a PV-dominant grid, a biomass-dominant grid, or an offshore-wind dominant grid; but that any of these is cheaper than a grid with no single dominant technology.

Now, for the policy-maker in this scenario, there is nothing to choose between supporting PV, supporting biomass, or supporting offshore wind, all other things being equal. Which makes it impossible for the private sector to know where to invest.  Only when a long-term policy commitment (one that the market can trust) is made that uniquely benefits one of the three, will the direction be certain.


## Answer 116

- posted by: [Zermelo](https://stackexchange.com/users/-1/68-zermelo) on 2011-10-12
- score: 0

I am not a macroeconomist, but I read this paper a few years ago for a Master's project.

I suspect that the authors were interested in making a stylized model to convey an idea, and are not necessarily concerned with the actual mechanics of solving the model out. The authors would argue that as long as the model is used only to illustrate an idea (and is not being used in some real application), this is not a big problem (I don't agree, but I suspect many others do).



---

All content is licensed under [CC BY-SA 3.0](https://creativecommons.org/licenses/by-sa/3.0/).
