#### Structured Query Language (SQL)
##Basics of SQL
Structured Query Language is a database tool which is used to create and access database to support software application.

<b>Aggregate Function:-</b>
</br>
SQL Aggregate Functions calculates values from multiple columns in a table and returns a single value.
</br>
There are 7 aggregate functions we use in SQL
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

