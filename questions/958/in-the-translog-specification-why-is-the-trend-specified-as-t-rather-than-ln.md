## In the Translog specification, why is the trend specified as $t$ rather than $ln(t)$ [natural log(t)]?

- posted by: [seb](https://stackexchange.com/users/-1/684-seb) on 2012-02-13
- tagged: `econometrics`
- score: 0

A trend is usually used to proxy technical change in translog speciifcation of production, cost, profit, distance, etc functions. But can anyone explain why the trend is commonly specified as $t$ rather than $ln(t)$ like all other variables in a translog specification? I think the use of $t$ implies technology takes the form $e^t$.

Does the common use of $t$ instead of $ln(t)$ imply the exponential form is better than the alternative, and if so, why?



## Answer 959

- posted by: [mzuba](https://stackexchange.com/users/-1/219-mzuba) on 2012-02-13
- score: 1

Yes. What is the mathematical consequence of this setup? Constant technological advance will mean that production becomes more efficient by the same factor between two sequent periods. The specification $ln(t)$ would imply that technology has a larger inpact between periods 2 and 3 than between periods 10 and 11.

Compare with interest yield, where the specification is $i^{t}$. 


## Answer 967

- posted by: [seb](https://stackexchange.com/users/-1/684-seb) on 2012-02-13
- score: 1

Thanks mzuba! 
I also found that $lnt$ is not invariant to the starting point of $t$; i.e., $t$=1,2,3.. may give a different result than $t$ = 5, 6, 7....This may explain the popularity of the $t$ specification which is free from this problem though at the cost of being restrictive. A short and clear discussion of the issues is in a paper by Watts and Quiggins (1984) below
http://ageconsearch.umn.edu/bitstream/12259/1/52020091.pdf





---

All content is licensed under [CC BY-SA 3.0](https://creativecommons.org/licenses/by-sa/3.0/).
