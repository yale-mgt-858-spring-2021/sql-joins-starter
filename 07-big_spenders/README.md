Please make a list of customer emails for customers that have spent more than $10,000 in the gift store 
(i.e., greater than $10,000). To do this, you’ll need to join *three* tables in the gift_store schema 
(now that you are familiar with this database, we'll let you determine what tables are relevant 😎).
Please sort in descending order of net spend.

For this query, remember that revenue (or spend) equals price * quantity 💰.

You might find the following SQL constructs useful in your answer: `JOIN`, `ON`, `SUM`, `HAVING`

Please name your columns `email` and `net_spend`, respectively.

Your results should look something like this:
```
│           email            │ net_spend │
├────────────────────────────┼───────────┤
│ Zita.Breeding@gmail.com    │  13204.57 │
│ Earlean.Bonacci@yahoo.com  │  12577.61 │
│ Theresia.Edwin@yahoo.com   │  12224.53 │
│ Samatha.Hedgpeth@yahoo.com │  12109.45 │
│ Derek.Crenshaw@gmail.com   │  11651.52 │
│ Ozella.Roles@gmail.com     │  11525.50 │
│ Zita.Luman@yahoo.com       │  10397.50 │
│ Shanell.Maxson@gmail.com   │  10228.71 │
```