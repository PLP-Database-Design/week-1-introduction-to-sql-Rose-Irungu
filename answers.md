Question one

A DBMS has the following core components:

Database Engine: Handles data storage, retrieval, and updates. It is responsible for managing transactions and ensuring data integrity.
Query Processor: Interprets and executes database queries written in SQL.
Database Schema: Defines the structure of the data in terms of tables, relationships, and constraints.
Data Manager: Manages the storage and retrieval of data in the database, ensuring efficiency.
Transaction Manager: Ensures that database operations are executed in a safe and reliable manner using ACID (Atomicity, Consistency, Isolation, Durability) properties.
Database Users: Includes administrators, developers, and end-users who interact with the DBMS for various purposes.

QUESTION TWO

A relational database stores data in tables (relations), which consist of rows and columns. Each table represents an entity, and relationships between tables are established using keys.

Examples:

MySQL
PostgreSQL
Oracle Database
Microsoft SQL Server

QUESTION THREE

Data Definition Language (DDL): Used to define the database schema and structure.

Example: CREATE, ALTER, DROP.
Purpose: Modify database structure (e.g., creating tables or schemas).
Data Manipulation Language (DML): Used for managing data within tables.

Example: INSERT, UPDATE, DELETE, SELECT.
Purpose: Manipulate and retrieve data.
Data Control Language (DCL): Used to manage access to the database.

Example: GRANT, REVOKE.
Purpose: Control user permissions and security.

QUESTION FOUR

Definition:

A Primary Key is a unique identifier for each record in a table. It ensures that no two rows in the table have the same value for this key.
A Foreign Key is a field in one table that refers to the Primary Key in another table, establishing a relationship between the two tables.
Uniqueness:

The Primary Key must always contain unique values. It uniquely identifies each record in the table.
The Foreign Key can have duplicate values, as multiple rows in a table may refer to the same Primary Key in another table.
Null Values:

The Primary Key cannot contain null values; every record must have a value for this key.
The Foreign Key can sometimes contain null values if the relationship is optional.
Purpose:

The Primary Key ensures that each record in the table is distinct.
The Foreign Key is used to link two tables together and enforce referential integrity between the related data.


QUESTION FIVE

An Entity-Relationship Diagram is a visual representation of entities in a database and their relationships. It consists of:

Entities: Objects or concepts (e.g., Customer, Order).
Attributes: Properties of entities (e.g., CustomerID, Name).
Relationships: Links between entities (e.g., places relationship between Customer and Order).
Purpose: ERDs are used in database design to map out the structure before implementation.

QUESTION SIX

Data Integrity: Ensures accuracy and consistency of data through constraints.
Flexibility: Easy to update and query using SQL.
Scalability: Supports large amounts of data efficiently.
Relationships: Handles complex relationships between entities via foreign keys.
Security: Access control and permissions can be implemented at different levels.

QUESTION SEVEN

Integer: Stores whole numbers (e.g., INT, BIGINT).
String/Text: Stores text data (e.g., VARCHAR, TEXT).
Date/Time: Stores date and time values (e.g., DATE, TIMESTAMP).
Floating Point/Decimal: Stores decimal or fractional numbers (e.g., FLOAT, DECIMAL).

QUESTION EIGHT

The main purpose of a DBMS is to efficiently store, retrieve, and manage data while ensuring:

Data Integrity: Guarantees accuracy and reliability.
Data Security: Protects data through authentication and authorization.
Data Consistency: Maintains data correctness in a multi-user environment.
Data Organization: Enables logical storage and retrieval of data using queries.
Scalability: Handles growing amounts of data and users effectively.


