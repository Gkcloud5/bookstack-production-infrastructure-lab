# BookStack Production Infrastructure Lab

## 1. Project Overview

This project is a hands-on infrastructure learning project based on the open-source BookStack application.

The goal is to take BookStack from a source-code repository and progressively transform it into a containerized, secured, tested, monitored, documented, and cloud-deployed system.

The project is designed to develop practical skills for Cloud Engineer, Linux Infrastructure Engineer, and Senior Systems Engineer roles.

## 2. Project Philosophy

The project follows this learning cycle:

```text
Understand
    ↓
Build
    ↓
Test
    ↓
Break
    ↓
Investigate
    ↓
Fix
    ↓
Verify
    ↓
Document
    ↓
Improve
```

The objective is not to memorize commands.

The objective is to understand how an infrastructure engineer operates an application.

## 3. Application

The selected open-source application for this project is:

**BookStack**

Repository:

https://github.com/BookStackApp/BookStack

BookStack will be treated as the real application that we are responsible for running, securing, monitoring, troubleshooting, and recovering.

## 4. Planned Learning Progression

```text
BookStack Repository
        ↓
Understand Application
        ↓
Run Locally
        ↓
Containerize
        ↓
Docker Compose
        ↓
Networking
        ↓
Persistent Storage
        ↓
Security
        ↓
Failure Testing
        ↓
Troubleshooting
        ↓
Monitoring & Logging
        ↓
CI/CD
        ↓
Cloud Deployment
        ↓
Backup & Recovery
        ↓
Production Review
```

## 5. Initial Architecture

The initial learning environment is planned around a Linux host running the application stack.

The expected architecture is:

```text
User
  ↓
Linux Host / VM
  ↓
Docker
  ↓
Docker Compose
  ├── BookStack Application
  └── Database
          ↓
    Persistent Storage
```

This is a preliminary architecture.

The actual BookStack architecture, dependencies, database requirements, ports, configuration, and storage requirements will be determined during Phase 1.

## 6. Project Scope

The project will cover:

- Linux
- Git and GitHub
- Docker
- Docker Compose
- Networking
- Persistent storage
- Security
- Troubleshooting
- Health checks
- Logging
- Monitoring
- CI/CD
- Cloud deployment
- Backup and recovery
- Technical documentation
- Learning documentation
- Interview preparation

## 7. Current Status

**Current Phase:** Phase 0 — Project Preparation

**Application:** BookStack

**Next Phase:** Phase 1 — Understand the Application

## 8. Important Principle

This project is not simply a Docker project.

The goal is to learn how to take responsibility for running an application:

- How does it work?
- What does it depend on?
- Where does the data live?
- How does traffic reach it?
- What can fail?
- How do we detect failures?
- How do we troubleshoot them?
- How do we secure the system?
- How do we recover it?
- How do we safely deploy changes?

The project should grow in complexity only after the previous layer is understood.