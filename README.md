# Java JDBC – Employee Database App

## 📌 Objective
Connect to a MySQL/PostgreSQL database and perform CRUD (Create, Read, Update, Delete) operations using Java JDBC.

## 🛠 Tools & Technologies
- **Java** (JDK 8+ recommended)  
- **MySQL** or **PostgreSQL**  
- **JDBC Driver** (Connector/J for MySQL or PostgreSQL JDBC driver)  
- **VS Code** (or any Java IDE)  

## 📦 Deliverables
A Java DB application with connection code that supports:
- Adding employees
- Viewing employee records
- Updating employee details
- Deleting employee records

## 🚀 Setup Guide

1. **Set up the Database**
   ```sql
   CREATE DATABASE employee_db;

   USE employee_db;

   CREATE TABLE employees (
       id INT PRIMARY KEY AUTO_INCREMENT,
       name VARCHAR(100) NOT NULL,
       department VARCHAR(50),
       salary DOUBLE
   );
