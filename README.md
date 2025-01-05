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
IN ORDER BY, WE CAN ALSO USE LIMIT KEYWORD FOR SETTING THE LIMIT OF THE ROWS WE WANT TO SELECT

SELECT * FROM STUDENT ORDER BY COLUMN NAME ASC LIMIT 3;


aggregate functions:
count()
max()
min()
sum()
avg()


aggregate functions er age always comma use korte hobei hobe.
group by and order by er por obviously column name add hobe.
order by sober last e
group by order by er age.
ek ta query te jodi ekadikh column ke query kora hoy tahole tader maj e comma boshbe.


where clause er moto ekta clause holo Having
normally where er por group by use korte hoy
but having er khetre group by er por having use korte hoy.
2 ta clause e condition add kore


mainly having clause holo group er upor condition add kora.

general order: 
![image](https://github.com/user-attachments/assets/08913593-dd85-49e2-b1ba-403157e73dd0)

select column name
where condition
having condition
from table name
group by columns
order by columns


UPDATE table_name
SET column1 = value1,
    column2 = value2,
    column3 = value3
WHERE condition;


DELETE FROM TABLE NAME
WHERE MARKS>40;


