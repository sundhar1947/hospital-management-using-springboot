# hospital-management-using-springboot

A web-based Hospital Management System built using Spring Boot and MySQL that enables efficient management of patients, doctors, appointments, and medical records. The system is designed to simplify hospital workflows by allowing digital access to healthcare operations.

---

📌 Features

👥 User Roles
- Patient
  - Registration/Login
  - View and edit profile
  - Search doctors by specialization, name, or location
  - Book and manage appointments
  - View medical history and prescriptions

- Doctor
  - Registration/Login
  - Manage schedule and availability
  - View and respond to appointment requests
  - Write consultation notes and diagnoses
  - View patient medical records

---
🗓️ Appointment Management

Appointments are at the core of the system. Patients can:
- View available slots for a selected doctor
- Book appointments based on doctor availability
- Receive confirmation or rejection from the doctor
- Cancel or reschedule their bookings

Doctors can:
- Block unavailable days
- Manage appointment requests
- View upcoming and past consultations
- Record medical notes during or after the session

The appointment module includes:
- Appointment Status: `Pending`, `Approved`, `Cancelled`, `Completed`
- Slot Management: Time and date selection
- Notifications (basic UI alerts or future email/SMS)

---

🛠️ Technologies Used
---------------------------------------------------------------
| Layer             | Technology                               |
|-------------------|------------------------------------------|
| Backend           | Spring Boot, Spring MVC, Spring Data JPA |
| Frontend          | HTML, CSS                                |
| Database          | MySQL Workbench                          |
| Security          | Spring Security                          |
| API Style         | RESTful APIs                             |
| Build Tool        | Maven or Gradle                          |
---------------------------------------------------------------
---

💾 Database Schema

- `patients` table: Stores patient details.
- `doctors` table: Stores doctor details.
- `appointments` table: Links patients and doctors with booking info.
- `medical_records` table: Stores diagnosis and treatment history.

---

🚀 Getting Started

Prerequisites
- Java 17+
- Spring Boot
- MySQL Server and Workbench
- Maven

