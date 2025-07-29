# LearnConnect API

**Personal project** focused on building a collaborative environment for questions, answers, and idea sharing between students and educators. Developed with a scalable architecture, strong engineering practices, and cloud service integration.

## Features

- **User registration and login** with JWT-based authentication
- **Topic and answer creation**, including **image uploads** via Cloudflare R2 (S3-compatible)
- **Event-driven notification system** for real-time updates
- **Content organization** using categories and tags
- **Data validation** with Zod
- **Automated testing**:
  - Unit tests with Vitest
  - End-to-end (E2E) tests using NestJS testing utilities

## Tech Stack

- **Backend:** Node.js, TypeScript, NestJS, Express
- **Database:** PostgreSQL, Prisma ORM
- **Cloud Storage:** Cloudflare R2 (S3-compatible)
- **Validation:** Zod
- **Testing:** Vitest (unit), NestJS testing tools (E2E), Postman (HTTP requests)

## Architecture & Practices

- **Clean Architecture** and **Domain-Driven Design (DDD)**
- **SOLID principles** and layered separation of concerns
- **Decoupled validation** using Zod schemas
- **Dependency Injection** for modularity and testability
- **Design Patterns** applied across services and controllers
