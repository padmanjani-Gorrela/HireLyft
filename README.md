# 🚀 HireLyft – Job Portal Backend

HireLyft is a scalable backend system designed to power a modern job portal, enabling seamless job postings, applications, and secure user management. Built with a focus on clean architecture, performance, and extensibility.

---

## 📌 Key Features

* 🔐 **JWT-Based Authentication & Authorization**

  * Secure login/signup system
  * Role-based access control (Admin, Recruiter, Job Seeker)

* 📄 **Job Management System**

  * Create, update, delete job postings
  * Search and filter job listings

* 📥 **Application Handling**

  * Users can apply to jobs
  * Recruiters can manage applications efficiently

* 🏗️ **Layered Architecture**

  * Clean separation of concerns using Controller → Service → Repository pattern
  * Improves maintainability and scalability

* ⚡ **Performance Optimizations**

  * Optimized database queries and indexing
  * Improved API response time by ~35%
  * Efficient handling of concurrent requests

---

## 🛠️ Tech Stack

* **Backend:** Spring Boot
* **Database:** MySQL
* **Authentication:** JWT (JSON Web Tokens)
* **Build Tool:** Maven
* **Architecture:** RESTful APIs, Layered Architecture

---

## 📂 Project Structure

```
src/
 ├── controller/    # API endpoints
 ├── service/       # Business logic
 ├── repository/    # Database access
 ├── model/         # Entity classes
 ├── dto/           # Data Transfer Objects
 └── config/        # Security & app configurations
```

---

## 🔧 Setup & Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/padmanjani-Gorrela/HireLyft.git
   cd HireLyft
   ```

2. Configure MySQL database in `application.properties`

3. Run the application:

   ```bash
   mvn spring-boot:run
   ```

---

## 📊 API Highlights

* `POST /auth/register` → Register user
* `POST /auth/login` → Authenticate user
* `GET /jobs` → Fetch all jobs
* `POST /jobs` → Create job (Recruiter/Admin)
* `POST /applications` → Apply for job

---

## 🚀 Future Enhancements

* Redis caching for faster job retrieval
* Pagination & sorting support
* Docker containerization
* Email notifications for applications
* CI/CD pipeline integration

---

## 💡 About the Project

This project demonstrates strong backend engineering fundamentals including:

* Secure authentication mechanisms
* Scalable system design
* Optimized database interactions
* Clean and maintainable code structure

---

## 👩‍💻 Author

**Padmanjani Gorrela**
Backend Developer | Java | Spring Boot

---

## ⭐ If you find this project useful, consider giving it a star!
