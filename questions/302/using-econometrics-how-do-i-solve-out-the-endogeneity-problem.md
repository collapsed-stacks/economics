## Using econometrics, how do I solve out the endogeneity problem?

- posted by: [Aarthi](https://stackexchange.com/users/-1/1-aarthi) on 2011-10-22
- tagged: `econometrics`
- score: 6

I had a project from before I graduated from college that was effectively me acting as a research aid to a politician. The project served as my senior thesis, as well. The portion of the report that I was working on focused on determining the effect of new fuel economy legislation for heavy-duty vehicles, such as 18-wheelers or large lorries and their drivers. 

I managed to get the data cleaned up and put together, but when I ran a regression (with dummy variables for year, region, etc) I realized that I was seeing the [police-and-crime][1] problem in action: wages affected employment which affected wages etc. Indeed, I checked the regression by running it once with wages and employment against one another and had a *very* significant p-value spit back out at me, with a 99% R-value -- making me realize that I had a problem.

I know that I need to find some variable that only affects one (wages or employment) but not the other. (In the Levitt paper, he uses elections, which affect police presence and not crime.) What type of variable would this be in my wage/employment model? Are there other ways of working around the endogeneity problem?

I can post data if it is requested, though my question is more conceptual than data-focused.


 [1]: http://socserv.socsci.mcmaster.ca/bjerk/PublicPapers/Levitt97.pdf

## No Answers

There were no answers to this question.


---

All content is licensed under [CC BY-SA 3.0](https://creativecommons.org/licenses/by-sa/3.0/).
