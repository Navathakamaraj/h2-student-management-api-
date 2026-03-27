# Student Management System API 🎓

[![Java](https://img.shields.io/badge/Java-17-orange.svg)](https://www.oracle.com/java/)
[![Spring Boot](https://img.shields.io/badge/Spring%20Boot-3.x-green.svg)](https://spring.io/projects/spring-boot)
[![Database](https://img.shields.io/badge/Database-H2%20%7C%20MS%20SQL-blue.svg)](https://www.microsoft.com/en-us/sql-server/)

A robust **RESTful Backend API** built using **Spring Boot** and **Java** to manage student records. This project demonstrates a clean implementation of the **3-tier architecture** (Controller, Service, Repository) with persistent data storage and industry-standard design patterns.



## 🚀 Key Features
* **Full CRUD Lifecycle:** End-to-end support for creating, reading, updating, and deleting student records.
* **3-Tier Architecture:** High maintainability through clear separation of Web, Business Logic, and Data Access layers.
* **Data Persistence:** Uses **Spring Data JPA** and **Hibernate** for automated ORM (Object-Relational Mapping).
* **Enterprise Ready:** Dual-database configuration for **H2** (Fast Development) and **Microsoft SQL Server** (Production).

## 🏗️ System Architecture
The application follows the standard Spring Boot request-response flow:
1. **Controller Layer:** Handles HTTP requests and maps JSON to Java Objects.
2. **Service Layer:** Contains business logic and service-level validations.
3. **Repository Layer:** Communicates with the database using JPA/Hibernate.

## 🛠️ Tech Stack
* **Backend:** Java 17, Spring Boot 3.x
* **Security & Data:** Hibernate, Spring Data JPA
* **Build Tool:** Maven
* **Databases:** H2 (In-memory), Microsoft SQL Server
* **API Documentation & Testing:** Postman

## 🚦 Getting Started
1. **Clone the repository:**
   ```bash
   git clone [https://github.com/Navathakamaraj/h2-student-management-api-.git](https://github.com/Navathakamaraj/h2-student-management-api-.git)
