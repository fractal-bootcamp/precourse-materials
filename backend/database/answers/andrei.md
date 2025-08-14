# DATABASE

## QUESTIONS

- What is a database (DB)?
A database is an organized collection of data that is stored and accessed electronically. It allows you to efficiently store, manage, retrieve, and update information.
- What is a column? A row? A table? What do these represent?
cols represent a field of information you want for all entries (like a name or ID), and rows are specific entries (like a user)
- What is a primary key? Why is it important?
a primary key is a column or set of columns that is unique for each row in a table. used to identify a row in the database and to ensure that no two rows have the same value for that column. basically an ID
- What is the difference between a SQL DB, NoSQL DB, and Graph DB?
SQL DB: relational SQL DB - has primary key with rows and columns
NoSQL DB: non-relational DB without SQL - various formats like key-value pairs, graphs, etc.
Graph DB: specialized graph data (nodes and edges)
- What is data persistence? Why is it important?
storing data in a way that allows it to be retrieved later (and not changing it accidentally). both in memory and storage persistence are important. integrity and availability of data is important for any application.
- What is a data model?
representation of data to be stored in a database -> entities and relationships. used by db engine to optimize data access and manipulation. 
- What is an ORM?
object relational mapping (ORM) is a software library that is used to bridge the gap between databases and programming langauges (an abstraction layer between them). Django and MySQL are examples. 

## ADVANCED

- What is 3rd Normal Form (3NF)?
a database that has 1) each non-key attribute must depend direclty on the primary key and 2) all dependencies between non-key attributes must be through the primary key
- What are the three types of relationships in a relational database, and what’s the difference between them?
1) one to one - two tables where one table has one row that is related to one row in another table. ex: a customer and an order have a one to one relationship, where one customer can have multiple orders
2) one to many - one table has multiple rows that are related to one row in another table. ex: a student and their courses 
3) many to many - ex: a customer and their orders where multiple items are in orders

## RESOURCES

What is a database:

- https://aws.amazon.com/what-is/database/
- https://builtin.com/data-science/database
- https://www.geeksforgeeks.org/what-is-database/

Data Persistence:

- https://www.mongodb.com/databases/data-persistence

ORMs:

- https://www.prisma.io/dataguide/types/relational/what-is-an-orm
- https://www.prisma.io/dataguide/types/relational/comparing-sql-query-builders-and-orms

Relationships:

- https://www.sqlshack.com/learn-sql-types-of-relations/
