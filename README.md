# 3-Tier Node.js MySQL User Management App

This is a 3-tier web application for managing users built using Node.js, Express, and MySQL. The application allows users to be added, viewed, updated, and deleted through a web interface.

This project was developed as part of a DevOps Bootcamp and demonstrates a complete three-tier architecture consisting of a frontend, backend, and database.

---

## 3-Tier Architecture

Presentation Layer:
- HTML
- CSS
- JavaScript

Application Layer:
- Node.js
- Express.js

Data Layer:
- MySQL

---

## Features

- Add new users
- View all users
- Edit user details
- Delete users
- Responsive user interface
- MySQL database integration

---

## Prerequisites

Make sure you have the following installed:

- Node.js
- MySQL
- Git

Check versions:

```bash
node -v
npm -v
mysql --version
```

---

## Database Setup

Login to MySQL:

```bash
mysql -u root -p
```

Create database:

```sql
CREATE DATABASE test_db;
USE test_db;
```

Create users table:

```sql
CREATE TABLE users (
    id INT AUTO_INCREMENT PRIMARY KEY,
    name VARCHAR(255) NOT NULL,
    email VARCHAR(255) NOT NULL UNIQUE,
    role ENUM('Admin', 'User') NOT NULL
);
```

---

## Setup Instructions

Clone the repository:

```bash
git clone https://github.com/your-username/nodejs-mysql-user-management-app.git
cd nodejs-mysql-user-management-app
```

---

## Setup Client

```bash
cd client
npm install
npm run build
```

---

## Setup Server

```bash
cd server
npm install
npm start
```

---

## Access Application

Open in browser:

http://localhost:5000

---

## Technologies Used

- Node.js
- Express.js
- MySQL
- HTML
- CSS
- JavaScript

---

## Author

Hanzala Israr  
BS Computer Science – 4th Semester  
DevOps Bootcamp Student
