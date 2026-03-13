Advanced Backend Masterclass: Go, Docker & Microservices
This repository contains a high-level backend project focused on scalability, security, and modern infrastructure. It demonstrates the implementation of a robust financial system (Simple Bank) using the most demanded technologies in the Go ecosystem.

🛠 Tech Stack & Modules
01. Database Persistence (PostgreSQL & SQLC)
Automated database migrations with golang-migrate.
Type-safe SQL execution using SQLC (Zero ORM approach for maximum performance).
Database design with indexing and relational integrity.

02. RESTful API & Security (Gin, JWT & PASETO)
High-performance routing with Gin Gonic.
Modern authentication using PASETO (Platform-Agnostic Security Tokens) and JWT.
Structured error handling and input validation.

03. Infrastructure & Cloud (Docker, Kubernetes & AWS)
Containerization of the entire stack with Docker and Docker Compose.
Deployment workflows and orchestration concepts.
Cloud-ready architecture for AWS environments.

04. Advanced Communication (Sessions & gRPC)
Implementation of gRPC for high-performance inter-service communication.
Session management and refresh token patterns for secure persistent logins.

05. Background Tasks & Caching (Asynq & Redis)
Distributed task queues using Asynq and Redis.
Asynchronous processing for heavy tasks (email sending, report generation).

06. Authorization & Production Ready (PGX, RBAC & CORS)
Advanced Postgres driver with PGX for connection pooling.
RBAC (Role-Based Access Control) for fine-grained authorization.
Security headers and CORS configuration for production environments.

🚀 Key Engineering Concepts
Clean Architecture: Clear separation of concerns between business logic and external drivers.
Transational Integrity: Implementing DB transactions to ensure data consistency in financial operations.
Unit & Integration Testing: High code coverage to ensure system reliability.
