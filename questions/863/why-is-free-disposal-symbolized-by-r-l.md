## Why is "free disposal" symbolized by -R+^L?

- posted by: [Luigi](https://stackexchange.com/users/-1/414-luigi) on 2012-01-19
- tagged: `microeconomics`
- score: 4

I've found on Mas-Colell (Microeconomic Analysis) a part about free-disposal. I've understood what it is (if you add one more unit of input, you will not get less output), but I don't understand why it is symbolized by $-\mathbb{R}^L_+$, where L is the number of commodities. I don't understand why that "minus" before the "real numbers" symbol. Could you help me? Thank you!


## Answer 867

- posted by: [Tom Au](https://stackexchange.com/users/-1/178-tom-au) on 2012-01-19
- score: 2

The minus refers to the "disposal" part. That is, you can have L commodities, and subtract (minus) one or more of them, without getting out of the set R. Not leaving the set means that the disposal is "free." If it weren't, you'd have to leave the set R to dispose of the commodity.


## Answer 1244

- posted by: [Frank](https://stackexchange.com/users/-1/659-frank) on 2012-04-18
- score: 2

Free disposal states that the production set $Y$ contains $Y-R^L_+$. This condition can be broken down as follows:

 - The part you were asking about is called the positive orthant:
$$
R^L_+:=\{x\in R^L: x_i\geq 0,\ i=1,...,L\}
$$
 - The full thing is then
$$
Y-R^L_+=\{z:z=y-x\text{ for some }y\text{ in }Y\text{ and some }x\text{ in }X\}
$$

So, free disposal says that starting from any $y$ in the set, we can increase inputs and reduce outputs (both of which are like subtracting some $x\geq0$ from $y$) and stay in the set.



---

All content is licensed under [CC BY-SA 3.0](https://creativecommons.org/licenses/by-sa/3.0/).
