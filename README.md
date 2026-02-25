

# Bangladesh Organizational Database: Relational Model Demonstration

This SQL project demonstrates the core concept of relational database design using primary keys and foreign keys.

The **BANGLADESH** database enforces data integrity by establishing relationships between multiple tables and applying constraints such as PRIMARY KEY, FOREIGN KEY, UNIQUE, and NOT NULL.

The project ensures that invalid or inconsistent data cannot be inserted into related tables.

---

## Key Principles of Relational Database Design

The project achieves structured data management by:

### Data Integrity

Uses PRIMARY KEY constraints to uniquely identify records.

### Relationship Management

Applies FOREIGN KEY constraints to maintain relationships between tables.

### Uniqueness Enforcement

Uses UNIQUE constraint to prevent duplicate country names.

### Mandatory Fields

Implements NOT NULL constraint to ensure required data is provided.

### Structured Design

Demonstrates a clean hierarchical database structure.

---

## Database Structure

The database contains four related tables:

* COUNTRY
* DEPARTMENT
* EMPLOYE
* FOLDER

Each table is connected using foreign key relationships forming a hierarchical structure.

---

## Program Demonstration Steps

The execution of the SQL script highlights the benefits of relational database design:

* The  database is created.
* Four tables are defined with proper constraints.
* Five records are inserted into each table.
* Foreign key relationships ensure valid references between tables.
* SELECT queries retrieve and display stored data.
* Constraint violations (such as duplicate or invalid references) are prevented by the database system.

---

This project clearly demonstrates how relational databases maintain data consistency, enforce rules, and organize structured information efficiently.
