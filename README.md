# Andrey Zakharov

### Java Backend Developer

Moscow, Russia (Open to remote opportunities) | [andr.zax@gmail.com](mailto:andr.zax@gmail.com) | @andrzax | github.com/Andezahr

---

## About

Java Backend Developer with practical experience building backend applications using Java, Spring Boot, Kafka, and PostgreSQL. BMSTU graduate (2024) interested in distributed systems, event-driven architecture, and designing reliable business logic.

Developed a P2P crypto trading platform as a pet project, implementing asynchronous communication with Kafka, transactional outbox, and Telegram notifications. Comfortable working with modern Java, the Spring ecosystem, relational databases, and Docker. I enjoy understanding how systems work under the hood and continuously improving both code quality and architecture.

---

## Technical Skills

| Category         | Technologies                                                                       |
| :--------------- | :--------------------------------------------------------------------------------- |
| **Languages**    | Java (17/21/25), SQL, Python (Basic)                                               |
| **Frameworks**   | Spring Boot, Spring MVC, Spring Data JPA, Spring Security, Thymeleaf, Resilience4j |
| **Architecture** | REST API, Event-Driven Architecture, Domain-Driven Design (DDD), SOLID, OOP        |
| **Messaging**    | Apache Kafka, Transactional Outbox                                                 |
| **Databases**    | PostgreSQL, H2                                                                     |
| **Tools**        | Docker, Git, Maven, Swagger/OpenAPI, IntelliJ IDEA                                 |

---

## Projects

### P2P-OMS | Crypto-Fiat Trading Platform

Backend for a P2P cryptocurrency trading platform built around an event-driven architecture.

* Introduced **Kafka-based event delivery** using the **Transactional Outbox** pattern to guarantee reliable event publication after successful database transactions.
* Implemented **idempotent Kafka consumers** to safely process duplicate messages without affecting business state.
* Added **retry mechanisms with Resilience4j** to improve resilience against temporary infrastructure failures.
* Implemented **concurrency control** for critical order operations to prevent duplicate execution during simultaneous requests.
* Built **asynchronous Telegram notifications** triggered by order lifecycle events.

**Stack:** Java, Spring Boot, Apache Kafka, PostgreSQL, Docker, Resilience4j

---

### Charka | RPG Character Manager

Full-stack web application for managing tabletop RPG characters, inventories, notes, and game resources.

* Designed REST endpoints and server-rendered pages using **Spring MVC** and **Thymeleaf**.
* Implemented CRUD functionality for characters, inventory, notes, counters, and related game entities.
* Designed relational database models and entity relationships using **Spring Data JPA**.

**Stack:** Java, Spring Boot, Spring MVC, Thymeleaf, Spring Data JPA, PostgreSQL, H2

---

## Education

**Bauman Moscow State Technical University (BMSTU)**
Bachelor's Degree
Graduated: 2024

---

## Languages

* Russian — Native
* English — B2 (Upper-Intermediate)
