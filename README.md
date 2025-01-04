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
