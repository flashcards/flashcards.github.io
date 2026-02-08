# Introduction | SQL Flashcards

<iframe class="FlashcardsIO" src="https://embed.flashcards.io/?url=https://flashcards.github.io/sql/introduction.html" frameborder="0"></iframe>

### SQL
SQL, **S**tructured **Q**uery **L**anguage, is a programming language designed to manage data stored in relational databases. SQL operates through simple, declarative statements. This keeps data accurate and secure, and it helps maintain the integrity of databases, regardless of size.

### row
A database row represents a single, implicitly structured data record in a table. In simple terms, a database table can be thought of as consisting of rows and columns.

### column
A database column is a set of data values of a particular simple type, one value for each row of the database. A column may contain text values, numbers, or even pointers to files in the operating system.

### CREATE TABLE
`CREATE TABLE` creates a new table in the database. It allows you to specify the name of the table and the name of each column in the table.

### ALTER TABLE
`ALTER TABLE` lets you add columns to a table in a database.

### PRIMARY KEY
A primary key, sometimes labeled as the unique identifier, is a specific choice of a set of columns that uniquely identify a row in a relational table. Simply put, a primary key is the attributes which identify a record.

### INSERT
`INSERT` statements are used to add a new row to a table.

### CASE
`CASE` statements are used to create different outputs (usually in the `SELECT` statement). It is SQL’s way of handling if-then logic.

### DELETE
`DELETE` statements are used to remove rows from a table.

### INNER JOIN
An INNER JOIN will combine rows from different tables if the *join condition* is true.

### OUTER JOIN
An outer join will combine rows from different tables even if the join condition is not met. Every row in the *left* table is returned in the result set, and if the join condition is not met, then `NULL` values are used to fill in the columns from the *right* table.

### UPDATE
`UPDATE` statements allow you to edit rows in a table.

### WITH
`WITH` clause lets you store the result of a query in a temporary table using an alias. You can also define multiple temporary tables using a comma and with one instance of the `WITH` keyword.
The `WITH` clause is also known as common table expression (CTE) and subquery factoring.

### AS
Columns or tables in SQL can be *aliased* using the `AS` clause. This allows columns or tables to be specifically renamed in the returned result set.

### SELECT
The `SELECT *` statement returns all columns from the provided table in the result set.

### DISTINCT
Unique values of a column can be selected using a `DISTINCT` query.

### SELECT DISTINCT
`SELECT DISTINCT` specifies that the statement is going to be a query that returns unique values in the specified column(s).

### WHERE
The `WHERE` clause is used to filter records (rows) that match a certain condition.

### LIKE
The `LIKE` operator can be used inside of a `WHERE` clause to match a specified pattern.

### _
The `_` wildcard can be used in a `LIKE` operator pattern to match any single unspecified character.

### %
The `%` wildcard can be used in a `LIKE` operator pattern to match zero or more unspecified character(s).

### BETWEEN
The `BETWEEN` operator can be used to filter by a *range* of values. The range of values can be text, numbers or date data.

### AND
The `AND` operator allows multiple conditions to be combined. Records must match both conditions that are joined by `AND` to be included in the result set.

### OR
The `OR` operator allows multiple conditions to be combined. Records matching either condition joined by the `OR` are included in the result set.

### IS NULL / IS NOT NULL
`IS NULL` and `IS NOT NULL` are operators used with the `WHERE` clause to test for empty values.

### ORDER BY
The `ORDER BY` clause can be used to sort the result set by a particular column either alphabetically or numerically. It can be ordered in ascending (default) or descending order with `ASC`/`DESC`.

### LIMIT
The `LIMIT` clause is used to narrow, or *limit*, a result set to the specified number of rows.

### NULL
Column values in SQL records can be `NULL`, or have no value. These records can be matched (or not matched) using the `IS NULL` and `IS NOT NULL` operators in combination with the `WHERE` clause.

### Aggregate Functions
Aggregate functions perform a calculation on a set of values and return a single value:

### COUNT()
The `COUNT()` aggregate function in SQL returns the total number of rows that match the specified criteria.

### SUM()
The `SUM()` aggregate function takes the name of a column as an argument and returns the sum of all the value in that column.

### MAX()
The `MAX()` aggregate function in SQL takes the name of a column as an argument and returns the largest value in a column.

### MIN()
The `MIN()` aggregate function in SQL returns the smallest value in a column.

### AVG()
The `AVG()` aggregate function returns the average value in a column.

### GROUP BY
The `GROUP BY` clause will group records in a result set by identical values in one or more columns. It is often used in combination with aggregate functions to query information of similar records. The `GROUP BY` clause can come after `FROM` or `WHERE` but must come before any `ORDER BY` or `LIMIT` clause.

### HAVING
The `HAVING` clause is used to further filter the result set groups provided by the `GROUP BY` clause. `HAVING` is often used with aggregate functions to filter the result set groups based on an aggregate property.

### ROUND()
The `ROUND()` function will round a number value to a specified number of places. It takes two arguments: a number, and a number of decimal places. It can be combined with other aggregate functions

### Column References
The `GROUP BY` and `ORDER BY` clauses can reference the selected columns by number in which they appear in the `SELECT` statement.

## References:
- https://www.codecademy.com/articles/sql-commands

