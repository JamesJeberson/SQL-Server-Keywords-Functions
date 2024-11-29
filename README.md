# SQL Server Keywords:
Keywords in SQL Server are reserved words used to perform various operations, define structures, and control query behavior.

## Data Definition Language (DDL):
- **CREATE:** Defines new database objects such as tables, views, indexes, and schemas.
- **ALTER:** Modifies an existing database object.
- **DROP:** Removes an existing database object.
- **TRUNCATE:** Removes all rows from a table but does not log individual row deletions.
## Data Manipulation Language (DML):
- **SELECT:** Retrieves data from one or more tables.
- **INSERT:** Adds new rows into a table.
- **UPDATE:** Modifies existing rows in a table.
- **DELETE:** Removes rows from a table.
## Transaction Control:
- **COMMIT:** Saves all changes made in the current transaction.
- **ROLLBACK:** Reverts changes made in the current transaction.
- **BEGIN TRANSACTION:** Starts a transaction.
- **SAVEPOINT:** Defines a point in a transaction to which you can roll back.
## Constraints:
- **PRIMARY KEY:** Identifies a unique record in a table.
- **FOREIGN KEY:** Defines a relationship between two tables.
- **CHECK:** Ensures the values in a column meet a specified condition.
- **UNIQUE:** Ensures all values in a column are unique.
- **DEFAULT:** Sets a default value for a column.
## Joins and Set Operations:
- **INNER JOIN:** Retrieves matching rows from both tables.
- **LEFT JOIN / LEFT OUTER JOIN:** Retrieves all rows from the left table and matching rows from the right.
- **RIGHT JOIN / RIGHT OUTER JOIN:** Retrieves all rows from the right table and matching rows from the left.
- **FULL JOIN / FULL OUTER JOIN:** Retrieves matching rows from both tables, and non-matching rows from either side.
- **UNION:** Combines the result sets of two or more queries.
- **INTERSECT:** Retrieves common rows from two queries.
- **EXCEPT:** Retrieves rows from the first query not present in the second query.
## Filtering and Sorting:
- **WHERE:** Filters rows based on a condition.
- **ORDER BY:** Sorts results in ascending (ASC) or descending (DESC) order.
- **GROUP BY:** Groups rows with the same values into summary rows.
- **HAVING:** Filters groups based on a condition (used with GROUP BY).
- **DISTINCT:** Eliminates duplicate rows in the result set.
- **IN:** Filters data based on a list of values.
- **BETWEEN:** Filters data within a range.
- **LIKE:** Filters data based on pattern matching.
## Other Keywords:
- **SELECT INTO:** Copies data from one table into another.
- **EXISTS:** Checks if a subquery returns any results.
- **ALL:** Compares a value to all values in another result set.
- **ANY:** Compares a value to any value in another result set.
- **NULL:** Represents a missing or undefined value.
- **IS NULL / IS NOT NULL:** Checks if a value is NULL or not.
- **TOP:** Limits the number of rows returned by a query.
- **WITH:** Defines Common Table Expressions (CTEs).

# SQL Server Functions:
SQL Server provides built-in functions for performing a variety of operations on data, including mathematical, string, date, and conversion operations.

## Aggregate Functions:
- **COUNT():** Returns the number of rows.
- **SUM():** Returns the sum of numeric values.
- **AVG():** Returns the average of numeric values.
- **MAX():** Returns the maximum value.
- **MIN():** Returns the minimum value.
- **GROUP_CONCAT():** Concatenates values from multiple rows into a single string (MySQL-specific but not standard in SQL Server).
## String Functions:
- **LEN():** Returns the length of a string.
- **TRIM():** Removes leading and trailing spaces.
- **UPPER():** Converts a string to uppercase.
- **LOWER():** Converts a string to lowercase.
- **SUBSTRING():** Extracts a portion of a string.
- **CHARINDEX():** Returns the starting position of a substring within a string.
- **REPLACE():** Replaces occurrences of a substring within a string.
- **CONCAT():** Combines two or more strings into one.
- **RTRIM():** Removes trailing spaces.
- **LTRIM():** Removes leading spaces.
## Mathematical Functions:
- **ABS():** Returns the absolute value of a number.
- **ROUND():** Rounds a number to a specified decimal place.
- **CEILING():** Returns the smallest integer greater than or equal to a number.
- **FLOOR():** Returns the largest integer less than or equal to a number.
- **RAND():** Generates a random number.
- **POWER():** Returns the result of a number raised to a power.
- **SQRT():** Returns the square root of a number.
## Date and Time Functions:
- **GETDATE():** Returns the current date and time.
- **GETUTCDATE():** Returns the current UTC date and time.
- **DATEADD():** Adds a specified time interval to a date.
- **DATEDIFF():** Returns the difference between two dates.
- **DATEPART():** Returns a specific part of a date (e.g., year, month, day).
- **YEAR(), MONTH(), DAY():** Extracts the year, month, or day from a date.
- **FORMAT():** Formats a date and time value according to a specified format.
## Conversion Functions:
- **CAST():** Converts an expression to a specified data type.
- **CONVERT():** Converts an expression to a specified data type, with optional formatting.
## Conditional Functions:
- **CASE:** Provides conditional logic in queries (similar to IF statements).
- **IIF():** Returns one of two values based on a condition (like IF).
- **COALESCE():** Returns the first non-null value in a list of expressions.
- **NULLIF():** Returns NULL if two expressions are equal, otherwise returns the first expression.
## Ranking Functions:
- **ROW_NUMBER():** Assigns a unique sequential integer to rows in a result set.
- **RANK():** Assigns a rank to rows in a result set, with gaps in ranking for ties.
- **DENSE_RANK():** Similar to RANK() but without gaps in ranking.
- **NTILE():** Divides the result set into a specified number of groups.
## System Functions:
- **GETDATE():** Returns the current system date and time.
- **NEWID():** Generates a uniqueidentifier (UUID).
- **CURRENT_TIMESTAMP:** Returns the current date and time (equivalent to GETDATE()).
##  Window Functions:
- **OVER():** Defines a window (partition) over which a function operates.
- **PARTITION BY:** Divides a result set into partitions to which the OVER() function is applied.

## Summary:
Keywords in SQL Server are reserved words that define the structure of SQL statements (e.g., SELECT, FROM, JOIN).
Functions are predefined operations for manipulating data (e.g., COUNT(), LEN(), GETDATE(), CAST()).
Each of these functions and keywords plays an important role in writing effective SQL queries in SQL Server.
