# Email Sender Service API

Microservice for asynchronous email dispatch, template rendering, and notification queues.

## Features
- Asynchronous message processing for outgoing transactional emails.
- HTML template rendering and attachment handling.
- SMTP integration with configurable retry mechanisms.

## Tech Stack
- Java 21 LTS
- Spring Boot, Spring Mail
- RabbitMQ integration
- Maven Wrapper

## Running
```bash
./mvnw clean compile
./mvnw spring-boot:run
```
