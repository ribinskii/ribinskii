# Aleksandr Ribinski

**Python Backend Developer, 6+ years experience**  
Location: UTC+4 (Tbilisi, Georgia)

[![Telegram](https://img.shields.io/badge/Telegram-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white)](https://t.me/ribinski) [![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:aleksandr.riabinski@gmail.com) [![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/aleksander-ribinski) [![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/ribinski) [![Phone](https://img.shields.io/badge/Phone-%2B7%20(926)%20660--3633-007EC6?style=for-the-badge&logo=phone&logoColor=white)](tel:+79266603633)

---

## About Me

Python Backend Developer with 6+ years of commercial experience building and supporting production backend systems across fintech, edtech, and industrial domains.

Experienced in system architecture and end-to-end backend delivery: from business requirements and API contracts to data storage, integrations, observability, and production support.

Strongest at building backend systems that process business-critical data, automate internal workflows, integrate with external services, and stay reliable under production load.

---

## Technical Stack

### Backend & Frameworks
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white) ![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white) ![Django](https://img.shields.io/badge/Django-092E20?style=for-the-badge&logo=django&logoColor=white) ![Tornado](https://img.shields.io/badge/Tornado-092E20?style=for-the-badge) ![SQLAlchemy](https://img.shields.io/badge/SQLAlchemy-000000?style=for-the-badge&logo=sqlalchemy&logoColor=white) ![gRPC](https://img.shields.io/badge/gRPC-4285F4?style=for-the-badge) ![GraphQL](https://img.shields.io/badge/GraphQL-E10098?style=for-the-badge&logo=graphql&logoColor=white) ![REST API](https://img.shields.io/badge/REST%20API-FF6C37?style=for-the-badge)

### Databases & Storage
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white) ![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white) ![ClickHouse](https://img.shields.io/badge/ClickHouse-FFCC01?style=for-the-badge&logo=clickhouse&logoColor=black) ![OpenSearch](https://img.shields.io/badge/OpenSearch-005EB8?style=for-the-badge&logo=opensearch&logoColor=white) ![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white) ![GreenPlum](https://img.shields.io/badge/GreenPlum-00A98F?style=for-the-badge)

### Messaging, Infrastructure & Observability
![Kafka](https://img.shields.io/badge/Kafka-231F20?style=for-the-badge&logo=apachekafka&logoColor=white) ![RabbitMQ](https://img.shields.io/badge/RabbitMQ-FF6600?style=for-the-badge&logo=rabbitmq&logoColor=white) ![Celery](https://img.shields.io/badge/Celery-37814A?style=for-the-badge) ![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white) ![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white) ![OpenShift](https://img.shields.io/badge/OpenShift-EE0000?style=for-the-badge&logo=redhatopenshift&logoColor=white) ![Helm](https://img.shields.io/badge/Helm-0F1689?style=for-the-badge&logo=helm&logoColor=white) ![Grafana](https://img.shields.io/badge/Grafana-F46800?style=for-the-badge&logo=grafana&logoColor=white) ![Arize Phoenix](https://img.shields.io/badge/Arize%20Phoenix-000000?style=for-the-badge)

### AI, LLM & Data
![LangChain](https://img.shields.io/badge/LangChain-000000?style=for-the-badge) ![LangGraph](https://img.shields.io/badge/LangGraph-000000?style=for-the-badge) ![RAG](https://img.shields.io/badge/RAG-5A4FCF?style=for-the-badge) ![LLM](https://img.shields.io/badge/LLM-111827?style=for-the-badge) ![OpenSpec](https://img.shields.io/badge/OpenSpec-2563EB?style=for-the-badge) ![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white) ![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)

---

## Work Experience

### SBERBANK | October 2023 - Present
**Product:** Internal bank services

**Achievements:**
- Designed and built an autonomous AI incident-investigation agent for a 30+ microservice banking product, reducing production issue investigation from hours or occasionally days to minutes by analyzing centralized logs, retrieving service and code context, identifying likely root causes, and sending messenger alerts with incident summaries and recommended fixes.
- Implemented and evangelized Spec-Driven Development using OpenSpec, establishing specification-first pipelines across team services so user stories, bugs, and releases were consistently designed, validated, and delivered from explicit technical specs.
- Implemented and evangelized end-to-end AI-agent tracing with Arize Phoenix across the team, instrumenting 10+ production services with structured spans for agent runs, LLM calls, tool execution, retrieval steps, external service calls, retries, and errors.
- Designed and built an internal LangChain wrapper library for bank LLM integrations, standardizing retries, circuit breakers, timeouts, structured-output validation, automatic response repair, fallback behavior, prompt metadata, sensitive-data masking, and Redis-backed distributed concurrency counters.
- Implemented production RAG pipelines for analytical reports and internal bank news, consuming content through Kafka, normalizing and chunking documents, generating embeddings, and indexing knowledge sources for semantic search.
- Implemented AI-powered code review automation in the internal bank repository platform, triggering an internal review agent for every pull request to analyze diffs, detect risky changes, validate team conventions, and publish actionable feedback directly in the PR.
- Created and promoted a standardized service bootstrap template for new microservices across the team and adjacent teams, embedding production-ready defaults for logging, metrics, clean architecture, internal libraries, OpenSpec specifications, uv-based dependency management, Docker setup, and base configuration.

**Technologies:** Python, Go, FastAPI, gRPC, GraphQL, Grafana, Helm, LangChain, LangGraph, PostgreSQL, BitBucket, Jenkins, SonarQube, Docker, Kubernetes, OpenShift, MongoDB, GreenPlum, Redis, Kafka, SMTP, OpenSearch, ClickHouse

---

### VK | December 2020 - October 2023
**Product:** Tetrika, an online platform for exam preparation and school performance improvement

**Achievements:**
- Developed backend features for the Lesson Constructor, enabling tutors to assemble interactive lesson programs from a shared library of methodist-prepared materials; reduced lesson preparation time, improved content reuse, and helped standardize lesson quality.
- Created backend functionality for mini-group lessons, extending lesson, schedule, and billing logic from one-to-one tutoring to group-based classes; enabled a lower-cost learning format and kept teacher schedules, student enrollment, and lesson accounting consistent.
- Developed backend APIs for the student and parent personal account redesign, supporting schedule, lesson materials, homework, lesson balance, purchase history, and payment status data.
- Implemented backend functionality for purchasing lesson packages, connecting package selection, payment processing, installment payments, lesson balance updates, and purchase history into a consistent billing flow.
- Developed backend functionality for lesson rescheduling and cancellation workflows, synchronizing schedule changes with lesson statuses, notifications, student balances, and teacher availability.

**Technologies:** Python, Tornado, FastAPI, PostgreSQL, Docker, Kubernetes, Redis, SQLAlchemy, gRPC, Kafka, aiohttp, pyjwt, bcrypt, pandas, numpy, Cassandra, RabbitMQ, Celery, MongoDB, GraphQL, WebSockets, Aioboto3, S3, httpx, Twilio, aiosmtplib

---

### ROSTEC | November 2019 - December 2020
**Product:** Digital manufacturing management platform

The platform helped industrial enterprises digitize production workflows: technologists created manufacturing process cards, planners built production plans, operators executed work on equipment, machines sent status events, and managers tracked production history through dashboards and reports.

**Achievements:**
- Developed early backend modules for digital production passports, enabling engineers to store structured manufacturing data, production stages, materials, equipment references, and operation history in a unified system.
- Developed backend APIs for managing manufacturing process cards, allowing technologists to define ordered production operations, required materials, equipment, operation duration, and document versions.
- Built backend APIs for equipment monitoring dashboards, processing machine status events and exposing current state, downtime, workload, and error metrics.
- Implemented asynchronous processing for production planning and reporting tasks with Celery and RabbitMQ, moving long-running workload calculations and report generation out of HTTP requests.

**Technologies:** Python, Django, PostgreSQL, Redis, Celery, RabbitMQ, Linux, Bash, Marshmallow, Docker, requests, pandas, matplotlib, numpy, gRPC

---

## Education

**Moscow Aviation Institute, Moscow, Russia**  
Bachelor's Degree in Information and Computer Science  
2018 - 2022

---

## PDF Resume

[![PDF Resume](https://img.shields.io/badge/PDF%20Resume-FF0000?style=for-the-badge&logo=adobeacrobatreader&logoColor=white)](./resume.pdf)
