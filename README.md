# 🏥 Patient Management System – Microservices with Spring Boot

A microservices-based patient management system built using Java, Spring Boot, gRPC, Apache Kafka, PostgreSQL, and Docker. This project demonstrates how to design and implement a secure, event-driven, distributed system with modern Spring technologies.

## 🔹 What I Implemented

**Microservices Architecture** – Each service is independent and focused on a single responsibility.

- **Patient Service** – Handles core patient data management with PostgreSQL.
- **Billing Service** – Communicates via gRPC for efficient inter-service calls.
- **Notification Service** – Listens to Kafka topics and sends notifications asynchronously.
- **Auth Service** – Provides authentication and authorization using Spring Security + JWT.
- **API Gateway** – Built with Spring Cloud Gateway, routing requests securely after JWT validation.

## 🔹 Key Highlights

- **Designed a secure request flow:**
  ```
  Browser → API Gateway → JWT Validation → Target Microservice
  ```

- **Used Kafka as a message broker** to enable event-driven communication.

- **Integrated gRPC** for fast, lightweight inter-service communication.

- **Implemented JWT authentication** to secure APIs across services.

- **Containerized each service individually** with Docker for portability and consistency.

## 🔹 Tech Stack

- **Java 17** / **Spring Boot**
- **Spring Cloud Gateway** (API Gateway)
- **gRPC** for service-to-service communication
- **Apache Kafka** for asynchronous messaging
- **Spring Security + JWT** for authentication & authorization
- **PostgreSQL** as database
- **Docker** for containerization
