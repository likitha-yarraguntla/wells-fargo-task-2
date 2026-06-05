Wells Fargo Software Development Job Simulation – Task 2
📌 Project Overview

This repository contains my implementation of Task 2 – Implement a Data Model from the Wells Fargo Software Development Job Simulation offered through Forage.

The objective of this task was to design and implement a scalable data model using Java Persistence API (JPA) and Spring Boot, translating a real-world business scenario into a relational database structure. The solution focuses on creating entity relationships, applying object-relational mapping (ORM) principles, and following industry-standard software development practices.

🛠️ Technologies Used
Java
Spring Boot
Spring Data JPA
Hibernate ORM
Maven
Git & GitHub
Relational Database Concepts
Object-Oriented Programming (OOP)
🚀 Features Implemented
Financial Advisor Management
Created entity models for Financial Advisors
Supported advisor-to-client relationships
Client Management
Implemented client entity structure
Established associations between clients and portfolios
Portfolio Management
Designed portfolio entities for storing investment information
Maintained one-to-one relationships with clients
Security Management
Implemented securities with attributes including:
Security Name
Category
Purchase Date
Purchase Price
Quantity
📚 Key Learning Outcomes
Java Persistence API (JPA)
Implemented entity mapping using:
@Entity
@Id
@GeneratedValue
@OneToMany
@OneToOne
Database Design
Converted an Entity Relationship Diagram (ERD) into a functional JPA data model
Applied relational database design principles
Object-Oriented Design
Developed maintainable Java classes using encapsulation
Implemented constructors, getters, and setters following best practices
Version Control
Managed project changes using Git and GitHub
Practiced repository management and code commits
🗂️ Data Model

The application consists of the following entities:

FinancialAdvisor
Client
Portfolio
Security
Relationships
One Financial Advisor → Many Clients
One Client → One Portfolio
One Portfolio → Many Securities
📁 Project Structure
src/main/java/com/wellsfargo/counselor
│
├── entity
│   ├── FinancialAdvisor.java
│   ├── Client.java
│   ├── Portfolio.java
│   └── Security.java
│
└── Application Files

pom.xml
