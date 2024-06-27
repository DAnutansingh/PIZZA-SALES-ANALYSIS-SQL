# PIZZA-SALES-ANALYSIS-SQL
MYSQL

This repository contains the sql queries performed on Mysql workbench.

SQL (Structured Query Language) is a domain-specific language used in programming and designed for managing and manipulating relational databases. SQL is used to perform tasks such as updating data in a database or retrieving data from a database. 

some important queries used are:

1. Window functions:
Window functions in SQL are a powerful tool that allow you to perform calculations across a set of table rows that are somehow related to the current row. They are often used for ranking, running totals, moving averages, and other similar calculations. Unlike aggregate functions, which return a single value for a set of rows, window functions can return multiple rows for each partition of the data.
- Common window functions are:
  rank(),dense_rank(),lead(),lag(),row_number(),avg(),sum()

2. Aggregate functions:
Aggregate functions in SQL are used to perform calculations on a set of values and return a single value. They are often used in conjunction with the GROUP BY clause to group rows that have the same values into summary rows, such as finding the total number of items in each category.
-Common functions are:
 avg(),sum(),count(),min(),max()

3.Joins:
Joins in SQL are used to combine rows from two or more tables based on a related column between them. Joins allow you to query data across multiple tables and are fundamental to relational database design.
-Types are:
 inner join,left join,right join,full outer join

4.Group by statement:
The GROUP BY statement groups rows that have the same values into summary rows, like "find the number of customers in each country".
The GROUP BY statement is often used with aggregate functions (COUNT(), MAX(), MIN(), SUM(), AVG()) to group the result-set by one or more columns.

5.Order by statement:
The ORDER BY keyword is used to sort the result-set in ascending or descending order.
