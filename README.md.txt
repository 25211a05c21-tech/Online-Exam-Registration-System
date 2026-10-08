# Online Exam Registration System

## 📌 Project Overview

The Online Exam Registration System is a web-based application that allows students to register for semester examinations online.

The system provides separate interfaces for students and administrators. Students can create an account, log in, view their profile, check examination details, select subjects, and register for examinations. Administrators can view registered students, registrations, and revenue information.

## ✨ Features

### Student Features
- Student registration
- Student login
- Student dashboard
- View student profile
- View examination details
- Select examination subjects
- Automatic examination fee calculation
- View examination registration
- Student logout

### Admin Features
- Admin login
- Admin dashboard
- View total students
- View total registrations
- View total revenue
- View registered students
- View examination registrations
- Admin logout

## 📚 Examination Subjects

The system currently contains the following subjects:

- Java Programming
- Database Management System
- Computer Networks
- Operating Systems
- Software Engineering

**Examination Date:** 15-12-2026

**Fee:** ₹500 per subject

## 🛠️ Technologies Used

- HTML5
- CSS3
- JavaScript
- Browser Local Storage
- Browser Session Storage

## 📂 Project Structure

```text
Online-Exam-Registration-System/
│
├── index.html
└── README.md
```

## ▶️ How to Run

1. Download or clone this repository.
2. Open the project folder.
3. Open `index.html` in a web browser.
4. Register as a student or use the admin section.

No server or database is required because this project uses browser storage for demonstration purposes.

## 🔐 Admin Login

For demonstration purposes, the project contains a predefined admin account.

**Username:** `admin`

**Password:** `admin123`

> This authentication is intended only for an academic/demo project and is not suitable for a production application.

## 🔄 Application Flow

```text
Student
   ↓
Registration
   ↓
Login
   ↓
Dashboard
   ↓
Examination Details
   ↓
Select Subjects
   ↓
Calculate Fee
   ↓
Confirm Registration
   ↓
View Registration
```

## 💾 Data Storage

The application uses:

- `localStorage` for storing student and registration data.
- `sessionStorage` for maintaining the currently logged-in student session.

## 🎯 Project Purpose

The main purpose of this project is to demonstrate a simple online examination registration system using frontend web technologies.

It can be further improved by connecting it to a backend server and database for real-world use.

## ⚠️ Limitations

This is currently a frontend-based academic project.

- No real database is connected.
- Authentication is not secure for production use.
- Data is stored only in the browser.
- Admin credentials are hard-coded for demonstration.

## 🚀 Future Enhancements

- Add a backend server.
- Add MySQL/MongoDB database.
- Implement secure authentication.
- Add email notifications.
- Add online payment integration.
- Generate examination registration receipts.
- Deploy the application online.

## 📄 License

This project is created for educational and academic purposes.