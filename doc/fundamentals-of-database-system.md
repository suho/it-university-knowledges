# Fundamentals of Database System

About:

- Database Management System (*)
- Relational Data Model & SQL (*)
- Conceptual Modeling & Database Design (*)
- Object and Object-Relational Databases
- Database Programming Techniques
- Database Design Theory and Normalization
- File Structures, Indexing, and Hashing
- Query Processing and Optimization, and Database Tuning
- Transaction Processing, Concurrency Control, and Recovery (*)
- Additional Database Topics: Security and Distribution (*)
- Advanced Database Models, Systems, and Applications (*)
(*) Important

## Overview

### 1. Define the following terms: 

- data: known facts that can be recorded and have implicit meaning
- database: collection of related data
- DBMS: collections of programs that enables user to creat and maintain db 
- database catalog: the database definition / descriptive info is stored by DBMS in the form of a database catalog or dictionary, it's called meta-data
- deductive database system
- meta-data: The information stored in the catalog is called meta-data, and it describes the structure of the pri- mary database

### 2. What four main types of actions involve databases? Briefly discuss each.

- Self-describing nature of a database system: A fundamental characteristic of the database approach is that the database system contains not only the database itself but also a complete definition or description of the database structure and constraints. This definition is stored in the DBMS cata- log, which contains information such as the structure of each file, the type and stor- age format of each data item, and various constraints on the data. The information stored in the catalog is called meta-data, and it describes the structure of the pri- mary database

- Insulation between programs and data, and data abstraction:
	- In traditional file processing, the structure of data files is embedded in the applica- tion programs, so any changes to the structure of a file may require changing all pro- grams that access that file. 
	- By contrast, DBMS access programs do not require such changes in most cases. The structure of data files is stored in the DBMS catalog sepa- rately from the access programs. We call this property program-data independence.
	- The characteristic that allows program-data independence and program-operation independence is called data abstraction. A DBMS provides users with a conceptual representation of data that does not include many of the details of how the data is stored or how the operations are implemented.

- Support of multiple views of the data:
	- A database typically has many users, each of whom may require a different perspec- tive or view of the database. 
	- A view may be a subset of the database or it may contain virtual data that is derived from the database files but is not explicitly stored. 
	- Some users may not need to be aware of whether the data they refer to is stored or derived. 
	- A multiuser DBMS whose users have a variety of distinct applications must provide facilities for defining multiple views

- Sharing of data and multiuser transaction processing:
	- The DBMS must include concurrency control software to ensure that several users trying to update the same data do so in a controlled manner so that the result of the updates is correct.
	- A transaction is an executing program or process that includes one or more database accesses, such as reading or updating of database records. Each transaction is supposed to execute a logically correct database access if executed in its entirety without interference from other transactions.
	- The isolation property ensures that each transaction appears to execute in isolation from other transactions, even though hundreds of transactions may be executing concurrently. 
	- The atomicity property ensures that either all the database operations in a transaction are executed or none are. 

### 3. Discuss the main characteristics of the database approach and how it differs from traditional file systems.

### 4. What are the responsibilities of the DBA and the database designers?

- Database administrator DBA: chief administrator to oversee and manage these resources
- Database designers are responsible for identifying the data to be stored in the database and for choosing appropriate structures to represent and store this data.

### 5. What are the different types of database end users? Discuss the main activities of each.

- End user: are the people whose jobs require access to the database for querying, updating, and generating reports; the database primarily exists for their use.

### 6. Discuss the capabilities that should be provided by a DBMS.

- Controlling Redundancy
- Restricting Unauthorized Access
- Providing Persistent Storage for Program Objects
- Providing Storage Structures and Search Techniques for Efficient Query Processing
- Providing Backup and Recovery
- Providing Multiple User Interfaces
- Representing Complex Relationships among Data
- Enforcing Integrity Constraints
- Permitting Inferencing and Actions Using Rules
- ...

### 7. Discuss the differences between database systems and information retrieval systems.

## Database System Concepts and Architecture

### 1. Define the following terms: 

- data model 
	- Data model is a collection of concepts that can be used to describe the structure (data types, rela- tionships, and constraints that apply to the data) of a database—provides the necessary means to achieve this abstraction. 
	- Most data models also include a set of basic operations for specifying retrievals and updates on the database.
	
- database schema: In any data model, it is important to distinguish between the description of the data- base and the database itself. The description of a database is called the database schema, which is specified during database design and is not expected to change frequently
	- A displayed schema is called a schema diagram
	- We call each object in the schema—such as STUDENT or COURSE—a schema construct.

- database state: The data in the database at a particular moment in time is called a database state or snapshot. = current set of occurrences or instances

- internal schema
- conceptual schema
- external schema
- data independence
- DDL, DML, SDL, VDL
- query language, host language, data sublanguage
- database utility, catalog
- client/server architecture
- three-tier architecture, n-tier architecture.

### 2. Discuss the main categories of data models. What are the basic differences between the relational model, the object model, and the XML model?
### 3. What is the difference between a database schema and a database state?
### 4. Describe the three-schema architecture. Why do we need mappings between schema levels? How do different schema definition languages support this architecture?
### 5. What is the difference between logical data independence and physical data independence? Which one is harder to achieve? Why?
### 6. What is the difference between procedural and nonprocedural DMLs?
### 7. Discuss the different types of user-friendly interfaces and the types of users
who typically use each.
### 8. With what other computer system software does a DBMS interact?
### 9. What is the difference between the two-tier and three-tier client/server architectures?
### 10. Discuss some types of database utilities and tools and their functions.
### 11. What is the additional functionality incorporated in n-tier architecture
(n > 3)?