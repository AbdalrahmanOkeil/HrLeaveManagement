# HrLeaveManagement System

## 📌 Overview
This project is a **Leave Management System** built using **ASP.NET Core** following **Clean Architecture principles**.

It was developed as part of a learning journey to build scalable, maintainable, and production-like applications using modern .NET practices.

---

## 🎯 Learning Objectives
This project focuses on mastering:

- Clean Architecture
- CQRS Pattern
- MediatR
- Repository & Unit of Work Patterns
- API Integration
- Authentication & Authorization

---

## 🧠 Architecture
The project follows **Clean Architecture** and is divided into multiple layers:

- **Domain Layer** → Core business entities
- **Application Layer** → Business logic, CQRS, validation
- **Infrastructure Layer** → Database & external services
- **API Layer** → RESTful APIs

---

## 🛠️ Technologies Used
- ASP.NET Core (.NET 8)
- Entity Framework Core
- MediatR
- AutoMapper
- FluentValidation
- SQL Server
- NSwag / Swagger

---

## ✨ Features
- 👤 Authentication & Authorization
- 🏷️ Leave Types Management
- 📊 Leave Allocation System
- 📝 Leave Requests (Apply / Approve / Reject)
- 🧑‍💼 Role-based Access Control
- 🔄 API Integration
- ⚠️ Global Exception Handling
- 🧪 API Testing using Swagger

---

## 🔄 Implemented Concepts

- Clean Architecture
- CQRS (Command Query Responsibility Segregation)
- MediatR Pattern
- Repository Pattern
- Unit of Work Pattern
- Fluent Validation
- Custom Response Wrappers
- API Authentication (JWT)
- Database Seeding
- NSwag Client Generation

---

## ⚙️ Setup Instructions

1. Clone the repository:
```bash
git clone https://github.com/AbdalrahmanOkeil/HrLeaveManagement.git
```

2. Navigate to the project folder:
```bash
cd HrLeaveManagement
```

3. Configure your database connection in:
```
appsettings.json
```

4. Apply migrations:
```bash
dotnet ef database update
```

5. Run the project:
```bash
dotnet run
```

---

## 🔐 Notes
- Add your own database connection string.
- This project is **for educational purposes**.
