## What is the significance of the "residual maker" matrix?

- posted by: [Patience](https://stackexchange.com/users/-1/14-patience) on 2011-10-25
- tagged: `econometrics`
- score: 2

I'm studying economics and came across this matrix $M = (I-X(X'X)^{-1}X')$ in my econometrics module. However, I don't find much info on it online, could you explain the significance of this matrix in economics?


## Answer 319

- posted by: [Jason B](https://stackexchange.com/users/-1/26-jason-b) on 2011-10-25
- score: 3

I tend to agree that this isn't really an economics question... it is a regression question without any economic context.  In any case...

We know the OLS formula for $\hat{\beta}$ in matrix notation is $\hat{\beta}=(X'X)^{-1}(X'Y)$. 

Then $\hat{Y}=X\hat{\beta} =X(X'X)^{-1}(X'Y)$

So the residuals are $e=Y-\hat{Y}=Y-X(X'X)^{-1}(X'Y)$. Pulling out $Y$, We can write this as $e=(I-X(X'X)^{-1}X')Y$.  

Define $M\equiv I-X(X'X)^{-1}X'$ (the "residual maker").  Then, notice that for any vector, $Y$, $MY$ will yield the OLS residuals from a regression of $Y$ on$X$.

This is a commonly encountered type of "orthogonal projection matrix" (along with $P\equiv X(X'X)^{-1}X'$, so $M=I-P$).  They are convenient largely because they are both idempotent (e.g. $MM=M$) and they are mutually orthogonal (e.g. $MP=PM=0$)--see Greene's text for a number of proofs and derivations that rely on these properties.

> could you explain the significance of this matrix in economics?

To my knowledge, the matrix has no particular economic interpretation or importance beyond its use in statistics/econometrics.



---

All content is licensed under [CC BY-SA 3.0](https://creativecommons.org/licenses/by-sa/3.0/).
