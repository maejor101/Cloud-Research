# Cloud-Research

1.  simply put cloud computing is the delivery of computing services including servers, storage, databases, networking, software, analytics, and intelligence - over the internet. 

2. * cost benefit: using computing elim8nates the capital expenses of buying hardware and software
     and setting up and running onsite daacenters.
   *speed benefit: vast amount of computing resources can be provisioned in minutes typically
     with just a few clicks.
   *Productivity benefit: onsite datacenters require alot of rackingt and stackinf and onther it management chores so cloud computing removes the need of many of this tasks so that
     the it team can spend time on more  important business goals.
   *reliabi;ity benefit: cloud computing makes data backup, disaster recovery, and business continuity easier and less expensive because data can be mirrored at multiple redundaant
	 sites on the cloud providers network.
3.
     *.IaaS - you rent IT infrastructure - servers and virtual machines, storage, networks, operating systems, from a cloud provideron a pay-as-you -go basis.
     * PaaS - refers to cloud computing services that supply an on-demand enviroment for developing, testing, deliveryig, and managing software applications.
     * SaaS -  is a method of deliverying software applications over the internet, on demand and typically on a subscription basis.
     * Serveless computing - focus on building app functionality without spending time continually managing the servers and infrastructure required to do so.

4. A database is an organized collection of structured information, or data, typically stored electronically in a computer system. A database is usually controlled by a database management system (DBMS).

5. Sometimes abbreviated as RT, real-time is a process or event that occurs immediately. For example, chat occurs in real-time, where messages are seen immediately after the user presses their Enter key.

6.
	* Relational databases: The name comes from the way that data is stored in multiple, related tables. Within the tables, data is stored in rows and columns. The relational database management system (RDBMS) is the 
      program that allows you to create, update, and administer a relational database
    * NoSQL databases: NoSQL is a broad category that includes any database that doesn’t use SQL as its primary data access language. These types of databases are also sometimes referred to as non-relational databases.
    * Cloud databases: A cloud database refers to any database that’s designed to run in the cloud. Like other cloud-based applications, cloud databases offer flexibility and scalability, along with high availability. 
  	* Columnar databases: store data in columns rather than rows. These types of databases are often used in data warehouses because they’re great at handling analytical queries
    * Wide column databases: Wide column databases, also known as wide column stores, are schema-agnostic. Data is stored in column families, rather than in rows and columns. Highly scalable, wide column databases can 
      handle petabytes of data, making them ideal for supporting real-time big data applications.
  	* Object-oriented databases: An object-oriented database is based on object-oriented programming, so data and all of its attributes, are tied together as an object. Object-oriented databases are managed by object- 
      oriented database management systems (OODBMS)
    * Key-value databases:  key-value databases save data as a group of key-value pairs made up of two data items each. They’re also sometimes referred to as a key-value store. Key-value databases are highly scalable and 
      can handle high volumes of traffic 
    * Hierarchical databases: Hierarchical databases use a parent-child model to store data. If you were to draw a picture of a hierarchical database, it would look like a family tree, with one object on top branching 
      down to multiple objects beneath it
    * Document databases: also known as document stores, use JSON-like documents to model data instead of rows and columns. Sometimes referred to as document-oriented databases, document databases are designed to store 
      and manage document-oriented information,
    * Graph databases: Graph databases are a type of NoSQL database that are based on graph theory. Graph-Oriented Database Management Systems (DBMS) software is designed to identify and work with the connections between 
      data points
    * Time series databases: A time series database is a database optimized for time-stamped, or time series, data. Examples of this type of data include network data, sensor data, and application performance monitoring 
      data.

7.one of the main differences between relational databases and NoSQL systems is that while relational databases generally support minimal transactions, NoSQL systems allow transactions to run on any row and transaction records.

8. Firebase is Google’s mobile application development platform that helps you build, improve, and grow your app.
   
9. its a Platform-as-a-SERVICE since it supplies  an on-demand enviroment for developing, testing, deliveryig, and managing software applications.
   
10.Cloud Firestore is a NoSQL, document-oriented database. Unlike a SQL database, there are no tables or rows. Instead, you store data in documents, which are organized into collections.

11. 
	* native aggregation queries:  Since query performance at massive scale is extremely important in Firestore, it simply doesn’t offer these sort of expensive aggregation queries.
	* Document write frequency limit of 1 per second: Firestore’s limits on writes and transactions are could throw a wrench in its ability to scale under load. The maximum sustained write rate to a document is 1 per 		  second.
	* Document size limit of 1MB: Firestore places a limit of 1MB on the amount of data that can be stored in a single document. This is more than enough for most cases. However, things start to break down when using map 	 and  array type fields that can grow unbounded over time.-Performance of offline/cached queries:

	*Query flexibility and index management: firestore, queries aren’t nearly as flexible as SQL allows (notably: no aggregations or joins).

12. structure - Relational databases require a lot of structure and some planning because you have to define columns and correctly fit data into fairly rigid categories. While this structure is great in some situations, it presents problems related to other drawbacks, such as Lack of maintenance and flexibility and scalability 
maintenance issues. Developers and other staff working with databases must spend time maintaining the database and fine-tuning it as more data is adde

Lack of flexibility. Relational databases are not ideal for handling large amounts of unstructured data. Data that is largely qualitative, not easily defined, or dynamic is not ideal for relational databases because it takes time to change or evolve the schema in response to the data. 
Lack of scalability. Relational databases do not scale well across the physical storage structures of multiple servers. Managing a relational database that spans multiple servers is difficult. This is because the structure becomes confusing as the size and distribution of the data set grows, and using multiple servers impacts performance and availability, such as application response time. 

13.The primary component of relational schemas is the tables, which are typically sets of records. 

14. NoSQL databse such as mongoDB is the best database for a Minimum Viable Product Since the will be low traffic to the app and also the data that is supposed to be stored wont be complex or complicated 

15. NoSQL databases are the best option because they provide the performance and scalability needed to effectively manage large catalogs and unstructured data such as user data and images. 
