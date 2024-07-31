1. What is a primary key?
Answer: A primary key is a column or a combination of columns in a table that uniquely identifies each row in that table. 
Primary keys must contain unique values and cannot contain NULLs.

2. What is a foreign key?
Answer: A foreign key is a column or a set of columns in one table that refers to the primary key in another table.
It is used to link the two tables.

3. What is a unique key?
Answer: A unique key is a constraint that ensures all values in a column are unique.
Unlike primary keys, unique keys can have NULL values.

4. What are indexes?
Answer: Indexes are used to speed up the retrieval of rows from a table.
They create a data structure that improves the speed of data retrieval operations on a database table.

5. What is a join in SQL?
Answer: A join is an SQL operation used to combine rows from two or more tables, based on a related column between them.
There are various types of joins including INNER JOIN, LEFT JOIN, RIGHT JOIN, and FULL OUTER JOIN.

6. Explain the difference between INNER JOIN and LEFT JOIN.
Answer: INNER JOIN: Returns records that have matching values in both tables.
LEFT JOIN (or LEFT OUTER JOIN): Returns all records from the left table, and the matched records from the right table.
The result is NULL from the right side if there is no match.

7. What is a subquery?
Answer: A subquery is a query nested within another query.
It can be used in SELECT, INSERT, UPDATE, or DELETE statements or inside another subquery.

8. What is a correlated subquery?
Answer: A correlated subquery is a subquery that uses values from the outer query.
It is evaluated once for each row processed by the outer query.

9. Explain the use of GROUP BY clause.
Answer: The GROUP BY clause is used to arrange identical data into groups.
It is often used with aggregate functions (COUNT, MAX, MIN, SUM, AVG) to perform operations on each group of data.

10. What is the HAVING clause and how is it different from WHERE?
Answer: The HAVING clause is used to filter records that work on summarized GROUP BY results.
It is similar to the WHERE clause but is used for aggregate functions.

11. What is a view in SQL?
Answer: A view is a virtual table based on the result set of an SQL statement.
It contains rows and columns just like a real table and can be used to simplify complex queries.

12. Explain the difference between UNION and UNION ALL.
Answer: UNION: Combines the result sets of two queries and removes duplicate rows.
UNION ALL: Combines the result sets of two queries including all duplicates.

13. What is a stored procedure?
Answer: A stored procedure is a set of SQL statements that can be stored in the database and executed repeatedly. 
It allows for more modular, reusable, and manageable SQL code.

14. What is a trigger in SQL?
Answer:
A trigger is a set of SQL statements that automatically "fires" or executes when a specified event occurs on a table or view, such as an insert, update, or delete.

15. What is normalization?
Answer:
Normalization is the process of organizing data in a database to reduce redundancy and improve data integrity. It involves dividing large tables into smaller tables and defining relationships between them.

16. What are the different normal forms?
Answer: 1NF (First Normal Form): Ensures each column contains atomic (indivisible) values.
2NF (Second Normal Form): Meets all 1NF requirements and ensures all non-key attributes are fully functionally dependent on the primary key.
3NF (Third Normal Form): Meets all 2NF requirements and ensures no transitive dependency of non-key attributes on the primary key.
BCNF (Boyce-Codd Normal Form): A stricter version of 3NF.
4NF (Fourth Normal Form) and 5NF (Fifth Normal Form): Deal with multi-valued dependencies and join dependencies, respectively.

17. What is denormalization?
Answer: Denormalization is the process of combining tables to reduce the number of joins in a query and improve performance. It can lead to some redundancy and the risk of data anomalies.

18. What is a CTE (Common Table Expression)?
Answer:
A CTE is a temporary result set defined within the execution scope of a single SELECT, INSERT, UPDATE, or DELETE statement. It is defined using the WITH clause.

19. What is the difference between DELETE and TRUNCATE?
Answer:

DELETE: Removes rows one at a time and can include a WHERE clause to filter rows. It is slower and can be rolled back.
TRUNCATE: Removes all rows from a table without logging individual row deletions. It is faster but cannot be rolled back.
20. What is a cursor in SQL?
Answer:
A cursor is a database object used to retrieve, manipulate, and navigate through a result set one row at a time.

21. What is the difference between a clustered and a non-clustered index?
Answer:

Clustered Index: Determines the physical order of data in the table. There can be only one clustered index per table.
Non-clustered Index: Does not alter the physical order of the data. A table can have multiple non-clustered indexes.
22. What is a partitioned table?
Answer:
A partitioned table is divided into smaller, more manageable pieces called partitions, which can improve performance and simplify maintenance.

23. What is the SQL Injection?
Answer:
SQL Injection is a code injection technique that exploits a security vulnerability in an application by inserting malicious SQL statements in input fields, allowing attackers to access or manipulate the database.

24. What is the ACID property in a database?
Answer:

Atomicity: Ensures transactions are all-or-nothing.
Consistency: Ensures transactions bring the database from one valid state to another.
Isolation: Ensures transactions are securely and independently processed.
Durability: Ensures committed transactions are permanently stored.
25. Explain the concept of a transaction in SQL.
Answer:
A transaction is a sequence of one or more SQL operations executed as a single unit of work. Transactions ensure data integrity and are governed by the ACID properties.
