# An introduction to SQL: a beginner's guide

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
