# 1.What is PostgreSQL?
PostgreSQL (often abbreviated as Postgres) is a powerful, open-source relational database management system (RDBMS). It is known for its robust features, standards compliance, and strong support for complex queries and data integrity.

Key Features of PostgreSQL:
- Open Source
- ACID Compliant
- SQL and NoSQL Capabilities
- Extensibility
- Concurrency
- Advanced Indexing and Full-text Search
- Foreign Data Wrappers

# 2.What is the purpose of a database schema in PostgreSQL?
In PostgreSQL, a database schema serves as a namespace within a database that organizes and separates database objects, such as tables, views, indexes, functions, and sequences. The primary purpose of a schema is to provide logical grouping and structure to database objects, which helps in managing complexity, enhancing security, and avoiding name collisions.

Purposes of a Schema in PostgreSQL:
- Namespace Management
- Organization
- Access Control and Security
- Support for Multi-Tenancy
- Ease of Development and Maintenance
- Modular Design

# 3.Explain the Primary Key and Foreign Key concepts in PostgreSQL.
In PostgreSQL, Primary Key and Foreign Key are crucial concepts for maintaining data integrity and defining relationships between tables.

🔑 Primary Key
A Primary Key is a column or a set of columns in a table that uniquely identifies each row in that table.

Characteristics:
- Unique
- Not NULL
- A table can have only one primary key

🔗 Foreign Key
A Foreign Key is a column or a set of columns in one table that refers to the primary key (or a unique key) in another table. It creates a relationship between two tables.

Purpose:
- Ensures referential integrity
- Helps maintain consistent and connected data across tables