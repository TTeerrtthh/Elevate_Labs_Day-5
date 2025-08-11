# SQL Developer Internship – Task 5  
**Performing SQL Joins**

## 📌 Overview
This task focuses on retrieving data from multiple tables using:
- `INNER JOIN`
- `LEFT JOIN`
- `RIGHT JOIN`
- `FULL OUTER JOIN` 
- `Self Join`

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

1️⃣ `INNER JOIN`
Retrieve books with their corresponding authors.

2️⃣ `LEFT JOIN`
Retrieve all books and their authors, showing NULL where no author is linked.

3️⃣ `RIGHT JOIN`
Retrieve all authors and their books, showing NULL where an author has no books.

4️⃣ `FULL OUTER JOIN`
Combine LEFT and RIGHT joins to simulate full join in MySQL.

5️⃣ `SELF JOIN`
Compare data within the same table.

## 📷 Screenshots

1. `INNER JOIN` example

![image_alt](https://github.com/TTeerrtthh/Elevate_Labs_Day-5/blob/e0701e57bba41e1695040c458f6d99cdac2daf70/1.png)

2. `LEFT JOIN` example

![image_alt](https://github.com/TTeerrtthh/Elevate_Labs_Day-5/blob/e0701e57bba41e1695040c458f6d99cdac2daf70/2.png)

3. `RIGHT JOIN` example

![image_alt](https://github.com/TTeerrtthh/Elevate_Labs_Day-5/blob/e0701e57bba41e1695040c458f6d99cdac2daf70/3.png)

4. `FULL OUTER` JOIN example

![image_alt](https://github.com/TTeerrtthh/Elevate_Labs_Day-5/blob/e0701e57bba41e1695040c458f6d99cdac2daf70/4.png)

5. `SELF JOIN` example

![image_alt](https://github.com/TTeerrtthh/Elevate_Labs_Day-5/blob/e0701e57bba41e1695040c458f6d99cdac2daf70/5.png)
