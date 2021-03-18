A `purchase_items` row must have a `state` that is one of three values:
Pending, Delivered, or Returned. We'd like to know for each U.S. state
(like VA, CA, or CT) how many purchase_items are in each state. (Sorry
that the term "state" is used in two different ways! 🙃)
Please `COUNT` the number of orders that we have in each state for each
U.S. state 😉. Order the results ascending by U.S. state first and
`purchase_items` state
second.
You might find the following SQL constructs useful in your answer: `JOIN`,
`ON`, `COUNT`, `GROUP`.

Your results should look something like this (these might not be correct results)
```
      state   | state | count 
   -----------+-------+-------
    Delivered | CO    |    89
    Pending   | CO    |     4
    Returned  | CO    |     5
    Delivered | FL    |    98
 