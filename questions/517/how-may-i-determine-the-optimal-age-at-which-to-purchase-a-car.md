## How May I Determine The Optimal Age At Which To Purchase A Car?

- posted by: [user8077](https://stackexchange.com/users/-1/71-user8077) on 2011-11-10
- tagged: `research`
- score: 3

Cars drop in value at different rates, but every car takes a huge drop in value when it is driven off the dealer's lot. For many cars there is historical data that shows approximately how quickly they will decrease in value. Eventually a car will start breaking down and become more trouble than it is worth. Therefore some people follow rules of thumb and buy 3-4 yr old cars with the intention of selling them when they are 8-9 years old. Is there a method of determining the optimal age at which to buy a car?


## Answer 518

- posted by: [Jason B](https://stackexchange.com/users/-1/26-jason-b) on 2011-11-10
- score: 1

I recall having a dynamic optimization problem almost exactly like this.  The prof had a habit of giving out general questions, and we had to come up with all of the assumptions needed to make the problem workable.   Since this looks like a homework problem, I'll answer in general: 

You can get pretty far by making some simplifying assumptions:

 - you derive constant known utility per unit time from having a car (ANY working car) or
 - you'd have to rent a car at some rate per day if you didn't own one

and that

 - maintenance cost, 
 - the market value of the car, and
 - the probability of major breakdown (incurring a known cost of repair)

are known functions of the age of the car (implicitly, the condition of the car is a function of its age).  The last assumption makes this a stochastic problem.

Then you find a buy date to maximize the expected PV of the net benefit stream.  How specific you can get depends on how much of the various functions you are able to specify (or how much you are willing to hold your nose and write them down) and you can make the problem more fun by adding more detail.

You can find similar examples in many dynamic optimization books (although they may not be about cars). 

Note that your (implicit) assumption that new cars aren't ever worth it has been questioned, see e.g. [Akerlof's (1970)](http://ideas.repec.org/a/tpr/qjecon/v84y1970i3p488-500.html) famous paper and the piles of articles that came after it.


## Answer 519

- posted by: [riotburn](https://stackexchange.com/users/-1/255-riotburn) on 2011-11-10
- score: 0

Ideally you would want to have data with fields like age of person, age of car, price, reason sold, price car was sold at after ownership, length of time a person had the car, repair costs over ownership, demographics of the person buying the car, type of car (luxury, sedan), etc.  It is this kind of data that will allow you to create consumer preference models and find your 'optimal age'.  You would also want to know location or at a minimum urban/suburban/rural because there is a huge change in consumer preference over these locations.  

If only you could get access to a big insurance company's data....



---

All content is licensed under [CC BY-SA 3.0](https://creativecommons.org/licenses/by-sa/3.0/).
