# 🚀 EasyByte-Microservices

> A modern Java Microservices project built using Spring Boot and Spring Cloud following enterprise-level architecture and best practices.

![Java](https://img.shields.io/badge/Java-21-orange)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-3.x-brightgreen)
![Spring Cloud](https://img.shields.io/badge/Spring_Cloud-2025-blue)
![Maven](https://img.shields.io/badge/Maven-Build-red)
![License](https://img.shields.io/badge/License-MIT-green)

---

# 📖 Project Overview

**EasyByte-Microservices** is a complete Microservices-based backend application developed using **Spring Boot** and **Spring Cloud**.

The primary objective of this project is to learn and implement enterprise-level Microservices architecture, where every service is developed, deployed, and maintained independently.

This project demonstrates modern backend development concepts including:

- Microservices Architecture
- RESTful APIs
- Service Discovery
- API Gateway
- Configuration Management
- Distributed Communication
- Fault Tolerance
- Security
- Monitoring
- Docker Containerization

---

# 🎯 Project Objectives

✔ Learn Enterprise Microservices Architecture

✔ Build Independent Services

✔ Implement Spring Cloud Components

✔ Develop REST APIs

✔ Practice Production Ready Development

✔ Deploy Scalable Applications

---

# 🏗 Project Architecture

```
                Client
                   │
                   ▼
           API Gateway
                   │
      ┌────────────┼─────────────┐
      ▼            ▼             ▼

 Account Service  Loan Service  Card Service
      │            │             │
      └────────────┼─────────────┘
                   ▼
             Config Server
                   │
                   ▼
          Eureka Discovery Server
```

---

# 🛠 Technologies Used

| Technology | Version |
|------------|----------|
| Java | 21 |
| Spring Boot | 3.x |
| Spring Cloud | Latest |
| Maven | Latest |
| REST API | ✔ |
| Spring Data JPA | ✔ |
| Hibernate | ✔ |
| MySQL | ✔ |
| PostgreSQL | Optional |
| H2 Database | Development |
| Eureka Server | ✔ |
| Config Server | ✔ |
| API Gateway | ✔ |
| OpenFeign | ✔ |
| Circuit Breaker | Resilience4J |
| Docker | ✔ |
| Docker Compose | ✔ |
| Kubernetes | Learning |
| Git | ✔ |
| GitHub | ✔ |
| IntelliJ IDEA | ✔ |

---

# 📂 Project Structure

```
EasyByte-Microservices
│
├── Account Service
├── Loan Service
├── Card Service
├── Config Server
├── Eureka Server
├── API Gateway
├── Shared Configurations
├── Docker Files
├── Kubernetes Files
└── Documentation
```

---

# ✨ Features

- ✅ Spring Boot Microservices
- ✅ REST APIs
- ✅ API Gateway
- ✅ Eureka Service Discovery
- ✅ Config Server
- ✅ External Configuration
- ✅ Spring Data JPA
- ✅ MySQL Database
- ✅ OpenFeign Client
- ✅ Circuit Breaker
- ✅ Retry Mechanism
- ✅ Rate Limiting
- ✅ Distributed Configuration
- ✅ Centralized Logging
- ✅ Docker Support
- ✅ Production Ready Architecture

---

# 📌 Modules

### 🏦 Account Service

- Create Account
- Update Account
- Delete Account
- Fetch Account Details

---

### 💳 Card Service

- Create Card
- Card Details
- Update Card
- Delete Card

---

### 💰 Loan Service

- Create Loan
- Loan Details
- Update Loan
- Delete Loan

---

# ⚙ Prerequisites

Before running this project install:

- Java 21
- IntelliJ IDEA
- Maven
- MySQL
- Git
- Docker Desktop

---

# 🚀 Installation

Clone Repository

```bash
git clone https://github.com/ankitkumarme14/EasyByte-Microservices.git
```

Go to Project

```bash
cd EasyByte-Microservices
```

Build Project

```bash
mvn clean install
```

Run Application

```bash
mvn spring-boot:run
```

---

# 🌐 REST API Example

Create Account

```
POST /api/accounts
```

Fetch Account

```
GET /api/accounts/{id}
```

Update Account

```
PUT /api/accounts/{id}
```

Delete Account

```
DELETE /api/accounts/{id}
```

---

# 📸 Screenshots

Add screenshots of:

- IntelliJ Project
- Swagger UI
- Eureka Dashboard
- API Gateway
- Postman Collection

---

# 📈 Future Enhancements

- JWT Authentication
- Spring Security
- OAuth2
- Kafka Messaging
- RabbitMQ
- Kubernetes Deployment
- Jenkins CI/CD
- SonarQube
- Prometheus
- Grafana
- ELK Stack

---

# 🤝 Contributing

Contributions are welcome.

1. Fork the repository
2. Create your feature branch
3. Commit your changes
4. Push the branch
5. Open a Pull Request

---

# 📚 Learning Outcomes

This project helps developers understand:

- Microservices Architecture
- Spring Boot
- Spring Cloud
- REST APIs
- Service Discovery
- API Gateway
- Docker
- Kubernetes
- Distributed Systems
- Enterprise Application Development

---

# 👨‍💻 Author

**Ankit Kumar**

GitHub:
https://github.com/ankitkumarme14

---

# ⭐ Support

If you found this project useful,

⭐ Star this repository

🍴 Fork this repository

📢 Share it with others

---

## Thank You ❤️

Happy Coding 🚀
