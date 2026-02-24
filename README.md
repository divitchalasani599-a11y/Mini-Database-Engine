# 🗄 Mini Database Engine (File-Based Database System)

A lightweight file-based Mini Database Engine built using Python that supports basic database operations such as CREATE, INSERT, SELECT, and DELETE.

---

## 📌 Project Overview

The Mini Database Engine is a simplified implementation of a database management system built from scratch using Python.

It simulates core database functionalities like table creation, data insertion, querying, and deletion without using any external database software.

This project demonstrates understanding of data storage, query parsing, and basic DBMS concepts.

---

## 🎯 Objective

- To understand internal working of a database system.
- To implement basic SQL-like operations.
- To manage structured data using file handling.
- To simulate database storage and retrieval mechanisms.

---

## ✨ Features

- 🏗 Create tables  
- ➕ Insert records  
- 🔍 Select records  
- ❌ Delete records  
- 💾 File-based persistent storage  
- 📄 Simple query parser implementation  

---

## 🛠 Technologies Used

- Python  
- File Handling  
- JSON / Text-based Storage  
- Object-Oriented Programming  

---

## ⚙ Installation

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/your-username/mini-database-engine.git
cd mini-database-engine
```

---

### 2️⃣ No External Dependencies Required

This project runs using standard Python libraries.

Make sure Python 3.x is installed:

```bash
python --version
```

---

## ▶ Usage

### 1️⃣ Run the Application

```bash
python database.py
```

---

### 2️⃣ Example Commands

```
CREATE TABLE students (id, name, age)
INSERT INTO students VALUES (1, Divit, 21)
SELECT * FROM students
DELETE FROM students WHERE id = 1
```

---

## 📂 Project Structure

```
mini-database-engine/
│
├── database.py
├── parser.py
├── storage/
│   └── data.txt
├── requirements.txt
└── README.md
```

---

## 🔄 How It Works

1. User enters a SQL-like command.
2. The parser interprets the query.
3. The engine processes the operation.
4. Data is stored or retrieved from local files.
5. Output is displayed in structured format.

---

## 🧠 Concepts Implemented

- Basic DBMS architecture  
- Query parsing  
- File-based data storage  
- CRUD operations  
- Data serialization  

---

## 🚀 Future Enhancements

- WHERE clause support with multiple conditions  
- UPDATE operation implementation  
- Indexing mechanism  
- Transaction support  
- GUI-based interface  
- B-Tree indexing structure  

---

## 👨‍💻 Developer

Divit Chalasani  

---

## 📄 License

This project is developed for academic and core database learning purposes.

---
