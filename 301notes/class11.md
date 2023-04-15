# MongoDB and Mongoose

## Fill in the chart below with five differences between SQL and NoSQL databases:

SQL	NoSQL

Uses relational databases, data is structured and stored in tables with defined relationships. Data is stored in a variety of ways, including document-oriented databases, key-value stores, graph databases, and more.
Data is stored in a fixed schema with pre-defined tables, columns, and relationships. Data is typically stored in a flexible schema that can accommodate changing data structures and relationships.
Suitable for complex queries and data that needs to be strictly structured. Suitable for handling large amounts of unstructured or semi-structured data.
Supports transactions and provides ACID (Atomicity, Consistency, Isolation, Durability) guarantees. Does not typically provide ACID guarantees but can support eventual consistency and other forms of data consistency.
Good for applications that require strong data integrity and consistency, such as financial systems or e-commerce platforms. Good for applications that require high scalability and performance, such as social networks or big data applications.

## What kind of data is a good fit for an SQL database?

Financial data, such as transaction records or banking information.
E-commerce data, such as customer orders, inventory, and shipping records.
Healthcare data, such as patient records and medical billing information.
Human resources data, such as employee records and payroll information.
Customer relationship management (CRM) data, such as customer profiles and contact information

## Give a real world example.

An e-commerce platform typically stores a large amount of structured data, including information about customers, products, orders, and transactions.

## What kind of data is a good fit a NoSQL database?

Big data applications, such as log files or machine-generated data.
Social media data, such as user profiles, comments, and posts.
Real-time data, such as stock prices or sensor readings.
Internet of Things (IoT) data, such as sensor data from connected devices.
Content management systems, such as blogs or news sites.

## Give a real world example.

A CMS for a news website stores a large amount of unstructured or semi-structured data, including articles, images, videos, and comments. This data may not have a well-defined schema, and the relationships between different types of data may be complex and variable

## Which type of database is best for hierarchical data storage?

a hierarchical database management system

## Which type of database is best for scalability?

NoSQL databases 

## What does SQL stand for? 

 Structured Query Language.

## What is a relational database?

 rganizes data into one or more tables, where each table consists of a set of rows and columns

## What type of structure does a relational database work with?

 works with a tabular structure.

## What is a ‘schema’?

  a logical structure that defines the organization of the database

## What is a NoSQL database?

   a non-relational database that is designed to store and manage large volumes of unstructured, semi-structured, and structured data.

## How does it work?

depends on the data model it uses

## What is inside of a MongoDB database?

 collection is a grouping of MongoDB documents

 ## Which is more flexible - SQL or MongoDB? and why.

 MongoDB is generally considered to be more flexible than SQL databases because of its document-oriented data model, which allows for more flexible schemas and easier scaling

 ## What is the disadvantage of a NoSQL database?

 Limited querying: NoSQL databases often have limited querying capabilities compared to SQL databases, as they are designed for simple queries and aggregations. This can make it difficult to perform complex data analysis or generate detailed reports.

Lack of standardization: Unlike SQL databases, which have a standardized query language (SQL), NoSQL databases do not have a standardized interface or query language. This can make it difficult to switch between different NoSQL databases or to integrate with other systems.

Limited transaction support: NoSQL databases often have limited support for transactions, which can make it difficult to maintain data consistency in complex systems.

Limited tooling: NoSQL databases may have limited tooling support compared to SQL databases, making it harder to manage and monitor the database.

Limited community support: NoSQL databases often have smaller communities than SQL databases, which can make it harder to find help or resources when needed.

Overall, it is important to carefully consider the advantages and disadvantages of NoSQL databases before choosing them for a particular use case. While they offer many benefits, they may not be the best choice for every situation.
