## Hexagonal RBAC Starter 

A Golang starter template built using Hexagonal Architecture, designed to provide a clean foundation for authorization and authentication-related features.

## Current Status

- RBAC domain and application services implemented
- Database layer and adapters are still a work in progress

## Planned Features

- Role-Based Access Control (RBAC)
- JWT-based authentication
- One-Time Passwords (OTP)
- Multi-Factor Authentication (MFA)

## Architecture

This project follows a Hexagonal (Ports and Adapters) architecture to keep business logic independent from external concerns such as databases, frameworks, and delivery mechanisms.

The core consists of domain logic and application use cases. Interactions with external systems occur through ports (interfaces), which are implemented by adapters.

All dependencies point inward — external layers (HTTP, database, messaging) depend on the application core, never the other way around.
