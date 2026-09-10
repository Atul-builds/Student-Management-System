# 🎓 Student Management System

A simple **Student Management System** built using Python.

This project allows users to add, view, search, update, and delete student records. It also calculates the average marks of all students.

## 🚀 Features

* ➕ Add Student
* 👀 View All Students
* 🔎 Search Student by Name
* ✏️ Update Student Details
* 🗑️ Delete Student by Roll Number
* 📊 Calculate Average Marks
* 🚪 Exit Program
* ❌ Handles invalid choices

## 🛠️ Technologies Used

* Python
* Lists
* Dictionaries
* `while` loop
* `for` loop
* `if-elif-else`
* `input()`
* `append()`
* `remove()`
* `enumerate()`
* Basic calculations

## 📋 Student Information

The program stores the following information:

```text
Name
Class
Roll Number
Age
Course
Marks
```

Example:

```text
Name        : Atul
Class       : 12
Roll Number : 101
Age         : 18
Course      : BCA
Marks       : 85
```

## 🎮 Main Menu

When the program starts, it displays:

```text
================================
     STUDENT MANAGEMENT SYSTEM
================================

1. Add Student
2. View Students
3. Search Student
4. Update Student
5. Delete Student
6. Calculate Average Marks
7. Exit
```

## ➕ Add Student

The user can add a new student by entering their details.

Example:

```text
Enter Student Name: Atul
Enter Student Class: 12
Enter Student Roll Number: 101
Enter Student Age: 18
Enter Student Course: BCA
Enter Student Marks: 85
```

The student information is stored in a dictionary and added to the students list.

## 👀 View Students

Displays all students currently stored in the system.

Example:

```text
1. Name: Atul | Class: 12 | Roll: 101 | Age: 18 | Course: BCA | Marks: 85
2. Name: Amit  | Class: 12 | Roll: 102 | Age: 18 | Course: BCA | Marks: 78
```

## 🔎 Search Student

The user can search for a student by entering their name.

Example:

```text
Enter Student Name to search: Rahul
```

The program checks the students list and displays the matching student.

## ✏️ Update Student

The user can update an existing student's information using their **Roll Number**.

Example:

```text
Enter Roll Number to update: 101

Enter New Name: Atul Kumar
Enter New Class: 12
Enter New Age: 19
Enter New Course: BCA
Enter New Marks: 90
```

The old information is replaced with the new information.

## 🗑️ Delete Student

The user can delete a student using their Roll Number.

Example:

```text
Enter Roll Number to delete: 102

Student deleted successfully!
```

## 📊 Calculate Average Marks

The program calculates the average marks of all students.

Example:

```text
Student 1 → 85
Student 2 → 75
Student 3 → 90

Average Marks: 83.33
```

## 🧠 What I Learned

While building this project, I practiced:

* Working with lists
* Working with dictionaries
* Taking user input
* Using loops
* Using conditional statements
* Searching records
* Updating dictionary values
* Deleting records
* Calculating averages
* Building a menu-driven application

## 🔮 Future Improvements

I plan to improve this project by adding:

* 💾 Permanent data storage using JSON
* 📅 Student admission date
* 📈 Grade calculation
* 🏆 Top-performing student
* 📊 Subject-wise marks
* 🔐 Login system
* 🖥️ GUI using Tkinter
* 🗄️ Database integration using SQLite

## ▶️ How to Run

Make sure Python is installed on your computer.

Run the program using:

```bash
python student_management.py
```

## 👨‍💻 Author

**Python Practice Project**

Built while learning Python and improving programming logic.
