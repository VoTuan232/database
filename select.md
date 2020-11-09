`SELECT`

```
USE sql_store;
SELECT * FROM orders;
```

`WHERE`

```
USE sql_store; SELECT * FROM orders where order_id = 1
```

`ORDER_BY`

```
USE sql_store; SELECT * FROM orders where order_id = 1 order by order_date;
```

`NEW COLUMNS`

```
SELECT first_name, last_name, points, points + 10 FROM sql_store.customers;
```

`NEW COLUMNS WITH CUSTOM NAME`

```
SELECT first_name, last_name, points, (points + 10) * 100 as new_points
FROM sql_store.customers;
```

`NEW COLUMNS WITH ANY NAME`

```
SELECT first_name, last_name, points, (points + 10) * 100 as 'new points'
FROM sql_store.customers;
```

`DISTINCT`

```
SELECT distinct state
FROM sql_store.customers;
```
