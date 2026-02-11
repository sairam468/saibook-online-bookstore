# 📚 SAIBOOK - Online Bookstore Application

## 📌 Overview

SAIBOOK is a Java web application developed using core Java web technologies including JDBC, Servlets, JSP, and EL/JSTL.

The application simulates an online bookstore system with user and admin modules, cart management, and order processing functionality.

This project demonstrates strong foundational knowledge of Java web development before Spring Boot.

---

## 🛠 Tech Stack

- Java
- JDBC
- Servlets
- JSP
- EL (Expression Language)
- JSTL
- Oracle 
- Apache Tomcat

---

## 👥 Modules

### 👨‍💼 Admin Module

- Admin Login
- Add New Books
- Update Book Details
- Delete Books
- View All Books
- Manage Inventory

---

### 👤 User Module

- User Registration
- User Login
- View Available Books
- Add to Cart
- Remove from Cart
- View Cart
- Purchase Books
- Logout

---

## 🏗 Architecture

The application follows MVC pattern using Servlets:

JSP (View) → Servlet (Controller) → DAO (Model) → Database

### Design Patterns Used:

- DAO Pattern
- MVC Architecture
- Session Management

---

## 🗄 Database Design

- Structured relational schema
- Book entity management
- User authentication tables
- Cart and order tracking
- Optimized JDBC query handling

---

## 🔐 Session Management

- HTTP Session used for:
  - User authentication tracking
  - Cart item storage
- Prevented unauthorized access to protected pages

---

## ⚡ Key Features

- Layered DAO architecture
- Reusable database connection utility
- CRUD operations using JDBC
- Dynamic data rendering using JSP & EL
- Server-side request handling via Servlets

---

## 🚀 How to Run

1. Configure database credentials in `DBConnection.java`
2. Deploy project on Apache Tomcat
3. Access application via:
   http://localhost:8080/SAIBOOK_App

---

## 🎯 Key Learning Outcomes

- Built complete web application without Spring framework
- Implemented MVC using Servlets and JSP
- Applied DAO pattern for database abstraction
- Managed sessions for authentication and cart handling
- Strengthened JDBC and SQL integration skills

---

## 👨‍💻 Author

**Ganta Lakshman Naga Durga Sairam**  
Java Full Stack Developer  
Hyderabad, India
