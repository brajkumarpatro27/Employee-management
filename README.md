# Employee Management System (Java + MySQL)

A console-based Employee Management System built using Java and MySQL. This application allows users to add, view, update, and delete employee records stored in a MySQL database.

## Features

- Add new employees with ID, name, department, and salary
- View all employee records
- Update existing employee details
- Remove employees by ID
- MySQL database integration using JDBC
- Clean and modular code structure

## Technologies Used

- Java (JDK 17 or later recommended)
- MySQL
- JDBC (Java Database Connectivity)
- MySQL Connector/J (JDBC Driver)

## Prerequisites

- Java installed on your system
- MySQL server running locally or remotely
- MySQL Connector/J `.jar` file downloaded

## Database Setup

1. Log in to your MySQL terminal:

```sql
CREATE DATABASE employee_db;
USE employee_db;

CREATE TABLE employees (
    id INT PRIMARY KEY,
    name VARCHAR(100),
    department VARCHAR(100),
    salary DOUBLE
);