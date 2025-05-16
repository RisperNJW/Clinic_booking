# 🏥 Clinic Booking System

## 📌 Project Description

The **Clinic Booking System** is a relational database designed using MySQL to streamline and manage the operations of a medical clinic. It handles core functionalities such as patient registration, doctor management, appointment scheduling, service tracking, and payment recording.

This project demonstrates how to design a real-world relational database with proper use of constraints, normalization, and relationship modeling using only SQL.

## ⚙️ Features

- **Patient Management**: Store and manage patient details.
- **Doctor Management**: Add doctors with unique specializations.
- **Appointment Scheduling**: Book appointments linking doctors and patients.
- **Service Catalog**: Maintain a list of services with pricing.
- **Appointment Services**: Support for multiple services per appointment (Many-to-Many).
- **Payment Tracking**: Record payments for each appointment.

## 🧩 Database Schema Overview

- **Tables**:
  - `Specializations`
  - `Doctors`
  - `Patients`
  - `Services`
  - `Appointments`
  - `Appointment_Services` (junction table)
  - `Payments`

- **Relationships**:
  - `Doctors` ↔ `Specializations`: One-to-One
  - `Appointments` ↔ `Doctors`, `Patients`: Many-to-One
  - `Appointments` ↔ `Services`: Many-to-Many
  - `Appointments` ↔ `Payments`: One-to-One

---

## 🛠️ Setup Instructions

1. **Install MySQL** on your machine.

2. **Clone the Repository**:
   ```bash
   git clone https://github.com/RisperNJW/Clinic_booking.git


