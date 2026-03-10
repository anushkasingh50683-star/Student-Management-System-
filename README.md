# Student-Management-System
A simple command-line Student Management System built with Python and SQLite.
This project allows users to add, view, update, and delete student records from a local database.

It demonstrates basic concepts such as:

Python modular programming

SQLite database operations

Input validation

CRUD operations

🚀 Features

➕ Add student records

📄 View all student records

✏️ Update student name or marks

❌ Delete student data

🗄️ Persistent storage using SQLite database

🛡️ Input validation for name and marks

🛠️ Tech Stack

Python

SQLite3

Command Line Interface (CLI)

📂 Project Structure
student-dashboard/
│
├── main.py          # CLI interface and program entry point
├── service.py       # Business logic and validation
├── database.py      # Database operations (CRUD)
├── students.db      # SQLite database file
└── README.md

main.py handles the user menu and input loop. 

main

service.py manages validation and business logic before interacting with the database. 

service

database.py performs direct SQLite operations like create, insert, update, delete, and fetch. 

database
