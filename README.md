<div align="center">

# Hi, I'm Sravani Kamjula 👋

### AI/ML Engineer | Generative AI | Python | RAG | FastAPI

<a href="https://sravaniportfoli.netlify.app/"><img src="https://img.shields.io/badge/Portfolio-00C7B7?style=for-the-badge&logo=netlify&logoColor=white" alt="Portfolio" /></a>
<a href="https://www.linkedin.com/in/sravani-kamjula/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge" alt="LinkedIn" /></a>
<a href="mailto:sravanikamjula@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
<a href="https://www.kaggle.com/sravanikamjula"><img src="https://img.shields.io/badge/Kaggle-20BEFF?style=for-the-badge&logo=kaggle&logoColor=white" alt="Kaggle" /></a>

<img src="https://komarev.com/ghpvc/?username=kamjula&label=Profile%20views&style=flat" alt="GitHub profile views" />

</div>

---

## About me

- 🔭 I'm an AI/ML Engineer. I build GenAI and machine learning systems in Python, from the data pipeline to the API and the evaluation around it
- 🚀 Recent builds: **DataPulse**, a GenAI data reliability copilot (ML anomaly detection + RAG root-cause diagnosis), and **RoboOps**, a robotics fleet monitoring platform (FastAPI, React, Kafka, PostgreSQL)
- 🌱 Currently working on LLM evaluation, LangGraph workflows, and RAG that cites its sources and says "I don't know" when it should
- 🎓 M.S. in Data Analytics, Indiana Wesleyan University
- 👯 Open to AI/ML Engineer, Machine Learning Engineer, and Generative AI Engineer roles
- 💬 Ask me about RAG, LLM evaluation, anomaly detection, FastAPI, and data quality
- ⚡ I care about systems that are measurable, easy to inspect, and clear about where they fail

---

## Tech Stack

Used in the projects below:

**AI / ML**  
<img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python" />
<img src="https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white" alt="scikit-learn" />
<img src="https://img.shields.io/badge/XGBoost-189FDD?style=for-the-badge" alt="XGBoost" />
<img src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white" alt="Pandas" />
<img src="https://img.shields.io/badge/LangGraph-1C3C3C?style=for-the-badge&logo=langgraph&logoColor=white" alt="LangGraph" />
<img src="https://img.shields.io/badge/Claude%20API-D97757?style=for-the-badge&logo=anthropic&logoColor=white" alt="Claude API" />
<img src="https://img.shields.io/badge/OpenAI-412991?style=for-the-badge" alt="OpenAI" />

**Backend & Data**  
<img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white" alt="FastAPI" />
<img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white" alt="PostgreSQL" />
<img src="https://img.shields.io/badge/SQL-336791?style=for-the-badge" alt="SQL" />
<img src="https://img.shields.io/badge/Apache%20Kafka-231F20?style=for-the-badge&logo=apachekafka&logoColor=white" alt="Apache Kafka" />
<img src="https://img.shields.io/badge/DuckDB-FFF000?style=for-the-badge&logo=duckdb&logoColor=black" alt="DuckDB" />
<img src="https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white" alt="Streamlit" />
<img src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" alt="React" />
<img src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white" alt="Node.js" />

**Delivery**  
<img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" alt="Docker" />
<img src="https://img.shields.io/badge/GitHub%20Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white" alt="GitHub Actions" />
<img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" alt="Git" />

**Also worked with:** LangChain · Apache Spark · Airflow · AWS · Google Cloud · Kubernetes  
**Areas:** RAG · NLP · anomaly detection · LLM evaluation · REST APIs · ETL/ELT · data quality

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
