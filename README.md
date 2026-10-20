# Hi, I'm Muhammad Ahmad

Senior Fullstack AI Engineer building pixel-perfect, production-grade web and mobile products end to end — architecture, design and deployment — with generative AI & LLM integration as my specialty.

3+ years experience · Pakistan · flexible overlap with US & EU hours

## Stack

![Next.js](https://img.shields.io/badge/Next.js-black?logo=next.js&logoColor=white) ![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?logo=supabase&logoColor=white) ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?logo=postgresql&logoColor=white) ![Generative AI](https://img.shields.io/badge/Generative%20AI-5B5BE6) ![LLM Integration](https://img.shields.io/badge/LLM%20Integration-5B5BE6) ![MongoDB](https://img.shields.io/badge/MongoDB-47A248?logo=mongodb&logoColor=white) ![Express](https://img.shields.io/badge/Express-000000?logo=express&logoColor=white) ![React](https://img.shields.io/badge/React-61DAFB?logo=react&logoColor=black) ![Node.js](https://img.shields.io/badge/Node.js-339933?logo=node.js&logoColor=white) ![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?logo=typescript&logoColor=white) ![React Native](https://img.shields.io/badge/React%20Native-20232A?logo=react&logoColor=61DAFB) ![Docker](https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white)

## What I do

- **Full-stack product engineering** — Next.js (App Router, Server Components/Actions), TypeScript, Supabase/PostgreSQL, and the MERN stack (MongoDB, Express, React, Node.js).
- **Generative AI & LLM integration** — production LLM API integration (OpenRouter), natural-language-to-query pipelines grounded in live data, Retrieval-Augmented Generation (RAG), vector search with `pgvector`, and token-cost/latency optimization for real AI features, not demos.
- **Mobile apps with React Native** — cross-platform iOS and Android apps in React Native and Expo, from sensor dashboards and real-time video calling to push notifications and release builds.
- **Pixel-perfect UI/UX** — enterprise-grade design systems built on design tokens (not default component-library styling), full dark/light theming, and WCAG AA accessibility — interfaces built to put in front of a client's own customers, not just functional.
- **DevOps & deployment** — Docker-containerized deployments, CI/CD, taking projects from local development to live production end to end.

## Featured projects

### [AssetGrid](https://github.com/ahm-mad/AssetGrid) — IoT asset management at enterprise scale

<p align="center"><img src="https://raw.githubusercontent.com/ahm-mad/AssetGrid/main/.github/screenshots/fleet-dashboard.png" alt="AssetGrid fleet dashboard" width="100%" /></p>

A full-stack IoT platform for device telemetry, automated buildings, marina/boat fleet management, CRM, and Stripe billing, on Next.js 16 + Supabase — built solo from scratch and run as a live production system used by real operators (the repo and screenshots use synthetic data).

- **Predictive risk intelligence** — risk engines forecast *forward* (days-to-threshold per device from real sensor trend history), plus aggregate trend-mining across the whole fleet's telemetry history; applied predictive modeling, not a chat or generative feature
- **118-table Postgres schema** — fully typed end to end (generated types, zero hand-maintained drift)
- **140 Row-Level Security policies** — the database enforces authorization, not the app
- **~127K telemetry readings/day** — on the live instance, via a tiered time-series pipeline (hot → 1-min → 15-min rollups, 11.9M+ rollups pre-aggregated), monthly-partitioned and `pg_cron`-automated for 10M+ rows without degradation
- **Real protocol decoding** — raw LoRaWAN packets, an alert/notification engine, and a full Stripe billing integration
- **Polished, consistent UI across 20+ distinct product surfaces** — dashboards, diagnostics, billing, and admin all in one coherent dark/light-themed design, not a patchwork of screens bolted together

→ [Full write-up, architecture diagrams, and schema](https://github.com/ahm-mad/AssetGrid#readme)

### [ConvoyAI](https://github.com/ahm-mad/ConvoyAI) — enterprise fleet management with a generative AI copilot

<p align="center"><img src="https://raw.githubusercontent.com/ahm-mad/ConvoyAI/main/docs/screenshots/ai-copilot.png" alt="ConvoyAI generative AI copilot answering a plain-English fleet question" width="100%" /></p>

A fleet operations platform built solo from scratch and used in production by real fleet operators, centred on a **dedicated LLM copilot**, not a chatbot bolted onto a CRUD API — a fleet manager asks a plain-English question about their own fleet data and gets back real numbers, charts and a drafted action plan.

- **LLM-powered copilot** (Python/FastAPI microservice via OpenRouter) — interprets a natural-language question, grounds it in live fleet data, and streams back a synthesized answer, plus a forecasting layer (maintenance due, fuel-spend projection, driver risk scoring)
- **Database-enforced, multi-tenant RBAC** — permissions live in the data layer, not scattered through app code
- **Live 3D fleet map** — dispatch, CRM & billing, fuel/maintenance/compliance tracking, all in one workspace
- **TimescaleDB** — hypertables for the fleet's time-series telemetry
- **Four independent processes from one codebase** — HTTP API, realtime ingestion, scheduler, and a BullMQ background worker, so a long-running job never blocks a request
- **Enterprise-grade, WCAG AA UI** — a token-based design system across dark and light themes, so the live 3D map, dashboards, and billing all feel like one cohesive product, not stitched-together pages

→ [Full write-up, architecture diagrams, and the copilot's own request flow](https://github.com/ahm-mad/ConvoyAI#readme)

### Also built

- **Explorer Bilge** — a React Native marine-monitoring app (live bilge, battery and mold-risk readings, real-time video calling), built solo from scratch, including its iOS and Android release process.
- **FocusWarden** and **DutchUp** — React Native mobile apps built as part of a team.

## Links

- 🌐 [Portfolio](https://muhammad-ahmad-engineer.vercel.app)
- 💼 [Upwork](https://www.upwork.com/freelancers/~0178f5d6c7d0374cdf)
