# 🎓 Thesis Management System

A web-based application for managing thesis projects, built with **Spring MVC** (backend) and **ReactJS** (frontend).  
This system helps administrators, faculty, and students manage graduation theses more efficiently.

---

## Features

### User Management
- Admin manages user accounts and assigns roles (student, lecturer, faculty officer).
- Users can change their passwords after account creation.
- Each account must include an avatar.

### Thesis Management
- Faculty officer registers new theses, including:
  - Thesis title
  - Students participating
  - Supervisors (up to 2 lecturers)

### Reviewer Assignment
- Faculty officer assigns reviewers for each thesis.
- Reviewers receive email/SMS notifications.

### Defense Committee Management
- Faculty officer creates defense committees (3–5 members):
  - Chairman
  - Secretary
  - Reviewer
  - Other members (optional)
- Each committee can evaluate up to 5 theses.

### Grading
- Lecturers log in and score based on predefined criteria.
- System automatically calculates average score per thesis.
- All scores must be confirmed before finalizing.
- Once finalized, scores cannot be edited.

### Reporting & Statistics
- Admin and faculty officers can view statistics:
  - Thesis scores by year
  - Participation rate per department
- Export thesis result reports to **PDF**.

### Notifications
- Students receive email notifications of their final thesis results.

---

## Tech Stack

- **Frontend**: ReactJS
- **Backend**: Spring MVC, Hibernate, MySQL
- **Other**: JWT Authentication, SendGrid

---

## Installation

### 1️⃣ Clone repository
```bash
git clone https://github.com/anhphapap/thesis-web.git
cd thesis-web
```

### 2️⃣ Setup backend
```bash
cd backend
mvn clean install
mvn spring-boot:run
```

### 3️⃣ Setup frontend
```bash
cd frontend
npm install
npm start
```

## Contributors
| Name         | GitHub                                       |
| ------------  | -------------------------------------------- |
| Pham Anh Pha | [@anhphapap](https://github.com/anhphapap)   |
| Nguyen Ho Vu | [@godreplyme](https://github.com/godreplyme) |
