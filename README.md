# 💼 Job Platform

A full-featured **Job Platform Application** built with **Spring Boot (Microservices Architecture)**.  
It provides a platform for **students/job seekers**, **recruiters**, and **admins** with modules for authentication, job posting, applications, payments, and analytics.

---

## 🚀 Features

- **Authentication & Authorization** (JWT-based login & registration)
- **Student Module**  
  - Register, login, update profile  
  - Apply for jobs  
  - View application status  
- **Recruiter Module**  
  - Post new jobs  
  - Manage job postings  
  - View applicants  
- **Admin Module**  
  - Manage users (students/recruiters)  
  - Manage subscription plans & payments  
  - View system analytics  
- **Payments & Subscription**  
  - Razorpay integration  
  - Subscription plans for recruiters  
  - Invoice generation  
- **File Upload & Email Service**  
  - Upload resumes/documents (via Cloudinary)  
  - Email notifications for jobs, applications, and payments  
- **Microservices Architecture**  
  - Config Server  
  - API Gateway  
  - Eureka Server (Service Discovery)  
  - Multiple independent services (Auth, Student, Recruiter, JobPost, Payment, etc.)  

---

## 🛠️ Tech Stack

- **Backend:** Java 8+, Spring Boot, Spring Security, JPA/Hibernate  
- **Database:** MySQL  
- **Authentication:** JWT  
- **Payment Integration:** Razorpay  
- **Cloud:** Cloudinary (File Uploads)  
- **Service Discovery:** Eureka Server  
- **API Gateway:** Spring Cloud Gateway  
- **Build Tool:** Maven  

---
## 📂 Project Structure

job_portal/
│-- src/main/java/com/jobPortal/
│ ├── Controller/ # REST Controllers (Student, Recruiter, Admin, Auth, etc.)
│ ├── DTO/ # Data Transfer Objects
│ ├── Entity/ # JPA Entities
│ ├── Enum/ # Enum classes (Roles, PaymentStatus, etc.)
│ ├── Repository/ # Spring Data JPA Repositories
│ ├── Security/ # JWT & Spring Security Config
│ ├── Service/ # Service Layer (Business Logic)
│ └── *Application.java# Multiple microservice entry points
│
│-- src/main/resources/
│ ├── application.properties
│ ├── static/
│ └── templates/
│
│-- pom.xml
## 📂 Project Structure

