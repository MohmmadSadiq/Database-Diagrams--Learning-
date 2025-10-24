# 🚀 Advanced Database Design & Data Modeling Portfolio

> A well-designed database is the backbone of any successful application. It's the silent engine that ensures data integrity, performance, and scalability. This repository is not just a collection of diagrams; it's a showcase of my ability to analyze complex business requirements and translate them into robust, efficient, and logical database schemas.

---

## 💡 Core Competencies Demonstrated

Across all projects, you will find a consistent application of advanced database design principles:

* **📊 Business Logic Translation:** The ability to listen to a "real-world" problem (like renting a car or managing a library) and model it accurately in data.
* **🔗 Normalization (1NF, 2NF, 3NF):** A strong focus on designing efficient schemas that eliminate data redundancy, prevent update/delete anomalies, and ensure data integrity.
* **🔑 Key & Constraint Mastery:**
    * **Primary Keys (PK):** Clear and simple unique identifiers for every entity.
    * **Foreign Keys (FK):** Building the "scaffolding" of the database by perfectly linking related tables to maintain referential integrity.
    * **Constraints (`UNIQUE`, `NOT NULL`, `CHECK`):** Using constraints as the first line of defense to guarantee that only valid data enters the system.
* **🔄 Complex Relationship Modeling:**
    * **One-to-Many (1:N):** The most common relationship, mastered here (e.g., one `Customer` can have many `Bookings`).
    * **Many-to-Many (N:M):** Implemented cleanly using **Junction Tables** (Associative Entities), such as connecting `Orders` with `Products` in the Online Store.
* **📈 Scalability by Design:** Designing schemas that are not just functional today, but are structured to grow and handle more complex queries in the future without a complete redesign.

---

## 📂 The Projects: From Concept to Schema

Each folder in this repository represents a unique design challenge.

### 🛂 DVLD (Driving & Vehicle License Department)
A complex, multi-entity system to manage all aspects of a national driving license program.
* **Design Highlight:** This schema demonstrates a deep hierarchy of related data (People -> Drivers -> Licenses; People -> Users) and tracks the "state" of applications and tests over time.

### 🚗 Car Rental System
A complete database for a car rental agency, managing its fleet, customers, and bookings.
* **Design Highlight:** This model excels at handling time-based data (booking start/end dates), managing vehicle availability (status), and logging transactions for reporting.

### 🛒 Online Store
The backend schema for a robust e-commerce platform.
* **Design Highlight:** Features the classic Many-to-Many relationship (via `Order_Items`) to link `Products` and `Orders`. It also effectively models customer accounts, inventory, and shopping cart state.

### 🍽️ My Restaurant Program
A database designed to manage a restaurant's daily operations.
* **Design Highlight:** This schema balances inventory management (recipes vs. raw ingredients), customer reservations, and point-of-sale (POS) transactions.

### 📚 Simple Library System
A foundational database for managing a library's catalog and members.
* **Design Highlight:** A clear and effective demonstration of core 1:N relationships (e.g., `Member` to `Loans`, `Book` to `Loans`) and tracking the state of an item (borrowed/available).

---

## 🛠️ Beyond the Diagram

Each schema here is a blueprint, ready to be implemented in any RDBMS (like PostgreSQL, MySQL, SQL Server, or Oracle). They serve as the solid foundation upon which robust, data-driven applications can be built.

Feel free to explore the diagrams to see how data flows and connects.
