# Answers

### Question No-1

`1. Write an SQL query to retrieve the names and emails of all customers.
`

```sql
select FirstName,LastName,Email
from customers
```

![alt text](q-1and.png)

### Question No-2

`2. Write an SQL query to list all orders with their order dates and corresponding customer names.
`

```sql
select OrderDate, c.FirstName,c.LastName
from orders o
join customers c on o.CustomerID = c.CustomerID
```

![alt text](q-2ans.png)
