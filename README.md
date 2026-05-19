# Banking System

A simple Java-based Banking System project developed using **OOP Concepts** and **JDBC**.  
This project allows users to manage banking accounts and store data in a MySQL database.

---

# Project Structure

```text
BankingSystem
└── src
    └── secure bank
        ├── Accounts.java
        ├── AccountsManager.java
        ├── User.java
        └── BankingApp.java
```

---

# Features

- User Registration
- Account Management
- Secure Banking Operations
- MySQL Database Connectivity using JDBC
- Object-Oriented Programming Concepts Implementation

---

# Technologies Used

- Java
- JDBC
- MySQL
- OOP Concepts

---

# OOP Concepts Used

- Class and Object
- Encapsulation
- Abstraction
- Method Calling
- Constructor Usage

---

# Database Details

## Database Name

```sql
banking-system
```

---

# Tables Used

## 1. user Table

Fields:

- fullName
- password
- email

---

## 2. accounts Table

Fields:

- fullName
- accountNumber
- email
- securityPin
- balance

---

# How to Run the Project

## 1️⃣ Clone the Repository

```bash
git clone https://github.com/Riteshkumar12345/Banking-System.git
```

---

## 2️⃣ Open the Project

Open the project in:
- Eclipse
- IntelliJ IDEA
- VS Code

---

## 3️⃣ Create Database in MySQL

```sql
CREATE DATABASE banking-system;
```

---

## 4️⃣ Create user Table

```sql
CREATE TABLE user(
    fullName VARCHAR(255),
    password VARCHAR(255),
    email VARCHAR(255)
);
```

---

## 5️⃣ Create accounts Table

```sql
CREATE TABLE accounts(
    fullName VARCHAR(255),
    accountNumber BIGINT,
    email VARCHAR(255),
    securityPin INT,
    balance DOUBLE
);
```

---

## 6️⃣ Update Database Credentials

Update your MySQL username and password in the Java files.

Example:

```java
String url = "jdbc:mysql://localhost:3306/banking-system";
String username = "root";
String password = "your_password";
```

---

## 7️⃣ Run the Application

Run:

```text
BankingApp.java
```

---

# Project Purpose

This project was built for learning and practicing:

- Java Programming
- JDBC Connectivity
- Database Handling
- OOP Concepts
- Real-world Banking Logic

---

# Author

Ritesh Kumar

GitHub:
https://github.com/Riteshkumar12345
