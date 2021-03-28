We would like to know how many pending items we have per zipcode.
(To figure that out,
you'll need to `JOIN` the
`purchase_items` and `purchases` tables, then
`GROUP` by `purchase_items.state`
and `purchases.zipcode`.)
You might find the following SQL constructs useful in your answer: `JOIN`, `ON`, `COUNT`, `GROUP BY`.

Your results should look something like this (these might not be correct results)
```
    state  | zipcode | total 
  ---------+---------+-------
    Pending |   41569 |     1
    Pending |   38012 |     1
    Pending |   19175 |     1
    Pending |   99867 |     1
```