A `purchase_items` row must have a `state` that is one of three values:
Pending, Delivered, or Returned. We'd like to know for each U.S. state
(like VA, CA, or CT) how many purchase_items are in each state. (The term 
"state" in this database has two different meanings: a U.S. state and an item status! 🙃)
Please `COUNT` the number of orders that we have in each item state for each
U.S. state 😉. Order the results ascending by U.S. state first and
`purchase_items` state second. 

Please name your columns as `state`, `item_state`, and `count`, respectively.

You might find the following SQL constructs useful in your answer: `JOIN`,
`ON`, `COUNT`, `GROUP`.

Your results should look something like this:
```
│ state │ item_state │ count │
├───────┼────────────┼───────┤
│ CO    │ Delivered  │   112 │
│ CO    │ Pending    │    10 │
│ CO    │ Returned   │    11 │
│ FL    │ Delivered  │   152 │
│ FL    │ Pending    │    10 │
│ FL    │ Returned   │    11 │
│ GA    │ Delivered  │   129 │
│ GA    │ Pending    │     8 │
│ GA    │ Returned   │     3 │
│ IL    │ Delivered  │   104 │
(...)
```