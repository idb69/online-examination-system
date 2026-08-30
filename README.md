# Cloud-Based Online Examination System

## Features
- Role-based authentication: ADMIN and STUDENT
- Timed examination (30 minutes) with automatic submission
- Question bank CRUD for administrators
- Automatic scoring, percentage and PASS/FAIL result generation
- Result history for administrators
- Cloud-ready configuration using environment variables
- Docker support for deployment

## Demo accounts
- Admin: `admin@onlineexam.com` / `admin123`
- Student: `student@onlineexam.com` / `student123`

## Database
Create MySQL database `online_exam_db`, then configure:
- `DB_URL`
- `DB_USERNAME`
- `DB_PASSWORD`

## Run
```bash
./mvnw spring-boot:run
```
Open `http://localhost:8080/login`.

## Cloud deployment
Deploy the Docker image or Spring Boot application to Render, Railway, AWS Elastic Beanstalk, EC2, or another cloud platform. Set `DB_URL`, `DB_USERNAME`, `DB_PASSWORD`, and optionally `PORT` as environment variables.
