# Student Registration System (React + FastAPI)

A full-stack web application for student registration and authentication. This system allows users to sign in, register students with detailed forms, and view all registered student data.

## 🧑‍💻 Tech Stack

- **Frontend**: React.js, React Router
- **Backend**: FastAPI, Python
- **Database**: MySQL (XAMPP)
- **Server**: Uvicorn

## 🔧 Setup Instructions

### 1. Start MySQL Server
- Open **XAMPP Control Panel**
- Start the **MySQL** module
- Create a database (e.g., `student_db`) via **phpMyAdmin**

### 2. Backend (FastAPI)
```bash
cd backend
pip install -r requirements.txt
uvicorn main:app --reload


