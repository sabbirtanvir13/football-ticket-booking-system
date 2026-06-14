# B7A3 - Football Ticket Booking System

## 📖 Project Overview

This project is a PostgreSQL database design assignment based on a Football Ticket Booking System.

The system manages football fans, match information, and ticket booking records through a relational database structure. The project demonstrates database normalization, table relationships, ERD design, and SQL query implementation using PostgreSQL.

---

## 🎯 Features

* User Management
* Football Match Management
* Ticket Booking System
* Payment Status Tracking
* Relational Database Design
* SQL Query Practice
* ERD Design

---

## 🗄️ Database Tables

### Users

Stores registered users and ticket managers.

| Field        |
| ------------ |
| user_id      |
| full_name    |
| email        |
| role         |
| phone_number |

### Matches

Stores football match information.

| Field               |
| ------------------- |
| match_id            |
| fixture             |
| tournament_category |
| base_ticket_price   |
| match_status        |

### Bookings

Stores ticket booking records.

| Field          |
| -------------- |
| booking_id     |
| user_id        |
| match_id       |
| seat_number    |
| payment_status |
| total_cost     |

---

## 🔗 Entity Relationship Diagram (ERD)

ERD Link:

https://drawsql.app/teams/tanvir-ahmed-sabbir/diagrams/football-ticket-booking-system

The ERD includes:

* Primary Keys (PK)
* Foreign Keys (FK)
* One-to-Many Relationships
* Many-to-One Relationships
* Referential Integrity

---

## 🧩 Relationships

### User → Booking

One User can create multiple Bookings.

### Match → Booking

One Match can have multiple Bookings.

### Booking

Each Booking belongs to exactly one User and one Match.

---

## 🛠 SQL Concepts Used

* SELECT
* WHERE
* LIKE
* ILIKE
* IS NULL
* COALESCE
* INNER JOIN
* LEFT JOIN
* Subqueries
* Aggregate Functions
* AVG()
* ORDER BY
* LIMIT
* OFFSET

---

## 📋 Implemented Queries

### Query 1

Retrieve all available Champions League matches.

### Query 2

Search users using LIKE and ILIKE.

### Query 3

Handle NULL payment status using COALESCE.

### Query 4

Retrieve booking details with user and match information using INNER JOIN.

### Query 5

Display all users including those without bookings using LEFT JOIN.

### Query 6

Find bookings with total cost greater than the average booking cost.

### Query 7

Retrieve the top expensive matches while skipping the highest-priced match.

---

## 💻 Technologies Used

* PostgreSQL
* SQL
* DrawSQL
* GitHub

---

## 📂 Repository Structure

```text
.
├── README.md
├── QUERY.sql
└── ERD
```

---

## 🚀 Submission Links

### ERD

https://drawsql.app/teams/tanvir-ahmed-sabbir/diagrams/football-ticket-booking-system

### GitHub Repository

(Add your GitHub repository link here)

### Interview Video

(Add your interview video link here)

---

## 👨‍💻 Author

**Sabbir**

Assignment: B7A3 - Football Ticket Booking System

Level 2 Web Development
