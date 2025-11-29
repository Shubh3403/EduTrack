# EduTrack
Student Course Management SQL Project
EduTrack is a beginner-friendly SQL project designed to help users understand database creation, normalization, relationships, and CRUD operations.
It is fully based on MySQL / XAMPP and includes tables, sample data, ER Diagram, and 20+ SQL queries.

🚀 Features
👨‍🎓 Student Management
Add, update, delete students
Search students by name

📚 Course Management
Add, update, delete courses
Categorize courses

📝 Enrollment & Results
Enroll students into courses
Record marks & grades
Generate reports

🔎 Search & Filtering
Courses by category
Courses taken by a specific student

🗂️ Database Schema
Table	      Description
students	  Stores student information
courses	    Stores course details
enrollments	Many-to-many mapping between students & courses
results	    Stores marks & grades

🛠️ Tech Stack

MySQL / XAMPP (phpMyAdmin)
SQL (DDL + DML + Joins + Group By)
Optional: Python / PHP / Flask for interface

🗄️ SQL File Included
Database creation
Insert sample data
20+ SQL queries (Joins, Aggregate, Search, Reports)
ER Diagram

🖼️ ER Diagram
STUDENTS ----< ENROLLMENTS ----< RESULTS
              |
              >---- COURSES


🧩 How to Run the Project
Install XAMPP
Start Apache + MySQL
Open phpMyAdmin
Create database:

CREATE DATABASE edutrack;

Import the file edutrack.sql
Run queries and explore the database

🏷️ Skills Used
SQL
MySQL
Database Design
ER Modeling
Joins & Relationships
CRUD Operations
Data Management
