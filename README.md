# Database Design & Schemas Showcase

Welcome to my database design repository! This collection serves as a practical portfolio of my skills in database architecture, schema design, and data modeling.

The primary goal of this repository is to demonstrate a strong understanding of how to translate real-world business requirements into logical, efficient, and scalable database structures.

## Key Concepts Demonstrated

Each project diagram in this repository is designed to showcase proficiency in fundamental database concepts, including:

* **Entity-Relationship Modeling (ERM):** Accurately identifying entities, their attributes, and the relationships between them.
* **Database Normalization:** Applying normalization forms (1NF, 2NF, 3NF) to reduce data redundancy and improve data integrity.
* **Relationship Types:** Implementing various relationship types, such as:
    * **One-to-One (1:1)**
    * **One-to-Many (1:N)**
    * **Many-to-Many (N:M)** (using junction/associative tables)
* **Data Integrity:** Enforcing data integrity through the use of:
    * **Primary Keys (PK):** Ensuring unique identification for each record.
    * **Foreign Keys (FK):** Maintaining referential integrity between related tables.
    * **Constraints:** Using `NOT NULL`, `UNIQUE`, and `CHECK` constraints where appropriate.
* **Schema Design:** Creating clear and logical schemas that are optimized for common queries and future scalability.

---

## Project Diagrams

This repository contains database diagrams for several distinct systems, each tackling a different set of business problems.

### 1. DVLD (Driving & Vehicle License Department)
* **Description:** A comprehensive system designed to manage driver's licenses, vehicle registrations, driving tests, and traffic violations.
* **Key Features:** This schema handles complex relationships between People, Drivers, Vehicles, Licenses, and Applications.

### 2. Car Rental System
* **Description:** A complete database for a car rental agency.
* **Key Features:** Manages the vehicle fleet, customer information, bookings, rental transactions, and payment details.

### 3. Online Store
* **Description:** The backend schema for a standard e-commerce platform.
* **Key Features:** This design supports core e-commerce functionalities like user accounts, product catalogs, shopping carts, orders, and payments.

### 4. My Restaurant Program
* **Description:** A database for managing a restaurant's operations.
* **Key Features:** Includes tables for menu items, inventory, customer orders, table reservations, and staff management.

### 5. Simple Library System
* **Description:** A foundational database for a public or school library.
* **Key Features:** Manages books, library members, and the borrowing/return process (checkouts).

---

## How to Use

These diagrams are intended as examples of my database design work. They can be viewed as blueprints that are ready to be implemented using SQL `CREATE TABLE` statements in any relational database management system (RDBMS) such as MySQL, PostgreSQL, or SQL Server.
