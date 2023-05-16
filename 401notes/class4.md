# Data Modeling

## What type of database is the best fit for the complex query intensive environment?

a relational database management system (RDBMS) is generally considered a good fit

## What type of database is the best fit for hierarchical data storage?

a database type that supports hierarchical data models is a good fit. One such database type is a hierarchical database.

## Describe the differences in scalability between a SQl and NoSQL database as though you were speaking to a non-technical friend.

SQL databases, also known as relational databases, have been around for a long time and are widely used. They are structured databases that store data in tables with predefined schemas. NoSQL databases, on the other hand, are designed to handle large-scale data and flexible data models. NoSQL stands for "Not Only SQL," indicating that they are not limited to the traditional SQL database model. They are typically used for unstructured or semi-structured data, such as documents, key-value pairs, graphs, or time-series data.

## Among data tables, what is a one-to-many relationship and how do we “relate” them?

a one-to-many relationship is a type of relationship where one record in a table is associated with multiple records in another table. It's a common type of relationship where the "one" side is connected to multiple records on the "many" side. To "relate" these tables and establish a one-to-many relationship, we typically use a concept called foreign keys. A foreign key is a field in the "many" side table that refers to the primary key of the "one" side table. It acts as a link between the two tables.

## Prior to designing your relational database, it might be useful to ___ a ___ of the database tables and their relationships

create, visual

## Explain the difference between a primary and foreign key.

A primary key is a unique identifier for a record in a table. It is like a special ID assigned to each row that makes it uniquely identifiable within that table. A foreign key is a field in one table that refers to the primary key in another table. 

## How do we treat keywords and parameters differently in SQL syntax?

Keywords in SQL are predefined reserved words that have specific meanings and functionalities within the language. Examples of keywords include SELECT, FROM, WHERE, JOIN, INSERT, UPDATE, DELETE, and so on. These keywords are used to construct SQL statements and define the structure and operations to be performed on the data.  Parameters in SQL are placeholders used to pass values into SQL statements dynamically. They are used in conjunction with prepared statements or parameterized queries to make the SQL statements reusable and protect against SQL injection attacks. Parameters are typically represented by placeholders, such as question marks (?) or named parameters (e.g., :param1, :param2). 

## Define normalization within the context of schemas and data.

the process of organizing and structuring a database in a way that reduces redundancy and improves data integrity and efficiency. It involves breaking down a database into multiple related tables and defining relationships between them.

## Explain the difference between one-to-one, one-to-many, and many-to-many relationships to a non-technical recruiter.

a one-to-one relationship as a unique and exclusive connection between two entities. It's like a marriage where one person is associated with only one other person. For example, let's consider the relationship between a person and their passport. Each person has only one passport, and each passport belongs to only one person. So, it's a one-to-one relationship. One-to-many like a parent-child relationship, where one parent can have multiple children. For instance, consider the relationship between a department and its employees in a company. A department can have many employees, but each employee belongs to only one department. So, it's a one-to-many relationship.  a many-to-many relationship, multiple entities from one side can be associated with multiple entities from the other side. It's like a friendship network, where people can have many friends, and those friends can have many other friends as well. For example, think of a relationship between students and courses. A student can enroll in multiple courses, and a course can have multiple students.

## What are your learning goals after reading and reviewing the class README?

I want to really understand how to use SQL.
