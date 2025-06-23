# 📘 Task 1: Database Setup and Schema Design

Domain: Library Management System

 Objective:
To design a structured relational schema with proper constraints and relationships using SQL and visualize with an ER diagram.

---

 Tools Used
- MySQL Workbench (for schema creation + ERD)
- GitHub (for code hosting)

---

 Tables Created:
1. Authors - Stores author details.
2. Books - Stores book details.
3. BookAuthors - Many-to-Many join between books and authors.
4. Members - Stores library members.
5. Borrow - Tracks borrowing transactions.

---

Key Concepts Used:
- DDL (CREATE TABLE, PRIMARY KEY, FOREIGN KEY)
- Normalization (3NF)
- ER Diagram Design
- AUTO_INCREMENT
- Composite Key in `BookAuthors`

---

ER Diagram
![ER Diagram]

---

 Interview Prep

1. What is normalization?
   Organizing data to reduce redundancy and improve integrity.

2. Explain primary vs foreign key.
   Primary uniquely identifies a row, foreign references a primary key in another table.

3. What are constraints?
   Rules like NOT NULL, UNIQUE, PRIMARY KEY, FOREIGN KEY, etc.

4. What is a surrogate key?
   An artificially generated key like AUTO_INCREMENT.

5. How do you avoid data redundancy?
   By normalization: breaking data into multiple related tables.

6. What is an ER diagram?
   Entity-Relationship diagram visually shows tables and their relationships.

7. What are the types of relationships in DBMS?
   One-to-One, One-to-Many, Many-to-Many.

8. Explain AUTO_INCREMENT.
   Automatically increments a numeric column for each new row (often used for IDs).

9. Default MySQL storage engine?
   InnoDB.

10. What is a composite key?
    A key that consists of two or more columns (like in BookAuthors).

---
