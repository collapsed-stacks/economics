## In supply and demand, how do you calculate what the demand is?

- posted by: [Community](https://stackexchange.com/users/-1/-1-community) on 2012-04-18
- tagged: `demand`, `games`
- score: 0

I have a basic question regarding Supply and Demand.  I am attempting to program a game that uses a very loose interpreation of supply/demand.  

In the examples I have seen online all assume you know what your demand is and can enter them into an excel spreadsheet, but this isn't always the case.

In my game, I have no idea what the demand is going to be.

I'm trying to calculate what the demand is, given a price and a product.

Product: Beer
Price: $10
Supply: 80 kegs

What is the demand?  This is what I am struggling with.

Thank you.



## Answer 1253

- posted by: [Dimitriy V. Masterov](https://stackexchange.com/users/-1/407-dimitriy-v-masterov) on 2012-04-19
- score: 2

<p>The demand is a relation between the price of a good and how much of it a consumer chooses to buy. Demand may also depend on other factors, like income, prices of competing or complementary products, weather, etc.. It ultimately stems from the preferences of people (things like I prefer an orange to a banana). You may also add up the individual consumer's demand curves up into a single market demand. </p>

<p>There are two ways to get demand curves:</p>

<ol>
<li>If I know a lot about your preferences, under certain conditions, they can be represented by a mathematical functions called utility functions. Doing a bunch of calculus and algebra to any of these functions, subject to the constraint of how much money you have to spend, will give you a demand curve for each consumer.</li>
<li>The other way is to figure out demand curves is to do a whole lot econometric analysis (statistics plus economics theory) on consumer data. This is also non-trivial. </li>
</ol>

<p>I don't know if you're talking about modeling the demand of characters, in which case (1) is what you need. If you're talking about the demands of players, it's probably (2), which is tricky since you don't have any data about game yet.</p>

<p>In any case, take a look at <a href="http://mypage.iu.edu/~castro/home.html" rel="nofollow">Edward Castranova's book and papers.</a> I think he's the guy who knows the most about video game economics out there.</p>



## Answer 1256

- posted by: [Owe Jessen](https://stackexchange.com/users/-1/81-owe-jessen) on 2012-04-19
- score: 0

I think for the application (using supply and demand in a game) you would probably be best of if you construct a basket of products your consumers will buy, giving them priorities, wheights for surplus income and limits, e. g. 

    Product Prio InitialSize Wheight Limit
    Bread   1    1           0.2     4
    Beer    2    1           0.3     7
    Clothes 1    1           0.2     3

You could then construct a waterfall, buying things first with the highest prio, up to a limit, with increasing demand depending on personal income. I think in general a good way to simulate personal behaviour in a game would be to ask: How would a normal person behave? Define necessities, then nice to haves, than luxury goods, distribute the income, and have rules for adjusting. This level only makes sense if you are simulating individual demand. If you are fine with aggregated demands, you can construct demand curves depending on aggregate income and a general distribution of differences in income onto the products. 


## Answer 1290

- posted by: [The Butterfly](https://stackexchange.com/users/-1/907-the-butterfly) on 2012-04-23
- score: 0

If you have a list such as:

    Product: Beer
    Price: $10 Supply: 80  kegs
    Price: $7  Supply: 100 kegs
    Price: $5  Supply: 120 kegs
    Price: $3  Supply: 140 kegs
    Price: $2  Supply: 160 kegs

Then the demand is the list itself.

When you plot the list, you get the demand curve.



---

All content is licensed under [CC BY-SA 3.0](https://creativecommons.org/licenses/by-sa/3.0/).
