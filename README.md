# Student management
# Instruction
A full-stack student management application built with Spring Boot (backend) and React (frontend).
# Installation
### 1. Clone repository
```bash
git clone https://github.com/tuanduog/JVNC_QLSV.git
```
### 2. Go frontend and install dependencies
```bash
cd student-management-frontend
open package.json and you need to install all in dependencies with correct version
example: npm install axios@^1.9.0
```
### 3. Go backend
```bash
cd student-management-backend
docker build -t your-app-name .
docker run -p 8080:8080 your-app-name
```
(you can change your-name-app with another name)
### 4. Database
Install mysql workbeck(if not installed) 

You can use my example database to test 

https://drive.google.com/file/d/17zYgjG_aIQ_R3bY4XsywJsUgfjgievlG/view?usp=sharing

Change application.properties in backend to fit with you database you make
```bash
spring.datasource.url=jdbc:mysql://localhost:3306/(your database)
spring.datasource.username=(your root)
spring.datasource.password=(your password)
```
# Technologies used
🔹 Backend
Spring Boot 3.4.5

Java 17

MySQL

🔹 Frontend
React 19.1.0 (with Vite)

React Router DOM 7.6.0

React Bootstrap 2.10.10

Bootstrap 5.3.6

Axios 1.9.0

jwt-decode 4.0.0

React Datepicker 8.3.0

date-fns 4.1.0

Font Awesome 6.7.2
