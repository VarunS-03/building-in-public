### 1. REPOSITORY NAME
FORGE — Founder Intelligence Operating System (FIOS)--- **Repository:** https://github.com/VarunS-03/FORGE

### 2. WHAT IT IS ABOUT
FORGE is an evidence-driven intelligence platform designed to help founders discover, evaluate, and prioritize business opportunities using structured information from public sources.

The system is being developed as a modular TypeScript monorepo with planned collectors, intelligence engines, persistence services, worker processes, APIs, and dashboard applications.

### 3. WHY I AM DOING IT
Founders often spend significant time manually collecting fragmented information, comparing competitors, evaluating demand, and assessing whether an opportunity is technically and commercially viable.

FORGE addresses this problem through a planned evidence pipeline that transforms public information into structured signals, analytical evidence, and explainable opportunity assessments. During August 2026, the project advanced from architectural documentation into implemented core infrastructure, providing practical experience in monorepo design, typed configuration, observability, event-driven communication, automated testing, and ORM integration.

### 4. HOW I AM DOING IT (PUBLIC TECHNICAL SPECIFICATION)

- **High-Level System Architecture:** 
        The project follows a modular monolith architecture with separate application, package, collector, and engine boundaries. The implemented foundation includes a configuration package, core logging, an immutable event model, an in-process event bus, and an initial Prisma/PostgreSQL persistence configuration. API, dashboard, worker, collector, and intelligence-engine directories are established as future implementation boundaries.

- **Tech Stack & Tooling:** 
        TypeScript, Node.js, pnpm workspaces, ES modules, TypeScript strict mode, Vitest, Prisma 7, and PostgreSQL configuration. The repository also contains architectural specifications for future API, dashboard, automation, and deployment layers.

- **Engineering Principles:** 
        Modular package boundaries, public package exports, immutable configuration and events, structured observability, environment-based configuration, sensitive-value redaction, explicit validation, testable components, and incremental milestone-based development. The project is designed to support future event-driven processing and independently replaceable collectors and analytical engines.

### 5. ADDITIONAL PROJECT METRICS & STATUS

- **Development Status:** Active Development — Phase 1 Complete (Work in Progress)

- **Current Phase Target:** Complete the persistence layer by defining domain schemas, implementing migrations and repositories, and validating CRUD operations against the documented data model.
