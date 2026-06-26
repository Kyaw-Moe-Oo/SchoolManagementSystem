# 🎓 School Management System (MVC - Pure PHP)

A School Management System built using Pure PHP and the MVC (Model-View-Controller) architecture. The application runs in Docker containers and provides modules for managing students, teachers, classes, subjects, attendance, grades, and more.

---

## 🧰 Technologies Used

- PHP (Pure PHP)
- MySQL
- HTML5
- CSS3
- JavaScript
- Bootstrap
- Docker
- Docker Compose
- MVC Architecture

---

## 📦 Requirements

- Docker
- Docker Compose

---

## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone git@github.com:Kyaw-Moe-Oo/SchoolManagementSystem.git
```

or

```bash
git clone https://github.com/Kyaw-Moe-Oo/SchoolManagementSystem.git
```

### 2. Go to the project directory

```bash
cd SchoolManagementSystem
```

### 3. Start Docker containers

```bash
docker compose up -d --build
```

### 4. Import the database

Import the SQL file located in the project (for example):

```
database/school_management_system.sql
```

into the MySQL container.

### 5. Open the application

```
http://localhost
```

or

```
http://localhost:8080
```

(depending on your Docker configuration)

### 6. Stop the containers

```bash
docker compose down
```

---

## 📂 Project Structure

```
app/
public/
database/
docker/
docker-compose.yml
README.md
```

---

## ✨ Features

- Student Management
- Teacher Management
- Class Management
- Subject Management
- Attendance Management
- Grade Management
- Authentication
- Role-Based Authorization
- Dashboard

---

## 👨‍💻 Author

Kyaw Moe Oo

GitHub: https://github.com/Kyaw-Moe-Oo
