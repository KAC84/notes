##SQL Bootcamp
Instructor: Jeff Konowitch



What is SQL? (Structured Query Language)


* MYSQL
* PostgeSQL
* Maria DB
* Access

####Structure: 

Database: defined as a set of tables/rows

DB server: houses # of different databases

DB client: interface to a DB server (ie.: MySQL workbench or app/software.)


####Lampstack:
* linux
* apache
* mySQL
* php


With SQL you have a structured data model.



host: will come as either a IP address or domain

port: 

username: 

password: 

####MySQL Workbench
Schemas=draft of a database

#####Types: 
varchar=type, string 
integer=number
float=decimal
boolean statement =true or false
date

What is the differnce between MySQL Workbench and a text editor like sublime?

####Queries
"SELECT * FROM users;" = pulls all the columns of data from table named users.

We're always selecting from a table. 

Types of queries:

* SELECT
* LIMIT
* ORDER BY
	* ASC 
	* DESC
* WHERE
	* Combine AND/OR
	* Matching 
		*	=
		* 	< >
		*  like 
		* 	null vs. not null. Null= no data in that record.
	
	% signs means doesn't matter what comes before or after
* FUCTIONS ie. CONCAT
* DISTINCT
	
####Relational Databases

Key Terms: 

* [ERD=Entity-Relationship Diagram](http://www.techopedia.com/definition/1200/entity-relationship-diagram-erd)

* Primary Key= means "unique indentifer" Type for ID column will be an integer (int) Database will assign IDs. Using MySQL it is autoincrement

* Foreign Key=column in one table that refers to a primary key in another table



Example: Zipcar

Relational Databases: Cars > Rentals > Customers

Cars: Make, Model, Location, Car ID (primary key)

Rentals: Car ID (foriegn key), Customers ID (forigen key), Location, Dates

Customers: Name, email, Customer ID (primary key)


#####Relationships Types: 

* many=many
* one=many
* one=one

[Database Normalization](http://en.wikipedia.org/wiki/Database_normalization)

INNER JOIN allows you to match up to tables

Foreign Key = Primary Key

For example: 
SELECT * FROM albums INNER JOIN tracklists ON albums.id = tracklists.album_id INNER JOIN songs ON tracklists.song_id = songs.id; 

####Summarizing Data

Functions: 

* COUNT ex: SELECT COUNT(*) FROM albums;
* SUM ex: SUM(gross)
* AVG
* GROUP BY ex: SELECT album_id, year, SUM(gross) FROM sales GROUP BY album_id, year;
* HAVING (use in lieu of WHERE for aggregated data sets)

####Tips/Tricks
* aliasing
* subqueries

####CSV Import Process
1. Name column headers and determine types of data ( varchar, integer, float, boolean, date)
2. Create table columns/Write Script?
3. CSV import tool
	* file
	* table
	* order of columns in csv
	
You can write commands to  create tables, drop tables, update, insert, and delete items

Resources: LEARN SQL THE HARD WAY book

Data wrangling/cleaning: learn a scripting language. Python or Ruby


**A SQL query walks into a bar and sees two tables. He walks up to them and says 'Can I join you?'**