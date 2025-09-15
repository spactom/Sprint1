# 📚 Library Management System

A Library Management System built using **Java**, **Hibernate**, and **MySQL** to manage books, users, and administrative operations.  
This project demonstrates CRUD operations, Hibernate mappings, and database interaction in a real-world scenario.

## 🚀 Features

- Add, update, delete, and view books.
- Manage users (students/admin).
- Issue and return books.
- Track due dates and penalties.
- Secure login for admin and users.
- Hibernate ORM for database handling.
-MySQL backend for data persistence.

## 🛠️ Tech Stack

- Programming Language: Java
- Framework: Hibernate
- Database: MySQL
- Build Tool: Maven/Gradle (if used)
- IDE: Eclipse / IntelliJ IDEA

## 📂 Project Structure
```
LibraryManagementSystem/
│── src/main/java/
│   ├── entity/          # Hibernate entity classes
│   ├── dao/             # Data Access Objects
│   ├── service/         # Business logic
│   ├── ui/              # User interface (console/GUI)
│
│── src/main/resources/
│   ├── hibernate.cfg.xml
│   ├── application.properties
│
│── pom.xml (if Maven used)
│── README.md
```

## ⚙️ Installation & Setup

1. Clone the repository:
   git clone https://github.com/yourusername/library-management-system.git
2. Import project into your IDE (Eclipse/IntelliJ).
3. Configure MySQL Database:
   CREATE DATABASE librarymanagement;
4. Update database username & password in hibernate.cfg.xml.
5. Run the project.

## 📖 Usage

- Admin Login: Manage books, users, and reports.
- User Login: View and borrow books.
- Perform CRUD operations from the console/GUI.

## 🗃️ Database Schema

Example tables:
- admin (adminId, contactNo, emailfirstName, lastName, password, usernamename, role)
- user (userId, email, name, password, username, admin_id)
- branch (branchId, contactNo, location, name, admin_id)
- book (bookId, availabilityStatus, language, quantity, typeadmin_id)
- book_transaction (transactionId, dueDate, timeStamp, transactionType, user_id, book_id)

## 🤝 Contribution

Pull requests are welcome. For major changes, open an issue first to discuss what you’d like to change.




