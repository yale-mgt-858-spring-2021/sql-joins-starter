A `purchase_items` row must have a `state` that is one of three values:
Pending, Delivered, or Returned. We'd like to know for each U.S. state
(like VA, CA, or CT) how many purchase_items are in each state. (Sorry
that the term "state" is used in two different ways! 🙃)
Please `COUNT` the number of orders that we have in each state for each
U.S. state 😉. Order the results ascending by U.S. state first and
`purchase_items` state second. You *do not* need to show rows that
have a zero count. For example, if CT has zero items in a state
of "Pending" you do not need to show a row for that.

You might find the following SQL constructs useful in your answer: `JOIN`,
`ON`, `COUNT`, `GROUP`.

Your results should look something like this:
```
│ state │ item_state │ count │
├───────┼────────────┼───────┤
│ CO    │ Delivered  │    89 │
│ CO    │ Pending    │     4 │
│ CO    │ Returned   │     5 │
│ FL    │ Delivered  │    98 │
│ FL    │ Pending    │     5 │
│ FL    │ Returned   │     7 │
│ GA    │ Delivered  │    86 │
│ GA    │ Pending    │     4 │
│ GA    │ Returned   │     6 │
│ IL    │ Delivered  │    81 │
│ IL    │ Pending    │     3 │
(...)
```