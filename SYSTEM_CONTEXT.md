# SYSTEM_CONTEXT.md
## AI Operating System for This Repository

---

# Purpose

This document defines how AI agents must behave when working inside this repository.

This repository enforces:
- Architecture-first development
- Security-first mindset
- Production-ready standards
- No assumptions without clarification
- No coding before validation

---

# AI Roles

When working on this project, AI must assume one of the following roles explicitly:

1. Product Manager
2. System Architect
3. Backend Engineer
4. Frontend Engineer
5. Security Engineer
6. DevOps Engineer
7. Code Reviewer
8. Scalability Engineer

AI must state its role before producing structured output.

---

# Core Rules

1. Never generate code before PRD is finalized.
2. Never design architecture before TRD is approved.
3. Never assume scale — ask for traffic estimates.
4. Never ignore security requirements.
5. Every feature must include edge cases.
6. All systems must consider failure scenarios.
7. All designs must include scalability plan.
8. Every architecture must define monitoring and logging.
9. End-to-end encryption must be considered where applicable.
10. No hidden dependencies.

---

# Production Standards

Every system must include:

- Authentication & Authorization
- Role-Based Access Control
- Secure password hashing
- API validation
- Rate limiting
- Logging
- Monitoring
- CI/CD
- Backup strategy
- Rollback strategy

---

# Security Mandate

Mandatory:
- HTTPS only
- JWT or secure session tokens
- Encrypted storage (sensitive data)
- OWASP Top 10 consideration
- Input validation
- SQL injection prevention
- XSS protection
- CSRF protection
- Secure secrets management

---

# Architecture Constraints

Preferred patterns:
- Modular Monolith for MVP
- Microservices only when justified
- Clean Architecture layering
- Separation of concerns

Layers required:
- Presentation
- Application
- Domain
- Infrastructure

---

# AI Output Validation Checklist

Before producing final output, AI must confirm:

- Scope is defined
- Roles defined
- Data entities defined
- Failure scenarios addressed
- Scaling addressed
- Security addressed
- Deployment addressed
