Imagine that today’s date is January 1, 2021 (‘2020-01-01’). 

We would like to conduct a quick analysis to determine which 
of our customers have made more than 20 purchases from the gift store 
but did not purchase anything in December 2020 (i.e., within the last month). 

Write a query that returns the customer’s email, 
the number of purchases that customer has made, and the date of that customer’s last purchase 
(i.e., `JOIN` the `users` table and the `purchases` table). 

Please name your columns `email`,`num_purchases`, and `lastest_purchase`, respectively.

You might find the following SQL constructs useful in your answer: `JOIN`, `MAX`, `HAVING`, `NOT BETWEEN`

Your results should look something like this:
```
│           email            │ num_purchases │    lastest_purchase    │
├────────────────────────────┼───────────────┼────────────────────────┤
│ Layne.Sarver@aol.com       │            22 │ 2019-11-25 07:53:00+00 │
│ Ozella.Yoshimura@gmail.com │            23 │ 2019-11-15 11:36:00+00 │
│ Wynona.Greening@aol.com    │            21 │ 2019-11-26 12:09:00+00 │
```