# Database Schema Demonstration using MySQL & Python

This repository demonstrates the **core components of a relational database schema** using **MySQL** integrated with **Python** in **Google Colab**.
The project creates a database, defines a structured table with constraints, inserts **1000 Indian records**, displays the MySQL table, and **exports 100 records to CSV**.

---

## ✨ Features

* MySQL setup inside Google Colab
* Database and table creation
* Demonstration of schema components:

  * Tables
  * Fields (columns)
  * Primary keys
  * Constraints
  * Data types
* Automatic generation of **1000 Indian names**
* Display of MySQL table data
* **CSV export of 100 records**

---

## 🛠 Tech Stack

* **Python 3**
* **MySQL 8.0**
* **mysql-connector-python**
* **Pandas**
* **Google Colab**

---

## 🗄 Database Schema

### Database

```
schema_demo
```

### Table: `student`

| Column     | Type         | Description         |
| ---------- | ------------ | ------------------- |
| student_id | INT          | Primary key         |
| name       | VARCHAR(100) | Student full name   |
| gender     | VARCHAR(10)  | Male / Female       |
| dob        | DATE         | Date of birth       |
| phone      | VARCHAR(15)  | Unique phone number |
| city       | VARCHAR(50)  | Indian city         |

---

## 🔑 Schema Components Covered

* **Tables**: `student`
* **Fields**: name, gender, dob, phone, city
* **Primary Key**: `student_id`
* **Constraints**:

  * `NOT NULL`
  * `UNIQUE`
* **Data Types**: `INT`, `VARCHAR`, `DATE`
* **Indexes**: Implicit via primary and unique keys

---

## 📊 Data Generation

* **1000 synthetic records** generated programmatically
* Indian context:

  * First names
  * Surnames
  * Cities
* Randomized gender, DOB, and phone numbers

---

## ▶️ How to Run

1. Open **Google Colab**
2. Upload or paste the notebook code
3. Run cells sequentially
4. MySQL installs and starts automatically
5. Database and table are created
6. 1000 records are inserted
7. MySQL table and structure are displayed
8. **100 records are exported as CSV**

---

## 📤 Output

* `SHOW TABLES` output
* `DESC student` table structure
* Printed student records from MySQL
* CSV file:

  ```
  student_100_records.csv
  ```

---

## 📁 Repository Structure

```
.
├── database_schema_demo.ipynb
├── student_100_records.csv
└── README.md
```

---

## 🚀 Use Cases

* Learning database schema design
* SQL query practice
* Academic mini-projects
* Backend data modeling
* Data extraction and CSV export

---

## 👤 Author

**Leora Saharia**

---
