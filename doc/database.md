# Database

## What is Database?

A database is a separate application that stores a collection of data. Each database has one or more distinct APIs for creating, accessing, managing, searching and replicating the data it holds.

Relational database management systems (RDBMS) - is called relational database because all the data is stored into different tables and relations are established using primary keys or other keys known as Foreign Keys.

## RDBMS Terminology

- **Database**: A database is a collection of tables, with related data.
- **Table**: A table is a matrix with data. A table in a database looks like a simple spreadsheet.
- **Column**: One column (data element) contains data of one and the same kind, for example the column postcode.
- **Row**: A row is a group of related data, for example the data of one subscription.
- **Redundancy**: Storing data twice, redundantly to make the system faster
- **Primary Key**: A primary key is unique. A key value can not occur twice in one table. With a key, you can only fine one row.
- **Foreign Key**: A foreign key is the linking pin between two tables.
- **Compound Key**: A compound key is a key that consists of multiple columns, because one column is not sufficiently unique.
- **Index**: An index in a database resembles an index it the back of a book.
- **Referential Integrity**: Referantial Integrity makes sure that a foreign key value always points to an existing row.

## Query

### Create Database

```sql
CREATE DATABASE database_name;
```

### Drop a Database

```sql
DROP DATABASE database_name;
```