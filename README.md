# 🎓 Student Management System (Java + JDBC Console App)

A modular, console-based Java application to manage student records using a MySQL database. Designed to demonstrate clean architecture principles with real-world CRUD operations — no frameworks, just solid Java + JDBC.

---

## ✨ What This Project Offers

- A complete backend system to manage student data via terminal.  
- Built using a layered architecture — separates responsibilities across DAO, Service, and Controller.  
- User-friendly prompts for every action.  
- Lightweight & framework-free — perfect for learning core Java and JDBC database interaction.  

---

## 🧠 Why I Built This

This was more than just a CRUD app. I wanted to:
- Solidify my understanding of JDBC and SQL integration
- Practice designing modular, scalable code
- Simulate real-world backend data flow and exception handling

---

## 🔍 Features Overview

- Add a new student with details
- View all registered students
- Search students by ID, name, or course
- Update existing student records
- Delete records by ID
- Robust input validation and error handling

---

---

## 🛠 Tech Stack

| Tech        | Description                    |
|-------------|--------------------------------|
|  Java      | Core logic and architecture     |
|  MySQL     | Relational database             |
|  JDBC      | Java-DB connector               |
|  Console   | Interactive input/output        |

---

## 🏁 Setup Instructions

1. **Clone the repository**
```bash
git clone https://github.com/Om3101/Student_Management_System.git
```

2. **Create the Database & Table**

```sql
CREATE DATABASE studentdb;
USE studentdb;

CREATE TABLE students (
  id INT PRIMARY KEY AUTO_INCREMENT,
  name VARCHAR(100),
  email VARCHAR(100),
  course VARCHAR(100),
  age INT
);
```

---

3. **Update DB Credentials in `DBConnection.java`**

```java
String url = "jdbc:mysql://localhost:3306/studentdb";
String username = "root";
String password = "your_password";
```

---

4. **Run the Application**

- Open the project in **Eclipse**, **IntelliJ**, or any IDE of your choice.
- Compile and run `Main.java`.

---

## 🤖 CLI Flow – Example Commands

```bash
--- Welcome to Student Management System ---
1. Add Student
2. View All Students
3. Search by ID/Name/Course
4. Update Student
5. Delete Student
6. Exit
```

---

## 📌 My Learnings

-  JDBC configuration and SQL query execution from Java  
-  Separating concerns using layered architecture  
-  Handling user input and edge cases cleanly  
-  Writing maintainable, scalable Java console apps  


---

