# Student Grade Management System

A web application developed using **PHP**, **MySQL**, **HTML**, **CSS**, and **JavaScript** for managing student grades and academic records.

The application provides separate interfaces for administrators and students. Administrators can manage grades, courses, and students, while students can securely view their academic results online.

---

# 📖 Overview

This project was developed to simplify the management of student grades within an educational institution.

The system allows administrators to record and update grades, while students can access their academic results through a secure web interface.

---

# ✨ Features

## Administrator

- Secure administrator authentication
- Manage student information
- Manage courses (Matières)
- Record student grades
- Update grades
- Delete grades
- Display student grade reports
- Filter data by academic level

## Student

- Secure login
- View personal grades
- View academic information
- Access course results

## General Features

- Responsive web interface
- Dynamic forms using JavaScript
- MySQL database integration
- User-friendly navigation

---

# 🏗 System Architecture

```
Browser
    │
    ▼
PHP Application
    │
    ▼
MySQL Database
```

Project structure:

```
GestionNoteEtudiant

├── admin/
│   ├── Administrator pages
│   ├── Grade management
│   ├── Student management
│   └── Authentication
│
├── etudiant/
│   ├── Student dashboard
│   ├── Grade consultation
│   └── Student interface
│
├── image/
│
├── ConnectionDB.php
├── connexion.php
├── destroy.php
├── app.js
└── get_niveau.php
```

---

# 🛠 Technologies Used

- PHP
- MySQL
- HTML5
- CSS3
- JavaScript
- Bootstrap
- Apache (XAMPP/WAMP)

---

# 🚀 Installation

## Clone the repository

```bash
git clone https://github.com/diallo1997/GestionNoteEtudiant.git
```

## Configure the database

1. Create a MySQL database.

2. Import the SQL script (if provided).

3. Update the database credentials in:

```
ConnectionDB.php
```

Example:

```php
$host = "localhost";
$dbname = "gestion_notes";
$user = "root";
$password = "";
```

---

## Run the application

Place the project inside your web server directory:

```
xampp/htdocs/
```

or

```
wamp/www/
```

Then open your browser:

```
http://localhost/GestionNoteEtudiant
```

---

# 📷 Screenshots

Create an **images/** folder and add screenshots such as:

```
images/

login.png
admin-dashboard.png
student-dashboard.png
grade-management.png
student-grades.png
```

Example:

```markdown
## Login

![Login](images/login.png)

## Administrator Dashboard

![Dashboard](images/admin-dashboard.png)

## Student Dashboard

![Student](images/student-dashboard.png)
```

---

# 🎯 Learning Outcomes

This project allowed me to strengthen my skills in:

- PHP Development
- MySQL Database Design
- CRUD Operations
- User Authentication
- Web Application Development
- Database Connectivity
- HTML/CSS/JavaScript
- Responsive User Interface Design

---

# 🔮 Future Improvements

- Password encryption
- Role-based access control
- PDF transcript generation
- Email notifications
- Statistics dashboard
- Search and filtering enhancements
- REST API integration
- Modern UI using Bootstrap 5

---

# 👨‍💻 Author

**Alpha Mamadou Falilou Diallo**

Java Full Stack Developer

- GitHub: https://github.com/diallo1997
- LinkedIn: https://www.linkedin.com/in/alpha-diallo

---

## 📄 License

This project is intended for educational and portfolio purposes.
