#  Flask Authentication System (SQLite + Sessions)

A secure user authentication system built with Flask, SQLite, and SQLAlchemy.  
This project demonstrates how real backend login systems work, including registration, login validation, password hashing, and session-based authentication.

---

##  Live Features

- User registration system
- Secure login authentication
- Password hashing using Werkzeug
- Session-based login persistence
- Protected dashboard route
- Logout functionality
- SQLite database integration
- Clean UI with CSS styling

---

##  What This Project Demonstrates

This project is not just a tutorial — it demonstrates real backend engineering concepts:

- How authentication systems work internally
- How sessions maintain user state
- How databases store and retrieve users
- How to prevent duplicate usernames
- How password hashing protects user data
- How Flask handles routing and templates

---

##  Tech Stack

- Python 
- Flask 
- SQLite 
- SQLAlchemy ORM
- Werkzeug Security (password hashing)
- HTML / CSS (frontend)

---

## 📁 Project Structure
lask-auth-system/
│
├── app.py
├── templates/
│ ├── login.html
│ ├── register.html
│ └── dashboard.html
│
├── static/
│ └── style.css
│
├── instance/
│ └── users.db (ignored in GitHub)
│
└── requirements.txt

---

##  System Workflow

```

User registers → password is hashed → stored in database
User logs in → credentials verified
Session created → user authenticated
User accesses dashboard
User logs out → session destroyed

 Security Features
Passwords are never stored in plain text
Passwords are hashed using Werkzeug
Session-based authentication prevents unauthorized access
Duplicate usernames are blocked at database level

 How to Run This Project
# Clone repository
git clone https://github.com/YOUR_USERNAME/flask-auth-system.git

# Enter project folder
cd flask-auth-system

# Create virtual environment
python -m venv venv

# Activate environment
source venv/Scripts/activate   # Windows Git Bash

# Install dependencies
pip install -r requirements.txt

# Run application
python main.py

Then open:
http://127.0.0.1:5000

 Test Credentials

You can create your own test users:

Register new account
Login with same credentials
Try wrong password to test validation

 Screenshots
Login Page

(Add screenshot here)

Dashboard Page

(Add screenshot here)
 Author

Built by Sarah Nabayi

This project was created while learning backend development and authentication systems using Flask.
