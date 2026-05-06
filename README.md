# Smart Attendance System

An AI-powered campus attendance management system with real-time **face recognition**, **manual attendance tracking**, and **student performance analytics**.

## Features

- **Face Recognition Attendance** — Camera-based student identification using face-api.js
- **Manual Attendance** — Mark students Present/Late/Absent from a class roster
- **Student Registration** — Enroll students with face images and auto-generate login credentials
- **Performance Analytics** — Charts showing attendance trends, top performers, and at-risk students
- **Class Management** — Create and manage class sections by department
- **Student Portal** — Students can view their own attendance and performance
- **Role-Based Access** — Admin and Student roles with scoped data visibility
- **Email Notifications** — Optional SMTP integration to email temporary passwords

## Tech Stack

| Layer    | Technology                                      |
| -------- | ----------------------------------------------- |
| Frontend | React 18, Vite, Tailwind CSS, Recharts          |
| Backend  | Express.js, sql.js (SQLite), JWT authentication |
| AI/ML    | face-api.js (TinyFaceDetector + FaceRecognition)|

