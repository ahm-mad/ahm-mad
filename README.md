# Hi, I'm Muhammad Ahmad

Senior Fullstack AI Engineer building production-grade web applications end to end — architecture, generative AI & LLM integration, and deployment.

3+ years experience · Sahiwal, Pakistan

## Stack

![Next.js](https://img.shields.io/badge/Next.js-black?logo=next.js&logoColor=white) ![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?logo=typescript&logoColor=white) ![React](https://img.shields.io/badge/React-61DAFB?logo=react&logoColor=black) ![Node.js](https://img.shields.io/badge/Node.js-339933?logo=node.js&logoColor=white) ![Express](https://img.shields.io/badge/Express-000000?logo=express&logoColor=white) ![MongoDB](https://img.shields.io/badge/MongoDB-47A248?logo=mongodb&logoColor=white) ![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?logo=supabase&logoColor=white) ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?logo=postgresql&logoColor=white) ![Generative AI](https://img.shields.io/badge/Generative%20AI-LLM%20integration-5B5BE6) ![Docker](https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white)

## What I do

- **Generative AI & LLM integration** — production LLM API integration (OpenRouter), natural-language-to-query pipelines grounded in live data, Retrieval-Augmented Generation (RAG), vector search with `pgvector`, and token-cost/latency optimization for real AI features, not demos.
- **Full-stack product engineering** — Next.js (App Router, Server Components/Actions), TypeScript, Supabase/PostgreSQL, and the MERN stack (MongoDB, Express, React, Node.js).
- **DevOps & deployment** — Docker-containerized deployments, CI/CD, taking projects from local development to live production end to end.

## Featured projects

### [ConvoyAI](https://github.com/ahm-mad/ConvoyAI) — enterprise fleet management with a generative AI copilot

<p align="center"><img src="https://raw.githubusercontent.com/ahm-mad/ConvoyAI/main/docs/screenshots/fleet-map.png" alt="ConvoyAI live 3D fleet map" width="100%" /></p>

A fleet operations platform built around a **dedicated LLM copilot**, not a chatbot bolted onto a CRUD API — a fleet manager asks a plain-English question about their own fleet data and gets back real numbers, charts and a drafted action plan.

- **LLM-powered copilot** (Python/FastAPI microservice via OpenRouter) — interprets a natural-language question, grounds it in live fleet data, and streams back a synthesized answer, plus a forecasting layer (maintenance due, fuel-spend projection, driver risk scoring)
- **Database-enforced, multi-tenant RBAC** — permissions live in the data layer, not scattered through app code
- **Live 3D fleet map**, dispatch, CRM & billing, fuel/maintenance/compliance tracking in one workspace
- **TimescaleDB** hypertables for the fleet's time-series telemetry
- **Four independent processes from one codebase** — HTTP API, realtime ingestion, scheduler, and a BullMQ background worker, so a long-running job never blocks a request

→ [Full write-up, architecture diagrams, and the copilot's own request flow](https://github.com/ahm-mad/ConvoyAI#readme)

### [AssetGrid](https://github.com/ahm-mad/AssetGrid) — IoT asset management at enterprise scale

<p align="center"><img src="https://raw.githubusercontent.com/ahm-mad/AssetGrid/main/.github/screenshots/fleet-dashboard.png" alt="AssetGrid fleet dashboard" width="100%" /></p>

A full-stack IoT platform for device telemetry, automated buildings, marina/boat fleet management, CRM, and Stripe billing, on Next.js 16 + Supabase — built and run as a live production system, not a demo.

- **Predictive risk intelligence** — risk engines forecast *forward* (days-to-threshold per device from real sensor trend history), plus aggregate trend-mining across the whole fleet's telemetry history; applied predictive modeling, not a chat or generative feature
- **118-table Postgres schema**, fully typed end to end (generated types, zero hand-maintained drift)
- **140 Row-Level Security policies** — the database enforces authorization, not the app
- **~127K telemetry readings/day** on the live instance, on a tiered time-series pipeline (hot → 1-min → 15-min rollups, 11.9M+ rollups pre-aggregated), monthly-partitioned and `pg_cron`-automated for 10M+ rows without degradation
- Real LoRaWAN packet decoding, an alert/notification engine, and a full Stripe billing integration

→ [Full write-up, architecture diagrams, and schema](https://github.com/ahm-mad/AssetGrid#readme)

## Links

- 🌐 Portfolio — [ADD YOUR PORTFOLIO SITE LINK]
- 💼 Upwork — [ADD YOUR UPWORK PROFILE LINK]
