<h1 align="center">Rahat Hasan Akanda</h1>

<p align="center">
  <b>Full-Stack TypeScript Engineer</b><br/>
  Node.js · NestJS · React · Real-time Systems · RAG / LLM Integration<br/>
  📍 Dhaka, Bangladesh
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/rahat-akanda/"><img src="https://img.shields.io/badge/LinkedIn-Rahat_Akanda-0A66C2?logo=linkedin&logoColor=white&style=for-the-badge" alt="LinkedIn"/></a>
  <a href="mailto:rh.rahat16@gmail.com"><img src="https://img.shields.io/badge/Email-rh.rahat16@gmail.com-D14836?logo=gmail&logoColor=white&style=for-the-badge" alt="Email"/></a>
</p>

---

## 👨‍💻 Introduction

I'm a software engineer who builds backend-focused, full-stack products with TypeScript. I focus on the parts of a system that matter in production: secure authentication, role-based access control, safe concurrent writes, real-time updates, payments, and automated testing.

I have also shipped LLM features into real business software (OpenAI-based chatbot and invoice extraction for Odoo at Nyntax) and built a RAG pipeline with pgvector in my own projects.

**🟢 Open to opportunities:** Backend Engineer · Full-Stack Engineer (Node.js / TypeScript) · AI Application Engineer

---

## 🚀 Featured Projects

### 🔹 [Nexus: AI-Powered Real-Time Team Workspace](https://github.com/RahatRyaan/nexus-saas-platform)
Multi-tenant SaaS with real-time Kanban boards and chat, an AI knowledge base, and subscription billing.
- Hierarchical RBAC (Owner / Admin / Member) with workspace switching
- JWT access/refresh rotation with token-family reuse detection
- Socket.io + Redis Pub/Sub, fractional indexing for concurrency-safe drag-and-drop
- RAG pipeline: pgvector (HNSW) + BullMQ workers for chunking, semantic search and summarization
- Stripe and SSLCommerz billing with webhook deduplication and idempotency
- Docker, GitHub Actions CI/CD, 37 Jest/Supertest integration tests

`React` `TypeScript` `Node.js` `MongoDB` `PostgreSQL` `pgvector` `Redis` `Socket.io` `BullMQ`

### 🔹 [SyncBoard: Real-Time Collaborative Kanban](https://github.com/RahatRyaan/syncboard-realtime-kanban)
Multi-user Kanban platform with live presence and conflict-safe writes, built as a pnpm monorepo.
- Optimistic concurrency control (`expectedVersion`) with typed `409 VERSION_CONFLICT` responses
- Argon2id hashing, rotating HTTP-only refresh tokens, session-family revocation on replay
- Redis pub/sub fan-out for multi-instance scaling, direct-to-S3 uploads via presigned URLs
- Prometheus metrics, readiness probes, tiered rate limiting
- CI with 32 unit tests and 17 E2E tests; load-tested with 200 concurrent WebSocket clients

`NestJS` `React 19` `MongoDB` `Redis` `Socket.io` `AWS S3` `GitHub Actions`

### 🔹 [SkillMap AI: Skill-Gap Analysis & Adaptive Roadmaps](https://github.com/RahatRyaan/skillmap-career-pathfinder)
Compares a student's skills with real career requirements and generates a study roadmap that re-plans as they progress.
- Scoring engine written as a shared pure TypeScript library used by both client and server
- 173 unit/API tests and 20 Playwright E2E tests covering NoSQL injection, token tampering and cross-account access
- Designed for WCAG 2.2 AA (table equivalents for charts, keyboard operability)

`MERN` `TypeScript` `Playwright`

### 🔹 [Multi-Vendor E-Commerce Platform](https://github.com/RahatRyaan/mainstays-ecommerce-)
Marketplace with separate Customer, Vendor and Admin portals, automated sub-order splitting and vendor payout tracking.
- Redis caching and optimized MongoDB aggregation pipelines reduced API latency by about 60% on catalog and search queries
- JWT/cookie auth, granular RBAC, rate limiting and Zod/Joi validation aligned with OWASP guidance
- Jest + Supertest tests (>80% coverage), Swagger/OpenAPI documentation

`React 19` `Express 5` `MongoDB` `Redis` `Zustand` `Stripe` `SSLCommerz`

### 🔹 [Aegis: LSM-Tree & Vector Search Engine](https://github.com/RahatRyaan/aegis-vector-engine)
Storage and retrieval engine combining an LSM-tree with HNSW vector search and BM25 hybrid retrieval for semantic search and RAG workloads.

`Systems Programming` `HNSW` `BM25` `Docker`

---

## 🛠 Tech Stack

| Area | Technologies |
|---|---|
| **Languages** | TypeScript, JavaScript (ES6+), Python, SQL |
| **Backend** | Node.js, Express, NestJS, REST APIs, Socket.io, BullMQ, JWT, RBAC |
| **Frontend** | React, Zustand, Tailwind CSS, Vite |
| **Databases** | MongoDB, PostgreSQL (pgvector), Redis |
| **AI** | OpenAI and Gemini APIs, RAG, vector search (HNSW), hybrid search (BM25) |
| **Testing** | Jest, Supertest, Playwright |
| **DevOps** | Docker, GitHub Actions, AWS S3, Vercel, Render, Prometheus |
| **Practices** | OWASP-aligned security, rate limiting, OpenAPI/Swagger, optimistic concurrency, monorepos |

<p>
  <img src="https://img.shields.io/badge/TypeScript-3178C6?logo=typescript&logoColor=white&style=flat-square"/>
  <img src="https://img.shields.io/badge/Node.js-339933?logo=node.js&logoColor=white&style=flat-square"/>
  <img src="https://img.shields.io/badge/NestJS-E0234E?logo=nestjs&logoColor=white&style=flat-square"/>
  <img src="https://img.shields.io/badge/React-61DAFB?logo=react&logoColor=black&style=flat-square"/>
  <img src="https://img.shields.io/badge/MongoDB-47A248?logo=mongodb&logoColor=white&style=flat-square"/>
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?logo=postgresql&logoColor=white&style=flat-square"/>
  <img src="https://img.shields.io/badge/Redis-DC382D?logo=redis&logoColor=white&style=flat-square"/>
  <img src="https://img.shields.io/badge/Socket.io-010101?logo=socket.io&logoColor=white&style=flat-square"/>
  <img src="https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white&style=flat-square"/>
  <img src="https://img.shields.io/badge/GitHub_Actions-2088FF?logo=githubactions&logoColor=white&style=flat-square"/>
  <img src="https://img.shields.io/badge/AWS_S3-232F3E?logo=amazon-aws&logoColor=white&style=flat-square"/>
  <img src="https://img.shields.io/badge/Jest-C21325?logo=jest&logoColor=white&style=flat-square"/>
  <img src="https://img.shields.io/badge/Playwright-2EAD33?logo=playwright&logoColor=white&style=flat-square"/>
</p>

---

## 💼 Experience

**Software Engineer, Nyntax** · Dhaka
- Customized and deployed an OpenAI chatbot integration for Odoo: secure API token configuration, business-specific prompts and response evaluation.
- Built an LLM-based invoice digitization workflow that replaces native OCR and maps structured data to Odoo vendor bills, with data-privacy and access controls.
- Tested software, resolved data inconsistencies and analyzed datasets to support product decisions.

---

## 🎓 Education

**B.Sc., American International University-Bangladesh (AIUB)**

---

## 📫 Let's Connect

- 💼 LinkedIn: [linkedin.com/in/rahat-akanda](https://www.linkedin.com/in/rahat-akanda/)
- 📧 Email: [rh.rahat16@gmail.com](mailto:rh.rahat16@gmail.com)

<!--
DATA & ANALYTICS SECTION: enable only after the analytics repos are public.
Replace LINK with your real repo URLs and move this block above "Tech Stack".

## 📊 Data & Analytics
| Project | Tools |
|---|---|
| [Customer Churn & Segmentation](LINK) | Python · SQL · Power BI |
| [Sales Forecasting](LINK) | Python · statsmodels · Power BI |
| [A/B Test & Funnel Analysis](LINK) | SQL · Python |
-->
