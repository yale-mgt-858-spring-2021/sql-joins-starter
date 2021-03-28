It seems that the store manager would also need to know the name of the product that was bought in 
all of the transactions from the previous query. That means that we will need to JOIN all four tables, 
in order to get all the required information: user.email, purchases.zipcode, purchase_items.price and products.title. 
Please, use the command INNER JOIN instead of JOIN.

Your results should look something like this (these might not be correct results)
```
              email            | zipcode | price  |      title       
  -----------------------------+---------+--------+------------------
   Ivana.Sosnowski@aol.com     |   71634 | 499.00 | 42" LCD TV
   Shanell.Maxson@gmail.com    |   73667 | 499.99 | Desktop Computer
   Kali.Damore@yahoo.com       |   98547 | 108.00 | MP3 Player
```