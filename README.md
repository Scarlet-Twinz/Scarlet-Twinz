# Anthony Emmanuella Mmasinachi

**Full-Stack & Systems Engineer · Backend & API Engineering · Distributed Systems · Networking · AI & Automation**

I build software across the application, backend, data, and infrastructure layers. My projects range from multi-tenant SaaS and financial workflows to event-driven platforms, AI-assisted operations, networking infrastructure, distributed execution, compilers, and bare-metal systems.

I care about the boundary between a feature and the system that makes the feature reliable: data ownership, API contracts, authorization, asynchronous work, failure handling, testing, observability, and maintainable architecture.

## What I Build

| Area | Representative work |
| --- | --- |
| Product & SaaS | AGATA, NEXORA |
| Event-driven systems | LOGVAULT, VANTA |
| Financial systems | VOLTIS |
| Networking & infrastructure | ATLAS, AEGIS |
| Distributed execution | FORGE |
| Compilers & runtimes | ASTER |
| Operating systems | ORBIT |
| AI & workflow automation | RUMI/LYROMI, AI Workflow Builder |
| Realtime applications | Real-time Kanban, LOGVAULT, VOLTIS |

## Engineering Focus

- Full-stack web application architecture
- Backend services and REST APIs
- Multi-tenant systems, authentication, and authorization
- PostgreSQL data modeling, migrations, constraints, and isolation
- Redis, queues, background workers, and asynchronous processing
- Event-driven and realtime systems
- HTTP/TCP networking, proxies, connection management, and resilience
- Distributed task execution and worker coordination
- AI/LLM integration with application-owned context
- Compiler construction, bytecode, virtual machines, and systems programming
- Docker, Linux, GitHub Actions, CI/CD, testing, and observability

## Technology

**Languages**  
Rust · TypeScript · JavaScript · Python · Java · C++ · SQL

**Frontend**  
React · Next.js · Vue.js · Angular · React Flow · Zustand · Tailwind CSS

**Backend & APIs**  
Node.js · Fastify · NestJS · Express.js · FastAPI · REST · Webhooks · JWT · OAuth

**Data & Messaging**  
PostgreSQL · MySQL · Redis · Prisma · TypeORM · BullMQ · Socket.IO · SSE

**AI & Automation**  
LLM Integration · AI Workflows · Ollama · Agents · Workflow Automation

**Systems & Infrastructure**  
HTTP/1.x · TCP · Tokio · Networking · Distributed Systems · Docker · Docker Compose · Linux

**Quality & Delivery**  
Git · GitHub Actions · CI/CD · Playwright · Vitest · Integration Testing · E2E Testing · Observability

## Selected Projects

### 1. AGATA
**Compliance intelligence for contractors and project teams.** A proprietary product in active development that connects requirements, evidence, project context, expiry, readiness decisions, remediation, and an AI intelligence layer called RUMI.

### 2. NEXORA
**Multi-tenant SaaS workplace.** Full-stack project-management platform with PostgreSQL RLS, transaction-local tenant context, RBAC, Redis/BullMQ workers, Stripe billing, Playwright E2E coverage, Docker, and CI.

### 3. VOLTIS
**Payment and ledger infrastructure.** Financial domain modeling around accounts, double-entry ledger state, idempotent payment operations, reconciliation, risk assessment, webhooks, background jobs, and realtime operations.

### 4. LOGVAULT
**Real-time event intelligence.** Event ingestion, asynchronous processing, operational metrics, statistical anomaly detection, and realtime dashboard updates through Redis/BullMQ and Socket.IO.

### 5. FORGE
**Distributed build/task execution engine in Rust.** DAG scheduling, coordinator-worker communication, persistent task state, heartbeats, retries, binary protocol framing, bounded concurrency, content-addressed artifacts, execution journaling, metrics, and tests.

### 6. ATLAS
**Systems-oriented HTTP reverse proxy in Rust.** TCP/HTTP handling, request parsing, response framing, connection reuse, keep-alive, retries, health checks, timeouts, graceful shutdown, metrics, structured logs, fault injection, and benchmarks.

### 7. ASTER
**Compiler and bytecode virtual machine.** Lexer, parser, AST, semantic analysis, bytecode generation, VM execution, call frames, recursion, disassembly, REPL, diagnostics, and tests.

### 8. ORBIT
**x86_64 `no_std` operating-system/kernel project.** Bootloader, physical frame allocation, interrupts, page faults, PIC, PIT, keyboard IRQ, scheduling model, storage abstraction, RAM disk, QEMU, and serial output.

### 9. AI Workflow Builder
**Node-based AI/workflow automation system.** React Flow + Zustand frontend with FastAPI backend and DAG validation for building and validating workflow graphs.

### 10. AEGIS
**Go HTTP reverse proxy.** Path routing, token-bucket rate limiting, request IDs, structured logs, health endpoints, metrics, graceful shutdown, Docker, and tests.

### 11. Real-time Kanban
**Collaborative realtime project management application.** Next.js, Fastify, Prisma/PostgreSQL, Socket.IO, JWT authentication, refresh tokens, optimistic updates, batch ordering, and Playwright coverage.

### 12. Incident Intelligence Platform / VANTA
**AI-assisted incident operations platform.** Incident classification, priority analysis, duplicate detection, analytics, Redis/BullMQ processing, SSE updates, PostgreSQL, Fastify, Next.js, and Ollama integration.

### Supporting Projects

- **Personal Agent** — AI agent integration/full-stack architecture based on a personal-agent template.
- **SCAFFOLD_ETH** — Ethereum application project built from the Scaffold-ETH ecosystem.
- **TWINS-KITCHEN-AND-BAKERY-WORLD** — proprietary commercial website/product catalogue for a real business; public development setup is intentionally not documented.
- **JOBLESSNESS** — public web project with a live frontend.

## Engineering Approach

I prefer systems that are explicit about their boundaries. When a project uses a queue, database isolation, realtime channel, AI model, or systems primitive, I try to make the behavior observable and document the actual implementation rather than hiding it behind marketing language.

The repositories below are therefore written as engineering case studies: what the system does, how it is structured, why important boundaries exist, how it is tested, and what is intentionally not implemented yet.

## Contact

**Email:** anthony@anthonytech.name.ng  
**LinkedIn:** [Anthony Emmanuella Mmasinachi](https://www.linkedin.com/in/anthony-emmanuella-mmasinachi-a515543b1)
