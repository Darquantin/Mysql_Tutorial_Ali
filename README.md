# Mysql_Tutorial_Ali
<head>MYSQL Tutorial</head>
<title>My SQL tutorial</title>
1) INTRODUCTION /n
help;
show database;
select @@hostname;
mysql-ctl start;
mysql-ctl cli;

show databases;
CREATING DATABASES
The general command for creating a database:

CREATE DATABASE database_name; 

A specific example:

CREATE DATABASE soap_store; 


---USING DATABASES---

USE <database name>;
 
-- example:
USE dog_walking_app;
 
SELECT database();

---CREATING TABLES---

CREATE TABLE tablename
  (
    column_name data_type,
    column_name data_type
  );
CREATE TABLE cats
  (
    name VARCHAR(100),
    age INT
  );
  
  ---SHOWING TABLES---
  
  SHOW TABLES;
 
SHOW COLUMNS FROM tablename;
 
 or 
 
DESC tablename;

---DELETING TABLES---

DROP TABLE <tablename>;

---Creating Your Own Tables Challenge---

CREATE TABLE pastries
  (
    name VARCHAR(100),
    quantity INT
  );
 
SHOW TABLES;
 
DESC pastries;
 
DROP TABLE pastries;

---------------------------------------
