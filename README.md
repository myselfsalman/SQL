# SQL
CREATE DATABASE SALMAN;

USE SALMAN;

CREATE TABLE table_name (
    column1 datatype constraint,
    column2 datatype constraint,
    ...
);


drop a database:
DROP DATABASE crud;

if drop database is not working in phpmyadmin, we have to change the settings of our internal xmapp settings in phpmyadmin file
file name: config.inc

write this code: $cfg['AllowUserDropDatabase'] = true;


Distinct keyword
when i need unique value from a column, suppose, there are a lot of city in the city column and there can be duplicate cities.
so i need only the unique cities.
then i can use DISTINCT KEYWOD.
HOW?
SELECT DISTINCT CITY FROM TABLENAME;


now, WHERE CLAUSE
WHERE CONDITION.

SELECT * FROM STUDENT WHERE MARKS > 80;
SELECT * FROM STUDENT WHERE CITY = "Mumbai";

Now, we can use where clasue or condition for multiple condition in a query
SELECT * FROM STUDENT WHERE MARKS > 80 AND CITY = "Mumbai";

Here, we used AND for multiple condition in the query of where condition


Now, Order By
for order by, we use ascending and descending keywords.
they are:
ASC
DESC

SELECT * FORM STUDENT ORDER BY COLUMN NAME ASCENDING OR DESCENDING;



BETWEEN, IN, NOT IN
THESE THREEE OPERATOR USED FOR SEARCHING DATA IN QUEARY
LIKE:


SELECT * FROM STUDENT WHERE MARKS BETWEEN 80 AND 90; HERE, BOTH MARKS AND INSIDE MARKS ARE ADDED.


ORDER BY
