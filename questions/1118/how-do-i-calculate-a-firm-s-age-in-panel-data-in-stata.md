## How do I calculate a firm's age in panel data in STATA?

- posted by: [Barba Sol](https://stackexchange.com/users/-1/788-barba-sol) on 2012-03-15
- tagged: `stata`
- score: -1

I have a bunch of firms and the date they were started, but don't know the exact code to give me the age of each firm. Can anyone help?


## Answer 1122

- posted by: [John](https://stackexchange.com/users/-1/790-john) on 2012-03-15
- score: 1

First get the start date into a STATA date variable, then use this and c(current_date) to get the firm's age.

See "Computations with elapsed dates" at <http://www.ats.ucla.edu/stat/stata/modules/dates.htm>, and <http://www.stata.com/support/faqs/data/dateandtime.html>.



---

All content is licensed under [CC BY-SA 3.0](https://creativecommons.org/licenses/by-sa/3.0/).
