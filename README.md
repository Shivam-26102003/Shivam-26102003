<div align="center">

# Shivam Sagar

**Software Engineer building backend systems, AI agents, and ML products.**

*Backend Systems &nbsp;•&nbsp; AI / ML & Agents &nbsp;•&nbsp; Algorithmic Problem Solving*

[LinkedIn](https://www.linkedin.com/in/shivam-sagar-40266225a/) &nbsp;|&nbsp; [Email](mailto:sagarshivam1626@gmail.com) &nbsp;|&nbsp; [GitHub](https://github.com/Shivam-26102003)

</div>

<br/>

<table align="center" width="100%">
  <tr>
    <td align="center" width="16%"><b>🎓 IIIT Bhopal</b><br/><sub>B.Tech CSE (8.50/10)</sub></td>
    <td align="center" width="16%"><b>⚔️ Codeforces</b><br/><sub>Expert (1600+)</sub></td>
    <td align="center" width="16%"><b>🏆 LeetCode</b><br/><sub>Knight (1900+)</sub></td>
    <td align="center" width="16%"><b>🧩 500+ DSA</b><br/><sub>Problems Solved</sub></td>
    <td align="center" width="16%"><b>🥇 CodeChef</b><br/><sub>Global Rank 59</sub></td>
    <td align="center" width="16%"><b>📈 IMC Prosperity</b><br/><sub>Global Rank 727</sub></td>
  </tr>
</table>

<br/>

## 🛠️ What I Build

<table>
<tr>
<td width="33%" valign="top">
<h3 align="center">🧠 AI / ML & Agents</h3>

- **AI Research Agents** with Composio MCP & Ollama
- **Deepfake Video Detection** via ResNeXt-50 + LSTM
- **Multi-Agent Systems** (Planner / Executor / Verifier)
- **Semantic Retrieval** & RAG data pipelines
</td>

<td width="33%" valign="top">
<h3 align="center">⚙️ Backend & Systems</h3>

- **Domain-Driven Design** & Clean Architecture
- **Financial Ledgers** (Double-entry bookkeeping)
- **Transactional Safety** (Pessimistic DB locking)
- **FastAPI, Spring Boot, PostgreSQL, Redis, Docker**
</td>

<td width="33%" valign="top">
<h3 align="center">📈 Quant & Algorithms</h3>

- **Market Making & Arbitrage** algorithms
- **Order Book Analytics** & inventory clearing
- **Options Pricing** (Black-Scholes European model)
- **Competitive Programming** (CF 1600+, LC 1900+)
</td>
</tr>
</table>

<br/>

## 🚀 Featured Projects

<table width="100%">
<tr>
<td width="50%" valign="top">

### 🤖 [Agent Buildability Lab](https://github.com/Shivam-26102003/Agent-Buildability-Lab)
*Evidence-first AI research agent evaluating API access, MCP readiness, and tool coverage across 100 applications.*

- **Tech Stack:** Python, Composio MCP, Ollama, Pydantic, Web Search
- **Architecture:** Multi-source web search & Composio tool lookups → Evidence Ledger (`.jsonl`) → Local LLM synthesis → 20-app verification loop
- **Metrics:** 100 apps across 10 categories, 90/100 Composio lookups completed, 100% verified accuracy on audited claims
- **Links:** [Live Case Study](https://shivam-26102003.github.io/Agent-Buildability-Lab/) &nbsp;|&nbsp; [GitHub Repository](https://github.com/Shivam-26102003/Agent-Buildability-Lab)

</td>
<td width="50%" valign="top">

### 💳 [User Payout Management System](https://github.com/Shivam-26102003/User_Payout_Management_system)
*Financial payout and reconciliation engine designed around strict transactional correctness and API idempotency.*

- **Tech Stack:** FastAPI, PostgreSQL, Redis, Next.js, Docker Compose
- **Architecture:** Modular Monolith with Clean Architecture & Domain-Driven Design (DDD)
- **Key Mechanics:** Double-entry ledger (`ledger_transactions`), pessimistic DB locking (`SELECT FOR UPDATE`), global idempotency key table, Money value object
- **Links:** [GitHub Repository](https://github.com/Shivam-26102003/User_Payout_Management_system)

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🛡️ [Facial Deepfake Video Detection](https://github.com/Shivam-26102003/Facial_Deepfake-video_detection)
*Spatial-temporal deep learning detector extracting frame artifacts and sequence inconsistencies to identify video manipulations.*

- **Tech Stack:** PyTorch, ResNeXt-50, LSTM, OpenCV, Flask, Python
- **Architecture:** ResNeXt-50 CNN extracts 2048-dim spatial feature vectors per frame; LSTM models sequence dependencies across frames
- **Evaluation:** Tested across 6,000 mixed videos (FaceForensics++, DFDC, Celeb-DF v2) achieving **87.8% accuracy** and 89.3% precision
- **Links:** [GitHub Repository](https://github.com/Shivam-26102003/Facial_Deepfake-video_detection)

</td>
<td width="50%" valign="top">

### 📡 [Uptime Monitor](https://github.com/Shivam-26102003/uptime-monitor)
*Containerized full-stack monitoring system tracking endpoint availability and response latencies with live reporting.*

- **Tech Stack:** FastAPI, React 18, TypeScript, PostgreSQL, Docker, nginx
- **Architecture:** APScheduler background worker pings endpoints every 60s; reverse-proxy nginx serves SPA & proxies `/api/*`
- **Features:** Auto-refreshing dashboard, instant check trigger (`POST /check-now`), historical per-URL metrics endpoint
- **Links:** [Live Dashboard](https://uptime-monitor-silk.vercel.app) &nbsp;|&nbsp; [GitHub Repository](https://github.com/Shivam-26102003/uptime-monitor)

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 📊 [IMC Trading Prosperity 2025 Algorithmic System](https://github.com/Shivam-26102003/IMC_Trading_Prosperity_2025)
*Automated market-making and arbitrage trading strategy built for IMC Trading's global algorithmic competition.*

- **Tech Stack:** Python, NumPy, Pandas, Order Book Analytics
- **Key Logic:** Dynamic fair price estimation, order book spread quoting, soft position limits, automated inventory clearing, and PnL analytics
- **Result:** Global Rank **727** out of thousands of participating international teams
- **Links:** [GitHub Repository](https://github.com/Shivam-26102003/IMC_Trading_Prosperity_2025)

</td>
<td width="50%" valign="top">

### ⚙️ [AI Ops Assistant](https://github.com/Shivam-26102003/ai_ops_assistant)
*CLI-based GenAI operations assistant using decoupled multi-agent architectures with real API integrations.*

- **Tech Stack:** Python, OpenAI API, Gemini API, GitHub REST API, OpenWeather API
- **Architecture:** Planner Agent (LLM JSON plan generation) → Executor Agent (API execution with retries) → Verifier Agent (LLM validation & output formatting)
- **Features:** Single & multi-API task execution, rate-limit resilient retry engine, low-temperature deterministic outputs
- **Links:** [GitHub Repository](https://github.com/Shivam-26102003/ai_ops_assistant)

</td>
</tr>
</table>

<br/>

## 🔬 Flagship System Architecture: Agent Buildability Lab

```
                   ┌────────────────────────┐
                   │       apps.json        │
                   │  100 Target Applications│
                   └───────────┬────────────┘
                               │
                               ▼
                   ┌────────────────────────┐
                   │    AI Research Agent   │
                   │   Python Orchestrator  │
                   └───────────┬────────────┘
                               │
               ┌───────────────┴───────────────┐
               ▼                               ▼
     ┌───────────────────┐           ┌───────────────────┐
     │  Free Web Search  │           │   Composio MCP    │
     │ API & Auth Docs   │           │ Tool Discovery    │
     └─────────┬─────────┘           └─────────┬─────────┘
               │                               │
               └───────────────┬───────────────┘
                               ▼
                    ┌─────────────────────┐
                    │   Evidence Ledger   │
                    │   evidence.jsonl    │
                    └──────────┬──────────┘
                               │
                               ▼
                    ┌─────────────────────┐
                    │  Ollama Synthesis   │
                    │  Pydantic Authority │
                    └──────────┬──────────┘
                               │
                               ▼
                    ┌─────────────────────┐
                    │ Verification Audit  │
                    │ 20-App QA Check     │
                    └──────────┬──────────┘
                               │
                               ▼
                    ┌─────────────────────┐
                    │     Case Study      │
                    │     index.html      │
                    └─────────────────────┘
```

<br/>

## 💼 Experience

### **Solvor** — *Software Developer Intern*
- Built embedding-based semantic retrieval pipelines for JEE/GATE question banks.
- Engineered student performance analytics and mock-test data ingestion pipelines.
- Developed high-throughput REST APIs, implementing Redis caching and backend query optimizations.

<br/>

## 🧰 Technical Skills

<table width="100%">
<tr>
<td width="100%" valign="top">

### ⚙️ Backend & Systems Architecture
- **Core Technologies:** FastAPI, Spring Boot, PostgreSQL, Redis, Docker, Flask, Django REST APIs
- **Engineering & Systems Concepts:** System Design, Domain-Driven Design (DDD), Clean Architecture, SOLID Principles, Concurrency, Transactional Safety (Pessimistic Locking `SELECT FOR UPDATE`, Double-Entry Ledgers), API Idempotency, Microservices, Distributed Systems
<br/>
<p align="left">
  <img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white" alt="FastAPI"/>
  <img src="https://img.shields.io/badge/Spring_Boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white" alt="Spring Boot"/>
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white" alt="PostgreSQL"/>
  <img src="https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white" alt="Redis"/>
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" alt="Docker"/>
</p>

</td>
</tr>
<tr>
<td width="100%" valign="top">

### 🧠 AI / ML & Agent Systems
- **Agentic & Tooling Infrastructure:** AI Agents, MCP, Ollama, LLMs, RAG, LangChain, LlamaIndex, Multi-Agent Systems (Planner / Executor / Verifier)
- **Deep Learning & ML Foundations:** PyTorch, TensorFlow, Machine Learning, Deep Learning
- **Vision & Language:** Computer Vision (ResNeXt-50, OpenCV), NLP (Embedding-based Semantic Retrieval), LSTM
<br/>
<p align="left">
  <img src="https://img.shields.io/badge/AI_Agents-0052CC?style=for-the-badge&logo=probot&logoColor=white" alt="AI Agents"/>
  <img src="https://img.shields.io/badge/MCP-8A2BE2?style=for-the-badge&logo=connectwise&logoColor=white" alt="MCP"/>
  <img src="https://img.shields.io/badge/Ollama-000000?style=for-the-badge&logo=ollama&logoColor=white" alt="Ollama"/>
  <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white" alt="PyTorch"/>
  <img src="https://img.shields.io/badge/Computer_Vision-OpenCV-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white" alt="Computer Vision"/>
</p>

</td>
</tr>
</table>

<table width="100%">
<tr>
<td width="60%" valign="top">

### 💻 Languages
- **Core Languages:** Python, C++, Java, TypeScript, JavaScript, SQL
- **Algorithmic Foundations:** Data Structures & Algorithms, Object-Oriented Design (OOD)
<br/>
<p align="left">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python"/>
  <img src="https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white" alt="C++"/>
  <img src="https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white" alt="Java"/>
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white" alt="TypeScript"/>
  <img src="https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=sqlite&logoColor=white" alt="SQL"/>
</p>

</td>
<td width="40%" valign="top">

### 🌐 Frontend
- **Frameworks & UI:** React.js, Next.js, HTML5, CSS3
<br/>
<p align="left">
  <img src="https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black" alt="React"/>
  <img src="https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white" alt="Next.js"/>
</p>

</td>
</tr>
</table>

<br/>

## 🎯 Currently Building

- 🧠 **Evidence-driven AI Agent Infrastructures:** Standardizing tool discovery and automated evaluation ledgers.
- ⚙️ **High-Reliability Financial Systems:** Exploring event-driven ledgering and idempotent transaction execution.
- 📈 **Quantitative Problem Solving:** Studying order book microstructure, market making, and option pricing models.

<br/>

## 📫 Connect with Me

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Shivam_Sagar-0A66C2?style=for-the-badge&logo=linkedin)](https://www.linkedin.com/in/shivam-sagar-40266225a/)
[![Email](https://img.shields.io/badge/Email-sagarshivam1626@gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:sagarshivam1626@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-Shivam--26102003-181717?style=for-the-badge&logo=github)](https://github.com/Shivam-26102003)

</div>
