# Hi, I'm Aayush Tripathi 👋

### ⚡ Distributed Systems, Agentic AI & Systems Engineer
**ECE Undergrad @ The LNM Institute of Information Technology (LNMIIT), Jaipur**

Building fault-tolerant distributed backends, autonomous AI agent runtimes, and local SLM inference pipelines. Passionate about systems that scale reliably under load, deterministic policy governance, and real-world applied ML engines.

- 🔭 Building **[Chrona](https://github.com/tripathi-aayush/Chrona)** — a distributed, fault-tolerant job scheduler in Go with leader election, atomic worker leasing, and crash recovery.
- 🛡️ Architecting **[ambit](https://github.com/tripathi-aayush/ambit)** — a runtime and policy governance engine that safely sandboxes and evaluates AI coding agents with OPA/Rego and DinD.
- 🧠 Fine-tuning **[Adaptive Conversational Agent](https://github.com/tripathi-aayush/adaptive_conversational_agent)** — hybrid local SLM (Phi-3 GGUF) + cloud LLM (Groq Llama 3.3) with mathematical momentum scoring.
- ⚡ Engineered **[NTPC-NVVN](https://github.com/tripathi-aayush/NTPC-NVVN)** — industrial real-time electrical demand forecasting engine for Indian state power grids with LightGBM & Django.
- 🤖 Co-building **[ForgeAI](https://github.com/tripathi-aayush/ForgeAI)** — autonomous codebase intelligence & bug-fixing engine with pgvector RAG and execution sandboxing.
- 💬 Created **[code_together](https://github.com/tripathi-aayush/code_together)** — collaborative real-time code editor with remote cursors and room state persistence.

---

### 🏆 Experience & Achievements

#### 🏢 IT Intern — **NTPC Limited** *(June – July 2026 | Noida, India)*
* **System Architecture:** Architected an end-to-end, per-state power demand forecasting platform for **NTPC-NVVN** across **33 Indian states/UTs** on a three-layer Django + SQLite + APScheduler stack, enabling new states to onboard via a single YAML config with zero code changes.
* **Modeling & Feature Engineering:** Trained and tuned per-state LightGBM models (50-trial Optuna search, SHAP-validated) on a strict temporal split with a **five-tier lag-fallback chain** and autoregressive chaining to extend forecasts to 16 days, achieving **0.91% MAPE / $R^2 = 0.9960$** on held-out data.
* **Reliability Engineering:** Root-caused a 100% live-data outage to MERIT India's geo-IP block via production logs and engineered a redundant Vercel Mumbai-region proxy layer with automated 3-minute retry sweeps, restoring live inference at zero infrastructure cost.
* **Production Hardening:** Diagnosed and resolved Gunicorn worker-timeout crashes, model-cache invalidation bugs, and monitoring false-positives directly from production telemetry.

#### 🥇 Meta PyTorch OpenEnv Hackathon — Scaler School of Technology
* Designed & built **[emailtriage](https://github.com/tripathi-aayush/emailtriage)**, an autonomous hybrid Q-learning + LLM reinforcement learning agent achieving **99.0% accuracy (100% on test cases)** across easy, medium, and edge-case classification tiers.

---

### 🛠 Tech Stack

#### Languages
<p>
  <img src="https://img.shields.io/badge/Go-00ADD8?style=for-the-badge&logo=go&logoColor=white" alt="Go" />
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white" alt="TypeScript" />
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript" />
  <img src="https://img.shields.io/badge/C%2B%2B-00599C?style=for-the-badge&logo=c%2B%2B&logoColor=white" alt="C++" />
  <img src="https://img.shields.io/badge/C-A8B9CC?style=for-the-badge&logo=c&logoColor=black" alt="C" />
  <img src="https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=postgresql&logoColor=white" alt="SQL" />
</p>

#### Distributed Systems & Backend
<p>
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white" alt="PostgreSQL" />
  <img src="https://img.shields.io/badge/Redis_Streams-DC382D?style=for-the-badge&logo=redis&logoColor=white" alt="Redis Streams" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" alt="Docker" />
  <img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white" alt="FastAPI" />
  <img src="https://img.shields.io/badge/Django-092E20?style=for-the-badge&logo=django&logoColor=white" alt="Django" />
  <img src="https://img.shields.io/badge/Node.js-5FA04E?style=for-the-badge&logo=node.js&logoColor=white" alt="Node.js" />
  <img src="https://img.shields.io/badge/Socket.io-010101?style=for-the-badge&logo=socket.io&logoColor=white" alt="Socket.io" />
</p>

#### AI, ML & Runtimes
<p>
  <img src="https://img.shields.io/badge/Local_SLM_(Phi--3)-0078D4?style=for-the-badge&logo=microsoft&logoColor=white" alt="Phi-3" />
  <img src="https://img.shields.io/badge/Groq_Cloud-F55036?style=for-the-badge&logo=groq&logoColor=white" alt="Groq" />
  <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white" alt="PyTorch" />
  <img src="https://img.shields.io/badge/LightGBM-4B0082?style=for-the-badge&logo=scikit-learn&logoColor=white" alt="LightGBM" />
  <img src="https://img.shields.io/badge/pgvector-336791?style=for-the-badge&logo=postgresql&logoColor=white" alt="pgvector" />
  <img src="https://img.shields.io/badge/Open_Policy_Agent_(OPA)-7D26CD?style=for-the-badge&logo=open-policy-agent&logoColor=white" alt="OPA" />
</p>

#### Frontend & Tools
<p>
  <img src="https://img.shields.io/badge/Next.js_16-000000?style=for-the-badge&logo=next.js&logoColor=white" alt="Next.js" />
  <img src="https://img.shields.io/badge/React_19-61DAFB?style=for-the-badge&logo=react&logoColor=black" alt="React" />
  <img src="https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white" alt="Streamlit" />
  <img src="https://img.shields.io/badge/Prometheus-E6522C?style=for-the-badge&logo=prometheus&logoColor=white" alt="Prometheus" />
  <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" alt="Git" />
</p>

---

### 🚀 Featured Projects

| Project | Description | Tech Stack |
| :--- | :--- | :--- |
| **[Chrona](https://github.com/tripathi-aayush/Chrona)** | Fault-tolerant distributed job scheduler featuring delayed/recurring tasks, atomic worker leasing, multi-node leader election, crash recovery, and Prometheus observability. | `Go` `Redis Streams` `PostgreSQL` `Docker` `Prometheus` |
| **[ambit](https://github.com/tripathi-aayush/ambit)** | Runtime & policy engine that governs AI coding agents. Uses deterministic risk scoring, OPA Rego policies, and isolated Docker-in-Docker command sandboxes. | `FastAPI` `Next.js 16` `OPA/Rego` `pgvector` `DinD` |
| **[Adaptive Conversational Agent](https://github.com/tripathi-aayush/adaptive_conversational_agent)** | Hybrid performance-based interview bot combining a local fine-tuned Phi-3 SLM for fast triage with Groq Llama-3.3-70B reasoning and sliding-window momentum scoring. | `Python` `Phi-3 (GGUF)` `Groq` `Streamlit` `Plotly` |
| **[ForgeAI](https://github.com/tripathi-aayush/ForgeAI)** | Autonomous codebase intelligence & bug-fixing engine with pgvector RAG indexing, Monaco diff editor, BullMQ queues, and sandboxed code execution. | `Next.js 16` `TypeScript` `Express` `Prisma` `BullMQ` `Redis` |
| **[NTPC-NVVN Demand Predictor](https://github.com/tripathi-aayush/NTPC-NVVN)** | Grid-scale real-time electrical power demand forecasting dashboard for Indian states with 96-slot rolling forecasts and MERIT API integration. | `Python` `Django` `LightGBM` `REST API` `Pytest` |
| **[code_together](https://github.com/tripathi-aayush/code_together)** | Collaborative in-browser code editor with real-time remote cursors, file tree synchronization, room state persistence, and activity feeds. | `React 19` `TypeScript` `Socket.IO` `Monaco` `Prisma` `Postgres` |
| **[emailtriage](https://github.com/tripathi-aayush/emailtriage)** | Hybrid Q-learning + LLM reinforcement learning agent for high-precision email classification (Meta PyTorch OpenEnv Hackathon — 99% accuracy). | `PyTorch` `Q-Learning` `FastAPI` `Docker` `Groq` |

---

### 📊 GitHub Activity

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=tripathi-aayush&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" width="48%" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=tripathi-aayush&layout=compact&theme=tokyonight&hide_border=true" width="48%" />
</div>
