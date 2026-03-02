# 🎓 Student Record Management System (C++)

A console-based Student Record Management System developed in C++ using file handling and STL concepts.

This project allows an **Admin** to manage student records and allows **Students** to securely view their profile and attendance.

---

## 🚀 Features

### 👨‍💼 Admin Functionalities
- Add new students
- View all students in a formatted table
- Update student information
- Delete students (including attendance records)
- Mark attendance (Present / Absent)
- View attendance report
- Automatic duplicate attendance cleanup

### 👨‍🎓 Student Functionalities
- Secure login using username & password
- View personal profile
- View attendance records
- No permission to modify data (read-only access)

---

## 🛠 Technologies Used

- C++
- Object-Oriented Programming (OOP)
- File Handling (ifstream, ofstream)
- STL Containers:
  - `vector`
  - `map`
- String Stream (`stringstream`)
- Data formatting (`iomanip`)

---

## 📂 File Structure

```
students.txt     → Stores student records  
attendance.txt   → Stores attendance data  
admin.txt        → Stores admin credentials  
main.cpp         → Main source code  
```

---

## 🏗 System Architecture

The system has two main user roles:

### 1️⃣ Admin
- Authenticated via `admin.txt`
- Full control over student data

### 2️⃣ Student
- Authenticated using stored credentials
- Can only view personal information

Internally, the system:
- Uses file handling for persistent storage
- Uses `map` to prevent duplicate attendance
- Uses `vector` for dynamic student storage

---

## 🔐 Default Admin Login

If `admin.txt` does not exist, the system creates:

```
Username: admin
Password: admin123
```

---

## 📌 Sample Student Record Format

```
ID,Name,Age,Course,GPA,Username,Password,Contact
```

Example:

```
101,John Doe,20,IT,3.50,john123,pass123,9876543210
```

---

## 🎯 Learning Objectives

This project demonstrates:

- Object-Oriented Programming
- File Handling
- Data Persistence
- Input Validation
- Error Handling
- Use of STL containers
- Console UI formatting

---

## 💡 Future Improvements

- Password encryption
- GUI version
- Database integration (MySQL)
- Search & filter functionality
- Role-based access control

---

## 👨‍💻 Developed By

**Cyuzuzo Heritier**  
B.Sc IT (2025–26)

---

## ⭐ If you like this project

Feel free to fork, improve, and give it a star ⭐
