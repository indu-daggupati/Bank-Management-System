# 🏦 Bank Management System

A Java-based Bank Management System built using **Java Swing** for GUI and **MySQL** for database management.  
This project simulates core banking operations such as account creation, login authentication, deposits, withdrawals, balance enquiry, and transaction history.

---

## 📌 Features

- 🆕 New Account Registration
- 🔐 Secure Login Authentication
- 💰 Deposit Money
- 💸 Withdraw Money
- 📊 Balance Enquiry
- 🧾 Mini Statement / Transaction History
- 🏧 PIN Generation
- 💳 Fast Cash Option

---

## 🛠️ Technologies Used

- **Java (JDK 17 or above)**
- **Java Swing (GUI)**
- **MySQL Database**
- **JDBC Connectivity**
- **IntelliJ IDEA**

---

## 🗄️ Database Setup

1. Install MySQL Server.
2. Open MySQL Workbench.
3. Create a database:

```sql
CREATE DATABASE bankmanagement;
USE bankmanagement;
Create required tables (example structure):

CREATE TABLE signup (
    formno VARCHAR(20),
    name VARCHAR(50),
    father_name VARCHAR(50),
    dob VARCHAR(20),
    gender VARCHAR(10),
    email VARCHAR(50),
    marital_status VARCHAR(20),
    address VARCHAR(100),
    city VARCHAR(30),
    state VARCHAR(30),
    pincode VARCHAR(10)
);

(Repeat for other tables like login, bank, etc., based on project files.)

▶️ How to Run the Project

Clone the repository:

git clone https://github.com/your-username/Bank-Management-System.git
Open in IntelliJ IDEA.

Configure MySQL connection in Conn.java file:

Connection c = DriverManager.getConnection(
    "jdbc:mysql://localhost:3306/bankmanagement",
    "root",
    "your_password"
);
Run the Login.java or Main Class.

📷 Project Screens

Login Page

Signup Form

Main Transaction Screen

Deposit & Withdraw Interface

🎯 Project Objective

The objective of this project is to understand:

JDBC connectivity

Database operations (CRUD)

GUI development using Swing

Basic banking workflow logic

Real-world application structure

🔒 Future Improvements

Password encryption

Admin dashboard

Online transaction feature

Improved UI design

Error handling enhancements
