# SQL

Welcome to the MySQL repository! 🎉

## SQL Queries

Here are some common SQL queries that you can use in this project:

## 1. Select all records from a table:

```sql
SELECT * FROM your_table;
```

## 2. Filter records based on a condition:

```sql
SELECT * FROM your_table WHERE condition;
```
## 3. Aggregate functions:
Calculate the average, sum, or count of a column:

```sql
SELECT AVG(column_name) AS average_value FROM your_table;
SELECT SUM(column_name) AS total_value FROM your_table;
SELECT COUNT(*) AS record_count FROM your_table;
```
## 4. Joins:
Combine data from two or more tables:

```sql
SELECT t1.column_name, t2.column_name
FROM table1 t1
JOIN table2 t2 ON t1.common_column = t2.common_column;
```
## 5. Insert records into a table:

```sql
INSERT INTO your_table (column1, column2, column3) VALUES (value1, value2, value3);
```
## 6. Update records:
```sql
UPDATE your_table SET column_name = new_value WHERE condition;
```
## 7. Delete records:
```sql
DELETE FROM your_table WHERE condition;
```

