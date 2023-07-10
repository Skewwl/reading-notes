# 401 class_04

## nosql vs sql

- What type of database is the best fit for the complex query intensive environment? Sql
  
- What type of database is the best fit for hierarchical data storage? NoSql
  
- Describe the differences in scalability between a SQl and NoSQL database as though you were speaking to a non-technical friend.
SQL databases are scaled by increasing the horse-power of the hardware. NoSQL databases are scaled by increasing the database servers. NoSql seems to have the upperhand here, unless square footage is a problem.

## sql modeling techniques

- Among data tables, what is a one-to-many relationship and how do we “relate” them?
When an entry in one table is related to more than one entry in another.
  
- Prior to designing your relational database, it might be useful to draw a sketch of the database tables and their relationships.
  
- Explain the difference between a primary and foreign key.
Primary keys uniquely identify each row in a table.  A table typically has one primary key. A foreign key is a column that matches a primary key in another table.


## sql vs nosql

- How do we treat keywords and parameters differently in SQL syntax?
Keywords are uppercase and parameters are lowercase.
  
- Define normalization within the context of schemas and data.
Normalization is a technique for organizing data in a database. It is important that a database is normalized to minimize redundancy (duplicate data) and to ensure only related data is stored in each table.
  
- Explain the difference between one-to-one, one-to-many, and many-to-many relationships to a non-technical recruiter.
One-to-one: A record in one table is related to a record in another table.
One-to-many: A record in one table is related to many records in another table.
Many-to-many: Multiple records in one table are related to multiple records in another table.
  

  
