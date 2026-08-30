# 🎓 Online Examination System

A cloud-based Online Examination System developed using **Java Spring Boot, PostgreSQL, Hibernate/JPA, HTML, CSS, and JavaScript**.

The system allows students to participate in online examinations, answer multiple-choice questions, and receive their results. Administrators can manage the question bank through the Admin Panel.

## 🚀 Live Demo

🌐 **Live Application:**  
https://online-examination-system-v0we.onrender.com

> Note: The application is deployed on Render. The free instance may take some time to start after inactivity.

---

## ✨ Features

### 👨‍🎓 Student Features

- Enter student name
- Start online examination
- Attempt multiple-choice questions
- Submit answers
- Get instant results
- View examination score

### 👨‍💼 Admin Features

- Admin Panel
- Add new questions
- Manage question bank
- Set multiple options
- Select correct answers

### ☁️ Cloud Features

- Cloud-hosted Spring Boot application
- PostgreSQL cloud database
- Environment variables for database security
- Deployed using Render

---

## 🛠️ Technologies Used

| Technology | Purpose |
|------------|---------|
| Java | Backend Development |
| Spring Boot | Application Framework |
| Spring Data JPA | Database Operations |
| Hibernate | ORM |
| PostgreSQL | Database |
| HTML | Frontend Structure |
| CSS | User Interface Design |
| JavaScript | Frontend Functionality |
| Maven | Dependency Management |
| Render | Cloud Deployment |

---

## 📂 Project Structure

```text
online-examination-system
│
├── src
│   ├── main
│   │   ├── java
│   │   │   └── com.onlineexam.system
│   │   │       ├── controller
│   │   │       ├── model
│   │   │       ├── repository
│   │   │       └── service
│   │   │
│   │   └── resources
│   │       ├── static
│   │       ├── templates
│   │       └── application.properties
│
├── pom.xml
└── README.md
