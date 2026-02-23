# Secure Messaging Platform

A modular monolith real-time messaging backend built with Java Spring Boot.

## Purpose

This project is built to practice and demonstrate:

- Secure authentication and authorization (JWT, BCrypt)
- Real-time communication using WebSockets
- Redis-based message broadcasting
- HTTPS and secure API design
- Modular monolith architecture
- Dockerized multi-service deployment
- Professional testing practices

## Architectural Style

Modular Monolith:
- Cleanly separated feature modules
- Single deployable Spring Boot application
- External services: PostgreSQL, Redis

## Architecture Decision Rationale

A modular monolith was chosen to maintain simplicity while enforcing clean separation of features.
This allows scalable architecture without premature microservice complexity.

## Tech Stack (Planned)

- Java 17+
- Spring Boot
- Spring Security
- WebSocket (STOMP)
- PostgreSQL
- Redis
- Docker & Docker Compose
- JUnit & Mockito

## Project Status

Version 0.0 – Initial planning phase
