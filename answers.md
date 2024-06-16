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

### Question No-3

`3. Write an SQL query to insert a new customer record into the "Customers" table. Include customer information such as name, email, and address.
`

```sql
insert into customers values (6,'Rithwik','Raj','rr@gmail.com',67890,'Madinaguda')
```

![alt text](q-3ans.png)
