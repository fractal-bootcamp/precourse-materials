
- What is a database (DB)?

A system for storing and organizing data so it can be easily accessed, managed, and updated.

- What is a column? A row? A table? What do these represent?

Table = a collection of related data
Row = one record (like a user)
Column = a field/attribute (like name, email, age)

Like a spreadsheet.

- What is a primary key? Why is it important?

A unique identifier for each row in a table.
Prevents duplicates and allows fast lookups.

- What is the difference between a SQL DB, NoSQL DB, and Graph DB?

SQL (Relational) = structured tables, uses SQL
NoSQL = flexible schemas (documents, key-value, etc.)
Graph DB = data as nodes + edges (relationships)

- What is data persistence? Why is it important?

Persistence = saving data so it doesn’t disappear when the app stops running.
Needed for long-term storage (like user accounts, posts, etc.)

- What is a data model?

A structured definition of how data is stored and related. Usually includes tables, fields, and relationships.

- What is an ORM?

ORM = Object-Relational Mapping
It lets you use objects in code to interact with a database, instead of writing raw SQL.

## ADVANCED

- What is 3rd Normal Form (3NF)?

No transitive dependencies (non-key columns can’t depend on other non-key columns)

- What are the three types of relationships in a relational database, and what’s the difference between them?

One-to-One = one row matches one row in another table
One-to-Many = one row matches many rows in another table
Many-to-Many = many rows match many rows (needs a join table)