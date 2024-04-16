# DATABASE

## QUESTIONS

- What is a database (DB)?
  - a data base is a server or hard drive that is used to create, read, update and delete data. These hard drives can be local, on a server or in "the cloud". There are two types of DBs, we have SQL and NoSQL. SQL is represented as a table with rows and columns. In a DB there might be more than one table represented in a DB. We also have NoSQl which is a document object type store with key value pairs.
  - update: aa DB is a system for managing DB, not just hard drives and servers and NoSQL includes document, columnar and graphDBs
- What is a column? A row? A table? What do these represent?
  - a column is the vertical representation of data as a type or classification. we could have a type of email or string or value. the row is connected to a specific ID and entry into the database and each row has a set of columns and cells in each column that match up with a row and column. A table is a collection of rows and columns representing a specific type of data. These tables can be linked.
  - update: each table represents a specific entity or subject and each column is an attribute or property of that entity.
- What is a primary key? Why is it important?
  - I'm not sure what a primary key is, I'm guessing it's eithher thhe ID or the entry of the NoSQL object where all the data sits under as the value.
  - update: it's a unique ID for each row or table ensuring each record is unique and easily retrievable and is foundational to the integrity and speed of operations in a DB.
- What is the difference between a SQL DB, NoSQL DB, and Graph DB?
  - SQL is a table, NoSQL is everything but a table like a key:value store and a Graph DB is a type of NoSQL DB.
  - update: SQL is Structured Query Language utilizing tables and support complex querying. NoSQL are non-relational and can handle unstructured data. Graph DBs are a type of NoSQL used to story and query data in terms of entities and their relationships.
- What is data persistence? Why is it important?
  - I believe data persistence is the ability to have redundant systems allowing any single hard drive of physical device to fail and still have access to the data base. There are different ways of doing this.
  - update: persistence is the characteristic of data that outlives the execution of the program that created it, crucial for data recovery and integrity across the system restarts or failures.
- What is a data model?
  - I believe a data model is how we design the different tables or objects so that the data is organized and easily accessed.
  - update: data model defines the logical structure of a database including relationships among data, rules and constraints.
- What is an ORM?
  - don't know...
  - Object-Relational Mapping is a programming technique for converting data between incompatible type systems using object-oriented programming languages automating the conversion between how data appears in a DB and how it's used.

## ADVANCED

- What is 3rd Normal Form (3NF)?
  - don't know
  - update: 3NF is a DB schema design approach for SQL DBs minimizing duplication of data with redundancy and ensuring first and second normal form integrity and only dependent on the primary key.
- What are the three types of relationships in a relational database, and what’s the difference between them?
  - row to column, table to table and not sure what the third is.
  - update: one to one is when one row in a table is linked with only one row in another table. one to many is where a row in one table can be linked to many rows in another table. many to many is when a third junction table is used where multiple rows in one table can be related to multiple rows in another table. 

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
