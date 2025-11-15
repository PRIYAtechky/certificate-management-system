# Certificate Management System

This project is an **Angular-based Certificate Management Module** that integrates with a **Spring Boot backend** and **PostgreSQL database**.  
It enables efficient handling of student certificates with operations for adding, viewing, updating, and deleting records.

##  Features

- Add, view, update, and delete certificates  
- Integration with Spring Boot REST APIs  
- Responsive and user-friendly interface  
- Clean table layout with icons and date formatting  
- Angular Material for form styling and UI enhancements  


## Tech Stack

<p align="left">
  <img src="https://img.shields.io/badge/Angular-DD0031?style=for-the-badge&logo=angular&logoColor=white" alt="Angular" />
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white" alt="TypeScript" />
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5" />
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3" />
  <img src="https://img.shields.io/badge/Spring%20Boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white" alt="Spring Boot" />
  <img src="https://img.shields.io/badge/PostgreSQL-336791?style=for-the-badge&logo=postgresql&logoColor=white" alt="PostgreSQL" />
</p>

| Component | Technology |
|------------|-------------|
| Frontend | Angular |
| Backend | Spring Boot |
| Database | PostgreSQL |
| Language | TypeScript, Java |
| Styling | CSS3 / Angular Material |


## How to Run the Angular App
### 1. Clone the repository

```bash
git clone https://github.com/PRIYAtechky/certificate-management-angular.git
cd certificate-management-angular
```

### 2. Install dependencies
```bash
npm install
```

### 3. Run the Angular application
```bash
ng serve
```
Open the app in your browser:

```bash
http://localhost:4200/
```

### 4. Ensure Backend is Running

Your Spring Boot backend should be active on:
```bash
http://localhost:8083/
```

### 5. Database Connection

The backend connects to PostgreSQL, so ensure it’s running and configured properly.

## How It Works

- The user interacts with the **Angular** interface to manage certificate details.

- The app sends requests to the **Spring Boot REST API** for CRUD operations.

- Data is stored and retrieved from the **PostgreSQL** database.

## Dependencies Used

**In Angular:**

* @angular/core

* @angular/forms

* @angular/material

* @angular/common/http

**In Spring Boot:**

* Spring Web

* Spring Data JPA

* PostgreSQL Driver

---

*Created and maintained by **Padmapriya** as part of the **TNSIF training program**.*
