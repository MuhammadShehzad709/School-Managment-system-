# 🏫 School Management System

A complete **C# Windows Forms Desktop Application** built using **Layered Architecture (3-Tier Architecture)** for managing school operations including students, teachers, classes, admissions, fees, users, and system logs.

---

## 🚀 Project Overview

This project is designed to automate school management processes using a structured and scalable architecture.

It follows:

- 🎨 Presentation Layer (PL) – Windows Forms UI
- ⚙ Business Logic Layer (BL)
- 🗄 Data Access Layer (DL)
- 📦 Models Layer (Data Transfer Objects)
- 🔐 Enums & Validations Layer

---

## ✨ Features

### 👨‍🎓 Student Management
- Add / Update / Delete / View Students
- Store personal information
- Upload documents (Form B, Domicile)

### 👨‍🏫 Teacher Management
- Manage teacher records
- CNIC, Qualification, Subject, Designation
- Date of Joining tracking

### 🏫 Class Management
- Class creation & section management
- Section strength handling
- Student-class mapping

### 🧾 Admission System
- Admission form management
- Form number tracking
- Student admission records

### 💰 Fee Management
- Fee submission system
- Pending fee tracking
- Fee status management

### 👤 User Management
- Role-based access control
- OTP verification system
- Email-based authentication

### 📜 Logging System
- Track system activities
- User actions monitoring
- Audit logs for students/users

---

## 📦 Models Structure

### 🎓 AdmissionModel
- Admission Id
- Form Number
- Admission Date
- Student Id

### 🏫 ClassModel
- Class Name
- Section
- Section Strength
- Student Id mapping

### 📜 LogModel
- Action Type
- User Id
- Student Id
- Message
- Created At

### 👨‍💼 EmployeModel
- Employee details
- CNIC, Qualification, Designation
- Email & Joining Date

### 💰 StudentFeeModel
- Fee Amount
- Pending Amount
- Submission Date
- Fee Status

### 👨‍🎓 StudentsModel
- Student Name
- Father Name
- Roll Number
- DOB
- Gender
- Documents (Form B, Domicile)

### 👨‍🏫 TeachersModel
- Teacher Name
- CNIC
- Qualification
- Subject
- Email
- Joining Date

### 👤 UserInfoModel
- Username
- Email
- Password
- Role
- OTP
- Status
- Profile Image

---

## 🛠 Technologies Used

- 💻 C# (.NET Framework)
- 🪟 Windows Forms (WinForms)
- 🗄 SQL Server
- ⚙ ADO.NET
- 🏗 Layered Architecture
- 🔐 Enums & Validations
- 📧 Email OTP System

---

## 📁 Project Structure
SchoolManagmentSystem
│
├── BL (Business Logic Layer)
├── DL (Data Access Layer)
├── MODELS
├── PL (Presentation Layer - UI)
├── Enums
├── Validations
├── Custom Classes
└── Program.cs

---

## 🏗 Architecture Flow
UI (PL)
↓
Business Logic (BL)
↓
Data Access Layer (DL)
↓
SQL Server Database


---

## 🔐 Security Features

- OTP Verification
- Role-based Authentication
- Input Validations
- Secure Login System

---

## 📌 Future Improvements

- ASP.NET Core Web Version
- REST API Integration
- Dashboard Analytics (Charts)
- Mobile Application
- Cloud Database Support

---

## 👨‍💻 Author

**Muhammad Shehzad**

- GitHub: https://github.com/MuhammadShehzad709

---

## ⭐ Status

✔ Completed Desktop Application  
✔ Layered Architecture Implemented  
✔ Database Integrated  
✔ GitHub Ready Project
