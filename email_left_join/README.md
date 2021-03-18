List customers that have placed orders over $100. Use the command DISTINCT to bring unique results.
Select the name, address and price of the order.
You might find the following SQL constructs useful in your answer: `RIGHT JOIN`, `ON`, `GROUP BY 1`.

Your results should look something like this (these might not be correct results)
```
          name       |    address     | price  
    ------------------+----------------+--------
    Isabel Crissman  | 1992 50th Ave. | 108.00
    Maudie Medlen    | 2049 44th Ave. | 899.99
    Nydia Moe        | 5847 50th Ave. | 499.00
    Dee Heavner      | 8021 8th Ave.  | 529.00
```