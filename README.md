# Database Management Systems Projects

This repository contains a collection of database management system (DBMS) projects, showcasing the creation and manipulation of databases for various real-world scenarios. Each project uses **MySQL** as the database management system and demonstrates essential operations like table creation, data insertion, table alteration, and queries.

## 📂 Projects Included
1. **Employee Management System**
2. **Hospital Management System**
3. **Library Management System**
4. **Online Learning Platform**
5. **Retail Store Management**
6. **Student Management System**

## 🛠️ Features Implemented
- **Database Design**:
  - Creating databases and tables for each management system.
  - Structuring tables with appropriate attributes and data types.

- **Data Manipulation**:
  - Inserting data into tables.
  - Performing queries to retrieve and manipulate data.

- **Data Relationships**:
  - Altering tables to add **foreign keys** to establish relationships between tables.

- **Queries**:
  - Practical examples of SELECT, JOIN, WHERE, GROUP BY, and other SQL operations.

## 📋 Table of Contents
1. [Project Structure](#project-structure)
2. [Technologies Used](#technologies-used)
3. [Setup Instructions](#setup-instructions)
4. [Examples of SQL Queries](#examples-of-sql-queries)

## 📁 Project Structure

. ├── Employee_Management │ ├── create_tables.sql │ ├── insert_values.sql │ ├── queries.sql │ └── ERD.png ├── Hospital_Management │ ├── create_tables.sql │ ├── insert_values.sql │ ├── queries.sql │ └── ERD.png ├── Library_Management │ └── ... ├── Online_Learning │ └── ... ├── Retail_Store │ └── ... ├── Student_Management │ └── ... └── README.md

## 💻 Technologies Used
- **MySQL**: For creating and managing databases and tables.
- **SQL**: For running queries to manipulate and retrieve data.

## ⚙️ Setup Instructions
1. Clone the repository:
   ```bash
   git clone https://github.com/PavithraBharathiR/-SQL-Case-Study.git
   
2. Navigate to the desired project folder.
3. Run the create_tables.sql file in your MySQL environment to set up the tables.
4. Execute the insert_values.sql file to populate the tables with sample data.
5. Run the queries from the queries.sql file to test and explore the database.

🧑‍💻 Examples of SQL Queries
Here are a few examples of the queries included in the projects:

Retrieve employees with a salary greater than $50,000:
SELECT * FROM employees WHERE salary > 50000;

List all patients admitted to a specific department:
SELECT * FROM patients WHERE department_id = 3;

Count the number of books borrowed by each student:
SELECT student_id, COUNT(*) AS borrowed_books FROM borrow_records GROUP BY student_id;

🛡️ License
This repository is licensed under the MIT License. Feel free to use and modify the code.
