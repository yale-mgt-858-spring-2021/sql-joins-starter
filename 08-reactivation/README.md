Imagine that today’s date is January 1, 2020 (‘2020-01-01’). 

We would like to conduct a quick analysis to determine which 
of our customers have made more than 20 purchases from the gift store 
but did not purchase anything in December 2020 (i.e., within the last month). 

Write a query that returns the customer’s email, 
the number of purchases that customer has made, and the date of that customer’s last purchase 
(i.e., `JOIN` the `users` table and the `purchases` table). 

Please name your columns `email`,`num_purchases`, and `lastest_purchase`, respectively.

You might find the following SQL constructs useful in your answer: `JOIN`, `MAX`, `HAVING`, `NOT BETWEEN`.
And, for the `WHERE/HAVING` filter on the date, you might use something like 
`'2020-01-01'::date - '1 month'::interval`, which is what we use in the answer key 😎.
The `::` syntax is the PostgreSQL way to "cast" or "coerce" one variable type
to another. It's particularly useful with "intervals", so you can do stuff
like `'3 weeks'::interval` or `'5.6 hours'::interval` and then add or subtract it
to a date.

Your results should look something like this:
```
│           email            │ num_purchases │    lastest_purchase    │
├────────────────────────────┼───────────────┼────────────────────────┤
│ Layne.Sarver@aol.com       │            22 │ 2019-11-25 07:53:00+00 │
│ Ozella.Yoshimura@gmail.com │            23 │ 2019-11-15 11:36:00+00 │
│ Wynona.Greening@aol.com    │            21 │ 2019-11-26 12:09:00+00 │
```