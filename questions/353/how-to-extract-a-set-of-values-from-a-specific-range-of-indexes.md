## How to extract a set of values from a specific range of indexes

- posted by: [methusaleh](https://stackexchange.com/users/-1/212-methusaleh) on 2011-10-27
- tagged: `homework`
- score: 1

I'm having some difficulty with a "chaining indexes" question I've come across in my statistics module:

> An insurance company uses a index to describe the number of agents working for it. Starting ten years ago, the index (index 1) takes the values 110, 125, 142, 167, 185, 207 (for consecutive years. The index is then re-based so that the value of the new index is 100 in the same in the year that the old index is 207. The new index (index 2) then takes the values 95, 87, 83, 76 for the next four consecutive years.

1) If the company had not changed to index 2, what values would index 1 have in years 7-10

2) What values would index 2 have in years 1-5?

**3) If the company had 486 agents in year 8, how many did it have in each of the other years?**

I have answered question 1) and 2) [here][1]. Would appreciate any help in q3).

  [1]: http://licf.ronaldboadi.com/Book2-q3-1.pdf


## Answer 354

- posted by: [Jason B](https://stackexchange.com/users/-1/26-jason-b) on 2011-10-27
- score: 1

Think about what it means for the second index to equal 97 in year 8 (and, contrary to your linked answer, is it not given that this value is 97 and not 87 as you wrote, or is the text in your question transcribed incorrectly above?).  What percentage of year 6's index value is that?   Then, if you know the number of agents for year 8, you can derive the number for year 6.  

Since year 6 is the base year of the second index, if you derive the number of workers for year 6, would it then be trivial to use that value to derive the number of workers in the other years?


## Answer 356

- posted by: [Zermelo](https://stackexchange.com/users/-1/68-zermelo) on 2011-10-28
- score: 1

If 87 is the index-2 for 486 what would twice of 87 represent? what about 1.5 times 87? How many times 87 is index for year 7? So then what value does the year 7 index represent? This should be enough of a hint to help you solve the third part.


## Answer 357

- posted by: [Nick Toller](https://stackexchange.com/users/-1/215-nick-toller) on 2011-10-28
- score: 1

Base year's are chosen to provide a relative measurement of change over time. Occasionally they are re-chosen (or the the index re-based) so the variation from year to year gives a more accurate depiction of real change, and doesn't include compounded nominal change (the compounded increase in prices due to inflation). Or in the case of changes in staff or some other variable, it makes the proportionate change more easily observable. A change of 2349.22 to 2584.142 is an increase, but the proportion is not easily observable. Making 2349.22 the base year with a value of 100, the value of the second year becomes 110; and the proportionate change is easily observable.

1. To answer question 1 for year 7, first determine how to equate the value 207 to the base year value of 100. specifically:  
207/x = 100
x = 207/100
x = 2.07

The values for years 7-10 have been altered so that they represent the change from the base year, but not they're real value. For year 7:
y/2.07 = 95
y = 95 x 2.07
y = 196.65


2. to answer question 2, reverse the process above.

3. to answer question 3, consider year 8 to be your base year with a value of 486, and a base of 97. Then determine how 486 can be equated to 97, and then use that same operation to equate the base values to real values.



---

All content is licensed under [CC BY-SA 3.0](https://creativecommons.org/licenses/by-sa/3.0/).
