## What type of database is the best fit for the complex query intensive environment?

SQL databases 
## What type of database is the best fit for hierarchical data storage?
NoSQL database 

## Describe the differences in scalability between a SQl and NoSQL database as though you were speaking to a non-technical friend.

SQL databases are vertically scalable, which means you can handle increased workload by upgrading the resources (CPU, RAM, etc.) of a single server. NoSQL databases, on the other hand, are horizontally scalable. They allow you to handle more traffic by adding more servers to distribute the workload across a cluster of machines


## Among data tables, what is a one-to-many relationship and how do we “relate” them?

one-to-many relationship is a connection between two tables where each record in one table can have multiple related records in the other table. This relationship is established using foreign keys that reference the primary key of the related records.

## Prior to designing your relational database, it might be useful to ___ a ___ of the database tables and their relationships.
create a schema



## Explain the difference between a primary and foreign key.

-primary key : is a unique identifier within a table that helps identify each record uniquely.

-foreign key: a foreign key is a field in a table that establishes a relationship with the primary key of another table. It enables the linking of related records between tables



## How do we treat keywords and parameters differently in SQL syntax?

 - in SQL syntax keywords are reserved words that have a specific meaning and functionality within the language. They are predefined and have a fixed purpose, such as SELECT, FROM, WHERE, and ORDER BY.

 - parameters are values that are used to provide dynamic input to SQL statements. Parameters act as placeholders and allow for flexibility in executing queries or statements. They can be used in various parts of an SQL statement, such as in the WHERE clause to filter data or in the VALUES clause to insert data.


 ## Define normalization within the context of schemas and data.

 
Normalization is a process in database design that helps organize and structure data efficiently by eliminating data redundancy and improving data integrity. It involves breaking down a database into multiple tables and defining relationships between them to reduce data duplication and anomalies

## Explain the difference between one-to-one, one-to-many, and many-to-many relationships to a non-technical recruiter.

- One-to-One: relation between person and passport , each person has one passport, and each passport belongs to one person.

- One-to-Many:relation between bookstore and books. The bookstore can have multiple books, but each book is associated with only one specific bookstore

- Many-to-Many: students and classes in a school,Students can be enrolled in multiple classes, and each class can have multiple students.