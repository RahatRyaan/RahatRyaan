<div align="center">

# Rahat Hasan Akanda

### Full-Stack Engineer (MERN · TypeScript) &nbsp;|&nbsp; Data Analyst (SQL · Python · Power BI)

📍 Dhaka, Bangladesh

<a href="https://www.linkedin.com/in/rahat-akanda/"><img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?logo=linkedin&logoColor=white&style=for-the-badge" alt="LinkedIn"/></a>
<a href="mailto:rh.rahat16@gmail.com"><img src="https://img.shields.io/badge/Email-Contact_Me-D14836?logo=gmail&logoColor=white&style=for-the-badge" alt="Email"/></a>

</div>

---

## 👨‍💻 About Me

I build secure, real-time, full-stack products with **TypeScript, Node.js and React**, and I turn raw data into decisions with **SQL, Python and Power BI**.

On the engineering side, I focus on what matters in production: authentication, role-based access control, safe concurrent writes, real-time updates, payments and automated testing. On the data side, I clean messy datasets, run statistical analysis, and present findings as dashboards and clear recommendations.

At **Nyntax**, I worked as a Software Engineer, shipping LLM-powered features (OpenAI chatbot and invoice extraction) into Odoo business software.

> 🟢 **Open to work:** Full-Stack / Backend Engineer (Node.js, TypeScript) · Data Analyst · AI Application Engineer

---

<div align="center">

# 💻 Full-Stack Engineering

</div>

### 🔹 [Nexus: AI-Powered Real-Time Team Workspace](https://github.com/RahatRyaan/nexus-saas-platform)
Multi-tenant SaaS with real-time Kanban and chat, an AI knowledge base (RAG) and subscription billing.

- Hierarchical RBAC (Owner / Admin / Member) and JWT access/refresh rotation with token-family reuse detection
- Socket.io + Redis Pub/Sub, with fractional indexing for concurrency-safe drag-and-drop
- RAG pipeline: pgvector (HNSW) + BullMQ workers for chunking, semantic search and summarization
- Stripe and SSLCommerz billing with webhook deduplication and idempotency
- Docker, GitHub Actions CI/CD, 37 Jest/Supertest integration tests

`React` `TypeScript` `Node.js` `MongoDB` `PostgreSQL` `pgvector` `Redis` `Socket.io` `BullMQ`

### 🔹 [SyncBoard: Real-Time Collaborative Kanban](https://github.com/RahatRyaan/syncboard-realtime-kanban)
Multi-user Kanban platform with live presence and conflict-safe writes (pnpm monorepo).

- Optimistic concurrency control with typed `409 VERSION_CONFLICT` responses
- Argon2id hashing, rotating HTTP-only refresh tokens, session-family revocation on replay
- Redis pub/sub fan-out for multi-instance scaling, direct-to-S3 uploads via presigned URLs
- 32 unit + 17 E2E tests in CI; load-tested with 200 concurrent WebSocket clients

`NestJS` `React 19` `MongoDB` `Redis` `Socket.io` `AWS S3` `GitHub Actions`

### 🔹 [SkillMap AI: Skill-Gap Analysis & Adaptive Roadmaps](https://github.com/RahatRyaan/skillmap-career-pathfinder)
Compares a student's skills with real career requirements and generates a roadmap that re-plans as they progress.

- Scoring engine written as a shared pure TypeScript library used by both client and server
- 173 unit/API tests and 20 Playwright E2E tests, including NoSQL injection, token tampering and cross-account access
- Designed for WCAG 2.2 AA accessibility

`MERN` `TypeScript` `Playwright`

<table>
<tr>
<td width="50%" valign="top">

**[Multi-Vendor E-Commerce Platform](https://github.com/RahatRyaan/mainstays-ecommerce-)**<br/>
Customer, Vendor and Admin portals, sub-order splitting, vendor payouts. Redis caching and optimized aggregations cut API latency by about 60%.<br/>
<sub>`React 19` `Express 5` `MongoDB` `Redis` `Stripe` `SSLCommerz`</sub>

</td>
<td width="50%" valign="top">

**[Aegis: LSM-Tree & Vector Search Engine](https://github.com/RahatRyaan/aegis-vector-engine)**<br/>
Storage engine combining an LSM-tree with HNSW vector search and BM25 hybrid retrieval for RAG workloads.<br/>
<sub>`Systems Programming` `HNSW` `BM25` `Docker`</sub>

</td>
</tr>
</table>

---

<div align="center">

# 📊 Data Analytics

</div>

| Project | What I did | Tools |
|---|---|---|
| **Customer Churn & Segmentation** | Analyzed the IBM Telco Churn dataset, built RFM-style segments, identified churn drivers and trained a logistic regression model. Power BI dashboard shows churn by contract, tenure and service type. | `Python` `SQL` `scikit-learn` `Power BI` |
| **Sales Forecasting & Demand Analysis** | Time-series decomposition (trend, seasonality) on retail sales data. Built ARIMA and exponential smoothing models and compared accuracy using MAE and RMSE. | `Python` `statsmodels` `Power BI` |
| **A/B Test & Marketing Funnel Analysis** | Wrote SQL funnel and cohort-retention queries (CTEs, window functions). Ran z-test and chi-square tests on conversion rates and wrote a business recommendation. | `SQL` `Python` `Statistics` |
| **E-Commerce Sales Dashboard** | Cleaned raw sales data and answered business questions on revenue, products and trends. Interactive dashboard with KPIs, slicers and DAX measures. | `Power BI` `SQL` `Python` `Excel` |
| **HR / Finance Analytics Dashboard** | End-to-end analysis (cleaning, transformation, visualization) with a Power BI dashboard for non-technical users. | `Power BI` `Python` `SQL` |

**Analytics toolkit:** SQL (joins, CTEs, window functions) · pandas · NumPy · matplotlib · seaborn · hypothesis testing · A/B testing · regression · time-series forecasting · Power BI (DAX, Power Query) · Excel (Pivot Tables, XLOOKUP)

---

## 🛠 Tech Stack

| Area | Technologies |
|---|---|
| **Languages** | TypeScript, JavaScript (ES6+), Python, SQL |
| **Backend** | Node.js, Express, NestJS, REST APIs, Socket.io, BullMQ, JWT, RBAC |
| **Frontend** | React, Zustand, Tailwind CSS, Vite |
| **Databases** | MongoDB, PostgreSQL (pgvector), MySQL, Redis |
| **AI & Search** | OpenAI and Gemini APIs, RAG, vector search (HNSW), hybrid search (BM25) |
| **Data & BI** | pandas, NumPy, scikit-learn, statsmodels, Power BI, Excel |
| **Testing** | Jest, Supertest, Playwright |
| **DevOps** | Docker, GitHub Actions, AWS S3, Vercel, Render, Prometheus |

<p>
  <img src="https://img.shields.io/badge/TypeScript-3178C6?logo=typescript&logoColor=white&style=flat-square"/>
  <img src="https://img.shields.io/badge/Node.js-339933?logo=node.js&logoColor=white&style=flat-square"/>
  <img src="https://img.shields.io/badge/NestJS-E0234E?logo=nestjs&logoColor=white&style=flat-square"/>
  <img src="https://img.shields.io/badge/React-61DAFB?logo=react&logoColor=black&style=flat-square"/>
  <img src="https://img.shields.io/badge/MongoDB-47A248?logo=mongodb&logoColor=white&style=flat-square"/>
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?logo=postgresql&logoColor=white&style=flat-square"/>
  <img src="https://img.shields.io/badge/Redis-DC382D?logo=redis&logoColor=white&style=flat-square"/>
  <img src="https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white&style=flat-square"/>
  <img src="https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white&style=flat-square"/>
  <img src="https://img.shields.io/badge/pandas-150458?logo=pandas&logoColor=white&style=flat-square"/>
  <img src="https://img.shields.io/badge/scikit--learn-F7931E?logo=scikitlearn&logoColor=white&style=flat-square"/>
  <img src="https://img.shields.io/badge/Power_BI-F2C811?logo=powerbi&logoColor=black&style=flat-square"/>
  <img src="https://img.shields.io/badge/Jest-C21325?logo=jest&logoColor=white&style=flat-square"/>
  <img src="https://img.shields.io/badge/Playwright-2EAD33?logo=playwright&logoColor=white&style=flat-square"/>
</p>

---

## 💼 Experience

**Software Engineer, Nyntax** · Dhaka
- Customized and deployed an OpenAI chatbot integration for Odoo: secure API token configuration, business-specific prompts and response evaluation.
- Built an LLM-based invoice digitization workflow that replaces native OCR and maps structured data to Odoo vendor bills, with data-privacy and access controls.
- Tested software for quality and reliability, and investigated and resolved application and data issues.

## 🎓 Education

**B.Sc., American International University-Bangladesh (AIUB)**

## 📫 Let's Connect

[![LinkedIn](https://img.shields.io/badge/LinkedIn-rahat--akanda-0A66C2?logo=linkedin&logoColor=white&style=flat-square)](https://www.linkedin.com/in/rahat-akanda/)
[![Email](https://img.shields.io/badge/Email-rh.rahat16@gmail.com-D14836?logo=gmail&logoColor=white&style=flat-square)](mailto:rh.rahat16@gmail.com)
