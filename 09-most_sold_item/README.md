We would like to determine what items are the top ten best selling at the gift store. 

Please write a query that returns a product’s id, title, and the total quantity of 
that product sold (again, we will leave it to you to determine the relevant tables 🤪)

Please name your columns `product_id`, `product_title`, and `sum`, respectively. 

You might find the following SQL constructs useful in your answer: `JOIN`, `SUM`, `LIMIT`


Your results should look something like this:
```
│ product_id │  product_title   │ sum │
├────────────┼──────────────────┼─────┤
│         17 │ Documentary      │ 145 │
│         12 │ Holiday CD       │ 139 │
│         14 │ Pop CD           │ 139 │
│          2 │ Python Book      │ 137 │
│          6 │ Desktop Computer │ 135 │
│         13 │ Country CD       │ 133 │
│         16 │ Comedy Movie     │ 132 │
│         10 │ 42" Plasma TV    │ 128 │
│          4 │ Baby Book        │ 127 │
│          8 │ MP3 Player       │ 121 │
```