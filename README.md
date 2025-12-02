# Online Feedback System

A complete web-based application that allows students to submit feedback for teachers/courses and provides admins with tools to manage questions, view responses, and analyze feedback.

---

## 📘 Overview

This project digitizes the traditional feedback system used in colleges and institutions.

### Includes:
- 👨‍🎓 Student module
- 🧑‍💼 Admin module  
- 🔐 Secure login system  
- ❓ Dynamic feedback questions  
- ⭐ Rating submission  
- 📊 Admin dashboard with analytics  
- 🎨 Responsive UI using Bootstrap  

---

## 🛠️ Tech Stack

**Frontend:** HTML, CSS, Bootstrap, JavaScript  
**Backend:** PHP  
**Database:** MySQL  
**Tools:** PHPMailer (optional), cPanel / InfinityFree hosting  

---

## ✨ Features

### 🔹 Student
- Login & registration  
- View available feedback forms  
- Submit feedback with ratings  
- Mobile-friendly UI  

### 🔹 Admin
- Manage questions  
- View feedback  
- View charts & analytics  
- Manage students (optional)  

---

## 📁 Project Structure
project-folder/
│── admin/
│── frontend/
│── assets/
│── config/
│ └── db.php
│── vendor/ (if using PHPMailer)
│── index.php



## 🗄️ Database Setup

1. Create database `online_feedback`
2. Import provided SQL file
3. Update `config/db.php`:

```php
<?php
$host = "localhost";
$user = "root";
$pass = "";
$db   = "online_feedback";

$conn = new mysqli($host, $user, $pass, $db);

if ($conn->connect_error) {
    die("Connection failed: " . $conn->connect_error);
}
?>

