# Spring Boot Projects Repository

This repository contains two backend applications built using Spring Boot:

1. **Hospital Management System**
2. **Doctor Appointment Management System**

Each project follows clean architecture principles, RESTful APIs, and proper exception handling. These applications are designed for learning, practice, and real-world implementation.

---

## 🏥 1. Hospital Management System

### 🚀 Features
- Patient registration and record management
- Doctor management
- Department categorization
- Inpatient/Outpatient handling
- Billing system
- Admin panel functionalities

### 🛠️ Tech Stack
- **Backend:** Spring Boot, Spring MVC, Spring Data JPA
- **Database:** MySQL / H2 (for development)
- **Build Tool:** Maven / Gradle
- **ORM:** Hibernate

### 📁 Project Structure

### 🔗 API Endpoints Example
- `POST /api/patients` – Add new patient
- `GET /api/doctors` – List all doctors
- `PUT /api/patient/{id}` – Update patient details
- `DELETE /api/doctor/{id}` – Remove doctor

---

## 🩺 2. Doctor Appointment Management System

### 🚀 Features
- Book, update, and cancel appointments
- View doctor availability
- Patient and doctor registration
- Appointment status (pending, confirmed, completed)
- Admin access for managing appointments and users

### 🛠️ Tech Stack
- **Backend:** Spring Boot, Spring MVC, Spring Data JPA
- **Database:** MySQL / H2
- **Build Tool:** Maven / Gradle
- **Authentication:** (Optional) Spring Security / JWT (if implemented)

### 📁 Project Structure

### 🔗 API Endpoints Example
- `POST /api/appointments` – Book appointment
- `GET /api/appointments/{id}` – View appointment details
- `PUT /api/appointments/{id}` – Reschedule
- `DELETE /api/appointments/{id}` – Cancel

---

## 📦 How to Run

### Prerequisites
- Java 11 or higher
- Maven or Gradle
- MySQL or H2 DB

### Steps
1. Clone the repo:
   ```bash
   git clone https://github.com/your-username/springboot-projects.git
