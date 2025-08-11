# SQL Developer Internship – Task 5  
**Performing SQL Joins**

## 📌 Overview
This task focuses on retrieving data from multiple tables using:
- INNER JOIN
- LEFT JOIN
- RIGHT JOIN
- FULL OUTER JOIN (emulated in MySQL)
- Self Join

## 🛠 Tools Used
- MySQL Workbench
- MySQL Server

## 📂 Database Schema:
- `Authors`
- `Books`
- `Members`

**Relationships:**
- Each Book has an `author_id` referencing Authors.
- Members table is independent for this task.

## 📜 SQL Commands Used

1️⃣ INNER JOIN
Retrieve books with their corresponding authors.


2️⃣ LEFT JOIN
Retrieve all books and their authors, showing NULL where no author is linked.


3️⃣ RIGHT JOIN
Retrieve all authors and their books, showing NULL where an author has no books.


4️⃣ FULL OUTER JOIN (Emulated)
Combine LEFT and RIGHT joins to simulate full join in MySQL.


5️⃣ SELF JOIN
Compare data within the same table.


## 📷 Screenshots

1. INNER JOIN example


2. LEFT JOIN example


3. RIGHT JOIN example


4. FULL OUTER JOIN example


5. SELF JOIN example
