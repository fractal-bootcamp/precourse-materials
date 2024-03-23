## QUESTIONS

- What is a database (DB)?

A database is an electrically stored, systematic collection of data.

- What is a column? A row? A table? What do these represent?

Columns and rows are parts of a table in which data is stored. These elements follow strict protocols for storing data because that data will need to be in the correct place in order to be accessed.

- What is a primary key? Why is it important?

Primary keys are important in relational databases as they are what is used to relate data between tables. Within each table a column is created to define what specific data is present in each row of the table. The elements in this column are the primary keys for all the data stored in the rows of that table.

- What is the difference between a SQL DB, NoSQL DB, and Graph DB?

SQL databases use SQL queries to extract, import, and manipulate data within relational databases. NoSQL databases also store data but they do not use tables. Instead they store data as documents, key-value pairs, or graphs. A Graph DB is a type of NoSQL DB that store data relationships directly next to the data itself.

- What is data persistence? Why is it important?

Data persistence is the longevity of data specific to an application after that application has closed. This persistence is important because certain data may need to be accessed upon the re-opening of an application. The idea is that we don't want to lose any data between sessions of an application.

- What is a data model?

A data model specifically determines the structure of data.

- What is an ORM?

An Object Relational Mapper is software that bridges the gap between data representations used in Object-Oriented Programming and databases. By abstracting from the boiler plate code required to converse between an application and database, an ORM allows developers to use their chosen programming language as means to interact with otherwise hard-to-interact-with software.

## ADVANCED

- What is 3rd Normal Form (3NF)?

Firstly, a non-prime attribute is an attribute that is not part of the candidate key, and therefore can have duplicates. Secondly, transitive dependency occurs when one non-prime attribute is dependent on another non-prime attribute. Now, 3NF is a state that a database table can be in. This specific state, 3NF, is when the table is in 2NF and also doesn't have a non-prime attribute that is transitively dependent on the primary key.

- What are the three types of relationships in a relational database, and what’s the difference between them?

The three types of relationships are one to one, one to many, and many to many. One to many is the most commonly used type and the other two are subtypes of it. In one to many, a single data element can have a relationship to many other data elements. This is different from one to one because in that case a single data element is related to another single data element, like how a single employee is related to only a single ID card. Likewise, many to many is also different from these other two. Here is an example to show this relationship: an employee can call many customers and a customer can receive many calls from employees. To handle this many to many relationship, another table needs to be made to associate the two properly, so a "call" table is made that employs two foreign keys, relating the employees and customers.
