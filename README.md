# C--Projects-LMSMANAGEMENTSYTEM
LMS Database &amp; Management System (C++)  A console-based C++ app that manages attendance using simple file storage. It uses role-based login by username to present teacher or student interfaces. Teachers record attendance (date, time, day) in day-named files; students view their records. Demonstrates file I/O and basic programming fundamentals.
LMS Database & Management System (C++)
Overview
The LMS Database & Management System is a console-based C++ application designed to manage student attendance using a file-based storage system. The project demonstrates how core C++ programming concepts can be used to build a simple Learning Management System without relying on external databases or frameworks.
The system supports role-based access, providing separate interfaces for teachers and students. Teachers can record attendance, while students can view their attendance records based on stored data.
Features
1. User Login System
Users log in by entering a username.
The system identifies whether the user is a teacher or a student.
Based on the role, the corresponding interface is displayed.
2. Teacher Interface
Teachers can record attendance for students.
Required inputs:
Date
Day
Class time
Attendance status is taken for each student.
Attendance data is saved in a text file named after the day, which acts as a simple database.
Each record includes student name, roll number, date, day, time, and attendance status.
3. Student Interface
Students log in using their first name, last name, and roll number.
Students can select a specific day to view attendance.
The system reads data from the saved files and displays the student’s attendance record.
Technologies Used
Language: C++
Libraries:
<iostream> for input/output
<fstream> for file handling
<windows.h> for console text coloring
Concepts:
File handling
Arrays
Conditional statements
Functions
Console-based UI
Role-based logic
File Handling Logic
Attendance records are stored in .txt files.
Each file is named according to the day entered by the teacher.
Files act as a lightweight database for storing and retrieving attendance data.
How to Run
Compile the program using a C++ compiler (e.g., Dev C++, Code::Blocks, or g++).
Run the executable file.
Enter a valid username:
Teacher usernames grant access to the teacher interface.
Other users are redirected to the student interface.
Follow on-screen instructions to record or view attendance.
Project Purpose
This project was developed as an academic project to practice:
File-based data management in C++
Implementation of role-based systems
Structured and modular programming
Limitations
Uses file-based storage instead of a database
Console-based interface
User authentication is basic and hardcoded
Future Improvements
Database integration (MySQL / SQLite)
Improved authentication system
Graphical user interface (GUI)
Dynamic student data handling
Author
Developed as part of an academic C++ project.
Brutally honest feedback (important)
Logic works, but code is very repetitive (long if-else chain).
Next improvement should be:
using structures/classes
using loops instead of hardcoded checks
separating logic into multiple files

Despite that, for an academic-level C++ project, this is valid, functional, and presentable.
