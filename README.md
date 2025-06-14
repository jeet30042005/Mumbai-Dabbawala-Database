#  Mumbai Dabbawala DBMS Project

This is the project developed in the 4th semester as part of the Database Management Systems (DBMS) course. It models the **Mumbai Dabbawala** lunchbox delivery system using relational database concepts like ER modeling, normalization, SQL, and functional dependency analysis.

---

##  Project Overview

The Mumbai Dabbawala network is renowned for delivering over 200,000 lunchboxes daily with near-perfect accuracy. This project captures and simulates that system through a structured relational database that supports customers, dabbawalas, delivery tracking, orders, payments, and more.

---

##  Files Included

-  **Mumbai Dabbawala Database.pdf** — Complete documentation including:
  - Project description & scope
  - ER Diagram & Relational schema
  - Functional Dependencies
  - BCNF proofs
  - Table designs with attribute details

-  **scripts and queries.zip** — Contains:
  -  `DDL Scripts` – Create tables and schema
  -  `Insert Scripts` – Sample data population
  -  `SQL Queries` – Real-world use-case queries (search, join, filter, etc.)

---

##  Tables in Database

- `Customer` — Stores customer info and assigned dabba
- `Dabbawala` — Tracks dabbawala details and hierarchy
- `Dabba` — Delivery container info, source/destination
- `Orders` — Customer orders linked to dabba and payment
- `Payment` — Tracks transactions per order
- `Donation` — Optional donations by customers
- `Holiday` — Leave records for dabbawalas
- `Punishment` — Records of rule violations by staff

---

##  Technologies Used

- MySQL (can be adapted to PostgreSQL or others)
- SQL (DDL, DML, Queries)
- ER Diagram Tools (dbdiagram.io / Draw.io)

---

##  Features

- BCNF-compliant normalized schema
- Sample data and pre-written SQL queries
- Realistic modeling of Dabbawala workflow
- Ready-to-run SQL files included
- Designed for academic and interview presentation

---

##  Group Members

- Maharshi Raval (202201003)
- Anjali Chandwani (202201032)
- Ayush Gandhi (202201057)
- Jeet Patel (202201089)

---

##  How to Run

1. Import the `DDL Script` file to your MySQL server.
2. Execute the `Data_Insertion_Script` script to populate sample data.
3. Run SQL queries from the `SQL queries` file to interact with the database.

---

## Conclusion

This project showcases a practical implementation of DBMS concepts through the lens of a real-world logistics system. It emphasizes relational design, normalization, and structured query handling. Ideal for academic submission, learning, or demo during interviews.
