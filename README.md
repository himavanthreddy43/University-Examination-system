# 📚 University Examination System & Online Book Store Database Projects

## 👨‍🎓 Project 1: University Examination System

This project models a **University Examination System** using SQL with clearly structured tables and relationships to manage data related to:

- Departments
- Faculty members
- Courses and coordination
- Student enrollment and attendance
- Exams and attempts

### 📌 Features

- Departments headed by faculty
- Faculty can teach, coordinate, and head departments
- Courses belong to departments and are coordinated by faculty
- Students belong to departments and enroll in multiple courses
- Exam information including internal/external types
- Student exam attempts with marks and attempt tracking

### 🛠️ ER Diagram Entities

- **Department**
- **Faculty**
- **Course**
- **FacultyCourse (Teaching mapping)**
- **Student**
- **StudentCourse (Enrollment + Attendance)**
- **Exam**
- **ExamAttempt**

### 🧾 SQL Tables & Sample Data

Includes:
- SQL `CREATE TABLE` statements for all entities
- `INSERT` statements for each table with real-world sample data

---

## 📘 Project 2: Online Book Store

This project is an **Online Book Publishing & Sales Platform** database schema using SQL. It captures complete information related to:

- Books, editions, genres, and authors
- Customers, orders, and wishlists
- Shipping addresses and payment info

### 📌 Features

- Books can have multiple editions, authors, and genres
- Editions include publisher info, pricing, and ISBN
- Customers have multiple addresses and wishlists
- Orders with item-level discounts and quantity
- Full support for many-to-many relationships (e.g., books-authors, books-genres)

### 🛠️ ER Diagram Entities

- **Author**
- **Publisher**
- **Genre**
- **Book**
- **BookEdition**
- **BookAuthor**
- **BookGenre**
- **Customer**
- **ShippingAddress**
- **Wishlist**
- **Orders**
- **OrderItems**



![image](https://github.com/user-attachments/assets/faddf6e8-8eba-48cd-8d9d-1deda8e7c927)



