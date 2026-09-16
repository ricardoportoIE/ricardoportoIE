<div align="center">

# Ricardo Porto

### Software Engineer · Backend · Cloud · Production-Oriented Systems

I build software with a strong focus on **backend architecture, cloud infrastructure, security, observability, testing and reliable delivery**.

My portfolio is built around real engineering problems rather than isolated demos: each project is designed to show how I think about **system design, trade-offs, deployment, maintainability and production readiness**.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Ricardo%20Porto-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/ricardoportoie/)
[![GitHub](https://img.shields.io/badge/GitHub-ricardoportoIE-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/ricardoportoIE)

</div>

---

## Featured Engineering Work

### 1. Job Application Tracker

**Production-oriented full-stack platform for tracking job applications, companies, interviews and hiring pipelines.**

[![Repository](https://img.shields.io/badge/Repository-View%20Project-181717?style=flat-square&logo=github)](https://github.com/ricardoportoIE/job-application-tracker)
[![Backend CI](https://github.com/ricardoportoIE/job-application-tracker/actions/workflows/backend-ci.yml/badge.svg)](https://github.com/ricardoportoIE/job-application-tracker/actions/workflows/backend-ci.yml)
[![Frontend CI](https://github.com/ricardoportoIE/job-application-tracker/actions/workflows/frontend-ci.yml/badge.svg)](https://github.com/ricardoportoIE/job-application-tracker/actions/workflows/frontend-ci.yml)
[![Terraform CI](https://github.com/ricardoportoIE/job-application-tracker/actions/workflows/terraform-ci.yml/badge.svg)](https://github.com/ricardoportoIE/job-application-tracker/actions/workflows/terraform-ci.yml)
[![Docker CI](https://github.com/ricardoportoIE/job-application-tracker/actions/workflows/docker-ci.yml/badge.svg)](https://github.com/ricardoportoIE/job-application-tracker/actions/workflows/docker-ci.yml)

**What it demonstrates**

- FastAPI REST API with JWT authentication and user-scoped resource ownership
- PostgreSQL 17, SQLAlchemy and Alembic migrations
- React + TypeScript frontend
- Dockerized full-stack delivery
- Terraform-based AWS infrastructure
- ECS Fargate, RDS, ECR, ALB, ACM, Route 53 and Secrets Manager
- Private ECS/RDS networking and least-privilege runtime database access
- Structured logging, request IDs, health checks and Prometheus metrics
- Immutable ECR deployments using Git commit SHA tags
- Four independent GitHub Actions quality gates
- Real AWS deployment validation with captured operational evidence
- Cost-aware teardown after validation

**Validated production path**

```text
Cloudflare DNS
    |
    v
Route 53
    |
    v
ACM + HTTPS ALB
    |
    v
ECS Fargate
    |
    v
FastAPI
    |
    v
Private PostgreSQL RDS
```

The environment was deployed, validated end to end, exercised through real authentication and persistence flows, documented with evidence, and then destroyed with Terraform to avoid unnecessary ongoing cost.

**Core stack**

`Python 3.14` · `FastAPI` · `PostgreSQL 17` · `SQLAlchemy` · `Alembic` · `React` · `TypeScript` · `Docker` · `Terraform` · `AWS ECS Fargate` · `RDS` · `ECR` · `ALB` · `Route 53` · `ACM` · `Secrets Manager` · `Prometheus` · `GitHub Actions`

---

### 2. GDA — Environmental Reporting Platform

**Modernised environmental reporting platform focused on secure web engineering, geospatial data and automated quality.**

[![Repository](https://img.shields.io/badge/Repository-View%20Project-181717?style=flat-square&logo=github)](https://github.com/ricardoportoIE/gda-environmental-reporting-platform)
[![CI](https://github.com/ricardoportoIE/gda-environmental-reporting-platform/actions/workflows/ci.yml/badge.svg)](https://github.com/ricardoportoIE/gda-environmental-reporting-platform/actions/workflows/ci.yml)
[![Release](https://img.shields.io/github/v/release/ricardoportoIE/gda-environmental-reporting-platform)](https://github.com/ricardoportoIE/gda-environmental-reporting-platform/releases)
[![Licence: MIT](https://img.shields.io/badge/Licence-MIT-2ea44f.svg)](https://github.com/ricardoportoIE/gda-environmental-reporting-platform/blob/main/LICENSE)

**What it demonstrates**

- Django + Django REST Framework backend
- React + TypeScript frontend
- PostgreSQL + PostGIS geospatial data
- Redis-backed application support
- Session authentication and CSRF protection
- Role-based and object-level authorisation
- Evidence upload validation
- Auditable workflow transitions
- Structured request logging and correlation IDs
- Liveness and readiness endpoints
- Vitest, Testing Library and Playwright
- Accessibility validation with axe-core
- Coverage enforcement and security checks
- Nginx, Docker Compose and GitHub Actions
- Versioned release workflow

**Quality profile**

- Backend test coverage above 80%
- Frontend automated coverage
- Playwright end-to-end journeys
- Accessibility scanning
- OpenAPI validation
- Type checking with MyPy and TypeScript
- Dependency and secret scanning

**Core stack**

`Python` · `Django` · `Django REST Framework` · `PostgreSQL` · `PostGIS` · `Redis` · `React` · `TypeScript` · `Vite` · `Leaflet` · `Nginx` · `Docker` · `Playwright` · `Vitest` · `GitHub Actions`

---

## What I Bring Across Projects

| Area | Practical focus |
|---|---|
| **Backend engineering** | API design, domain services, authentication, authorization, migrations, validation |
| **Cloud engineering** | AWS networking, ECS, RDS, ECR, ALB, ACM, Route 53, Secrets Manager |
| **Infrastructure as Code** | Terraform, reproducible environments, cost-aware architecture |
| **Databases** | PostgreSQL, relational modelling, indexing, PostGIS, migration strategy |
| **Security** | Least privilege, private networking, JWT/session auth, CSRF, hardened containers |
| **Testing** | Pytest, Vitest, Testing Library, Playwright, integration and end-to-end validation |
| **Observability** | Structured logging, request IDs, health/readiness checks, Prometheus metrics |
| **Delivery** | Docker, Docker Compose, CI quality gates, immutable deployments, release workflows |
| **Engineering practice** | ADRs, explicit trade-offs, production-readiness thinking, documentation |

---

## Technology Stack

### Backend

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Django](https://img.shields.io/badge/Django-092E20?style=flat-square&logo=django&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)

### Frontend

![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white)

### Cloud & DevOps

![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-844FBA?style=flat-square&logo=terraform&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=flat-square&logo=nginx&logoColor=white)

### Quality & Engineering

`REST APIs` · `SQLAlchemy` · `Pydantic` · `Alembic` · `PostGIS` · `pytest` · `Vitest` · `Playwright` · `Testing Library` · `Ruff` · `MyPy` · `ESLint` · `OpenAPI` · `Prometheus` · `Git`

---

## Engineering Principles

I try to make portfolio projects reflect the way production software is actually built.

That means I care about:

- correctness before unnecessary complexity
- secure defaults
- explicit ownership and authorization boundaries
- automated quality gates
- reproducible infrastructure
- observability from the beginning
- documentation of architectural decisions
- measurable validation instead of unsupported claims
- realistic cost and operational trade-offs

---

## Current Focus

I'm continuing to deepen my experience in:

- Backend Engineering
- Cloud-native application design
- AWS architecture
- Infrastructure as Code
- PostgreSQL and data modelling
- Observability and reliability
- Distributed systems
- Performance engineering
- Applied AI and automation

---

## Portfolio Direction

The portfolio is being developed as a set of complementary engineering case studies rather than repeated CRUD applications.

| Project | Primary engineering focus | Status |
|---|---|---|
| **Job Application Tracker** | Backend, AWS, Terraform, production delivery | ✅ Published |
| **GDA Environmental Reporting Platform** | Full-stack, geospatial, security, automated quality | ✅ Published |
| **CloudOps Monitoring Platform** | Cloud operations and observability | Planned |
| **Enterprise Knowledge Search** | Search, retrieval and applied AI | Planned |
| **Real-Time Risk & Fraud Detection Platform** | Distributed systems and ML | Planned |
| **Intelligent Incident Detection & Response System** | Streaming, observability and automation | Planned |

---

## Opportunities

I'm interested in opportunities where I can contribute to real engineering problems involving:

**Software Engineering · Backend Engineering · Cloud Engineering · Platform / DevOps-oriented work**

Particularly in **Ireland and the UK**.

---

## Connect

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/ricardoportoie/)
[![GitHub](https://img.shields.io/badge/GitHub-Follow-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/ricardoportoIE)

---

<div align="center">

**Building software that is designed, tested, deployed and explained — not just coded.**

</div>
