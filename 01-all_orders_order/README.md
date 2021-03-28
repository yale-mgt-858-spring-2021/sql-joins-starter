(This is the same as the previous question except it requires sorting.)
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
Sort the results in ascending order by state abbreviation (CT, VA, etc).
You might find the following SQL constructs useful in your answer: `JOIN`, `ON`, `ORDER BY`, `ASC`.

Your results should look something like this (these might not be correct results)
```
  id    |          name          |        address         | state | zipcode |             email             
--------+------------------------+------------------------+-------+---------+-------------------------------
    185 | Kristofer Morejon      | 8541 10th Ave.         | CO    |   49772 | Derek.Crenshaw@gmail.com
    100 | Rubie Wassink          | 4864 10th Ave.         | CO    |   35894 | Romaine.Birdsell@aol.com
    160 | Keri Puett             | 4652 8th Ave.          | CO    |   72241 | Sherilyn.Hamill@gmail.com
    154 | Cammy Halpin           | 3778 45th St.          | CO    |   80611 | Tonette.Alba@gmail.com
```