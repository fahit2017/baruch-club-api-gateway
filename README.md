# Baruch Club API Gateway

This project provides a simple Spring Cloud Gateway configuration for routing requests to microservices. It registers with a Eureka server and exposes routes for student, club and event services.

## Building

Use the Maven wrapper to build the project:

```bash
./mvnw package
```

## Running

Run the application with:

```bash
./mvnw spring-boot:run
```

The gateway starts on port `8765` and requires a running Eureka server at `http://localhost:8761/eureka`.
