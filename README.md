# Arogyamapan – Student Health Monitoring System

Arogyamapan is a full-stack MERN application designed to digitally track and manage students’ physical health records within educational institutions.

The system replaces manual record-keeping with a secure and structured platform for monitoring student health metrics over time.

---

## Tech Stack

- **Frontend:** React.js  
- **Backend:** Node.js, Express.js  
- **Database:** MongoDB  
- **Authentication:** JSON Web Tokens (JWT)

---

## Problem Statement

Traditional student health records are often maintained manually or in spreadsheets, leading to:

- Lack of structured historical tracking  
- Limited data access control  
- Inconsistent record management  
- Difficulty in analyzing growth patterns  

Arogyamapan provides a centralized and secure solution to manage student health information efficiently.

---

## Features

### Role-Based Authentication
- JWT-based secure login system  
- Separate access roles:
  - Teacher (Admin)
  - Parent (Student Access)  
- Protected routes for secure data operations  

### Health Record Management
- Track student health metrics:
  - Height  
  - Weight  
  - BMI (auto-calculated)  
  - Vision  
  - Hearing  
  - Posture  
  - Dental health  

### Longitudinal Data Storage
- MongoDB schema designed to store multiple health entries per student  
- Enables historical tracking instead of overwriting records  

### API-Based Data Handling
- Backend routes for creating, updating, retrieving, and deleting health records  
- Structured validation to ensure reliable data storage  

### Dashboard Interface
- Responsive React-based UI  
- Displays student health information dynamically  
- Visual monitoring of growth patterns  

---

## System Architecture

Frontend (React)  

Backend (Node.js + Express)  
  
MongoDB Database  

- Authentication handled via JWT  
- Backend manages validation and business logic  
- Frontend communicates with backend through HTTP requests  

---
