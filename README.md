# 🏥 Patient Management Microservices

A microservices-based **Patient Management System** built with **Spring Boot**, designed to manage healthcare data efficiently. The system follows a modular approach with multiple independent services communicating via REST APIs or messaging queues.

## 📦 Microservices Overview

| Service Name       | Description                                        | Port |
|--------------------|----------------------------------------------------|------|
| `patient-service`  | Manages patient records and profiles               | 8081 |
| `doctor-service`   | Manages doctor data and availability               | 8082 |
| `appointment-service` | Handles appointment booking and scheduling     | 8083 |
| `discovery-server` | Eureka server for service discovery                | 8761 |
| `api-gateway`      | Centralized gateway for routing and security       | 8080 |
| `config-server`    | Centralized external configuration management      | 8888 |

> Optional:
> - `notification-service`: Sends email/SMS notifications
> - `billing-service`: Manages patient billing and invoices

---

## ⚙️ Tech Stack

- **Java 17**
- **Spring Boot 3.x**
- **Spring Cloud** (Eureka, Config, Gateway)
- **Spring Data JPA**
- **MySQL/PostgreSQL**
- **RabbitMQ/Kafka** *(optional for async communication)*
- **Docker + Docker Compose**
- **Swagger/OpenAPI** for API documentation

---

## 🚀 Getting Started

### Prerequisites

- Java 17+
- Maven
- Docker (optional but recommended)
- MySQL/PostgreSQL instance running (or use Docker)

### Clone the Repository

```bash
git clone https://github.com/yourusername/patient-management-system.git
cd patient-management-system
