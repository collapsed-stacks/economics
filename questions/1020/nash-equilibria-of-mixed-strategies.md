## Nash equilibria of mixed strategies

- posted by: [Marie. P.](https://stackexchange.com/users/-1/730-marie-p) on 2012-02-27
- tagged: `homework`, `game-theory`
- score: 0

I am given the following game to find nash equilibria in pure and mixed strategies:

 

$\begin{pmatrix}& & Litte John &\\ & & c & w \\Big John & c & (5,3) & (4,4) \\ & w & (9,1) & (0,0) \end{pmatrix} $

The pure-strategy equilibria will be if one plays $w$ and the other one $c$, no matter which one.

Now for the mixed strategy, I assigned the probabilities $p,1-p$ to strategies $c,w$ for big John, and $q,1-q$ for $c,w$ for little John, i.e.:

$\begin{pmatrix}& & Litte John &\\ & & q & 1-q \\Big John & p & (5,3) & (4,4) \\ & 1-p & (9,1) & (0,0) \end{pmatrix}$

Then I would create functions that show the Expectational value of bigJohn w.r.t. $p$, because he can only change his own strategy, hence 

$B(p)=5pq+4p(1-q)+9(1-p)q$, and similar for Little John, $L(q)=4pq+4p(1-q)+1(1-p)q$

Then we find the derivatives, $B'(p)=-8q+4$ and $L'(q)=-2p+1$. Then these are set equal to zero to maximize the payoff for both Johns, and then? Is that the end? I am suspicious to my solution because now everyone's optimal strategy mix will depend on the other's mix. Isn't it the purpose to maximize the payoff independent of the enemy player? Can somebody clear this up for me please?

## No Answers

There were no answers to this question.


---

All content is licensed under [CC BY-SA 3.0](https://creativecommons.org/licenses/by-sa/3.0/).
