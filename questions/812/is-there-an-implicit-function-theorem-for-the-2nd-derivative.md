## Is there an implicit function theorem for the 2nd derivative?

- posted by: [richardh](https://stackexchange.com/users/-1/28-richardh) on 2012-01-05
- tagged: `microeconomic-theory`
- score: 1

I will provide some context for my question. I am reading Kaplan and Zingales (QJE 1997) where each firm selects $I$ to solve $\max F(I) - C(E, k) - I$, such that $I = W + E$, where $I$ is total investment, $W$ is investment from internal funds, and $E$ is investment from external funds.

The first order condition is $F_1(I) = 1 + C_1(I - W, k) = 0$, which provides an implicit function to find their result for the first derivative $$\frac{dI}{dW} = \frac{C_{11}}{C_{11} - F_{11}}$$ using the implicit function theorem. And I can get their result for for the second deriviative $$\frac{d^2I}{dW^2} = \frac{F_{111} C^{2}_{11} - C_{111}F^{2}_{11}}{(C_{11} - F_{11})^3}$$ the "long way" (for lack of a better term), but is there an implicit function theorem for the second derivative? Thanks.


## Answer 920

- posted by: [Dimitris](https://stackexchange.com/users/-1/11-dimitris) on 2012-02-04
- score: 1

Yes, there is, it is the one and only implicit function theorem: when $z = f(x,y)$ with $f\in C^n$ ($n$ times continuously differentiable) and $f_y(x,y)\neq 0$, we can apply the IFT in order to express e.g. variable $y$ as a function $\phi$ of $z,x$. Then $\phi$ is $C^n$, with the partial derivative
$$\phi_x := \frac{\partial y}{\partial x} = -\frac{f_x(x,y)}{f_y(x,y)}$$
and the second-order derivative $\phi_{xx}$ obtained as $\frac{\partial }{\partial x}\phi_x$.

In other words, the IFT guarrantees existence of $\phi$, and its smoothness up to order $n$ when $f$ is smooth up to order $n$; whenever you can, you have to derive it "by hand" or "the long way", as you put it.


## Answer 814

- posted by: [JDrama](https://stackexchange.com/users/-1/529-jdrama) on 2012-01-05
- score: 0

in case your looking for an easy way to find this second derivative, take the first derivative and use the quotient rule to find the second derivative, this way it is really simple.
the quotient rule is very simple to use.
if you have F(x) = g(x)/h(x) the derivative of F(x) is
F'(x)= ( h(x).g'(x) - h'(x).g(x) ) / (h(x))^2.   

g'(x) is the derivative for g(x) and so on.
 



---

All content is licensed under [CC BY-SA 3.0](https://creativecommons.org/licenses/by-sa/3.0/).
