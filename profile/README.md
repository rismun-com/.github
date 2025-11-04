
<p align="center">
  <img src="assets/rismun-logo-en.svg" alt="Rismun" width="220" />
  <br />
  <a href="README.fa.md">فارسی</a> · <a href="README.ar.md">العربية</a> · <a href="README.md">English</a>
</p>

# Rismun

Rismun is an Iranian software company (est. 2009 / 1388) that builds mission‑critical digital platforms for enterprises and the public sector. We specialize in microservices and micro‑frontend architectures, API‑first systems, and secure data workflows that run on‑premises or in private/hybrid clouds. Our teams blend product thinking with rigorous engineering to deliver reliable, observable, and privacy‑aware software at scale.


## Company at a Glance
- Persian name: پردازش اطلاعات ریسمان
- Domains: e‑government platforms, enterprise automation, financial/administrative systems
- Differentiators: standards‑driven architecture, strong delivery discipline, bilingual (FA/AR/EN) and RTL support


## What We Do
- Platform engineering
  - Rismun Digital Platform accelerators: identity & access, workflow/BPMS, forms, documents, notifications, integration hub.
- Product development
  - Discovery → UX/UI → build → deploy → run; measurable outcomes with SLIs/SLOs and release cadences.
- Microservices and micro‑frontends
  - Domain‑driven design, event‑driven systems, API gateway and service mesh, independent scaling and deployments.
- Integration and interoperability
  - REST/GraphQL/gRPC, messaging, webhooks, and CDC pipelines; connectors for ERP/CRM/Tax and government systems.
- Workflow and automation
  - BPMN‑style modeling, SLAs, e‑signature, audit trails; compliant processes for regulated domains.
- Data and AI enablement
  - Streaming pipelines, search/analytics, BI exports; AI‑assisted intake and retrieval‑augmented search where appropriate.
- Cloud and DevOps
  - Containers, CI/CD, IaC, Kubernetes operations; progressive delivery and environment parity.
- Security and governance
  - OIDC, RBAC/ABAC, encryption in transit/at rest, auditing; privacy‑by‑design and least‑privilege access.
- Training and support
  - Enablement, documentation, and long‑term maintenance to ensure successful adoption.


## Flagship Products and Solutions
- Rismun Digital Platform (RDP)
  - Unified foundation of microservices and micro‑frontends providing identity & access, workflow, forms, documents, notifications, audit, and an integration hub.
  - Tech: micro‑frontends (Next.js, module federation), microservices (.NET, Node.js/NestJS), gRPC for internal calls, REST/GraphQL at the edge, Kafka/RabbitMQ, PostgreSQL/MongoDB/Redis, OpenSearch, S3‑compatible object storage, API gateway, service mesh, OIDC, OpenTelemetry.

- RISAPP Low‑Code Forms & Process
  - WYSIWYG designer, schema‑driven forms, rule engine, multi‑step flows, versioning, rollout/feature flags, offline/PWA, mobile‑ready.
  - Tech: Next.js micro‑frontends, Node.js/NestJS or .NET backends, GraphQL gateway, gRPC inter‑service, JSON Schema, PostgreSQL + MongoDB, Redis cache.

- Office Automation & Workflow (BPMS)
  - BPMN‑style modeling, correspondence, task routing, SLAs and escalations, e‑signature, PKI/HSM integration, DMS, comprehensive audit.
  - Tech: .NET services, micro‑frontends, gRPC, Kafka events, OpenSearch for full‑text, S3‑compatible document store.

- Human Resources Management System (HRMS)
  - Employee master data, onboarding, payroll alignment, leave/attendance, performance, self‑service; multi‑tenant with localization and strong access controls.
  - Tech: .NET microservices, Next.js micro‑frontends, PostgreSQL, Redis, RabbitMQ; OIDC; GraphQL API.

- Electronic Document & Records Management (EDRMS)
  - Ingestion, OCR/classification, retention and legal holds, versioning, access control, collaboration, secure backups, zero‑trust sharing; vector search.
  - Tech: OpenSearch/Elasticsearch, S3‑compatible storage, Kafka for indexing pipelines, .NET/Node.js services, Next.js micro‑frontends.

- Omnichannel Messaging & Notifications
  - SMS, email, push, in‑app messaging; templates and localization; rate limiting, delivery receipts, multi‑provider failover; webhooks and events.
  - Tech: Node.js services, Kafka/RabbitMQ, REST webhooks, OIDC, OpenTelemetry.

- Integration Hub & API Gateway
  - Connectors for ERP/CRM/Tax systems; REST/GraphQL APIs; gRPC bridging; change‑data‑capture with Debezium; transformation and scheduling; secrets management; service mesh.
  - Tech: API gateway, GraphQL federation, gRPC proxy, Kafka, PostgreSQL, Vault, Istio/Linkerd.

- Data & Analytics Foundation
  - Operational reporting, near‑real‑time pipelines, materialized views, BI exports, data catalog and lineage; CDC pipelines from source systems.
  - Tech: Kafka streams, PostgreSQL, OpenSearch, object storage.

- Optional modules and R&D (hypothetical)
  - AI‑assisted forms and document extraction, retrieval‑augmented search over archives, anomaly detection on financial events, conversational helpdesk.
  - Tech: vector databases, embedding pipelines, on‑prem or private‑cloud models, guardrail middleware, privacy‑by‑design.


## Representative Projects
- Bisti Mobile App — unified app for events, messaging, ticketing, correspondence, and bill payments.
  - Tech Stack: React Native (TypeScript) + Web Portal (Next.js), NestJS microservices (Node.js), gRPC (internal) + REST/GraphQL (external), PostgreSQL, Redis cache; Docker/Kubernetes; OIDC; OpenTelemetry.

- Doctor Saze — building inspection and engineering assessment platform.
  - Tech Stack: Next.js (React + TypeScript) micro‑frontend, NestJS microservices (Node.js), gRPC + REST gateway, PostgreSQL, OpenSearch for content/search, S3‑compatible storage; GitHub Actions CI/CD.

- Bank Mellat Branch Form Designer (RISAPP) — digital banking workflows and low‑code form design.
  - Tech Stack: Micro‑frontends (Next.js, federated modules), .NET microservices (C#) + gRPC, API gateway (REST/OpenAPI), Kafka for events, MongoDB for dynamic form definitions, PostgreSQL for transactional data, Redis; Helm/Kustomize on Kubernetes.

- HR Management — Iran Post — centralized personnel and HR processes.
  - Tech Stack: .NET microservices (minimal APIs), internal gRPC, Next.js micro‑frontends, PostgreSQL, RabbitMQ for work queues, RBAC/ABAC with Keycloak (OIDC), dashboards via Grafana.

- Accounting Documents — TCEO — automated fee calculation and accounting reports.
  - Tech Stack: .NET services, event‑driven processing (Kafka), PostgreSQL, OLAP/BI exports, audit trails and immutable logs; observability with OpenTelemetry + Prometheus/Grafana.

- Office Automation — IRIR Railways — enterprise correspondence, workflow (BPMS) redesign.
  - Tech Stack: Micro‑frontends (Next.js), .NET microservices, gRPC for inter‑service, Elasticsearch for full‑text/document search, S3‑compatible document store, Keycloak for SSO/OIDC; multi‑env deployments on Kubernetes.


## Engineering Practices
- Architecture: modular services, clean boundaries, API‑first design; SPA front‑ends with typed contracts where appropriate.
- Quality: automated testing (unit/integration), code reviews, static analysis, and CI for repeatable builds.
- Delivery: incremental releases, environment parity, and observable deployments.
- Security: role‑based access control, least‑privilege data access, audit trails, and secure coding practices.
- Observability: structured logging and actionable metrics for operations and support.


## Technology Matrix
- Preferred
  - Backend: .NET (ASP.NET Core), C#; Node.js (NestJS/Express)
  - APIs: REST with OpenAPI, GraphQL, gRPC, WebSocket
  - Frontend: React + TypeScript; Next.js (App Router), Vite
  - UI: Tailwind CSS, Material UI; design tokens and Storybook
  - State/Data: React Query/RTK Query; React Hook Form; Zod for validation
  - Mobile: React Native (TypeScript), native modules when needed
  - Data: SQL Server, PostgreSQL, MongoDB; Redis for caching
  - Search/Analytics: Elasticsearch/OpenSearch, SQL BI exports
  - Messaging: RabbitMQ (work queues), Apache Kafka (event streams)
  - AuthN/Z: OAuth2/OIDC (Keycloak, Azure AD), JWT, RBAC/ABAC
  - DevOps: Docker, Kubernetes, GitHub Actions; Helm/Kustomize; Terraform (IaC)
  - Observability: OpenTelemetry, Prometheus, Grafana, ELK/OpenSearch

## Contact
- Website: https://rismun.ir
- Email: info@rismun.ir
- Address: Valiasr Street, No. 2361, Tehran, Iran
- Phone: +98 21 88178400, +98 21 88178500
- Fax: +98 21 88178500
- Business Hours: Saturday–Wednesday 09:00–17:00 (Thu/Fri closed)


## Social
- GitHub: https://github.com/rismun-com
- Instagram: https://www.instagram.com/rismuntech/
- Facebook: https://facebook.com/rismunco
- Twitter: https://twitter.com/rismunco


## Careers and Demo
- Careers: Job listings are embedded on the website.
- Request a Demo: Contact us to schedule a tailored walkthrough of your use case.

## Copyright
© All rights reserved by Rismun.
