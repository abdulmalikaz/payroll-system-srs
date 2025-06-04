# payroll-system-srs
Software Requirements Engineering

# Payroll Management System

A modern, secure, and automated **Payroll Management System** designed for **PayNow, Inc.**. This system replaces the outdated manual process and introduces mobile accessibility, automated payroll generation, timecard and purchase order handling, employee self-service, and administrative reporting.

---

## 📱 Project Overview

The **Payroll Management System** is a mobile-supported solution that:

- Enables employees to submit timecards and manage purchase orders.
- Automates paycheck generation based on employee classification.
- Provides administrative control over employee records and payroll reports.
- Supports different pay schedules: hourly, salaried, and performance-based.

---

## 📦 Features

### 🧑‍💼 Employee Features
- Login using phone number and password.
- Submit timecards (with validation rules, e.g., 8 hours/day limit).
- View current timecard status.
- Select payment method: bank deposit or office pickup.
- Request various payroll reports (total hours, pay to date, vacation time).
- Performance employees can:
  - Add, modify, and cancel purchase orders.
  - Earn commissions based on total sales (10% to 35%).

### 🛠️ Admin Features
- Add, edit, or delete employee records.
- Manage employee data such as:
  - Salary/hourly rate
  - Social security number
  - Tax and other deductions
- Generate administrative reports (e.g., hours worked, total pay to date).

---

## 🧠 What We Learned

This project helped us improve and apply a wide range of skills in a real-world context:

- **Requirements Engineering**: We learned how to elicit, write, and organize both functional and non-functional requirements clearly and professionally.
- **Modeling and Design**: We practiced using UML diagrams (use cases, class diagrams, sequence and activity diagrams) to communicate system behavior and architecture.
- **Collaboration and Teamwork**: Working as a group of six, we divided tasks effectively, coordinated design decisions, and reviewed each other’s contributions.
- **User-Centered Thinking**: By designing interfaces and flows for different types of users (employees, administrators), we focused on usability and accessibility.
- **Documentation**: We created a comprehensive Software Requirements Specification (SRS) document that can guide development and serve as a reference for future system improvements.

---

## 📑 Use Cases

Key use cases include:

- **Login**: Employee authentication
- **Submit Timecard**
- **Add/Change/Cancel Purchase Order**
- **Change Payment Method**
- **Request/Print Report**
- **Add/Edit/Delete Employee**
- **Generate Admin Reports**

Use case diagrams, sequence diagrams, and activity diagrams are included in the full documentation.

---

## 🔐 Security and Access Control

- Employees can only access and manage their own records.
- Purchase orders and timecards are private per employee.
- Administrators have elevated access and control over all employee data.

---

## ⚙️ System Requirements

### Interfaces

- **Mobile Interface**: For employee self-service.
- **Software Interface**: Connects to existing MySQL Work Management Database (read-only).
- **Banking System Interface**: For electronic paycheck deposits.

### Non-Functional Requirements

- 📈 Performance: Supports high concurrent access (e.g., hundreds of employees).
- 🔄 Availability: At least 99% uptime; must be operational during payroll cycles.
- 🔒 Security: Strict access control by roles.
- 🔧 Maintainability: Modular structure for easy updates.
- 📱 Portability: Runs on phones and tablets (iOS/Android).

---

## 🧩 Architecture and Models

Includes:
- Class Diagram
- Sequence Diagrams:
  - Change Payment Method
  - Request Report
  - Add Employee
  - Cancel Purchase Order
- Activity Diagrams:
  - Request Report
  - Cancel Purchase Order

---

## 🛠️ Technologies Used

- **Frontend**: Mobile interface (design-ready, implementation TBD)
- **Backend**: Secure server logic (language TBD)
- **Database**: MySQL (read-only integration with legacy system)
- **External Integration**: Banking systems for paycheck processing

---

## 📄 Documentation

Full Software Requirements Specification (SRS) is available in `swe312-f24-project-phase2-t14.pdf`. It includes:

- Functional and Non-Functional Requirements
- Use Case Tables and Descriptions
- UML Diagrams
- Class Structures
- User Interface Mockups

---

## 👥 Authors

This project was developed by **Group 14** for **SWE 312: Software Requirements Engineering** at **King Saud University**.

| Name                  |
|-----------------------|
| Abdurrahman Alzomea  | 
| Sulaiman Mokhaniq    |
| Abdullah Alyousef     | 
| Waleed Alharbi        | 
| Abdullah Al Ammar     | 
| Abdulmalik Alzeer     | 

---

## 📅 Timeline

- **Version**: 1.0  
- **Date**: October 24, 2024  
- **Course**: SWE 312 – Software Requirements Engineering  
- **Instructor**: *(TBD)*  

---

## 📘 License

This project is intended for educational purposes only and is not licensed for commercial use.

---
