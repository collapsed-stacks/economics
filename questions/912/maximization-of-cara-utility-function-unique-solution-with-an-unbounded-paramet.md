## Maximization of CARA utility function: unique solution with an unbounded parameter?

- posted by: [Marco](https://stackexchange.com/users/-1/650-marco) on 2012-02-03
- tagged: `investment`, `utility-function`, `microeconomic-theory`, `optimization`
- score: 2

I previously posted in quantitative finance and an user correctly addressed me here. I'm sorry for the duplicate. 

An investor at time $t_0$ can invest his wealth $w_0$ in a risky asset $x$ for an amount $a$ and the remain part in the riskless asset $w_0-a$.

At the end of the period $t_1$, the investor will obtain the wealth $w$:
$$
w = a(1+x)+(w_0-a)(1+r_f)
 =a(x-r_f)+w_0(1+r_f).
$$
Using a CARA (exponential negative) utility function we have,
$$
U(w)=-e^{-\lambda w}=-e^{-\lambda a(x-r_f)+w_0(1+r_f)}
$$
where $\lambda$ is an exogenous parameter for the risk coefficient aversion.
Then taking its expectation, it is clear that its maximization it does not depend on $w_0$ that is a fixed quantity but from $a$,
$$
\max_a\textrm{ }E[U(w)]=E[-e^{-\lambda a(x-r_f)}\times e^{w_0(1+r_f)}]
$$
where $e^{w_0(1+r_f)}$ is a fixed quantity $\tilde{q}$,
$$
\max_a\textrm{ }E[U(w)]=E[-e^{-\lambda a(x-r_f)}\times \tilde{q}]
$$
Here is my problem,
$$
\max_a\textrm{ }E[U(w)]=E[-e^{-\lambda a(x-r_f)}]
$$
If $a$ is unbounded this expected function has no point of maxima. It goes to infinity. So $a$ must be bounded and depends from the budget constraint of the initial wealth $w_0$. 
The professor by mail told me that is a well know result in finance and $a$ exists as an unique optimal solution. 

Because many authors set $w_0 = 0$ for convenience, so what are the implications for $a$? I don't get this point, it seems that $a$ exists and is unique without any assumption. It is clear that we need a budget constraint so if we bounded $a$ the maxima of the expected utility will be on the bound of $a$. Not make sense to maximize. Where am I wrong?


## Answer 918

- posted by: [Dimitris](https://stackexchange.com/users/-1/11-dimitris) on 2012-02-04
- score: 1

 Couple of points on terminology:

1. For a function $u$, we define the *risk aversion function* by $r_u(x):=-\frac{u''(x)}{u'(x)}$. In your utility function, $r_u(x) = \lambda$; hence, it is a *constant* absolute risk aversion utility and $\lambda$ is the "coefficient of risk aversion," not the "risk coefficient aversion".

2. The two points in time, $t_0,t_1$ can be seen as "beginning of period" and "end of period", where "period" is here the time interval $[t_0,t_1]$. This may be important: you don't need a dynamic approach as was suggested by some people. The guy in your problem allocates $a$ to the risky asset and $w_0-a$ to the riskless, over a time interval included between $t_0$ and $t_0$.

3. Your problem is the basic, canonical portfolio choice model with utility over final wealth. The guy in your problem just consumes what he has in the end of the time period. This is also important to bear in mind.

4. It's "negative exponential", not "exponential negative".

4. Rewrite $w(a)$ for final wealth (end of period, or at $t_1$); it depends on $a$, i.e. the part of $w_0$ that is invested in the risky asset. Your problem is:

$$\max_a \;E[U(w(a)] = \max_a \;E[-e^{-\lambda(x-r_f)}]$$

Let $\chi = x-r_f$, i.e. the *excess* return of the risky asset (relative to the risk-free). Denote its distribution function by $dF(\chi)$ and hence

$$ \max_a \;E[-e^{-\lambda\chi}] = \max_a \;\int -e^{-\lambda z} dF(z)$$

Let $a^* = \arg\max_a \;E[U(w(a))]$. The following condition should hold in order for the (interior) optimum $a^*$ of this function to be bounded (note the redundancy in what I wrote just now):

> Assumption (I) The values of the excess return random variable $\chi = x - r_f$  alternate in sign, i.e. $\chi$ takes values $\underline{\chi}\leq 0 \leq \overline{\chi}$ with positive probability.

If $\chi$ was positive *almost surely*, then $a$ is unbounded precisely because the objective is unbounded, as you very well understood from the beginning. Hence, Assumption (I) should be retained.

Trust your intuition - your professor is wrong.

Addendum:

if $a^*\rightarrow \infty$, i.e. if the optimal solution is unbounded, then the *derivative* of the expected utility evaluated at the optimal solution is zero - and since this doesn't make any sense, you have to rephrase it as 

$$ \lim_{a\rightarrow\infty} E\left[\frac{d}{da}U(w(a)) \right] = 0 $$

Now $U$ is concave. Hence, in order for $a^* \rightarrow \infty$ not to be a critical point, you have to have

$$ \lim_{a\rightarrow\infty} E\left[\frac{d}{da}U(w(a)) \right] <0  $$

and not positive. Replace the parametric form, take the derivative, and you will find a (strict) inequality relating the distribution function and the marginal utility at the limits.

And since this is supposed to be a hint and not a homework helpdesk, I have to stop here :) Already, you were right in your original answer, but you have to *prove* it as well.


## Answer 913

- posted by: [PGR](https://stackexchange.com/users/-1/632-pgr) on 2012-02-03
- score: 0

The traditional way of looking at problems such as these (have a look at the work of Andrew Abel, for example) is to choose a level of consumption $c$ that maximizes expected utility s.t. a budget constraint. The more the agent consumes, the less he saves. What you have here, in addition to an optimal saving (or consumption) problem, is a portfolio problem, i.e. the choice of how much to put in the risky asset vs. the risk-free asset. 

The optimal $a^*$ will obviously be dependent not only on the average return of the risky asset, $x$, over the risk-free return, $r_f$, but also on the volatility or variance of the returns. 

Think about it a little: what influences the choice between stocks and bonds? Certainly not just the average return, otherwise no one would invest in bonds. Stocks earn more on average but they are also riskier.



---

All content is licensed under [CC BY-SA 3.0](https://creativecommons.org/licenses/by-sa/3.0/).
