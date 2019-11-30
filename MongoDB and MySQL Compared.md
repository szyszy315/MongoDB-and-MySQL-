MongoDB and MySQL Compared
====

What is MongoDB
----
MongoDB is one of the most popular document-oriented databases under the banner of NoSQL database. <br>
It employs the format of key-value pairs which are stored in BSON files which are a little-modified version of JSON files and hence all JS are supported.Because of this, it is frequently used for Node.js projects. <br>
It offers greater efficiency and reliability which in turn can meet your storage capacity and speed demands.<br>

What is MySQL
----
MySQL is a popular open-source relational database management system (RDBMS) that is developed, distributed and supported by Oracle Corporation. 
MySQL stores data in tables and uses structured query language (SQL) for database access. <br>
In MySQL, you predefine your database schema based on your requirements and set up rules to govern the relationships between fields in your tables. every row in the table should have the same column. <br>


Different Query Language
----
MongoDB: This uses un-Structured Query Language. To build a query in JSON documents, you need to specify a document with properties you wish the results to match.<br>
MySQL: This uses the Structured Query Language SQL to communicate with the database. Despite its simplicity, it is indeed a very powerful language which consists mainly of two parts: Data Definition Language DDL & Data Manipulation Language DML.
![image](https://github.com/szyszy315/MongoDB-and-MySQL-/blob/master/Mysql%20vs%20mongodb.png)

JOIN operation
----
MongoDB: doesn’t support JOIN directly. This can be included as one of the stages in the aggregated pipeline. With the help of this operator, the work of combining data into a single query from multiple documents is possible.
MySQL: supports JOIN operations. JOIN allows the user to link data from two or more tables in a single query with the help of 'JOIN' command.

Sharding
----
Sharding is the method of distributing data across multiple machines to support deployments with large data sets and high throughput operations.<br>
MongoDB: Its sharding has the ability to break up a collection into subsets of data to store them across multiple shards. This allows the application to grow beyond the resource limits of a standalone server or replica set.<br>
MySQL: No standard sharding implementation. 

Replication
----
MongoDB: This supports only master-slave replication. It uses replica sets to create multiple copies of the data.
MySQL: This supports both master-slave replication and master-master replication. Multi-source replication gives you the ability to replicate data from several masters in parallel.

Performance & Speed
----
MongoDB: A main benefit it has over MySQL is its ability to handle large unstructured data. People are experiencing real world MongoDB performance mainly because it allows users to query in a different manner that is more sensitive to workload.<br>
MySQL: Developers note that MySQL is quite slow in comparison to MongoDB when it comes to dealing with the large database. Hence, it is a better choice for users with small data volume.


Conclusion
----
MySQL is well-recognized for its high performance, flexibility, reliable data protection, high availability, and management ease. Proper data indexing can solve the issue with performance, facilitate interaction and ensure robustness. But if your data is unstructured and complex, or if you can’t pre-define your schema, you’d better opt for MongoDB. And what is more, if you need to handle a large volume of data and store it as documents MongoDB is always a better choice.
