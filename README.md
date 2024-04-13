#### Structured Query Language (SQL)
<b>##Basics of SQL</b></br>
<b>Structured Query Language(SQL) is a database tool which is used to create and access database to support software application.</b></br>
</br>
<b>SQL Commands</b></br>
<b>There are 5 types of SQL commands mainly categorized as:-</b></br>
</br>
<b>DDL – Data Definition Language</b></br>
CREATE: This command is used to create the database or its objects (like table, index, function, views, store procedure, and triggers).</br>
DROP: This command is used to delete objects from the database.</br>
ALTER: This is used to alter the structure of the database.</br>
TRUNCATE: This is used to remove all records from a table, including all spaces allocated for the records are removed.</br>

<b>DQL – Data Query Language</b></br>
SELECT: It is used to retrieve data from the database.</br>

<b>DML – Data Manipulation Language</b></br>
INSERT: It is used to insert data into a table.</br>
UPDATE: It is used to update existing data within a table.</br>
DELETE: It is used to delete records from a database table.</br>

<b>DCL – Data Control Language</b></br>
GRANT: This command gives users access privileges to the database.</br>
REVOKE: This command withdraws the user’s access privileges given by using the GRANT command.</br>
</br>
<b>TCL – Transaction Control Language</b></br>
BEGIN: Opens a Transaction.</br>
ROLLBACK: Rollbacks a transaction in case of any error occurs.</br>
COMMIT: Commits a Transaction.</br>

<b>Referential integrity:-</b></br>
Referential integrity refers to the consistency that must be maintained between primary and foreign keys, i.e. every foreign key value must have a corresponding primary key value.</br>
</br>
<b>Trigger:-</b></br>
Trigger allows us to execute a batch of SQL code when a table event occurs (Insert, update or delete command executed against a specific table)

<b>Aggregate Function:-</b>
</br>
SQL Aggregate Functions calculates values from multiple columns in a table and returns a single value.</br>
</br>
<b>There are 7 aggregate functions we use in SQL</b>
</br>
AVG(): Returns the average value from specified columns
</br>
COUNT(): Returns number of table rows
</br>
MAX(): Returns largest value among the records
</br>
MIN(): Returns smallest value among the records
</br>
SUM(): Returns the sum of specified column values
</br>
FIRST(): Returns the first value
</br>
LAST(): Returns Last value

- [ ] AND CONDITION         : SELECT * FROM SQL_Demo WHERE Country='India' AND City='Jamshedpur';
- [ ] OR CONDITION          : SELECT * FROM SQL_Demo WHERE City='Jamshedpur' OR City='Benguluru'; 
- [ ] NOT CONDITION         : SELECT * FROM SQL_Demo WHERE NOT Country='India';
- [ ] AND & OR CONDITION    : SELECT * FROM SQL_Demo WHERE Country='India' AND (City='Jamshedpur' OR City='Benguluru');
- [ ] AND & NOT CONDITION   : SELECT * FROM SQL_Demo WHERE NOT Country='India' AND NOT Country='Berlin';
- [ ] ORDER BY ASC & DESC   : SELECT * FROM SQL_Demo ORDER BY Country ASC, CustomerName DESC;
- [ ] Insert Command        : INSERT INTO SQL_Demo (column1, column2, column3)VALUES (value1, value2, value3);
- [ ] Delete Command        : DELETE FROM SQL_Demo WHERE condition;

