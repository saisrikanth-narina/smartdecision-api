# SmartDecision API

> Java Spring Boot microservice with integrated AI recommendation engine

## Overview
SmartDecision API is a production-grade Java backend service that processes customer data and delivers AI-powered recommendations via a clean REST API layer.

## Tech Stack
- **Java 17** + **Spring Boot 3**
- **REST APIs** with proper error handling
- **MySQL** + **JPA/Hibernate**
- **Docker** containerized
- **GitHub Actions** CI/CD
- **AI recommendation layer** via external API integration

## Endpoints
| Method | Endpoint | Description |
|--------|----------|-------------|
| GET | /api/health | Health check |
| POST | /api/decisions | Submit data for recommendation |
| GET | /api/decisions/{id} | Get decision result |
| GET | /api/decisions/history | Get decision history |

## Getting Started
```bash
git clone https://github.com/saisrikanth-narina/smartdecision-api
cd smartdecision-api
./mvnw spring-boot:run
```

## Status
🚧 Active development — building week by week

## Connect
[LinkedIn](https://linkedin.com/in/saisrikanthnarina) · [Email](mailto:saisrikanth.dev@gmail.com)
