## Class 4 Reading notes

(https://www.thegeekstuff.com/2014/01/sql-vs-nosql-db/?utm_source=tuicool)
1. What type of database is the best fit for the complex query intensive environment?
SQL Databases are best suited.
<br>

2. What type of database is the best fit for hierarchical data storage?
NoSQL is better suited for heirarchical storage.
<br>

3. Describe the differences in scalability between a SQl and NoSQL database as though you were speaking to a non-technical friend.
SQL databases are better for storing data in a 'Deep' way that only a few people at a time may access, where as NoSQL is 'Shallow' and lots of people may access the data at once.
<br>

(https://www.essentialsql.com/get-ready-to-learn-sql-7-simplified-data-modeling/)
1. Among data tables, what is a one-to-many relationship and how do we “relate” them?
We connect lines between tables to show relationships.  In some cases an entry in one table can be related to more than one entry in another.  This is called a one-to-many relationship.
<br>

2. Prior to designing your relational database, it might be useful to _ draw__ a _picture__ of the database tables and their relationships.
<br>

3. Explain the difference between a primary and foreign key.

Foreign Key (columns) – This is a column or set of columns which match a primary key in another table.
The Primary Keys(rows).  Remember the primary keys uniquely identify each row in a table.  A table typically has one primary key, but can have more.  When the key has more than one column, it is called a compound key.

<br>


(https://www.youtube.com/watch?v=ZS_kXvOeQ5Y)
1.How do we treat keywords and parameters differently in SQL syntax?
They can be combined in order to make commands, and it is quite powerful!
<br>

2.Define normalization within the context of schemas and data.
"Normalization entails organizing the columns (attributes) and tables (relations) of a database to ensure that their dependencies are properly enforced by database integrity constraints.” source--(https://towardsdatascience.com/a-complete-guide-to-database-normalization-in-sql-6b16544deb0)
<br>

3.Explain the difference between one-to-one, one-to-many, and many-to-many relationships to a non-technical recruiter.
One to one means that a user and data are pairs and has a contact id, one to many means one user can be attached to lots of data (more than one to one) has a creator id, many to many means lots of data spread between multiples tables, user ids and role ids both get assigned.
<br>
