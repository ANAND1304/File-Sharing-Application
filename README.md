# File Sharing Application

A secure file sharing platform built with Spring Boot and JWT Authentication.

## Features
- User registration and login with JWT
- Upload, download and share files securely
- Role-based access control
- File metadata stored in MySQL

## Tech Stack
- Java 17, Spring Boot
- Spring Security + JWT
- MySQL + JPA/Hibernate
- HTML/CSS (Frontend)

## Setup Instructions
1. Clone the repo
2. Configure MySQL in application.properties
3. Run: mvn spring-boot:run

## API Endpoints
| Method | Endpoint | Description |
|--------|----------|-------------|
| POST | /auth/register | Register user |
| POST | /auth/login | Get JWT token |
| POST | /files/upload | Upload file |
| GET | /files/download/{id} | Download file 
