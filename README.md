<img width="1206" height="764" alt="Screenshot 2026-10-16 194444" src="https://github.com/user-attachments/assets/be316d84-163e-4a6b-9b2d-21668768ae7b" />
<img width="1187" height="732" alt="Screenshot 2026-10-16 194512" src="https://github.com/user-attachments/assets/c1e861c0-6952-41cb-971a-ede74f8125a3" />
<img width="1255" height="761" alt="Screenshot 2026-10-16 194604" src="https://github.com/user-attachments/assets/3aea51f6-9163-4317-9282-94abae438a08" />
<img width="1309" height="621" alt="Screenshot 2026-10-16 075627" src="https://github.com/user-attachments/assets/1934e98c-3088-4689-9098-3fde08029c90" />
<img width="1352" height="695" alt="Screenshot 2026-10-16 181528" src="https://github.com/user-attachments/assets/ccd7836d-b3b3-41aa-b0b7-c18075ba86e4" />
<img width="1361" height="765" alt="Screenshot 2026-10-16 061407" src="https://github.com/user-attachments/assets/31f1848a-b9b6-49ff-b10e-8e9ab145d403" />
# RaceDayAPI-Part2<img width="1358" height="762" alt="image" src="https://github.com/user-attachments/assets/4fa2a346-1584-4f42-b053-ed540623d86c" />
# RaceDayAPI – Part 2

## 1. Project Overview

RaceDayAPI is an ASP.NET Core Web API developed to manage race-day information. The API provides a backend for managing users, roles, events, categories, enrolments, and results using a SQL Server database.

This project builds on the database design from Part 1 and applies Entity Framework Core using the Code First approach. It also provides API endpoints that can be tested using Swagger.

## 2. Project Objectives

The main objectives of this project are to:

- Develop a RESTful API using ASP.NET Core.
- Connect the application to a Microsoft SQL Server database.
- Use Entity Framework Core for database access.
- Implement user registration and login functionality.
- Protect passwords using secure password hashing.
- Apply role-based authorization where required.
- Provide CRUD operations for the relevant resources.
- Test API endpoints using Swagger.
- Use Git and GitHub for source control.
- Configure automated build and test checks using GitHub Actions.

## 3. Technologies Used

- **Programming language:** C#
- **Framework:** ASP.NET Core Web API
- **Target framework:** .NET 10
- **Database:** Microsoft SQL Server
- **ORM:** Entity Framework Core
- **API documentation and testing:** Swagger / OpenAPI
- **Development environment:** Visual Studio Code
- **Version control:** Git and GitHub
- **Automation:** GitHub Actions

## 4. Main Features

### User Management
The API supports user-related operations, including registration and login, according to the implemented authentication functionality.

### Role Management
The application includes roles to support different levels of access. Role-based restrictions are applied to endpoints where configured.

### Event Management
The API supports operations for managing race-day events.

### Category Management
The API includes category-related functionality for organizing race-day information.

### Enrolment Management
The API supports managing enrolments associated with the race-day system.

### Results Management
The API includes functionality for managing race results.

### API Documentation
Swagger provides an interface for viewing and testing the API endpoints.

### Database Integration
Entity Framework Core connects the application to SQL Server and manages database access through the configured database context.

## 5. Database

The project uses a SQL Server database named `RaceDay`.

The database contains the following tables:

- `Users`
- `Roles`
- `Events`
- `Categories`
- `Enrolments`
- `Results`

The tables represent the main entities used by the application. Their relationships and constraints should correspond to the database design established in Part 1.

## 6. Prerequisites

Before running the project, ensure that you
