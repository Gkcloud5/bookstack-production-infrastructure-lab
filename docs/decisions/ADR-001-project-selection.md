# ADR-001 — BookStack Project Selection

## Status

Accepted

## Date

2026-10-01

## Decision

Use **BookStack** as the open-source application for the infrastructure learning project.

## Application Repository

https://github.com/BookStackApp/BookStack

## Context

The purpose of this project is to learn infrastructure engineering by operating a real open-source application rather than building a small toy application.

The application will be used as the foundation for learning:

- Linux infrastructure
- Docker
- Docker Compose
- Networking
- Storage
- Security
- Troubleshooting
- Monitoring
- CI/CD
- Cloud deployment
- Backup and recovery

## Decision Rationale

BookStack has been selected as the application for this learning project.

The project will first study the application's repository and documentation before making infrastructure decisions.

The following details will be determined during Phase 1:

- Application architecture
- Runtime requirements
- Dependencies
- Database requirements
- Configuration
- Network ports
- Persistent data
- Startup process

## Alternatives

Other open-source applications could have been selected.

However, BookStack is the selected application for this project.

## Consequences

### Positive

- The project is based on a real open-source application.
- Infrastructure concepts can be learned through an actual workload.
- The project can progressively evolve from local development to cloud deployment.
- Troubleshooting and failure scenarios can be performed against a realistic system.
- The final project can serve as a portfolio and interview-learning project.

### Negative

- The application may introduce dependencies and complexity that must be understood.
- Some infrastructure decisions cannot be finalized until the application is analyzed.
- The project may require additional infrastructure as learning progresses.

## Next Step

Complete Phase 1 by analyzing the BookStack repository and determining its actual technical requirements.