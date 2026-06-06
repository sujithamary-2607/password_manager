# 🔐 Secure Password Manager with Face Recognition

A secure password management system built using **Flask, Python, HTML, CSS, and JavaScript** that allows users to safely store, manage, and generate strong passwords. The application includes **Face Recognition Authentication** for enhanced security, ensuring that only authorized users can access their stored credentials.

---

## 📌 Features

### 👤 Face Recognition Login
- Secure biometric authentication using facial recognition.
- User identity verification before accessing stored passwords.
- Additional layer of security beyond traditional login methods.

### 🔑 Password Management
- Store website credentials securely.
- Save:
  - Website Name
  - Username/Email
  - Password
- View and manage saved passwords.

### 🎲 Password Generator
- Generate strong and secure passwords instantly.
- Randomized passwords with:
  - Uppercase Letters
  - Lowercase Letters
  - Numbers
  - Special Characters

### 🛡 Security Features
- Password hashing using Werkzeug Security.
- SQLite database for secure credential storage.
- Session-based authentication.
- Security logging for monitoring user activities.

### 📊 User Dashboard
- Easy-to-use interface.
- Manage stored credentials efficiently.
- Access password generation tools.

---

## 🛠 Tech Stack

### Frontend
- HTML5
- CSS3
- JavaScript

### Backend
- Python
- Flask

### Database
- SQLite

### Security & Authentication
- OpenCV
- Face Recognition
- Werkzeug Security

---

## 📂 Project Structure

```bash
password_manager/
│
├── app.py
├── index.html
├── login.html
├── dashboard.html
├── passwords.html
├── generator.html
├── about.html
│
├── password_manager.db
│
└── static/
    ├── css/
    ├── js/
    └── images/
```

---

## 🚀 Installation

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/your-username/password-manager.git
```

### 2️⃣ Navigate to Project Directory

```bash
cd password-manager
```

### 3️⃣ Create Virtual Environment

```bash
python -m venv venv
```

### 4️⃣ Activate Virtual Environment

Windows:

```bash
venv\Scripts\activate
```

Linux/Mac:

```bash
source venv/bin/activate
```

### 5️⃣ Install Dependencies

```bash
pip install flask opencv-python numpy werkzeug
```

### 6️⃣ Run Application

```bash
python app.py
```

### 7️⃣ Open Browser

```bash
http://127.0.0.1:5000
```

---

## 🎯 How It Works

1. User registers/login.
2. Face image is captured and verified.
3. Successful authentication grants access to the dashboard.
4. User can:
   - Store credentials
   - Generate strong passwords
   - Manage saved passwords
5. Passwords are securely stored in the database.

---


## 🔒 Security Considerations

- Passwords are protected using hashing techniques.
- Face recognition adds biometric authentication.
- User sessions prevent unauthorized access.
- Security logs help monitor suspicious activities.

---

## 🎓 Learning Outcomes

This project helped me gain practical experience in:

- Full Stack Web Development
- Flask Framework
- SQLite Database Management
- Face Recognition using OpenCV
- Authentication & Authorization
- Password Security Techniques
- Secure Session Handling

---

## 🚀 Future Enhancements

- End-to-End Password Encryption
- Multi-Factor Authentication (MFA)
- Cloud Database Integration
- Password Strength Analyzer
- Mobile Application Support
- Email Notifications for Security Alerts

---

## 👩‍💻 Author

**T. Sujitha Mary**

Artificial Intelligence and Data Science Student

- LinkedIn: www.linkedin.com/in/sujitha-mary-887367278
- Email: sujitha2607@gmail.com

---
