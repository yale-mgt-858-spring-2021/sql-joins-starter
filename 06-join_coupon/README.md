We would like to send a coupon by email to all our customers that have made 
at least 25 purchases in our store. Please write a query that shows customers’ emails 
and the number of purchases that particular customer has made. Your query should 
only return customers who have made 25 or more orders. Sort by descending number
of purchases.

To do this, JOIN the `users` table and the `purchases` table. Please name your columns `email` and `num_purchases`, 
respectively.

You might find the following SQL constructs useful in your answer: `JOIN`, `COUNT`, `HAVING`

Your results should look something like this:
```
│           email            │ num_purchases │
├────────────────────────────┼───────────────┤
│ Gudrun.Arends@gmail.com    │            30 │
│ Samatha.Hedgpeth@yahoo.com │            29 │
│ Romaine.Birdsell@aol.com   │            29 │
│ Derek.Crenshaw@gmail.com   │            27 │
│ Evelyn.Patnode@gmail.com   │            26 │
│ Zita.Breeding@gmail.com    │            26 │
│ Stacia.Schrack@aol.com        │            25 │
│ Vivian.Westmoreland@yahoo.com │            25 │
│ Granville.Hedgpeth@gmail.com  │            25 │
```