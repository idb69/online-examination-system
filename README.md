# Smart Attendance System on Cloud

A Spring Boot based Smart Attendance System created for the Cloud Computing Internship project.

## Features
- Admin and Student role-based login
- Secure password encryption using BCrypt
- Student registration
- QR-based attendance session
- Attendance auto-recording
- Attendance history
- Admin dashboard
- Attendance reports
- MySQL database support
- Ready for cloud deployment

## Technology Stack
- Java 21
- Spring Boot
- Spring Security
- Spring Data JPA
- Thymeleaf
- MySQL
- Maven
- ZXing QR Code

## Setup

### 1. Configure MySQL
Update `src/main/resources/application.properties`:

```properties
spring.datasource.username=root
spring.datasource.password=YOUR_MYSQL_PASSWORD
```

The database will be created automatically because of `createDatabaseIfNotExist=true`.

### 2. Run the application
Import as an Existing Maven Project in Eclipse/STS.

Run:
`SmartAttendanceSystemApplication.java`

Open:
`http://localhost:8081`

## Default Admin Login
Email: `admin@attendance.com`
Password: `admin123`

## Cloud Deployment
For internship submission, the application can be deployed with:
- Render
- Railway
- AWS EC2
- Azure App Service

For production, use environment variables for database credentials.
