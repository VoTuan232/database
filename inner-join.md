```
use sql_store;
SELECT * FROM orders
join customers on orders.customer_id = customers.customer_id;
```

`ALIAS`

```
use sql_store;
SELECT * FROM orders o
join customers c on o.customer_id = c.customer_id;
```
