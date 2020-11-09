```
SELECT * FROM sql_hr.employees m
join sql_hr.employees e
on m.reports_to = e.employee_id;
```
