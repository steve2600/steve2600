<!-- Centered Header -->
<h1 align="center">Hi, I'm Steve Sunny Subhash</h1>
<h3 align="center">NLP · RAG Systems · Data Engineering | B.Tech CSE @ VIT Vellore</h3>



<p align="center">
  <a href="https://linkedin.com/in/steve-sunny-subhash-850951317" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" />
  </a>
  <a href="https://github.com/steve2600" target="_blank">
    <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" />
  </a>
  <a href="mailto:stevesunnysubhash@gmail.com">
    <img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white" />
  </a>
</p>

---

## 🚀 Featured Projects

### ⚖️ [Verdicto-AI — Legal Intelligence Platform](https://github.com/steve2600/Verdicto-AI-1)
**Stack:** `Python` · `LangChain` · `Weaviate` · `FastAPI` · `InLegalBERT` · `Docker` · `GitHub Actions`

> 🥉 **3rd Place — Hack Elite Hackathon (National Level, SRM University, Oct 2025)**

**Description:** AI-powered legal analytics platform processing 1,000+ Indian court case documents (1950–2024) with 80%+ verdict prediction accuracy, cutting analysis time by 2×.

**Highlights:**
- Hybrid RAG pipeline with LangChain + Weaviate re-ranking → **35% better retrieval relevance**, P95 latency **<800ms**
- Fine-tuned InLegalBERT on **26,680 legal documents** → **+12% F1 score**
- Automated bias detection across 7 categories (gender, caste, religion, region, etc.)
- FastAPI backend with Docker + GitHub Actions CI/CD for reliable multi-user uptime

---

### 🏥 [T.R.I.A.G.E. — Clinical Risk Stratification Platform](https://github.com/steve2600/T.R.I.A.G.E)
**Stack:** `Python` · `scispaCy (BC5CDR)` · `medspaCy ConText` · `FastAPI`

**Description:** Deterministic clinical deterioration scoring engine over 11 physiological features with interpretable, auditable outputs — no black-box ML.

**Highlights:**
- Replaced regex symptom extraction with **scispaCy NER + medspaCy negation resolution** — fixed a critical patient safety bug where negated symptoms were scored as active findings
- Surge forecasting via hour-of-day statistical averaging (μ + 1.5σ) — reproducible statistical baseline over training-dependent models
- ML as an **optional enhancement layer with graceful degradation** — full triage functions without the ML service

---

### 📋 [Insurance Policy Q&A RAG System](https://github.com/steve2600/Fast-Insurance-Q-A-RAG-HackRx-6.0)
**Stack:** `Voyage AI` · `BM25` · `CrossEncoder` · `Weaviate` · `Groq` · `FastAPI`

> 🏆 **Top 75 Nationally — Bajaj Finserv HackerX 2025**

**Description:** Production-grade RAG pipeline over 1,000+ insurance policy documents with sub-second latency and high-accuracy retrieval.

**Highlights:**
- Hybrid retrieval (Voyage embeddings + BM25) with CrossEncoder re-ranking → **35% better relevance vs keyword search**
- Semantic chunking + batch embedding uploads (**128 docs/batch**) to Weaviate
- Handles **10+ concurrent queries** with **99.9% uptime**, P95 latency **<800ms**
- Human-validated on **100 edge-case queries**

---

### 🛒 [Cartelligence — Retail Intelligence Platform](https://github.com/steve2600/Cartelligence)
**Stack:** `Apache Airflow` · `PostgreSQL` · `FastAPI` · `React` · `Pandas` · `Docker`

**Description:** End-to-end retail data platform with production ETL pipelines, a star-schema warehouse, and an analytics-ready React dashboard.

**Highlights:**
- ETL DAGs (full load, daily incremental, 5-min micro-batch) ingesting **3M+ rows** across CSV, Parquet, PostgreSQL
- Handles **1.5GB+ raw data** with SCD Type 2 patterns + automated schema drift detection
- Star-schema warehouse with materialized views, DB triggers, and data quality checks (nulls, range, duplicates)
- FastAPI backend with **JWT auth + RBAC**; React dashboard with Apriori market basket analysis & customer segmentation

---

## 🛠 Core Tech Stack

<p align="center">

<b>ML & AI</b><br>
<img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" />
<img src="https://img.shields.io/badge/LangChain-1E1E1E?style=for-the-badge&logo=ai&logoColor=white" />
<img src="https://img.shields.io/badge/HuggingFace-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black" />
<img src="https://img.shields.io/badge/Weaviate-7A62B5?style=for-the-badge&logo=weaviate&logoColor=white" />
<img src="https://img.shields.io/badge/VoyageAI-0A0A0A?style=for-the-badge&logo=ai&logoColor=white" />
<img src="https://img.shields.io/badge/Groq-1F1F1F?style=for-the-badge&logo=groq&logoColor=white" />
<img src="https://img.shields.io/badge/scispaCy-4B8BBE?style=for-the-badge&logo=python&logoColor=white" />
<img src="https://img.shields.io/badge/XGBoost-FF6600?style=for-the-badge&logo=python&logoColor=white" />

<br><br>

<b>Backend & Data</b><br>
<img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white" />
<img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white" />
<img src="https://img.shields.io/badge/Apache_Airflow-017CEE?style=for-the-badge&logo=apacheairflow&logoColor=white" />
<img src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white" />
<img src="https://img.shields.io/badge/SQLite-003B57?style=for-the-badge&logo=sqlite&logoColor=white" />

<br><br>

<b>Frontend</b><br>
<img src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" />
<img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white" />
<img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" />

<br><br>

<b>Tools & DevOps</b><br>
<img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" />
<img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white" />
<img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" />
<img src="https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black" />
<img src="https://img.shields.io/badge/Oracle_Cloud-F80000?style=for-the-badge&logo=oracle&logoColor=white" />
<img src="https://img.shields.io/badge/Power_BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black" />
<img src="https://img.shields.io/badge/Jupyter-FF9933?style=for-the-badge&logo=jupyter&logoColor=white" />

</p>

---

## 🏅 Achievements & Certifications

- 🥉 **3rd Place — Hack Elite Hackathon** (National Level, SRM University, Oct 2025) — Verdicto-AI
- 🏆 **Top 75 Nationally — Bajaj Finserv HackerX 2025** — Insurance RAG Pipeline
- 🎯 **Finalist — IIT Hyderabad Elan & ηVision Hackathon**
- ☁️ **Oracle Cloud Infrastructure 2025 Certified AI Foundations Associate**
- 🎓 **NVIDIA Deep Learning Institute** — Building Real-Time Video AI Applications
- 🐍 **IBM** — Python for Data Science, AI & Development
- 🗄️ **University of Michigan** — Introduction to Structured Query Language (SQL)

---

## 📊 GitHub Stats

<table><tr><td valign="top" width="50%">
<img src="https://github-readme-stats.vercel.app/api?username=steve2600&show_icons=true&theme=github_dark&hide_border=true" align="left" style="width: 100%" />
</td><td valign="top" width="50%">
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=steve2600&layout=compact&theme=github_dark&hide_border=true" align="left" style="width: 100%" />
</td></tr></table>

---

## 👤 About Me

I'm a 2nd-year B.Tech CSE undergrad at **VIT Vellore** (CGPA: 9.61) building intelligent systems at the intersection of NLP, ML, and backend engineering. My build style? Ship fast, iterate faster.

- 🔍 Architecting **RAG pipelines** — semantic chunking, hybrid retrieval, vector stores, re-ranking
- ⚙️ Building **data engineering systems** — ETL, Airflow DAGs, star schemas, SCD patterns
- 🏥 Exploring **clinical NLP** — NER, negation resolution, deterministic scoring engines
- 🧠 Fine-tuning **domain-specific LLMs** — legal, clinical, and financial document understanding

---

![Profile views](https://komarev.com/ghpvc/?username=steve2600&style=flat-square)

*"Build it scrappy. Make it scale."*
