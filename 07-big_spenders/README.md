Please make a list of customer emails for customers that have spent more than $10,000 in the gift store 
(i.e., greater than $10,000). To do this, youâll need to join *three* tables in the gift_store schema 
(now that you are familiar with this database, we'll let you determine what tables are relevant ð).
Please sort in descending order of net spend.

For this query, remember that revenue (or spend) equals price * quantity ð°.

You might find the following SQL constructs useful in your answer: `JOIN`, `ON`, `SUM`, `HAVING`

Please name your columns `email` and `net_spend`, respectively.

Your results should look something like this:
```
â           email            â net_spend â
ââââââââââââââââââââââââââââââ¼ââââââââââââ¤
â Zita.Breeding@gmail.com    â  13204.57 â
â Earlean.Bonacci@yahoo.com  â  12577.61 â
â Theresia.Edwin@yahoo.com   â  12224.53 â
â Samatha.Hedgpeth@yahoo.com â  12109.45 â
â Derek.Crenshaw@gmail.com   â  11651.52 â
â Ozella.Roles@gmail.com     â  11525.50 â
â Zita.Luman@yahoo.com       â  10397.50 â
â Shanell.Maxson@gmail.com   â  10228.71 â
â Russ.Mcclain@yahoo.com     â  10128.68 â
```