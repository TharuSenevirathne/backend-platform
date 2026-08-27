# Backend Platform - Ticket Tracker

Spring Cloud platform for IJSE Ticket Tracker (GCP).

| Service | Port | Description |
|---------|------|-------------|
| `eureka-server` | 8761 | Service registry |
| `config-server` | 8888 | Centralized config (native) |
| `api-gateway` | 8080 | API entry point |

## Stack

- Java 25
- Spring Boot 3.5.x
- Spring Cloud 2025.0.x

## Start order

1. eureka-server
2. config-server
3. api-gateway

```bash
cd eureka-server && mvn spring-boot:run
cd config-server && mvn spring-boot:run
cd api-gateway && mvn spring-boot:run
```

## Student

- Student Name: tharu senevirathne
- Student Number: 241711076
