We would like to know how many pending items we have per state (e.g., CA, CT, etc.).

To figure that out, you'll need to `JOIN` the `purchase_items` and `purchases` tables, then
`GROUP BY` `purchases.state`. Limit your query where `purchase_items.state` equal `'Pending'`

You might find the following SQL constructs useful in your answer: `JOIN`, `ON`, `COUNT`, `GROUP BY`, `WHERE`

Your results should look something like this:
```
│ state │ num_items_pending │
├───────┼───────────────────┤
│ WY    │                 7 │
│ CO    │                10 │
│ TX    │                10 │
│ FL    │                10 │
│ SC    │                11 │
│ IL    │                 3 │
│ VA    │                 8 │
│ GA    │                 8 │
│ NY    │                 6 │
│ WA    │                 6 │
(...)
```