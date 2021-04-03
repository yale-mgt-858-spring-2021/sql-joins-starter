In this assignment, we will be working with the `gift_store` schema
which contains the following tables: `purchase_items`, `products`
`purchases`, and `users`. (One little confusing thing about the
schema: the `purchases` table is showing the name and address
of the gift recipient, not necessarily the name and address of
the customer who made the purchase. Sorry...I find this a 
little confusing and I suspect you will.  ¯\_(ツ)_/¯ We avoided
most queries involving the gift recipient name and address. )

You are an employee at the gift store that maintains this database.
Management has an upcoming meeting and wants us to conduct a few
analyses. 

A management report requires us to list certain purchase information
along with the email address of the user making the purchase. Please
`JOIN` the `purchases` table with the `users` table to produce an 
output table containing
`purchases.id`,
`purchases.name`,
`purchases.address`,
`purchases.state`,
`purchases.zipcode`, and
`users.email`.
You might find the following SQL constructs useful in your answer: `JOIN`, `ON`.
Make sure you get the column names right! E.g., here we named the `purchases.id`
column `purchase_id` to make it more clear than a column called `id`, which would
be ambiguous without the SQL query (is it user id or product id!?). In general,
you'll need to match the column names and column orders in all the questions!

Your results should look something like this:
-
```
│ purchase_id │         name           │        address         │ state │ zipcode │            email              │
├─────────────┼────────────────────────┼────────────────────────┼───────┼─────────┼───────────────────────────────┤
│           1 │ Harrison Jonson        │ 6425 43rd St.          │ FL    │   50382 │ Quinton.Gilpatrick@yahoo.com  │
│           2 │ Cortney Fontanilla     │ 321 MLK Ave.           │ WA    │   43895 │ Salvatore.Arends@aol.com      │
│           3 │ Ruthie Vashon          │ 2307 45th St.          │ GA    │   98937 │ Ozella.Yoshimura@gmail.com    │
│           4 │ Isabel Wynn            │ 7046 10th Ave.         │ NY    │   57243 │ Shanell.Lichtenstein@aol.com  │
│           5 │ Shari Dutra            │ 4046 8th Ave.          │ FL    │   61539 │ Claud.Westmoreland@aol.com    │
│           6 │ Kristofer Galvez       │ 2545 8th Ave.          │ WA    │   83868 │ Sherilyn.Hamill@gmail.com     │
(...)
```