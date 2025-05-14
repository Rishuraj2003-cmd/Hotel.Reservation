# 🏨 Hotel Reservation System (Java + MySQL)

A simple terminal-based Hotel Reservation System built in Java using **JDBC** to interact with a **MySQL** database.
This project demonstrates the core operations of a hotel booking system such as reserving rooms, updating reservations, 
deleting entries, and viewing details — all via a menu-driven command-line interface.

---

## 📌 Features

- 🔹 Reserve a Room
- 🔹 View All Reservations
- 🔹 Retrieve Room Number by Guest Name & Reservation ID
- 🔹 Update Reservation Details
- 🔹 Delete a Reservation
- 🔹 Exit the Application

---

## 🛠️ Technologies Used

- **Java**
- **JDBC (Java Database Connectivity)**
- **MySQL**
- **ZSH/Terminal for execution**

---

## ⚙️ Database Schema

### MySQL Table: `reservations`

```sql
CREATE DATABASE students;

USE students;

CREATE TABLE reservations (
    reservation_id INT AUTO_INCREMENT PRIMARY KEY,
    guest_name VARCHAR(100),
    room_number INT,
    contact_number VARCHAR(20),
    reservation_date TIMESTAMP DEFAULT CURRENT_TIMESTAMP
);


🚀 How to Run
🔧 Prerequisites
Java 8 or above installed

MySQL Server running locally

JDBC MySQL connector (e.g., mysql-connector-java-8.x.x.jar)
