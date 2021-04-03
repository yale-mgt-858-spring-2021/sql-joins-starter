What is the quantity of items sold by product title? 

Write a query that returns the title of each product and the 
total quantity of sales for that product. 

To do this, JOIN the `purchase_items` table with the `products` table and return the relevant columns 
(call your columns product and units_sold, respectively). 

You might find the following SQL constructs useful in your 
answer: `JOIN`, `SUM`, and `GROUP BY`
  
Your results should look something like this:
```
│     product      │ units_sold │
├──────────────────┼────────────┤
│ 42" LCD TV       │        118 │
│ Baby Book        │        127 │
│ Classical CD     │         93 │
│ Desktop Computer │        135 │
│ Holiday CD       │        139 │
│ Coloring Book    │        115 │
│ Laptop Computer  │         97 │
(...)
```