# 🌐 Website Architecture & DevOps Fundamentals

> "Every modern IT company runs on websites, applications, servers, and automation."
>
> Understanding how a website works from frontend → backend → database → deployment is the first step toward becoming a great DevOps Engineer.

---

# 📚 Table of Contents

1. What is a Website?
2. How Websites Make Money
3. Types of Website Architecture
4. Three Tier Architecture
5. Frontend
6. Backend
7. Database
8. Complete Request Flow
9. JSON Format
10. Real Life Analogy
11. IDEs & Tools
12. GitHub Repositories
13. What is Deployment?
14. DevOps Engineer Role
15. DevOps Lifecycle
16. DevOps Related Domains
17. Interview Revision Notes
18. Final Summary

---

# 1️⃣ What is a Website?

A website is an online application accessible through the internet using a browser.

Examples:

- flipkart.com
- amazon.com
- jivansathi.com
- shadi.com

A website helps users:
- Buy products
- Use services
- Store data
- Communicate online
- Access applications

---

# 2️⃣ How Websites Make Money?

Websites generate revenue using:

| Method | Example |
|---|---|
| Product Selling | Flipkart |
| Subscription | Netflix |
| Advertisements | YouTube |
| Service Fees | Upwork |
| Premium Features | LinkedIn Premium |

---

# 3️⃣ Types of Website Architecture

There are mainly 3 types:

---

## 🔹 Single Tier Architecture

Everything exists in one system.

```text
Frontend + Backend + Database
```

### Example:
- Simple desktop applications
- Small local tools

### Advantages:
- Easy to build
- Cheap

### Disadvantages:
- Poor scalability
- Hard to maintain

---

## 🔹 Two Tier Architecture

Frontend separated from database/backend.

```text
Frontend ↔ Backend + Database
```

### Example:
- Small internal company applications

---

## 🔹 Three Tier Architecture (MOST IMPORTANT)

Used by modern applications.

```text
Frontend ↔ Backend ↔ Database
```

---

# 4️⃣ Three Tier Architecture

This is the core concept of modern web applications.

---

## 🔥 Architecture Diagram

```text
User
 ↓
Frontend
 ↓
Backend
 ↓
Database
```

Response comes back:

```text
Database
 ↑
Backend
 ↑
Frontend
 ↑
User
```

---

# 5️⃣ Frontend

Frontend is the visible part of a website that users interact with.

---

## 🖥️ Frontend Includes

- Buttons
- Images
- Login Pages
- Forms
- Sliders
- Navigation Bars
- Footer
- User Interface (UI)

---

## 🔧 Frontend Technologies

| Technology | Purpose |
|---|---|
| HTML | Structure |
| CSS | Styling |
| JavaScript | Logic |
| React | Modern UI |
| Angular | Framework |
| NextJS | React Framework |
| Vite | Fast Build Tool |

---

## 👨‍💻 Frontend Developer Responsibilities

- Build UI
- Improve user experience
- Create responsive design
- Connect frontend with backend APIs

---

## 🛠️ Frontend IDEs

- VSCode
- IntelliJ IDEA
- Android Studio
- Cursor

---

# 6️⃣ Backend

Backend is the brain of the application.

It handles:
- Logic
- Authentication
- Calculations
- APIs
- Data processing

---

## 🔥 Example

Suppose user enters:

```text
A = 10
B = 20
```

Backend performs:

```text
SUM = A + B
```

Then sends result back.

---

## 🔧 Backend Technologies

| Technology | Usage |
|---|---|
| Java | Enterprise Apps |
| Python | Automation & APIs |
| .NET | Microsoft Ecosystem |
| Go | High Performance |
| Rust | Secure Systems |

---

## 👨‍💻 Backend Developer Responsibilities

- Build APIs
- Handle business logic
- Connect database
- Manage authentication
- Process requests

---

## 🛠️ Backend IDEs

- PyCharm
- Eclipse
- Visual Studio

---

# 7️⃣ Database

Database stores application data permanently.

---

## 📦 Database Stores

- User Data
- Passwords
- Orders
- Messages
- Profiles
- Transactions

---

## 🔧 Database Technologies

| Database | Type |
|---|---|
| MySQL | Relational |
| PostgreSQL | Advanced Relational |
| MongoDB | NoSQL |

---

## 🛠️ Database Tools

- MySQL Workbench
- PGAdmin
- SSMS

---

# 8️⃣ Complete Request Flow

This is one of the MOST IMPORTANT concepts.

---

## 🔥 End-to-End Flow

```text
1. User clicks button on website
2. Frontend sends request
3. Backend receives request
4. Backend processes logic
5. Database stores/fetches data
6. Backend receives database response
7. Backend sends response to frontend
8. Frontend displays result to user
```

---

## 📌 Example

### User Action

```text
Enter Number A = 10
Enter Number B = 20
```

---

### Frontend

Collects user input.

---

### Backend

```python
sum = a + b
```

---

### Database

Stores result.

---

### Backend

Returns result.

---

### Frontend

Displays:

```text
Result = 30
```

---

# 9️⃣ JSON Format

Most backend systems communicate using JSON.

---

## 🔥 Example JSON

```json
{
  "name": "Akansha",
  "role": "DevOps Engineer",
  "experience": "Fresher"
}
```

---

## 📌 Why JSON?

- Lightweight
- Fast
- Easy to understand
- Universal format

---

# 🔟 Real Life Analogy (Hotel Example)

This analogy explains architecture deeply.

---

## 🍽️ Hotel Example

| Real World | Website Architecture |
|---|---|
| Customer | User |
| Table | Frontend |
| Manager | Backend |
| Kitchen | Database |

---

## 🔥 Explanation

### 🪑 Frontend = Table

User interacts here.

---

### 👨‍💼 Backend = Manager

Manager takes request and coordinates operations.

---

### 🍳 Database = Kitchen/Storage

Actual resources/data stored here.

---

# 1️⃣1️⃣ GitHub Repositories

## Frontend Repository

https://github.com/devopsinsiders/elearn-frontend

---

## Backend Repository

https://github.com/devopsinsiders/elearn-backend

---

# 1️⃣2️⃣ What is Deployment?

Deployment means:

> Running application code on servers so users can access it online.

---

## 🔥 Deployment Flow

```text
Developer writes code
        ↓
Code pushed to GitHub
        ↓
DevOps Engineer builds application
        ↓
Application deployed to server
        ↓
Website becomes live
```

---

# 1️⃣3️⃣ DevOps Engineer Role

A DevOps Engineer connects:

```text
Development + Operations
```

---

# 🔥 Main Responsibilities

## ✅ Code Deployment

Deploy applications to servers.

---

## ✅ Automation

Automate repetitive tasks.

---

## ✅ CI/CD Pipelines

Build automatic deployment systems.

---

## ✅ Monitoring

Monitor application health.

---

## ✅ Server Management

Manage Linux/cloud infrastructure.

---

## ✅ Scalability

Handle large traffic efficiently.

---

# 1️⃣4️⃣ Goal of DevOps

The PDF describes this beautifully:

---

# 💡 "Sasta, Sundar, Tikau"

| Word | Meaning |
|---|---|
| Sasta | Cost Efficient |
| Sundar | Fast & Smooth |
| Tikau | Stable & Reliable |

---

# 1️⃣5️⃣ DevOps Lifecycle

```text
PLAN
 ↓
DEVELOP
 ↓
BUILD
 ↓
TEST
 ↓
RELEASE
 ↓
DEPLOY
 ↓
OPERATE
 ↓
MONITOR
```

---

# 1️⃣6️⃣ Important DevOps Tools

| Tool | Purpose |
|---|---|
| Git | Version Control |
| GitHub | Code Hosting |
| Docker | Containerization |
| Kubernetes | Container Orchestration |
| Jenkins | CI/CD |
| Linux | Server OS |
| AWS | Cloud |
| Azure | Cloud |
| Terraform | Infrastructure Automation |
| Ansible | Configuration Management |

---

# 1️⃣7️⃣ DevOps Related Domains

| Domain | Meaning |
|---|---|
| DevOps | Development + Operations |
| DevSecOps | Security + DevOps |
| FinOps | Cloud Cost Optimization |
| MLOps | ML Deployment |
| AIOps | AI Based Operations |

---

# 1️⃣8️⃣ Important Interview Questions

---

## ❓ What is Three Tier Architecture?

### ✅ Answer

Three tier architecture separates frontend, backend, and database into independent layers for better scalability, maintainability, and security.

---

## ❓ What is Frontend?

### ✅ Answer

Frontend is the user-facing part of an application built using technologies like HTML, CSS, JavaScript, and React.

---

## ❓ What is Backend?

### ✅ Answer

Backend handles business logic, APIs, authentication, and database communication.

---

## ❓ What is Database?

### ✅ Answer

Database stores application data permanently and helps retrieve information efficiently.

---

## ❓ What does a DevOps Engineer do?

### ✅ Answer

A DevOps Engineer automates deployment, manages infrastructure, builds CI/CD pipelines, monitors systems, and ensures applications run reliably.

---

# 🎯 Final Revision Notes

```text
Website = Frontend + Backend + Database

Frontend:
UI layer
HTML CSS JS React

Backend:
Logic layer
Java Python Go .NET

Database:
Data storage
MySQL PostgreSQL MongoDB

Architecture:
Frontend ↔ Backend ↔ Database

DevOps:
Deployment
Automation
CI/CD
Monitoring
Cloud
Infrastructure

Goal:
Cost Efficient
Reliable
Scalable
Fast
```

---

# 🚀 Final Understanding

A modern application works like a complete ecosystem.

```text
Users interact with Frontend
Frontend communicates with Backend
Backend processes logic
Database stores information
DevOps Engineers deploy and manage everything
```

---

# 🏆 Golden Line

> "A great DevOps Engineer does not just deploy applications —
> they build reliable systems that scale, survive, and serve users continuously."

---