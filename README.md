<div align="center">

# Sravani Kamjula

### AI/ML Engineer | Generative AI | Python | RAG | FastAPI

[Portfolio](https://sravaniportfoli.netlify.app/) ·
[LinkedIn](https://www.linkedin.com/in/sravani-kamjula/) ·
[Email](mailto:sravanikamjula@gmail.com) ·
[Kaggle](https://www.kaggle.com/sravanikamjula)  
**Building reliable AI systems from data to deployment.**  
<img src="https://komarev.com/ghpvc/?username=kamjula&label=Profile%20views&style=flat" alt="GitHub profile views" />

</div>

---

## About

<table>
<tr>
<td width="72%">

I build AI/ML systems end to end: data pipelines, machine learning, grounded GenAI, APIs, and the evaluation around them.

Getting a model or an LLM call to work is the easy part. Most of my time goes into making systems **measurable, easy to inspect, and clear about where they fail**.

**Engineering flow**

<img src="https://img.shields.io/badge/Data%20%26%20Telemetry-2563EB?style=flat-square&logo=postgresql&logoColor=white" alt="Data and Telemetry" />
→
<img src="https://img.shields.io/badge/ML%20Detection-4F46E5?style=flat-square&logo=scikitlearn&logoColor=white" alt="ML Detection" />
→
<img src="https://img.shields.io/badge/RAG%20%2F%20LLMs-7C3AED?style=flat-square&logo=openai&logoColor=white" alt="RAG and LLMs" />
→
<img src="https://img.shields.io/badge/FastAPI-0F766E?style=flat-square&logo=fastapi&logoColor=white" alt="FastAPI" />
→
<img src="https://img.shields.io/badge/Evaluation%20%26%20Observability-475569?style=flat-square&logo=grafana&logoColor=white" alt="Evaluation and Observability" />

**Focus areas:** Generative AI · RAG · ML systems · data reliability · API engineering

**Open to:** AI/ML Engineer · Machine Learning Engineer · Generative AI Engineer · AI Engineer

</td>
<td width="28%" align="center">

<img src="https://raw.githubusercontent.com/kamjula/kamjula/main/assets/ai-ml-engineering.svg" alt="AI/ML engineering systems visual" width="230" />

</td>
</tr>
</table>

---

## Featured Engineering Work

A few projects covering AI reliability, data quality, APIs, and evaluation.

### DataPulse: GenAI Data Reliability Copilot

<a href="https://github.com/kamjula/datapulse">
  <img src="https://raw.githubusercontent.com/kamjula/datapulse/main/datapulse-overview.png" alt="DataPulse GenAI Data Reliability Copilot" width="100%" />
</a>

**Problem:** pipeline failures are easy to flag and hard to explain reliably.  
**Built:** anomaly detection + runbook-grounded RAG + cited incident diagnosis + abstention + evaluation harnesses.

- Robust z-score + schema-drift detection
- IsolationForest was evaluated and removed after an ablation showed no added value
- Claude-backed narration with deterministic fallback
- LangGraph CI-triage workflow with cited verification
- Seeded synthetic evaluation: **Precision 0.96 · Recall 1.00 · F1 0.98**

[Repository](https://github.com/kamjula/datapulse)

---

### RoboOps: Robotics Fleet Monitoring & Condition Analytics

<a href="https://roboops-platform.vercel.app/">
  <img src="https://raw.githubusercontent.com/kamjula/roboops-platform/main/frontend/public/roboops-preview.png" alt="RoboOps fleet monitoring and condition analytics" width="100%" />
</a>

**Problem:** monitor a robot fleet end to end (telemetry, alerts, maintenance) on synthetic data, without treating anomaly signals as failure predictions.  
**Built:** a full-stack fleet platform with telemetry ingestion, analytics, alerts, maintenance records, RBAC, observability, and CI security checks.

- FastAPI + PostgreSQL + React
- Idempotent HTTP/Kafka telemetry workflows
- Kafka/Redpanda retry and DLQ handling
- JWT/RBAC, Prometheus metrics, structured logging
- Browser E2E, CodeQL, dependency audits, container scanning
- Condition scores are labeled as anomaly signals, not validated failure probabilities

[Repository](https://github.com/kamjula/roboops-platform) ·
[Live read-only demo](https://roboops-platform.vercel.app/) ·
[90-second demo tour](https://github.com/kamjula/roboops-platform/blob/main/docs/demo-tour.md)

---

### CortexOS: Enterprise Data Operations Platform

<a href="https://github.com/kamjula/cortex-enterprise">
  <img src="https://raw.githubusercontent.com/kamjula/cortex-enterprise/main/screenshots/cortexos-overview.png" alt="CortexOS enterprise data operations platform" width="100%" />
</a>

**Problem:** enterprise data tooling needs operational visibility, access control, and AI assistance without exposing unnecessary data.  
**Built:** an authenticated full-stack data operations platform with PostgreSQL persistence, RBAC, data-quality workflows, alerts, settings, and an optional OpenAI-backed Copilot.

- React + Node.js + Express + PostgreSQL
- JWT access/refresh authentication with Admin / Editor / Viewer RBAC
- Privacy-limited Copilot context using fixed aggregate queries
- Dataset CRUD, alerts, data-quality summaries, pipeline status controls, and per-user settings
- Docker Compose setup and documented secure deployment flow
- Pipeline trigger/retry controls update stored status; there is no real worker orchestrator behind them

[Repository](https://github.com/kamjula/cortex-enterprise)

---

### Enterprise Data Detective: AI-Assisted Transaction Analytics

**Problem:** transaction review is easier to trust when profiling, anomaly reasons, and generated queries stay visible and inspectable.  
**Built:** a compact Streamlit application that profiles data, surfaces explainable heuristic signals, and converts plain-English questions into DuckDB SELECT queries with Claude.

- Pandas profiling for missing values, duplicates, numeric statistics, and date ranges
- Explainable checks for amount outliers, velocity bursts, duplicate charges, off-hours activity, and other review signals
- Human-readable reasons attached to every flagged transaction
- Claude natural-language-to-SQL over a fixed transaction schema
- DuckDB local execution on synthetic data
- SELECT-only validation is a basic guard, not a production SQL sandbox (documented in the README)

**Stack:** Python · Pandas · DuckDB · Streamlit · Claude API

[Repository](https://github.com/kamjula/enterprise-data-detective)

---

## Additional ML Work

| Project | Status | What it covers |
|---|---|---|
| [**Healthcare Fraud Detection**](https://github.com/kamjula/healthcare-fraud-detection) | Implemented | Synthetic claims pipeline with configurable rules, XGBoost scoring, hybrid risk scoring, Docker, pytest, and SQL analysis |
| [**CausalLab**](https://github.com/kamjula/causallab) | Implemented | A/B simulation, sample-size planning, CUPED variance reduction, sequential testing, segment-level lift, T-learner treatment effects, a Streamlit dashboard, pytest, and CI |

---

## Core Stack

| Area | Working stack |
|---|---|
| **AI / ML** | Python · Generative AI · LLMs · RAG · LangChain · LangGraph · scikit-learn · NLP · anomaly detection · evaluation |
| **AI Applications** | FastAPI · REST APIs · Claude API · OpenAI · grounded retrieval · guardrails · validation · logging |
| **Data Systems** | SQL · PostgreSQL · PySpark · Apache Spark · Airflow · ETL/ELT · data quality · reconciliation |
| **Cloud / Delivery** | AWS · GCP Vertex AI · Docker · Kubernetes · Git · GitHub · CI/CD-oriented workflows |

---

## Engineering Principles

- **Measure first:** every project metric comes from a reproducible evaluation run in the repository.
- **Write down the limits:** each README lists its synthetic-data, model, and deployment caveats.
- **Build the unglamorous parts too:** validation, observability, access control, and failure handling are part of the implementation, not an afterthought.

---

## Selected Certifications

- Building with the Claude API (Anthropic)
- Claude Code 101 (Anthropic)
- AI Fluency: Framework & Foundations (Anthropic)
- Machine Learning A-Z: AI, Python & R (Udemy)

<div align="center">

**AI/ML Engineer · Generative AI · Python · RAG · FastAPI**

</div>
