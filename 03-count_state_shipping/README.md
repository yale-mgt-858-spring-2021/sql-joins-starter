We would like to know how many pending items we have per state (like CA, CT, etc.).
To figure that out,
you'll need to `JOIN` the
`purchase_items` and `purchases` tables, then
`GROUP` by `purchase_items.state`
and `purchases.state`.
You might find the following SQL constructs useful in your answer: `JOIN`, `ON`, `COUNT`, `GROUP BY`.

Your results should look something like this:
```
│ state │ num_items_pending │
├───────┼───────────────────┤
│ WY    │                 3 │
│ TX    │                 3 │
│ FL    │                 5 │
│ CO    │                 4 │
│ SC    │                 8 │
│ IL    │                 3 │
│ VA    │                 8 │
│ WA    │                 4 │
│ GA    │                 4 │
│ NY    │                 5 │
(...)
```