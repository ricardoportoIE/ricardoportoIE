<div align="center">

# Ricardo Porto

### Software Engineer · Python & Java · Backend · Cloud

I build API-driven applications with **Python, Java and React**, focusing on secure business workflows, relational data, automated testing and reproducible delivery.

**Based in Dublin, Ireland · Interested in software and backend engineering opportunities in Ireland and the UK**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/ricardoportoie/)

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Java](https://img.shields.io/badge/Java-21-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white)

</div>

## Portfolio at a glance

Three complementary case studies, with source code, tests and engineering documentation.

| Project | Business problem | Engineering evidence |
| --- | --- | --- |
| [**Resource Lending API**](https://github.com/ricardoportoIE/resource-lending-api) | Manage shared assets, loans and reservation queues | Java/Spring, concurrency control, transactional workflows, Outbox and observability |
| [**Job Application Tracker**](https://github.com/ricardoportoIE/job-application-tracker) | Organise applications, companies and hiring timelines | Python/FastAPI, user isolation, Terraform and a validated AWS deployment |
| [**GDA Environmental Reporting**](https://github.com/ricardoportoIE/gda-environmental-reporting-platform) | Submit, locate and review environmental reports | Django/React, PostGIS, access control, end-to-end and accessibility testing |

## Featured engineering work

### Resource Lending API
**Java 21 · Spring Boot · Spring Security · PostgreSQL · React · TypeScript**

[![CI](https://github.com/ricardoportoIE/resource-lending-api/actions/workflows/ci.yml/badge.svg)](https://github.com/ricardoportoIE/resource-lending-api/actions/workflows/ci.yml)

A modernised academic application for lending individually tracked assets, with a borrower console and staff operations dashboard.

- **Domain correctness:** explicit loan state transitions, role-based policies, FIFO reservations and audit events.
- **Concurrency:** pessimistic locking and database constraints, backed by PostgreSQL Testcontainers tests for simultaneous claims.
- **Reliable commands and integration:** persistent idempotency keys, response replay and transactional Outbox notifications with retries.
- **Security and visibility:** access-token revocation, rotating refresh tokens, recovery flows, OpenTelemetry, Prometheus, Grafana and Jaeger.
- **Verification:** JUnit, MockMvc, JaCoCo, Vitest, Testing Library and accessibility checks, with container builds and security workflows.

**Scope:** a modular monolith, not a microservices deployment. Cloud hosting, shared rate limiting and a production email provider remain extension points.

[Explore the code](https://github.com/ricardoportoIE/resource-lending-api) · [Architecture](https://github.com/ricardoportoIE/resource-lending-api/blob/main/docs/architecture.md) · [Testing strategy](https://github.com/ricardoportoIE/resource-lending-api/blob/main/docs/testing.md) · [Threat model](https://github.com/ricardoportoIE/resource-lending-api/blob/main/docs/threat-model.md)

### Job Application Tracker
**Python · FastAPI · PostgreSQL · React · TypeScript · AWS · Terraform**

[![Backend CI](https://github.com/ricardoportoIE/job-application-tracker/actions/workflows/backend-ci.yml/badge.svg)](https://github.com/ricardoportoIE/job-application-tracker/actions/workflows/backend-ci.yml)
[![Terraform CI](https://github.com/ricardoportoIE/job-application-tracker/actions/workflows/terraform-ci.yml/badge.svg)](https://github.com/ricardoportoIE/job-application-tracker/actions/workflows/terraform-ci.yml)

A full-stack recruitment workflow application with an end-to-end cloud deployment case study.

- JWT authentication, user-scoped ownership, SQLAlchemy models and Alembic migrations.
- Terraform infrastructure with private ECS Fargate and PostgreSQL RDS, HTTPS ingress through ALB/ACM, ECR and Secrets Manager.
- Least-privilege runtime database access, hardened containers, structured logs and protected Prometheus metrics.
- Independent backend, frontend, Terraform and Docker quality gates.

**Deployment evidence:** deployed and validated in AWS `eu-west-1`, including authentication and database persistence. Infrastructure was then destroyed with Terraform to control cost; this is not an always-on demo.

[Explore the code](https://github.com/ricardoportoIE/job-application-tracker) · [AWS validation evidence](https://github.com/ricardoportoIE/job-application-tracker/tree/main/docs/evidence) · [Architecture decisions](https://github.com/ricardoportoIE/job-application-tracker/tree/main/docs/adr)

### GDA Environmental Reporting Platform
**Python · Django REST Framework · React · TypeScript · PostGIS · Redis**

[![CI](https://github.com/ricardoportoIE/gda-environmental-reporting-platform/actions/workflows/ci.yml/badge.svg)](https://github.com/ricardoportoIE/gda-environmental-reporting-platform/actions/workflows/ci.yml)

A rebuilt final-year project connecting public reporting with secure staff case management.

- PostGIS-backed locations, interactive maps and nearby-report queries.
- Session authentication, CSRF protection, object-level authorisation and validated evidence uploads.
- Controlled case transitions with auditable history.
- Backend and frontend coverage gates, Playwright journeys, accessibility checks and containerised delivery.

[Explore the code](https://github.com/ricardoportoIE/gda-environmental-reporting-platform) · [Validation record](https://github.com/ricardoportoIE/gda-environmental-reporting-platform/blob/main/docs/VALIDATION.md) · [Deployment guide](https://github.com/ricardoportoIE/gda-environmental-reporting-platform/blob/main/docs/DEPLOYMENT.md)

## Technical skills demonstrated

| Area | Technologies and practices |
| --- | --- |
| **Backend** | Python, Java, FastAPI, Django REST Framework, Spring Boot, Spring Data JPA, Hibernate, REST APIs, OpenAPI |
| **Frontend** | React, TypeScript, JavaScript, Vite, responsive interfaces, API integration |
| **Data** | SQL, PostgreSQL, PostGIS, Redis, SQLAlchemy, Alembic, Flyway, transactions and locking |
| **Security** | Spring Security, JWT, refresh-token rotation, RBAC, ownership checks, CSRF, least privilege |
| **Testing** | Pytest, JUnit, MockMvc, Testcontainers, JaCoCo, Vitest, Testing Library, Playwright, axe-core |
| **Cloud and delivery** | AWS ECS Fargate, RDS, ECR, ALB, ACM, Route 53, Secrets Manager, Terraform, Docker, Nginx, GitHub Actions |
| **Observability** | Structured logging, correlation IDs, health checks, Micrometer, OpenTelemetry, Prometheus, Grafana, Jaeger |
| **Engineering practice** | Modular monoliths, state machines, Outbox, idempotency, ADRs, threat modelling and documented trade-offs |

## How I approach engineering

I make transaction boundaries and access rules explicit, test failure paths alongside successful workflows, and document the reasoning behind architecture choices. Deployment evidence and known limitations are part of each case study.

My current learning interests include **performance engineering, distributed systems, applied AI and automation**. These are development directions, separate from the implemented portfolio evidence above.

## Let's connect

Interested in **Software Engineer, Backend Engineer and Full Stack Developer** roles, including opportunities involving cloud delivery and automation.

[Connect on LinkedIn](https://www.linkedin.com/in/ricardoportoie/) · [Browse my repositories](https://github.com/ricardoportoIE?tab=repositories)
