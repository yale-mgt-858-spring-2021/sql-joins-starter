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

Your results should look something like this (these might not be correct results)
```
  id  |          name          |        address         | state | zipcode |             email             
------+------------------------+------------------------+-------+---------+-------------------------------
    1 | Harrison Jonson        | 6425 43rd St.          | FL    |   50382 | Quinton.Gilpatrick@yahoo.com
    2 | Cortney Fontanilla     | 321 MLK Ave.           | WA    |   43895 | Salvatore.Arends@aol.com
    3 | Ruthie Vashon          | 2307 45th St.          | GA    |   98937 | Ozella.Yoshimura@gmail.com
    4 | Isabel Wynn            | 7046 10th Ave.         | NY    |   57243 | Shanell.Lichtenstein@aol.com
```