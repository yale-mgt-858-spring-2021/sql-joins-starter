We would like to determine what items are the top ten best selling at the gift store. 

Please write a query that returns a productβs id, title, and the total quantity of 
that product sold (again, we will leave it to you to determine the relevant tables π€ͺ)

Please name your columns `product_id`, `product_title`, and `sum`, respectively. 

You might find the following SQL constructs useful in your answer: `JOIN`, `SUM`, `LIMIT`


Your results should look something like this:
```
β product_id β  product_title   β sum β
ββββββββββββββΌβββββββββββββββββββΌββββββ€
β         17 β Documentary      β 145 β
β         12 β Holiday CD       β 139 β
β         14 β Pop CD           β 139 β
β          2 β Python Book      β 137 β
β          6 β Desktop Computer β 135 β
β         13 β Country CD       β 133 β
β         16 β Comedy Movie     β 132 β
β         10 β 42" Plasma TV    β 128 β
β          4 β Baby Book        β 127 β
β          8 β MP3 Player       β 121 β
```