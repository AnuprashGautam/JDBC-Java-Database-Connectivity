# JDBC Notes and Code Files 📝

![Java](https://img.shields.io/badge/Java-8%2B-red)
![JDBC](https://img.shields.io/badge/JDBC-Learning-blue)
![Contributions](https://img.shields.io/badge/Contributions-Welcome-brightgreen)
![Repo Size](https://img.shields.io/github/repo-size/AnuprashGautam/JDBC-Java-Database-Connectivity)
![Last Commit](https://img.shields.io/github/last-commit/AnuprashGautam/JDBC-Java-Database-Connectivity)

A complete and structured repository for learning **Java Database Connectivity (JDBC)** with step-by-step notes, code files, and interview questions.  
Created while following a high-quality YouTube playlist—resources are neatly organized for fast revision and end-to-end preparation.

---

## 📑 Table of Contents


- [Project Structure](#-project-structure)  
- [Learning Resources](#-learning-resources)  
- [JDBC Architecture Diagram](#-jdbc-architecture-diagram)  
- [Contents Covered](#-contents-covered)  
- [Projects Built](#-projects-built)
- [Getting Started](#-getting-started)  
- [Contributing](#-contributing)


---

## 📁 Project Structure

```
JDBC-Java-Database-Connectivity/
│  
├── All Together Code ( Except Major Projects )/
├── Extra
├── Lecture 01/
├── Lecture 02/
├── Lecture 03/
├── Lecture 04/
├── Lecture 05/
├── Lecture 06/
├── Lecture 07/
├── Lecture 08/
├── Lecture 09 Hotel Management System/
├── Lecture 10/
├── Lecture 11/
├── Lecture 12/
├── Lecture 13/
├── Lecture 14 Banking Management System/
├── Lecture 15 Hospital Management System/
│
└── README.md
```

---

## 📚 Learning Resources  

- **YouTube Playlist (Follow along):**  
  ▶️ [JDBC YouTube Playlist](https://youtube.com/playlist?list=PL9q3G4cgja6cgxDbpg3cdvnqM9iWwQtNG)

- **PDF Notes:**  
  📄 [Download Notes](https://drive.google.com/file/d/1mIUf57IYEWXq4QqV03KxElJ7RxIj3k8E/view?usp=sharing)

- **Interview Questions:**  
  ❓ [Interview Questions Folder](https://drive.google.com/file/d/1xbCnTsa6MQQ_1mjeQxxs7EWRf65NfGrh/view?usp=sharing)

---

## 🧩 JDBC Architecture Diagram

```
            +------------------------+
            |      Java App          |
            +-----------+------------+
                        |
                        |  JDBC API
                        v
          +-------------+-------------+
          |     JDBC Driver Manager   |
          +-------------+-------------+
                        |
                        |  Driver Communication
                        v
          +-------------+-------------+
          |   JDBC Driver (MySQL,     |
          |     Oracle, etc.)         |
          +-------------+-------------+
                        |
                        |  SQL Queries / Results
                        v
            +-----------+------------+
            |     Database Server    |
            +------------------------+
```

---

## ✨ Contents Covered

- **Database Connections:** Connecting Java with MySQL/Oracle using `DriverManager`.
- **SQL Execution:**  
  - `Statement`  
  - `PreparedStatement`  
  - `CallableStatement`
- **Transactions:** Managing `commit()`, `rollback()`, and transaction handling.
- **ResultSet Navigation:** Reading and iterating over result sets.
- **Exception Handling:** Best practices for catching and managing SQL exceptions.
- **Interview Folder:** Resources to prepare for JDBC-based interviews.

---

## 🏗️ Projects Built

- 🏨 **Hotel Management System**  
  https://github.com/AnuprashGautam/Hotel-Management-System

- 🏦 **Banking Management System**  
  https://github.com/AnuprashGautam/Banking-Management-System

- 🏥 **Hospital Management System**  
  https://github.com/AnuprashGautam/Hospital-Management-System

---

## 🚀 Getting Started

Clone the repository:

```bash
git clone https://github.com/AnuprashGautam/JDBC-Java-Database-Connectivity
```

Open the project in your favorite IDE and start exploring the code files and notes.

---

## 🤝 Contributing

Contributions are always welcome!  
You can contribute by:

- Improving notes  
- Adding new interview questions  
- Providing sample JDBC programs  
- Fixing bugs or enhancing code  

---

**Happy Learning & Happy Coding! 😃**
