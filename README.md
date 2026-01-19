# 🗄️ 2.1_MongoDB_Queries

[![MySQL](https://img.shields.io/badge/mysql-%2300f.svg?style=for-the-badge&logo=mysql&logoColor=white)](https://www.mysql.com/)

Data alone explains nothing. With SQL, you learn to ask the questions that reveal what truly matters. This project focuses on the art of formulating precise queries to extract meaningful insights, an essential skill for backend development and data analysis.

---

## 📂 Project Structure

This repository contains two main database schemas designed to practice everything from basic selection to advanced multi-table operations:

### 🚀 Shop Database (Tienda)
Focuses on the relationship between products and manufacturers.
* **Tables:** `producto` and `fabricante`.
* **Relationship:** 1:N (One manufacturer can have many products).
* **Key Learning:** Data filtering, ordering, string manipulation, and basic joins.
* **Queries Included:** 41 tasks covering price calculations, rounding, limit/offset, and nested subqueries.

### 🚀 University Database (Universidad)
A complex relational system involving students, professors, departments, grades, and enrollments.
* **Core Logic:** Managing academic data and course logistics.
* **Key Learning:** Advanced `LEFT JOIN` and `RIGHT JOIN`, aggregate functions (`COUNT`, `SUM`), and complex grouping.
* **Queries Included:** 26 tasks covering student demographics, faculty management, and statistical summaries of academic credits.

---

## 🛠️ Technologies & Tools
* **Database Management:** MySQL.
* **Design & Query IDEs:**
    * [IntelliJ DataGrip](https://www.jetbrains.com/datagrip/)
    * [MySQL Workbench](https://www.mysql.com/products/workbench/)
* **Version Control:** Git.

---

## 📊 Entity-Relationship Insights

The exercises are designed to challenge logical thinking through:
1.  **Normalization:** Understanding how departments link to professors and how grades organize subjects.
2.  **Join Strategy:** Identifying when to use `INNER JOIN` vs. `OUTER JOINS` to find missing data.
3.  **Optimization:** Identifying the most efficient way to structure a query for clarity and performance.

---

## 📥 Installation & Usage

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/FedEx8525/2.1-MySQL_Database.git](https://github.com/FedEx8525/2.1-MySQL_Database.git)
    ```

2.  **Import the Databases:**
    * Locate `schema_tienda.sql` and `schema_universidad.sql`.
    * Open your SQL editor (DataGrip or Workbench) and execute the scripts.

3.  **Execute Queries:**
    * Queries are numbered. It is recommended to run them sequentially and reflect on the output.

---

## 📋 Task Highlights (Sample Queries)

### Shop Database
* **Price Conversion:** Calculations using exchange rates (EUR to USD) and rounding.
* **Manufacturer Analytics:** Identifying manufacturers with and without associated products.
* **Top Results:** Finding the cheapest/most expensive items using `ORDER BY` and `LIMIT`.

### University Database
* **Student Filtering:** Retrieving students by birth year or missing contact info.
* **Department Statistics:** Counting faculty members per department, including those with zero staff.
* **Academic Load:** Calculating the total credits per degree type.

---

## 🤝 Contributions
This is an educational project aimed at mastering SQL. Suggestions for query optimization or alternative modeling are highly appreciated.

---
*Developed by **Federico Cantore***
