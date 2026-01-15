## Overview
Backend API for managing orders with business rules and clean architecture.

## Business Rules
- Orders start with CREATED status
- Orders without items cannot be paid
- Canceled orders cannot change state
- Total amount is calculated in the backend

## Tech Stack
- Java 21
- Spring Boot
- Spring Data JPA
- PostgreSQL

## Architecture
- Domain-driven design
- Service layer for business use cases
- Controllers only handle HTTP concerns
