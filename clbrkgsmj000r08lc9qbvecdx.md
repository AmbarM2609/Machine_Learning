# Database : Different types of database

**First of all, we will see what is meant by database...?**

Well, A database is a structured collection of data that is stored electronically and is designed to be accessed and managed quickly and efficiently. There are several different types of databases, including relational databases, NoSQL databases, object-oriented databases, and graph databases. Each type is designed to support specific types of data and applications and is optimized for different types of queries and data manipulation.

Databases are used in a wide variety of applications, including business, government, healthcare, and more. They are an essential tool for storing, organizing and managing large amounts of data efficiently etc.

### **Several different types of database platforms are used to store, organize, and manage data. Some of the most common types include:**

### **Relational database:**

This is one type of database based on the relational model of data. It stores data in tables, with rows representing individual records and columns representing the attributes of those records.

In a relational database, data is organized into related tables, with each table representing a specific entity or concept. For example, a database for a business might have separate tables for customers, products, orders, and employees. The tables are linked together using keys, which are attributes that are used to identify and relate records in different tables.

Relational databases use a programming language called Structured Query Language (SQL) to define and manipulate the data. SQL is a declarative language, which means that it is used to specify what action should be performed, rather than how to perform it. This makes it easy to use and understand and allows it to be used to interact with a wide range of databases.

Relational databases are widely used in a variety of applications, including business intelligence, data analysis, and web development. They are an essential tool for storing, organizing and managing large amounts of structured data efficiently. Examples of popular relational databases include MySQL, Oracle, and Microsoft SQL Server.

###   
NoSQL databases:

(also known as "non-relational" or "not only SQL" databases) are a type of database that is designed to handle large volumes of unstructured data and support distributed, scalable applications. They are often used in web-based applications, where the ability to store and retrieve data quickly is critical.

Unlike relational databases, which are based on the relational model of data and use SQL to define and manipulate data, NoSQL databases do not use a fixed schema and can store data in a variety of formats, including documents, key-value pairs, and graph data. This makes them well-suited for handling unstructured data, such as text, images, and social media data, which can be difficult to fit into the fixed schema of a relational database.

NoSQL databases are often distributed, which means that they are designed to be distributed across multiple servers and can scale horizontally to support large amounts of data and high levels of traffic. They can also support real-time, high-speed data access, which makes them well-suited for use in applications that require low latency, such as gaming and social media.

Examples of popular NoSQL databases include MongoDB, Cassandra, and Redis.

### Object-oriented database:

An object-oriented database is a type of database that is designed to store and manipulate data in the form of objects. Objects are self-contained units of data and behavior that are typically used in object-oriented programming languages.

In an object-oriented database, objects are stored in the database and can be accessed and manipulated using object-oriented programming techniques. This allows developers to store and manipulate complex data structures and relationships directly in the database, rather than having to translate them into a more traditional database format.

Object-oriented databases are often used in applications that require the storage and manipulation of complex data structures, such as engineering design data or multimedia content. They can also support the integration of data and code, which allows developers to create more powerful and flexible applications.

Examples of object-oriented databases include ObjectDB and db4o.

### Graph database:

A graph database is a type of database that is designed to store and manipulate data in the form of graphs, with nodes representing entities and edges representing relationships between those entities.

Graph databases are particularly well-suited for modeling complex relationships and networks, and can support fast querying and analysis of data. They are often used in applications that require the efficient querying of relationships, such as social networking, fraud detection, and recommendation engines.

In a graph database, data is stored in the form of nodes and edges, which are interconnected to represent relationships between entities. Nodes can represent a wide range of entities, such as people, products, locations, or events, and can have properties associated with them that describe their characteristics. Edges represent relationships between nodes, and can also have properties associated with them to describe the nature of the relationship.

Graph databases can be queried using specialized query languages, such as Cypher and Gremlin, which are designed to support the efficient querying and manipulation of data stored in a graph.

Examples of popular graph databases include Neo4j and OrientDB.

I hope you get enough information about databases and types, according to this you can select what type of data is useful for your project.