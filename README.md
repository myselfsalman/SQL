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
