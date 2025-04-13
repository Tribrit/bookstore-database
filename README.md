# 📚 Bookstore Database Design & SQL Programming

## Overview

This project involves designing and developing a MySQL database for a Bookstore. As the database administrator, I was responsible for structuring and managing the data related to books, authors, customers, orders, shipping, and more. The goal was to create a clean, efficient, and secure relational database that supports real-world bookstore operations.

This hands-on task provided valuable experience in SQL programming, database normalization, relationship mapping, and user management.

---

## Tools and Technologies

- **MySQL** – for building and managing the database
- **Draw.io** – for visualizing the database schema and relationships (ERD)

---

## Prerequisites

To complete this project, the following skills and knowledge were required:

- Understanding of MySQL basics
- Ability to create tables and define relationships using SQL
- Knowledge of data types and database normalization
- User and role management in MySQL

---

## Project Objectives

- Design and implement a relational database to store bookstore data
- Create appropriate tables with normalized structure and correct data types
- Define and enforce relationships between tables using primary and foreign keys
- Manage users and roles for secure database access
- Write and test SQL queries to retrieve and analyze data efficiently

---

## Key Steps Followed

1. Created a new database to store all bookstore-related data.
2. Designed the database schema using Draw.io to outline entities and relationships.
3. Created all necessary tables with proper constraints and data types.
4. Implemented user roles and permissions for access control.
5. Tested the database using sample queries to ensure data integrity and performance.

---

## Tables Created

Below is a list of all the tables implemented in this project:

- `book` – Stores all books available in the store.
- `author` – List of all authors.
- `book_author` – Handles the many-to-many relationship between books and authors.
- `book_language` – Languages in which books are available.
- `publisher` – List of book publishers.
- `customer` – List of the bookstore's customers.
- `customer_address` – Connects customers to their multiple addresses.
- `address_status` – Status of an address (e.g., current, old).
- `address` – General address information.
- `country` – List of countries associated with addresses.
- `cust_order` – Orders placed by customers.
- `order_line` – Books included in each order.
- `shipping_method` – Available shipping methods.
- `order_status` – Possible statuses for orders (e.g., pending, shipped).
- `order_history` – Tracks the status changes for each order.

---

## Expected Outcomes

By completing this project, the following outcomes were achieved:

- A fully functional, normalized MySQL database designed for a bookstore
- Optimized table structures with appropriate keys and constraints
- User roles and access control policies implemented for secure database usage
- Sample queries tested to confirm data integrity and relationship accuracy

---

## Submission

- The group leader has created a GitHub repository containing:
  - SQL scripts for database creation
  - ERD diagram (Draw.io or exported image format)
  - This `README.md` file

