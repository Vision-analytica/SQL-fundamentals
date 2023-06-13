# An introduction to SQL: a beginner's guide

<div style="background-color: #1C7879; border: 2px solid #ddd; padding: 5px; text-align: left;">
<h1>SQL (Structured Query Language) basics</h1>
    <ul>
        <li> SQL is a domain-specific programming language that is used to manage relational databases.</li>
        <li> It is designed for managing and querying data that is organized in a relational database management system (RDBMS).</li>
        <li> SQL provides a standardized way to perform various database operations such as creating, modifying, and deleting database tables, inserting, updating, and deleting data in tables, and querying the database to retrieve specific information.</li>
        <li> SQL is used by a wide range of organizations to manage and analyze data stored in databases.</li>
        <li> It is a fundamental tool for data analysts, database administrators, software developers, and other professionals who work with data in relational databases.</li>
    </ul>
</div>

But Going into more details on SQL, first lets know what are main query languages used, what are database and understand differences between few terminology.

# Query Languages (QL)

- QL is a general term used to describe a variety of query languages used in database management systems (DBMS). 
- These query languages are used to interact with the database, allowing users to search, retrieve, and modify data stored within the system.

## Important Query languages:

There are numerous Query Languages (QL) used in database management systems (DBMS). Some of the most common QLs include:

1. <font color="blue">**SQL (Structured Query Language)** - used to communicate with relational databases.</font>

2. **XQuery** - used to retrieve and manipulate data stored in XML documents.

3. **SPARQL (SPARQL Protocol and RDF Query Language)** - used to query and manipulate data stored in RDF databases.

4. **Cypher** - used to query graph databases.

5. **Gremlin** - used to traverse and manipulate graph data stored in graph databases.

6. **MDX (Multidimensional Expressions)** - used to query data stored in multidimensional databases.

7. **Datalog** - used to query and reason about data stored in deductive databases.

8. **FQL (Facebook Query Language)** - used to query data stored in Facebook's data infrastructure.

9. **SOQL (Salesforce Object Query Language)** - used to query data stored in Salesforce's customer relationship management (CRM) system.

10. **OQL (Object Query Language)** - used to query and manipulate data stored in object-oriented databases.

These are just a few examples of the many QLs used in database management systems.

## Some of the advantages of SQL

- **Easy to learn:** SQL has a simple and easy-to-understand syntax, which makes it easy for beginners to learn.
- **Portable:** SQL is a standard language, which means that it can be used with a variety of relational database management systems (RDBMS).
- **High performance:** SQL is optimized for performance and can handle large amounts of data quickly and efficiently.
- **Scalable:** SQL databases can scale easily by adding more servers or increasing the resources of existing servers.
- **Flexible:** SQL can be used to perform a wide range of tasks, from simple queries to complex analytics and data mining.
- **Secure:** SQL includes built-in security features that can help protect against data breaches and unauthorized access.
- **Ad-hoc querying:** SQL allows users to run ad-hoc queries against their data, which can be useful for exploring data and finding insights.
- **Data integrity:** SQL databases include features such as transactions and constraints that help ensure the integrity of the data stored in the database.
- **Ease of integration:** SQL databases can be easily integrated with other applications and tools, making it easy to access and analyze data from different sources.
- **Standardization:** SQL is a standardized language, which means that developers can use the same language and code across different databases and platforms.

## Disadvantages of SQL
With the advantages of SQL, it also has some disadvantages, which are as follows:

- **Complexity:** SQL can be complex and difficult to learn, especially for those who are new to programming.
- **Limited scalability:** SQL databases can struggle with scalability when it comes to handling large volumes of data, especially when compared to NoSQL databases.
- **Limited flexibility:** SQL databases are designed to handle structured data, which means they may not be as flexible as NoSQL databases when it comes to handling unstructured or semi-structured data.
- **Cost:** SQL databases can be expensive, especially when using commercial database management systems.
- **Security concerns:** SQL databases can be vulnerable to SQL injection attacks, which can result in data loss or corruption.
- **Performance issues:** SQL databases can experience performance issues, especially when complex queries are involved. This can be exacerbated when dealing with large data sets.



🗒️ Table of content

1. What is Data?
2. Role of data in a program
3. Data categories
4. What is a Database?
5. Database Model
6. What is DBMS?
7. DBMS categories
8. What is a Relational Database?
9. What is SQL?
10. Need for SQL
11. SQL Commands, explained

## 1. What is Data?

Data are
   - individual facts
   - statistics
   - items of information
 
## 2. Role of data in a program

All the programs can be divided into two major parts.

   - Code (or algorithms)
   - Data

The code in a program is static. But data is dynamic. Hence the runtime behavior of a program is largely dependent on data.

## 3. Data categories

Data can be broadly categorized into 3 categories based on its format.

   - Structured
   - Unstructured
   - Semi-Structured
 
 ### 3.1. Structured Data

   Structured Data aka "Quantitative Data" is the data which
   
   - has a well-defined structure
   - conforms to a data model
   - can be easily accessed and, used

   Structured data accounts for only about 20% of data. Examples: Name, Address.
   
 ### 3.2. Unstructured Data

   Unstructured Data aka "Qualitative Data" is the data which
   - does not have any predefined data model
   - cannot be processed by conventional tools

   Unstructured data accounts for about 80% of data. Examples: Text Files, Audio/Videos.
   
 ### 3.3. Semi-structured Data

  - semi-structured data is the “bridge” between structured and unstructured data.
  - It does not have a predefined data model and is more complex than structured data, yet easier to store than unstructured data.
  - Mostly in JSON/XML/CSV formats.
 
## 4. What is a Database?

A database is ❝an organized collection of data❞.

   - stored in a computer system so that
   - it can be easily accessed and managed
   
## 5. Database Model

- A database model is a data model that determines the logical structure of a database.
- It fundamentally determines how data can be stored, organized, and manipulated.
- One popular database model is the relational model, which uses a table-based format.

## 6. What is DBMS?
 
DBMS stands for Database Management System.

- DBMS is the software that is used to manage a database (whereas a database is for storage).
- A DBMS interacts with
    - end users
    - applications
    - database

A DBMS would typically take care of

    ❯ AuthN & AuthZ
    ❯ Create, Modify, Delete a Database
    ❯ Create, Modify, Delete Database Objects
    ❯ Create, Modify, Delete Data
    ❯ Query Data
    ❯ Handle transactions


## 7. DBMS categories

- Broadly DBMS are categorized into
    - Relational DBMS (RDBMS)
    - NoSQL
- RDBMS handles relational models and manages structured data.
- NoSQL comes with various database models and manages both unstructured and semi-structured data.

## 8. What is a Relational Database?

A relational database is a ❝collection of data items❞ that have some ❝pre-defined relationships❞ between them.

These items are organized as a set of "Tables" with "Columns" and "Rows".
- A relationship between 2 tables is established based on one or multiple similar columns.

## 9. What is SQL?

"SQL stands for Structured Query Language".
- SQL is a computer language for storing, manipulating, and retrieving data in a relational database.
- SQL provides useful commands for performing these operations.

## 10. Need for SQL

- Because of its popularity, multiple vendors started their own implementations of relational databases.
- The need to develop one common language for managing both data and structures became necessary.


## 11. SQL Commands, explained

   - DDL
   - DML
   - DQL
   - DCL
   - TCL

  ![image](https://user-images.githubusercontent.com/15100077/217216740-11156098-d4f6-4dce-80b9-7d2cb637926f.png)

### 11.1. DDL
  
DDL  ➟  Data Definition Language

- DDL commands are used to define the database schema.
- DDL is a set of SQL commands that are used to create, modify, and delete database structures but not data.

#### List of DDL Commands

- CREATE: Used to create the database or its objects (like Table, Views, Stored Procedures, Index, etc.)
- DROP: Used to delete objects from the database.
- ALTER: Used to alter the structure of the database.
- TRUNCATE: Used to remove all records from a table, including all spaces allocated for the records.
- RENAME: Used to rename an object already existing in the database.
- COMMENT: Used to add comments to the data dictionary.
     
### 11.2. DML

DML  ➟  Data Manipulation Language

- DML commands are used to manipulate the data present in the database.

#### List of DML Commands

- INSERT: Used to insert data into a table.
- UPDATE: Used to update existing data within a table.
- DELETE: Used to delete records from a database table.
- LOCK: Used to control the concurrency on a table.
- CALL: Used to call a PL/SQL code.
- EXPLAIN PLAN: To describe the access path to data.

### 11.3. DQL

DQL  ➟  Data Query Language

- DQL commands are used for performing queries on the data within schema objects.

#### List of DQL Commands

- SELECT: Used to retrieve data from the database.

### 11.4. DCL

DCL  ➟  Data Control Language

- DCL commands mainly deal with the rights, permissions, and other controls of the database system.

#### List of DCL Commands

- GRANT: To give users access privileges to the database.
- REVOKE: To withdraw the user’s access privileges.

### 11.5. TCL

TCL  ➟  Transaction Control Language

- TCL commands deal with the transaction within the database.

#### List of TCL Commands

- COMMIT: Used to commit a transaction.
- ROLLBACK: Used to rollback a transaction in case of any error occurs.
- SAVEPOINT: Used to set a savepoint within a transaction.
- SET TRANSACTION: Used to specify characteristics for the transaction.
