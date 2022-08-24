# SQL-DBMS

DATA:

The facts which can be recorded and ehich have a meaning is known as Data.
Example: Customer Name, Student id, City etc.

DATABASE:

1. It is a collection of inter-related data,this can be stored in the form of tables.
2. A database can be of any size and varying complexity.
3. A database may be generated and manipulated manually or can be computerized.
Example: Customer dat base consist of the field customer-id, name,city etc.

DATABASE MANAGEMENT SYSTEM:

DBMS is a set of programs or software,which can be defined constructed,manipulated, whose overall purpose is to maintain the info and to make sure that the info is available on demand.

DATABASE SYSTEM :

Collection of DataBase and DBMS is called as DataBase System.



---------------------------------  STUCTURED QUERY LANGUAGE (SQL) -----------------------------


SQL commands are instructions. It is used to communicate with the database. It is also used to perform specific tasks, functions, and queries of data.
SQL can perform various tasks like create a table, add data to tables, drop the table, modify the table, set permission for users.
Types of SQL Commands

There are five types of SQL commands: DDL, DML, DCL, TCL, and DQL.

![SQL COMMANDS](https://static.javatpoint.com/dbms/images/dbms-sql-command.png)

1. Data Definition Language (DDL)

DDL changes the structure of the table like creating a table, deleting a table, altering a table, etc.
All the command of DDL are auto-committed that means it permanently save all the changes in the database.
Here are some commands that come under DDL:

CREATE
ALTER
DROP
TRUNCATE
a. CREATE It is used to create a new table in the database.
b. DROP: It is used to delete both the structure and record stored in the table.
c. ALTER: It is used to alter the structure of the database. This change could be either to modify the characteristics of an existing attribute or probably to add a new attribute.
d. TRUNCATE: It is used to delete all the rows from the table and free the space containing the table.

2. Data Manipulation Language

DML commands are used to modify the database. It is responsible for all form of changes in the database.
The command of DML is not auto-committed that means it can't permanently save all the changes in the database. They can be rollback.
Here are some commands that come under DML:
INSERT
UPDATE
DELETE
a. INSERT: The INSERT statement is a SQL query. It is used to insert data into the row of a table.
b. UPDATE: This command is used to update or modify the value of a column in the table.
c. DELETE: It is used to remove one or more row from a table.

3. Data Control Language

DCL commands are used to grant and take back authority from any database user.

Here are some commands that come under DCL:
Grant
Revoke
a. Grant: It is used to give user access privileges to a database.
b. Revoke: It is used to take back permissions from the user.


4. Transaction Control Language

TCL commands can only use with DML commands like INSERT, DELETE and UPDATE only.

These operations are automatically committed in the database that's why they cannot be used while creating tables or dropping them.

Here are some commands that come under TCL:

COMMIT
ROLLBACK
SAVEPOINT
a. Commit: Commit command is used to save all the transactions to the database.
b. Rollback: Rollback command is used to undo transactions that have not already been saved to the database.
c. SAVEPOINT: It is used to roll the transaction back to a certain point without rolling back the entire transaction.

5. Data Query Language

DQL is used to fetch the data from the database.

It uses only one command:

SELECT
a. SELECT: This is the same as the projection operation of relational algebra. It is used to select the attribute based on the condition described by WHERE clause.


ER-Diagram

![SQL COMMANDS](https://www.guru99.com/images/1/100518_0621_ERDiagramTu12.png)

)


