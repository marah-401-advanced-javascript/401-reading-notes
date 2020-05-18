# Data Modeling & NoSQL Databases


## Why would a developer choose to make data models?
-  Higher quality, since you should consider data before building an app.
-  Reduced cost.
-  Faster performance,simplifies database tuning
-  Fewer application errors. A data model causes participants to crisply define concepts and resolve confusion


## What purpose do CRUD operations serve?
- CRUD Prevents Casual Browsing and Changes
- using CRUD operations helps to prevent SQL injection attacks

## What kind of database is Postgres? What kind of database is MongoDB?
- **PostgreSQL** is an open-source RDBMS.PostgreSQL stores data in tables and uses Structured Query Language (SQL) for database access, in addition to PL/pgSQL, which resembles Oracle's PL/SQL procedural language.
- **MongoDB** is an open, non-tabular database database engineered by MongoDB, Inc. MongoDB stores data as documents in a binary representation called BSON. Related information is stored together in the same document for fast query access via the MongoDB query language.


## What is Mongoose and why do we need it?
A Mongoose model is a wrapper on the Mongoose schema. A Mongoose schema defines the structure of the document, default values, validators, etc., whereas a Mongoose model provides an interface to the database for creating, querying, updating, deleting records, etc.

## Define three related pieces of data in a possible application. 
-product
-category
-department
"each Product has a Category and belongs in a Department."

## Terms 

* database:
A database is an organized collection of data, generally stored and accessed electronically from a computer system. Where databases are more complex they are often developed using formal design and modeling techniques.
 
* data model: 
Models’ are higher-order constructors that take a schema and create an instance of a document equivalent to records in a relational database.

* CRUD:
Within computer programming, the acronym CRUD stands for create, read, update and delete. These are the four basic functions of persistent storage

* schema:
While Mongo is schema-less, SQL defines a schema via the table definition. A Mongoose ‘schema’ is a document data structure (or shape of the document) that is enforced via the application layer.

* sanitize:
Sanitize and Sanitized data is any computer data (usually a user's input) that is checked by software to see if it contains any information that might be harmful to the system. For instance, including HTML in a comment on a message board may be harmful to someone viewing the message since their computer might interpret the HTML as a command.
 
* Structured Query Language (SQL):
SQL stands for Structured Query Language,
SQL lets you access and manipulate databases,
SQL became a standard of the American National Standards Institute (ANSI), in 1986, and of the International Organization for Standardization (ISO) in 1987

* Non SQL (NoSQL): 
NoSQL is an approach to database design that can accommodate a wide variety of data models, including key-value, document, columnar and graph formats.

* MongoDB:
MongoDB is a document-oriented NoSQL database used for high volume data storage.

* Mongoose:
 A Mongoose model is a wrapper on the Mongoose schema. A Mongoose schema defines the structure of the document, default values, validators, etc., whereas a Mongoose model provides an interface to the database for creating, querying, updating, deleting records, etc.
  
* record:
In database management systems, a complete set of information. Records are composed of fields, each of which contains one item of information. A set of records constitutes a file.

* document:
 ‘Documents’ are equivalent to records or rows of data in SQL. While a SQL row can reference data in other tables, Mongo documents usually combine that in a document.
 
* Object Relation Mapping (ORM):
Object-relational-mapping is the idea of being able to write queries like the one above, as well as much more complicated ones, using the object-oriented paradigm of your preferred programming language.


## links & references:


- https://stackify.com/what-are-crud-operations/
- https://www.mongodb.com/compare/mongodb-postgresql
- https://www.freecodecamp.org/news/introduction-to-mongoose-for-mongodb-d2a7aa593c57/9781785880735/1/ch01lvl1sec12/disadvantages-of-tdd
- https://en.wikipedia.org/wiki/Databasewhat-is-a-good-usecase-for-the-es2015-static-methods
- https://medium.com/javascript-scene/master-the-javascript-interview-what-is-functional-programming-7f218c68b3a0
- https://www.computerhope.com/jargon/s/sanitized-data.htm
- https://searchdatamanagement.techtarget.com/definition/NoSQL-Not-Only-SQL
