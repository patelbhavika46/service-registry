# service-registry

This microservice acts as a **Service Registry** (e.g., Eureka Server) for service discovery in the Quiz Application.

## Features

- Registers all microservices
- Enables dynamic discovery and load balancing

## Tech Stack

- Java Spring Boot
- Netflix Eureka Server

## Getting Started

1. Build: `mvn clean install`
2. Run: `mvn spring-boot:run`
3. Service runs on default port (e.g., `8761`).

## Usage

- All microservices register themselves with the service registry.