## What is the Swing Voter's Curse in voting theory?

- posted by: [Zermelo](https://stackexchange.com/users/-1/68-zermelo) on 2011-10-11
- tagged: `voting`
- score: 3

While reading papers on voting theory, one often comes across refers to the Swing Voter's Curse. What is this curse, and under what conditions does the curse apply? Is it possible to explain in brief why voters choose to abstain?


## Answer 142

- posted by: [Ryan](https://stackexchange.com/users/-1/124-ryan) on 2011-10-13
- score: 6

As background information, you might want to first read Feddersen and Pesendorfer's 1994 paper "[Voting Behavior and Information Aggregation in Elections with Private Information](http://www.ssc.upenn.edu/ier/Political%20Economy%20Archives/Political%20Economy%20Pubs/Voting%20Behavior%20and%20Information%20Aggregation.pdf)." 

The conclusion is essentially that "elections fully aggregate [private] information in the sense that the chosen candidate would not change if all private information were common knowledge." They do *not* consider abstention in this paper. 

The paper that Matthew linked ([Feddersen, Pesendorfer 1995](http://www.econ.ucsb.edu/~tedb/Courses/UCSBpf/readings/curse.pdf)) has a model that is very closely related to their 1994 paper. In this paper, they do allow for abstention. Their proposition 1 states that abstention is strictly preferred by uninformed voters (when they are indifferent between the candidates and when no agent uses a strictly dominated strategy). The intuition they provide for this result is contained in the following. We assume that "all informed independents vote for the correct candidate in each state" and "the correct candidate for the UIA [uninformed independent agents] is the candidate favored by the informed independent voters." 

> [T]he uninformed voter strictly prefers to abstain because the only
> way her vote effects the outcome is if she votes for the candidate not
> supported by the informed voter, i.e., the wrong candidate. Given the
> behavior by the other voters, uninformed voters suffer the swing
> voter's curse: they are strictly better off abstaining than by voting
> for either candidate. This is true even though uninformed voters
> believe that the status quo is almost certainly the best candidate. 

For an experimental analysis of this phenomenon, check out [Battaglini, Morton, Palfrey 2008](http://www.princeton.edu/~mbattagl/swingvoter.pdf). Their laboratory results are consistent with the equilibrium predictions of Feddersen and Pesendorfer's paper. 



---

All content is licensed under [CC BY-SA 3.0](https://creativecommons.org/licenses/by-sa/3.0/).
