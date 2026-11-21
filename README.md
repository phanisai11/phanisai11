<div align="center">

# 👋 Hi, I'm Phani

### Forward Deployed Engineer · AI Systems · Solution Architecture

I embed with teams to take AI systems from **zero → production** — discovery,
design, build, deploy, and handoff. Not just writing code: owning the
outcome on the customer's ground.

![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazon-aws&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=next.js&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Langfuse](https://img.shields.io/badge/Langfuse-000000?style=for-the-badge)
![Qdrant](https://img.shields.io/badge/Qdrant-DC244C?style=for-the-badge&logo=qdrant&logoColor=white)

</div>

---

## 🚀 What I Do — The FDE Way

Forward Deployed Engineering is where **engineering meets consulting**:
sit inside the problem, ship working software against real constraints,
and leave the customer self-sufficient.

| Phase | What it looks like |
|---|---|
| **🔍 Discover** | Deep-dive ambiguous requirements, map real workflows, find the actual bottleneck — not the stated one |
| **🏗️ Architect** | Design deterministic, auditable systems — LLMs as *bounded assistants*, never the decision-maker |
| **⚡ Ship** | FastAPI + React + Postgres + AWS. Deploy to real EC2/RDS, wire CI, secure the perimeter |
| **📈 Operate** | SLA tracking, cost governance, observability (Langfuse/LangSmith), audit trails, kill-switches |
| **🤝 Consult** | Translate between business stakeholders and engineering — requirements → architecture → delivery plan |

---

## 🛠️ Core Skills

### AI / LLM Systems
- **Orchestration** — LangGraph state machines, bounded LLM patterns, deterministic routing
- **RAG** — hybrid retrieval, HyDE, pgvector/Qdrant, citation-grounded answers
- **Guardrails** — answer gates, human-in-the-loop lanes, PII redaction (Presidio), LLM kill-switches
- **Observability** — Langfuse/LangSmith tracing, token/cost accounting, audit logging
- **Evaluation** — golden datasets, LLM-as-judge, deterministic regression tests

### Platform Engineering
- **Backend** — Python, FastAPI, async workers, SQLite→PostgreSQL migration, RLS multi-tenancy
- **Frontend** — React, Next.js, real-time dashboards, ticket/journey UIs
- **Data** — PostgreSQL (RLS, migrations), pgvector, schema design, seed pipelines
- **Cloud (AWS)** — EC2, RDS, S3, EventBridge scheduling, security groups, IAM, CloudWatch, CloudFormation
- **Delivery** — Docker, systemd services, nginx + TLS, sslip domains, secrets management

### Consulting / Delivery
- Ambiguous problem → working prototype → production deployment
- Stakeholder communication, demo-ready builds, documentation
- Security audits (exposure review, secret hygiene, least-privilege)
- Cost engineering (scheduled instances, token budgets, tiered models)

---

## 🏗️ Selected Work

### 💼 Payce — Support Intelligence Platform
*Production multi-tenant support system for payroll/HR operations*

```
Customer message → deterministic routing → KB-grounded answers
→ auto-resolve / agent draft / human queue → SLA + CSAT tracking
```

- Deterministic pipeline (LLM optional via `PAYCE_ROUTING_LLM` flag — verified both modes live)
- RAG over Confluence-style KB with citation grounding + answer gate
- 50-ticket real-flow seed: 19 auto-resolved, 15 human-lane, reopen loops — all through real APIs
- Security-hardened: IP-locked SG, RLS tenant isolation, `600` secrets, audit tables
- React dashboard: queues, SLA risk, ticket journeys, LLM activity traces

### 🚚 SetuHaul — Freight Operations Platform
*Driver-facing logistics coordination with governed AI assistance*

- WhatsApp-style driver chat with delivery receipts (sent/delivered/read ticks)
- SQLite→PostgreSQL dialect layer, governance settings UI (kill-switch, breakers, masked secrets)
- AI governance layer: `ai_kill_switch`, circuit breakers, bounded LLM fallback, audit logs
- Next.js ops dashboard + FastAPI backend on AWS with TLS

### 📚 Applied AI Study Practice
Deep-dive documentation sets built alongside the systems:
`langgraph` · `langfuse` · `aws_architecture` (27 docs) · `qdrant` · `presidio` · `autogen` —
each mapped to real production decisions, not just theory.

---

## 📊 By the Numbers

```
2 production platforms shipped end-to-end (Payce · SetuHaul)
100+ numbered architecture/study docs written
19 DB migrations · 50+ API endpoints · full audit trails
$0 → deployed on AWS EC2+RDS with TLS, SG lockdown, scheduled costs
```

---

## 🧠 Engineering Philosophy

> **"LLM proposes. Code disposes."**

- Deterministic where it matters (routing, SLA, compliance)
- LLM only where it helps (parsing, drafting, summarizing)
- Every AI action auditable, reversible, cost-tracked
- Human approval gates on anything customer-facing or irreversible
- Ship boring infrastructure, interesting AI

---

## 📫 Let's talk

- 💼 Open to **FDE / AI engineering / solutions architecture** roles
- 🏢 Consulting engagements — embed with your team, ship against real constraints
- ✉️ Reach out via GitHub or email

<div align="center">

`deterministic core · bounded intelligence · auditable everything`

</div>
