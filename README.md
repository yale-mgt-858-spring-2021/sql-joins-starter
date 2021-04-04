# 

In this assignment you will practice SQL queries that use `JOIN`
to join multiple tables. You connect to the class database just
like you did in the previous assignment. 
When you're ready to start, [accept this GitHub Classroom invite](https://classroom.github.com/a/3vPt80gS)
and paste your repo URL below. Then you can push to GitHub up 
until the deadline. Don't be shy about asking for help in Slack.

❗❗❗Notice❗❗❗ - some people started the assignment lickety
split ...usually people most advanced and they pointed out some
problems in the problem set. As they've pointed these out, I
corrected them in the starter code. I'm keeping a journal of those
changes here. 

**Question 4 `count_state_shipping_optimized`** - needs to be sorted. 

**Question 3 `count_state_shipping`**. I had the wrong results shown.
The results you should get are 

```
│ state │ num_items_pending │
├───────┼───────────────────┤
│ WY    │                 7 │
│ CO    │                10 │
│ TX    │                10 │
│ FL    │                10 │
│ SC    │                11 │
│ IL    │                 3 │
│ VA    │                 8 │
│ GA    │                 8 │
│ NY    │                 6 │
│ WA    │                 6 │
```

**Question 4 for `count_state_shipping_optimized`**, the example results
should be 

```
│ CO    │ Delivered  │   112 │
│ CO    │ Pending    │    10 │
│ CO    │ Returned   │    11 │
│ FL    │ Delivered  │   152 │
│ FL    │ Pending    │    10 │
│ FL    │ Returned   │    11 │
│ GA    │ Delivered  │   129 │
│ GA    │ Pending    │     8 │
│ GA    │ Returned   │     3 │
│ IL    │ Delivered  │   104 │
(...)
```

**Question 7 `big_spenders`** - needs to be sorted.

**Question 9 `most_sold_item`** - this is very similar to question 5 `total_units`.
I wish I could say that was pedagogical 🤣.

**Question 7 `big_spenders`** - Russ.Mcclain was missing from the
bottom of the table. He spent 10128.68.

**Question 6 `join_coupon`** - Was missing a few rows in the example
output. Example output should have people with 25 purchases but
not 24. That is, greater than or equal to 25.


## Suggested order

We suggest you complete the questions in the following order

- [ ] 00-all_orders
- [ ] 01-all_orders_order
- [ ] 02-all_orders_order_between
- [ ] 03-count_state_shipping
- [ ] 04-count_state_shipping_optimized
- [ ] 05-total_units
- [ ] 06-join_coupon
- [ ] 07-big_spenders
- [ ] 08-reactivation
- [ ] 09-most_sold_item


As you complete questions, you can mark them as complete
in this Markdown file,  but you don't have to do so.
See [this example](https://github.blog/2014-04-28-task-lists-in-all-markdown-documents/).

