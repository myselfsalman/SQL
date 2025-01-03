# SQL
CREATE DATABASE SALMAN;

USE SALMAN;

CREATE TABLE TABLE1 VALUES(
ID INT PRIMARY KEY,
NAME VARCHAR(40),
ROLL INT,
AGE INT);

drop a database:
DROP DATABASE crud;

if drop database is not working in phpmyadmin, we have to change the settings of our internal xmapp settings in phpmyadmin file
file name: config.inc

write this code: $cfg['AllowUserDropDatabase'] = true;
