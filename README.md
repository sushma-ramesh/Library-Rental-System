# 📚 Library Rental System (Hibernate + HQL Project)

A real-world Library Rental Management System built using **Java**, **Hibernate ORM**, and **MySQL**, implementing advanced **HQL** queries and entity relationships.

## 🚀 Project Features

- 📘 **Book Management** (Add, Update, Delete, List)
- 👤 **Member Management**
- 🔄 **Book Rentals** (Rent a book, Return a book)
- 🧠 **Hibernate HQL queries**
- 🔗 **Entity Relationships** (`@OneToMany`, `@ManyToOne`)
- 📁 Follows DAO pattern and clean modular codebase

---

## 📦 Folder Structure
LibraryRentalSystem/
# ├── src/
  │ ├── entity/
  │ │ ├── Book.java
  │ │ ├── Member.java
  │ │ └── Rental.java
  │ ├── dao/
  │ │ ├── BookDAO.java
  │ │ ├── MemberDAO.java
  │ │ └── RentalDAO.java
  │ ├── util/
  │ │ └── HibernateUtil.java
  │ ├── main/
  │ │ └── LibraryApp.java
  ├── resources/
  │ └── hibernate.cfg.xml
  └── README.md

---

## ⚙️ Tech Stack

- **Java 17+**
- **Hibernate ORM**
- **HQL (Hibernate Query Language)**
- **MySQL** (or any RDBMS)
- **Maven** (Optional for dependency management)

---

## 🛠 Setup Instructions

### ✅ Prerequisites
- JDK 17+
- MySQL
- Hibernate 5.x
- Any IDE (IntelliJ, Eclipse)

### 🔧 Configuration

1. Update `hibernate.cfg.xml` with your MySQL database credentials:
```xml
<property name="connection.url">jdbc:mysql://localhost:3306/librarydb</property>
<property name="connection.username">root</property>
<property name="connection.password">your_password</property>

2. Create database schema in MySQL:
  CREATE DATABASE librarydb;

3.Compile and Run the LibraryApp main class.




