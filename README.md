# University Idea Management System (UIMS)

## COMP1640 – Enterprise Web Software Development  
**Group Coursework**

---

## 📌 Project Overview

The **University Idea Management System (UIMS)** is a secure, role-based, web-enabled application designed to collect, manage, and evaluate ideas for improvement submitted by staff members within a large university.

The system supports anonymous idea submission, structured categorisation, commenting, voting, reporting, and statistical analysis, while ensuring appropriate access control and data security.  
It has been developed following **Agile Scrum methodologies** in line with the COMP1640 coursework requirements.

---

## 🎯 Project Objectives

- Provide a secure platform for staff to submit improvement ideas
- Support role-based access control (RBAC)
- Enable anonymous participation while maintaining accountability
- Facilitate quality assurance workflows at department and university level
- Generate meaningful reports and statistics for decision-making
- Demonstrate enterprise-level web application development practices

---

## 👥 User Roles

| Role | Description |
|----|----|
| **Administrator** | Maintains system data such as staff accounts and closure dates |
| **QA Manager** | Oversees the entire idea collection process, manages categories, exports data |
| **QA Coordinator** | Manages and encourages idea submissions within their department |
| **Staff** | Submits ideas, comments, and votes on ideas |

---

## 🔑 Key Features

### 📝 Idea Submission
- Staff can submit one or more ideas
- Terms and Conditions acceptance is required before submission
- Optional document upload to support ideas
- Ideas can be submitted anonymously
- Ideas are tagged with one or more categories

---

### 🏷 Category Management
- QA Manager can add new categories
- Categories can only be deleted if they have not been used

---

### 💬 Interaction
- All staff can view all submitted ideas
- Commenting on ideas is enabled (anonymous or non-anonymous)
- Thumbs Up / Thumbs Down voting (limited to one vote per idea per user)

---

### ⏰ Closure Dates
- New idea submissions are disabled after the idea closure date
- Comments are disabled after the final closure date

---

### 📧 Notifications
- QA Coordinators receive email notifications when new ideas are submitted in their department
- Idea authors receive email notifications when comments are added to their ideas

---

### 📊 Reporting & Statistics
- Most Popular Ideas
- Most Viewed Ideas
- Latest Ideas
- Latest Comments
- Paginated idea lists (5 ideas per page)
- Statistical reports including:
  - Number of ideas per department
  - Percentage of ideas per department
  - Number of contributors per department
- Exception reports:
  - Ideas without comments
  - Anonymous ideas and comments

---

### 📤 Data Export
- QA Manager can export:
  - All system data in CSV format
  - All uploaded documents as a ZIP file after final closure date

---

### 📱 Responsive Design
- Fully responsive interface for:
  - Mobile phones
  - Tablets
  - Desktop devices
- Designed with usability and accessibility in mind

---

## 🗄 Database Design

The database follows a **relational model** with:
- Normalised tables
- Referential integrity enforced via foreign keys
- Support for role-based access control
- Support for anonymous content with secure author tracking

Key entities include:
- Users
- Roles
- Departments
- Ideas
- Categories
- Comments
- Votes
- Uploads
- Terms Acceptance

An Entity Relationship Diagram (ERD) is included in the repository.

---

## ⚙️ Technology Stack

> *(Adjust this section if required)*

- **Frontend**: HTML, CSS, JavaScript (React / Next.js)
- **Backend**: Node.js / Django / Laravel
- **Database**: MySQL / PostgreSQL
- **Authentication**: Role-based authentication
- **Version Control**: Git & GitHub
- **Email Service**: SMTP / Mail API

---

## 🧪 Testing

- Test Plan and Test Log included
- Functional, integration, and user acceptance testing conducted
- Test cases mapped to user stories in the product backlog

---

## 🔄 Agile Scrum Process

The project was developed using **Agile Scrum**, including:
- Product Backlog
- User Stories
- Sprint Planning
- Sprint Reviews
- Burn Down Charts
- Meeting Minutes

All Scrum artefacts are available in this repository.

---

## 🎥 Screencast & Presentation

- A Panopto screencast demonstrating key system functionality
- A presentation aimed at a non-technical audience to promote the system

> 🔗 Screencast URL: *(Add link here)*  
> 🔗 Live System URL: *(Add link here)*

---

## 📂 Repository Structure

/docs
├── ERD
├── UML Diagrams
├── Test Plan & Test Log
├── Meeting Minutes
/src
├── Frontend
├── Backend
/README.md

---

## 📌 Assumptions

- All staff members are pre-registered in the system
- Each staff member belongs to one department
- Voting is limited to one vote per idea per user
- Anonymous submissions store author details securely for investigation if required

---

## 👨‍💻 Team Members & Roles

| Name | Role |
|----|----|
| Student A | Scrum Master |
| Student B | Backend Developer |
| Student C | Database Designer |
| Student D | Frontend Developer |
| Student E | Tester |

---

## 📄 Licence

This project was developed for academic purposes as part of the COMP1640 coursework.

---

## ✅ Status

✔ Core features implemented  
✔ Database completed  
✔ Testing conducted  
✔ Documentation completed  
