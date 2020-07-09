

### AS statement

3 use cases:
1. column name alias
2. table name alias
3. Temporary table creation using: `WITH alias_name AS (subquery_stmt)`

### Where IN

Used for querying in subquery:
`select * from abc where abc.id in (sub_query or list)`

### Group BY

Groupby can be done on 1 column or multiple columns,
**Need to use aggregate functions like Max, Cnt, Avg with group by**

### Variables using SET
Set variables using `SET` and use them using `$name`

### Distinct
distinct can be done on one or multiple columns.
in case of multiple columns, The combination unique is shown.


