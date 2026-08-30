# Cloud-Based Online Examination System

## 📌 Project Overview

The **Cloud-Based Online Examination System** is a secure web-based application developed using **Spring Boot**. The system allows administrators to manage examinations and questions while students can securely log in, attempt timed examinations, and receive automatically generated results.

This project is designed according to the requirements of a **Cloud-Based Online Examination System**.

---

## 🚀 Features

### 🔐 Role-Based Authentication

The system provides separate access for:

* **Admin**
* **Student**

Admins and students have different permissions and dashboards.

---

### 👨‍💼 Admin Features

* Admin Login
* Manage Students
* Add Questions
* Edit Questions
* Delete Questions
* Manage Question Bank
* View Examination Results

---

### 👨‍🎓 Student Features

* Secure Student Login
* Attempt Online Examination
* Multiple Choice Questions
* Timed Examination
* Automatic Exam Submission
* View Results

---

### ⏱️ Timed Exam & Auto Submission

The examination includes a timer.

* Students must complete the exam within the specified time.
* The remaining time is displayed during the examination.
* When the timer reaches zero, the examination is automatically submitted.

---

### 📝 Question Bank Management

Administrators can manage the question bank.

Features include:

* Add new questions
* Update existing questions
* Delete questions
* View all questions
* Define correct answers

---

### 📊 Automatic Result Generation

After examination submission:

* Answers are evaluated automatically.
* Marks are calculated.
* Percentage is generated.
* PASS/FAIL status is displayed.
* Results can be stored and viewed by administrators.

---

## 🛠️ Technologies Used

* Java
* Spring Boot
* Spring MVC
* Spring Security
* Spring Data JPA
* Thymeleaf
* MySQL
* Maven
* HTML
* CSS
* JavaScript

---

## ☁️ Cloud Deployment

The application is designed to be cloud-ready.

It can be deployed using platforms such as:

* AWS
* Render
* Railway
* Azure

Database configuration can be managed using environment variables for secure cloud deployment.

---

## 📂 Project Structure

```text
online-examination-system
│
├── src/
│   ├── main/
│   │   ├── java/
│   │   └── resources/
│   │
│   └── test/
│
├── pom.xml
├── Dockerfile
├── README.md
├── mvnw
├── mvnw.cmd
└── .gitignore
```

---

## ▶️ How to Run the Project

### Step 1: Clone the Repository

```bash
git clone https://github.com/idb69/online-examination-system.git
```

### Step 2: Open the Project

Open the project using:

* Eclipse
* Spring Tool Suite (STS)
* IntelliJ IDEA

### Step 3: Configure Database

Update database details in:

```text
src/main/resources/application.properties
```

### Step 4: Run the Application

Run the Spring Boot main application class.

Or use Maven:

```bash
mvn spring-boot:run
```

---

## 👤 User Roles

| Role    | Permissions                       |
| ------- | --------------------------------- |
| Admin   | Manage Questions and View Results |
| Student | Attempt Exams and View Results    |

---

## 🎯 Assignment Requirements Completed

* ✅ Role-Based Login (Admin/Student)
* ✅ Timed Exams
* ✅ Auto Submission
* ✅ Question Bank Management
* ✅ Cloud-Ready Backend
* ✅ Automatic Result Generation

---

## 📸 Screenshots

Screenshots of the application can be added here after deployment.

---

## 👨‍💻 Author

**Babul Kumar**

---

## 📜 License

This project is created for educational and internship purposes.
