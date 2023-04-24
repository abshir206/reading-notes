# Readings: Data Modeling


## Reading

[nosql vs sql](https://www.thegeekstuff.com/2014/01/sql-vs-nosql-db/?utm_source=tuicool)

- What type of database is the best fit for the complex query intensive environment?
  - SQL is the best for complex queries as you can bring together models through relationships. This also makes complex data queries easier to organize.
- What type of database is the best fit for hierarchical data storage?
  - NoSQL as you do not have to define a strict schema and can simple keep everything in a single store.
- Describe the differences in scalability between a SQl and NoSQL database as though you were speaking to a non-technical friend.
  - SQL is upgrading pc components to handle more load while noSQL is buying more computers to handle more load

[sql modeling techniques](https://www.essentialsql.com/get-ready-to-learn-sql-7-simplified-data-modeling/)

- Among data tables, what is a one-to-many relationship and how do we “relate” them?
  - In some cases an entry in one table can be related to more than one entry in another. use Foreign Key
- Prior to designing your relational database, it might be useful to ___ a ___ of the database tables and their relationships.
  -  Design a diagram.
- Explain the difference between a primary and foreign key.
  -  A primary key is what the foreign key copies so that they maintain a relation to each other.

## Videos

[sql vs nosql](https://www.youtube.com/watch?v=ZS_kXvOeQ5Y)

- How do we treat keywords and parameters differently in SQL syntax?
  - Keywords are called using "SELECT", and parameters are called using "WHERE".
- Define normalization within the context of schemas and data.
  - The goal of normalization is to eliminate data anomalies that can occur when data is stored in a denormalized or redundant manner.
- Explain the difference between one-to-one, one-to-many, and many-to-many relationships to a non-technical recruiter.
  - In a one to one relationship one record of the first table will be linked to zero or one record of another table.


## Bookmark and Review

[sequelize api](https://sequelize.org/master/)

## Reflection
What are your learning goals after reading and reviewing the class README?