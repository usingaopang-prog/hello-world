# 📚 Thekwini Metropolitan Libraries: Library Management System

**Student Name:** Opang Usinga  
**Student Number:** 402314133  
**Module:** Intro to Programming 500  
**Institution:** Richfield Graduate Institute of Technology  

---

## 📖 Project Overview

This project is a console-based Python application made for **Thekwini Metropolitan Libraries**. It helps manage library branches from one central place. The program allows library staff to manage members, track book loans and returns, handle reservations, take payments, generate branch reports, manage staff accounts, and perform branch-related tasks.

The system uses Python dictionaries, lists, and sets to store data in memory. It demonstrates core programming concepts including:
- **Functions** for modular task execution.
- **Modular programming** to keep the code organized.
- **Decision structures** for logical choices.
- **Loops** for iteration and repetition.
- **Input validation** to ensure data integrity.
- **Role-based access control** to restrict staff actions based on their permissions.

---

## ✨ System Features

### 🔐 Staff Authentication
- Role-based login system for different user types.
- **User Roles:**
  - Librarian
  - Senior Librarian
  - System Administrator

### 👥 Member Management
- Register new members.
- Prevent duplicate SA IDs for members.
- View member details.
- Track loans and fines for each member.

### 📖 Book Loan Management
- Issue books to members.
- Process book returns.
- Calculate fines for late returns.
- Validate borrowing eligibility.
- Send reservation notifications to members.

### 💰 Fine Management
- Support partial fine payments.
- Calculate fines accurately.
- Track payment history for members.

### 📊 Reporting
- Generate branch-level reports.
- Generate overdue reports.
- Allow cross-branch comparisons.
- Provide loan statistics.

### ✅ Data Validation
- **ISBN validation** for books.
- **Date validation** for all entries.
- **Menu input validation** to prevent errors.
- **Numeric validation** to ensure correct data entry.

---

## 🏛️ Pre-Populated Sample Data

The system starts with sample data to demonstrate functionality, including:
- Minimum **10 members**
- Minimum **20 books**
- Minimum **15 loan records**
- **3 library branches**
- Staff accounts for each role

### 📍 Library Branches
| Branch Name | Branch Code |
| :--- | :--- |
| Durban Central Library | DBN001 |
| Pinetown Public Library | PIN002 |
| Umlazi Community Library | UML003 |

### 🎫 Membership Types
| Membership Type | Max Books | Loan Period |
| :--- | :--- | :--- |
| **Junior** | 3 | 14 days |
| **Standard** | 5 | 21 days |
| **Senior** | 8 | 30 days |
| **Student** | 10 | 21 days |

---

## ⚙️ How to Run the Program

1. Ensure **Python 3** is installed on your computer.
2. Extract the project folder from the ZIP file.
3. Open the project folder in **VS Code**, **IDLE**, **PyCharm**, **Command Prompt**, or **Terminal**.
4. Run the program by typing:
   ```bash
   python main.py
