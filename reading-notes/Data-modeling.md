# nosql vs sql

1- What type of database is the best fit for the complex query intensive environment? 
>For databases that need to handle complex queries, SQL databases are the best choice. They are designed to handle complicated questions about data efficiently and provide powerful querying capabilities.

2-What type of database is the best fit for hierarchical data storage? NoSQL?
>If you have data with a hierarchical structure (like parent-child relationships), NoSQL databases are a good fit. They allow you to store and manage data in a way that reflects these hierarchical relationships more easily.

3- Describe the differences in scalability between a SQl and NoSQL database as though you were speaking to a non-technical friend?
>SQL databases are vertically scalable whereas the NoSQL databases are horizontally scalable. SQL databases are scaled by increasing the horse-power of the hardware. NoSQL databases are scaled by increasing the databases servers in the pool of resources to reduce the load.

# sql modeling techniques

1.Among data tables, what is a one-to-many relationship and how do we “relate” them?
>an entry in one table can be related to more than one entry in another.

2.Prior to designing your relational database, it might be useful to ___ a ___ of the database tables and their relationships?
>to create a diagram

3.Explain the difference between a primary and foreign key?
>A primary key is a unique identifier for each record in a table, ensuring that each record has a distinct identity. A foreign key is a column in a table that refers to the primary key of another table, establishing a relationship between them. The primary key uniquely identifies records within a table, while the foreign key links records between different tables.

# sql vs nosql

1.How do we treat keywords and parameters differently in SQL syntax?
>-keywords have predefined meanings in SQL and are used to define the structure and actions of SQL statements like [ SELECT, INSERT, UPDATE, DELETE, CREATE ] .
>-parameter represents a value to be supplied at runtime , and it used to handle user input .

2.Define normalization within the context of schemas and data?
>Normalization helps to improve database performance, reduce data duplication, and enhance data integrity.

3.Explain the difference between one-to-one, one-to-many, and many-to-many relationships to a non-technical recruiter?
>one-to-one : its mean that one table belong an relate to only one table

>one-to-many : its mean that one table belong to multiple users , or multiple users belong and relate to only one table it’s like having a single source connected to multiple destinations.

>many-to-many : its mean that multiple instances of one entity can be associated with multiple instances of another entity , for example we have students and courses each student can enroll in multiple courses and each course can has multiple students
