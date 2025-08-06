
u0_a338 whoami in termux
mysql -u root -p -> to enter mysql as root
pwd -> 231212

## DataBase Commands

CREATE DATABASE "DataBaseName";
DROP DATABASE "DataBaseName";
USE "DataBaseName";
SHOW DATABASES;

## Table Commands

CREATE TABLE "table_name"(
column_name_1,
column_name_2,
etc...
);
To CREATE TABLE must at least have one column

Example:
CREATE TABLE employees(
    -> employee_id INT,
    -> first_name VARCHAR(50),
    -> last_name VARCHAR(50),
    -> hourly_pay DECIMAL(5, 2),
    -> hire_date DATE
    -> );
To see tables use SHOW TABLES; command

To see columns use SHOW COLUMNS FROM "table_name";

To modify a table use ALTER TABLE

ALTER TABLE "table_name" 
ADD "column_name" "datatype";

Example:
ALTER TABLE employees
ADD phone_number VARCHAR(15);

To rename column use

ALTER TABLE "table_name"
RENAME COLUMN "old_column" TO "new_column";

Example:
ALTER TABLE employees
RENAME COLUMN phone_number TO
email;

To move a column use

ALTER TABLE "table_name"
MODIFY "column_name" "column_type"
FIRST;

ALTER TABLE "table_name"
MODIFY "column_name_1" "column_type"
AFTER "column_name_2;

Example:

ALTER TABLE employees
MODIFY phone_number VARCHAR(15)
AFTER last_name;

To populate a table use 

INSERT INTO "table_name" VALUES
(value_column_1, value_column_2, ....., etc.);

Example:

INSERT INTO employees VALUES
(1, "Jorge", "Collao", "+569-88893348", "collaojorge52@gmail.com", "2021-09-17", 25.50);