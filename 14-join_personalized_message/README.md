The store manager would like to send a personalized message by email to the top 10 buyers in November of 2019. 
Please, select the email and the total amount spent by each of them during that month.
You might need to consider to JOIN three different tables: users, purchases and purchase_items
You might find the following SQL constructs useful in your answer: `SUM` ,`WHERE`, `GROUP BY 1`, `ORDER BY DESC`, `LIMIT`

Your results should look something like this (these might not be correct results)
```      
              email            |   sum   
  -----------------------------+---------
   Ozella.Roles@gmail.com      | 1537.95
   Derek.Crenshaw@gmail.com    | 1461.96
   Eve.Kump@yahoo.com          | 1453.97
```