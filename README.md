LMS Database & Management System (C++)
Overview
The LMS Database & Management System is a console-based application developed in C++ to manage student attendance using a simple and efficient file-based storage system. The project demonstrates how core programming concepts can be applied to build a basic Learning Management System without relying on external databases or frameworks.

The system implements role-based access, allowing teachers and students to interact with the application through separate interfaces. Teachers can record attendance, while students can view their attendance records based on stored data.

Features
User Login System

Users log in using a username.

The system identifies the user role (Teacher or Student).

Access is granted based on predefined credentials.

Teacher Interface

Teachers can record attendance for students.

Required inputs include:

Date

Day

Class time

Attendance data is saved in text files named according to the day.

Each file acts as a simple database for storing attendance records.

Student Interface

Students log in using their name and roll number.

Students can select a specific day to view attendance.

Attendance records are retrieved from stored files.

Technologies Used

Language: C++

Libraries:

<iostream>

<fstream>

<windows.h>

Concepts:

File handling

Arrays

Conditional logic

Functions

Console-based UI

File Structure
src/
 └── LMS_SYSTEM.cpp
data/
 └── DataBase.txt
README.md

How to Run

Open the project in any C++ compiler (Dev C++, Code::Blocks, or g++).

Compile the LMS_SYSTEM.cpp file.

Run the executable.

Enter a valid username to access the teacher or student interface.

Follow on-screen instructions to record or view attendance.

Project Purpose

This project was developed as an academic project to demonstrate file-based data management and role-based system design using C++.

Limitations

Uses file-based storage instead of a database

Console-based interface

Hardcoded user credentials

Future Improvements

Database integration (MySQL / SQLite)

Improved authentication system

Graphical user interface (GUI)

Code refactoring for better scalability

Author

Developed as part of an academic C++ project.
