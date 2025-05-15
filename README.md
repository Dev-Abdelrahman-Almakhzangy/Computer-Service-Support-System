# Computer Service Support System

A front-desk support application for managing computer part repairs (CD-ROM, Hard-drive, Floppy, etc.) with three user roles—Customer, Technician, and Admin. Customers submit and track service tickets; Technicians update statuses and notify customers; Admins manage user accounts and oversee all tickets.

---

## 📑 Table of Contents

1. [Features](#features)  
2. [Functional Requirements](#functional-requirements)  
3. [Non-Functional Requirements](#non-functional-requirements)  
4. [Architecture & Diagrams](#architecture--diagrams)  
5. [Documentation](#documentation)  
6. [Team Members](#team-members)  
7. [Getting Started](#getting-started)  
8. [Contributing](#contributing)  
9. [License](#license)  

---

## 🎞️ Features

- **Authentication**  
  - Login (2FA via OTP, expires in 5 min)  
  - Signup / Registration  
- **Customer**  
  - Submit, prioritize (High/Low), view, manage or cancel tickets  
  - Provide service feedback  
  - Update own profile (username, password, email, phone, address)  
- **Technician**  
  - View assigned tickets  
  - Update ticket status (Fixed / Not Fixed / In Progress) & email notification  
  - Edit own profile  
- **Administrator**  
  - View all tickets, customers & technicians  
  - Create, edit or delete user accounts (assign roles)  

---

## 🛠️ Functional Requirements

| ID    | Feature               | Description                                                                                   |
|-------|-----------------------|-----------------------------------------------------------------------------------------------|
| FR1   | Login                 | Authenticate users as Customer, Technician, or Admin                                          |
| FR2   | Signup                | Register new user accounts                                                                    |
| FR3   | Submit Ticket         | Customer submits repair ticket with priority                                                  |
| FR4   | Manage Ticket         | Customer & Technician modify ticket details                                                   |
| FR5   | View Ticket Status    | Customer checks “Fixed”, “Not Fixed”, etc.                                                    |
| FR6   | Cancel Ticket         | Customer cancels their ticket                                                                 |
| FR7   | Provide Feedback      | Customer rates and comments on service                                                        |
| FR8   | Update Ticket Status  | Technician updates status and triggers notification                                           |
| FR9   | View Assigned Tickets | Technician lists tickets assigned to them                                                     |
| FR10  | Manage User Accounts  | Admin creates/edits/deletes user records                                                      |

---

## 🔒 Non-Functional Requirements

1. **Security**: Two-Factor Authentication (OTP expires in 5 min)  
2. **Scalability**: Support up to 1,000 concurrent users  
3. **Performance**: Process requests within 60 seconds  
4. **Usability**: 85% of core functionality discoverable within 15 minutes by new users  
5. **Availability**: 24/7 uptime  
6. **Portability**: Compatible with IE, Safari, Chrome, Firefox  

---

## 🏗 Architecture & Diagrams

- **Context Diagram**  
- **Use-Case Diagram & Scenarios** (e.g. Submit Ticket ST_1234)  
- **Sequence Diagrams** (SubmitTicket, CancelTicket)  
- **Class Diagram**  
- **Database Schema**  
- **GUI Wireframes & Screenshots**

_All diagrams and detailed design are in the Phase 3 Report (PDF)._  

---

## 📄 Documentation

See [Phase 3 Report – Software Engineering I (Group 3)](Phase%203%20Report%20-Software%20Engineering%20I%20-%20Group%203.pdf) for full requirements, UML diagrams, sequence flows, class models, and UI mockups.

---

## 👥 Team Members

| BUE ID  | Name                         | Email                                    |
|--------|------------------------------|------------------------------------------|
| 235576 | Abdelrahman Almakhzangy      | Abdelrahman235576@bue.edu.eg             |
| 234742 | Ahmed Ali Abdallah           | Ahmed234742@bue.edu.eg                   |
| 236264 | Hala Emad Gaber              | Hala236264@bue.edu.eg                    |
| 230036 | Manar Hisham                 | Manar230036@bue.edu.eg                   |
| 235697 | Mohamed Hussien              | Mohamed235697@bue.edu.eg                 |
| 235174 | Hossam Rashad                | Hossam235174@bue.edu.eg                  |

---

## 🚀 Getting Started

1. **Clone the repo**  
   ```bash
   git clone https://github.com/Dev-Abdelrahman-Almakhzangy/Computer-Service-Support-System.git
   cd Computer-Service-Support-System
   ```

2. **Open the report**  
   - Review `Phase 3 Report – Software Engineering I – Group 3.pdf` in `/docs/`

3. **Implementation**  
   - Front-end and back-end code modules to follow course guidelines (not included here)

---

## 🤝 Contributing

This is a course deliverable. For updates or improvements, please contact the project authors via BUE email.

---

## 📜 License

This project was developed for educational purposes at the British University in Egypt as part of the Introduction to Software Engineering course.
