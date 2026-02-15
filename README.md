# 🔐 Secure User Authentication System
---

# Project Overview
This project implements a secure user authentication system using Python and Flask.
Users can register, login, and access protected routes. The system ensures that passwords are securely hashed and that only authenticated users can access sensitive pages.
Optional role-based access control allows some routes to be restricted to admins.
# Features
- ✅ User Registration with hashed passwords (bcrypt)
- ✅ Secure Login and Logout
- ✅ Protected Dashboard Route
- ✅ Optional Admin-only route
- ✅ Session Management (Flask-Login)
- ✅ Modern gradient UI for forms (HTML + CSS)

# Folder Structure
Task01_FS/
├── app.py             # Main Flask application
├── models.py          # Database models
├── templates/
│   ├── login.html
│   ├── register.html
│   └── dashboard.html
├── static/
│   └── style.css      # Styles for the UI
├── requirements.txt   # Python dependencies
└── README.md  

# Usage
- Register a new user account
- Login with your credentials
- Access the Dashboard (protected route)
- Logout to end the session
- (Optional) Access /admin if your user role is set to admin

---

# Auhtor
- Name: Pruonh Kimliya
- Email: kimliyapruonh@gmail.com
