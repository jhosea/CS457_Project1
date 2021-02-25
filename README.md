# CS 457 Project 1: Metadata Management

This program manages the metadata in a database system with the ability to create and delete databases as well as create, delete, query, and alter a table within a give database.

##Requirements:
* Python 3
* pandas

## How to use and valid commands:

To run this program you can pass a SQL file as a command line argument like the following:  
`python3 project1.py test.sql`
If no file is specified, it will use the standard input.

## Using commands:
_Note:_ Commands must end with a semicolon.
To exit the program simply enter `exit`
* Create database:
  * To create a database the command must be formatted as `CREATE DATABASE database_name;`
* Drop database:
  * To drop a database the command must be formatted as `DROP DATABASE database_name;`
* Use database:
  * To use a database the command must be formatted as `USE database_name;`
  * _Note:_ To perform an operation on a table, you use must be using a database.
* Create table:
  * To create a table the command must be formatted as `CREATE TABLE table_name;`
* Drop table:
  * To drop a table the command must be formatted as `DROP TABLE table_name;`
* Query table:
  * To query a table the command must be formatted as `SELECT [* or column_names] FROM table_name;`
  ** _Note:_ You are only able to select columns
* Alter table:
  ** To add a column to a table the command must be formatted as `ALTER TABLE table_name ADD column_name column_type`
  ** To remove a column to a table the command must be formatted as `ALTER TABLE table_name REMOVE column_name`
