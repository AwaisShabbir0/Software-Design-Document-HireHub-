# Job Portal System (HireHub)

This project is a console-based **Job Portal System** implemented in **C++**, demonstrating key **Object-Oriented Programming (OOP)** concepts, **SOLID principles**, and **Design Patterns**. The system supports roles such as **Admin**, **Employer**, **JobSeeker**, and **Freelancer**, with operations like posting jobs, applying for jobs, uploading CVs, and more.

---

## 📌 Features

- User registration and authentication
- Job posting, editing, and deletion
- Job application and CV management
- Admin controls for reporting and user management
- Freelancer hiring and portfolio tracking

---

## 🧠 Applied SOLID Principles

| Principle | Applied To | Purpose |
|----------|-------------|---------|
| **SRP** (Single Responsibility Principle) | Each class has one clear purpose (e.g., `CVManager`, `JobPostingService`) | Keeps code modular and easy to maintain |
| **OCP** (Open/Closed Principle) | Interfaces like `IAuthenticationService`, `IJobPostingService` | New functionality can be added without changing existing code |
| **ISP** (Interface Segregation Principle) | Role-specific interfaces like `JobSeekerActions`, `EmployerActions` | Prevents roles from depending on unused methods |
| **DIP** (Dependency Inversion Principle) | High-level classes depend on abstractions (`ICVManager`, `IJobPostingService`) | Improves flexibility, testability, and decoupling |

---

## 🎯 Applied Design Patterns

| Pattern | Purpose | Where Used |
|--------|---------|------------|
| **Factory Method** | Abstracts object creation logic | For creating user roles dynamically |
| **Adapter** | Converts one interface to another for compatibility | Could be used to integrate third-party CV format validators |
| **Bridge** | Decouples abstraction from implementation | Separates user roles from job services in future scalability |
| **Command** | Encapsulates requests as objects | For tracking user actions (e.g., ApplyJobCommand) — extendable in future

---
## Credits
Developed by **Awais Shabbir (me)** in collaboration with mate **Owais Awan**
As part of the ***Software Design & Architecture course.***

