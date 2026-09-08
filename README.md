<h1 align="center">
  <img
    src="https://capsule-render.vercel.app/api?type=waving&color=0:0F2027,50:2C5364,100:00C6FF&height=190&section=header&text=Sanchit%20Mohite&fontSize=44&fontColor=ffffff&animation=fadeIn&fontAlignY=42"
    width="100%"
  />
</h1>

<p align="center">
  <a href="https://linkedin.com/in/sanchit-mohite">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"/>
  </a>
  <a href="mailto:sanchitmohite15@gmail.com">
    <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white"/>
  </a>
  <a href="https://github.com/sanchitmoh">
    <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white"/>
  </a>
</p>

<p align="center">
  <img
    src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=21&duration=3000&pause=1000&color=00C6FF&center=true&vCenter=true&width=800&lines=Backend+Engineer+%7C+Java+%7C+Spring+Boot;Building+APIs%2C+Caching+%26+Distributed+Systems;RAG+%2F+LLM+Backend+Engineering"
    alt="Typing SVG"
  />
</p>

<p align="center">
  <img
    src="https://komarev.com/ghpvc/?username=sanchitmoh&label=Profile%20Views&color=00C6FF&style=flat"
    alt="Profile Views"
  />
</p>

---

## 👋 About Me

- 🎯 Final-year **MCA** student at KES Shroff College, Mumbai
- ⚙️ Backend engineer focused on **Java, Spring Boot, APIs and distributed systems**
- 🚀 Built Redis caching that reduced seat-check latency by **~40%**
- 🔎 Built Elasticsearch search returning results in **150–200ms** across 10k+ documents
- 🧠 Currently working with **RAG, LLMs, multi-agent pipelines and semantic caching**
- 📫 **sanchitmohite15@gmail.com**

---

## 🛠️ Tech Stack

<p align="center">

<img src="https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white"/>
<img src="https://img.shields.io/badge/Spring_Boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white"/>
<img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white"/>
<img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white"/>

<br/>

<img src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB"/>
<img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white"/>
<img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white"/>
<img src="https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white"/>

<br/>

<img src="https://img.shields.io/badge/Redis-DD0031?style=for-the-badge&logo=redis&logoColor=white"/>
<img src="https://img.shields.io/badge/Elasticsearch-005571?style=for-the-badge&logo=elasticsearch&logoColor=white"/>
<img src="https://img.shields.io/badge/AWS-FF9900?style=for-the-badge&logo=amazonaws&logoColor=white"/>
<img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white"/>

<br/>

<img src="https://img.shields.io/badge/Kafka-000000?style=for-the-badge&logo=apachekafka&logoColor=white"/>
<img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white"/>
<img src="https://img.shields.io/badge/JWT-black?style=for-the-badge&logo=jsonwebtokens&logoColor=white"/>

</p>

---

## 🚀 Featured Engineering Projects

<p align="center">
  <em>Architected for high concurrency, low latency, and distributed intelligence.</em>
</p>

<table>
<tr>

<td width="50%" valign="top">

<div align="center">
  <a href="https://github.com/sanchitmoh/Evenzaa">
    <img src="https://img.shields.io/badge/Project-Evenza_Event_Platform-00C6FF?style=for-the-badge&logo=spring&logoColor=white&labelColor=0F2027" width="100%"/>
  </a>
</div>

### 🎟️ [Evenza — Event Booking Platform](https://github.com/sanchitmoh/Evenzaa)
> *Microservices-based event ticketing platform engineered for zero overselling and high concurrent throughput.*

<p>
  <img src="https://img.shields.io/badge/Latency-~40%25_Lower-00C6FF?style=flat-square&logo=speedtest&logoColor=white"/>
  <img src="https://img.shields.io/badge/Transactions-Idempotent-success?style=flat-square"/>
  <img src="https://img.shields.io/badge/Locking-Row--Level-blue?style=flat-square"/>
</p>

- ⚡ **Redis In-Memory Caching:** Slashed seat availability query response time by **~40%** under peak traffic.
- 🔒 **Race-Condition Elimination:** Database row-level pessimistic locking (`PESSIMISTIC_WRITE`) guarantees zero double-bookings.
- 💳 **Resilient Payments:** Razorpay webhook handling with automated, idempotent refund workflows and state machines.

<details>
  <summary><b>🔍 Deep Dive: Architecture & Engineering</b></summary>

  - **Concurrency Model:** Redis atomic decrements for instant seat availability verification coupled with transactional database locks at checkout.
  - **Modular Architecture:** Spring Boot backend with clean layered design (Controllers, Services, Repositories, DTOs).
  - **Security & Integrity:** Stateless JWT authentication with role-based access control (RBAC) and BCrypt password hashing.
</details>

<br/>

<div align="center">
  <a href="https://github.com/sanchitmoh/Evenzaa"><img src="https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white"/></a>
  <a href="https://github.com/sanchitmoh/Evenzaa"><img src="https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white"/></a>
  <a href="https://github.com/sanchitmoh/Evenzaa"><img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white"/></a>
  <a href="https://github.com/sanchitmoh/Evenzaa"><img src="https://img.shields.io/badge/Razorpay-02042B?style=flat-square&logo=razorpay&logoColor=3395FF"/></a>
  <a href="https://github.com/sanchitmoh/Evenzaa"><img src="https://img.shields.io/badge/View_Repo_→-181717?style=flat-square&logo=github&logoColor=white"/></a>
</div>

</td>

<td width="50%" valign="top">

<div align="center">
  <a href="https://github.com/sanchitmoh/corporate-digital-library-yv">
    <img src="https://img.shields.io/badge/Project-Corporate_Digital_Library-00C6FF?style=for-the-badge&logo=elasticsearch&logoColor=white&labelColor=0F2027" width="100%"/>
  </a>
</div>

### 📚 [Corporate Digital Library](https://github.com/sanchitmoh/corporate-digital-library-yv)
> *Enterprise document lifecycle system featuring distributed search indexing and cloud persistence.*

<p>
  <img src="https://img.shields.io/badge/Search_Latency-150--200ms-00C6FF?style=flat-square&logo=speedtest&logoColor=white"/>
  <img src="https://img.shields.io/badge/Scale-10k+_Docs-purple?style=flat-square"/>
  <img src="https://img.shields.io/badge/Storage-AWS_S3-orange?style=flat-square&logo=amazonaws&logoColor=white"/>
</p>

- 🔎 **Sub-Second Search:** Elasticsearch integration delivering **150–200ms query latency** across 10,000+ indexed enterprise documents.
- ☁️ **Cloud Storage Pipeline:** Automated document versioning and storage pipeline backed by AWS S3 with signed retrieval URLs.
- 🛡️ **Access Governance:** Granular RBAC enforcing document-level visibility policies and immutable audit trails.

<details>
  <summary><b>🔍 Deep Dive: Architecture & Engineering</b></summary>

  - **Elasticsearch Ingestion:** Custom analyzer pipelines with multi-field tokenization, edge n-grams, and typo-tolerant fuzzy matching.
  - **Storage Lifecycle:** Tiered document storage with automated scheduled backups to Amazon S3 buckets.
  - **Relational Integrity:** Normalized MySQL schema optimized with composite indexes for fast permission checks.
</details>

<br/>

<div align="center">
  <a href="https://github.com/sanchitmoh/corporate-digital-library-yv"><img src="https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white"/></a>
  <a href="https://github.com/sanchitmoh/corporate-digital-library-yv"><img src="https://img.shields.io/badge/Elasticsearch-005571?style=flat-square&logo=elasticsearch&logoColor=white"/></a>
  <a href="https://github.com/sanchitmoh/corporate-digital-library-yv"><img src="https://img.shields.io/badge/AWS_S3-569A31?style=flat-square&logo=amazons3&logoColor=white"/></a>
  <a href="https://github.com/sanchitmoh/corporate-digital-library-yv"><img src="https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white"/></a>
  <a href="https://github.com/sanchitmoh/corporate-digital-library-yv"><img src="https://img.shields.io/badge/View_Repo_→-181717?style=flat-square&logo=github&logoColor=white"/></a>
</div>

</td>

</tr>

<tr>

<td width="50%" valign="top">

<div align="center">
  <a href="https://github.com/sanchitmoh/CFO">
    <img src="https://img.shields.io/badge/Project-AI_CFO_Intelligence-00C6FF?style=for-the-badge&logo=openai&logoColor=white&labelColor=0F2027" width="100%"/>
  </a>
</div>

### 📊 [AI CFO — Financial Intelligence Platform](https://github.com/sanchitmoh/CFO)
> *Autonomous financial intelligence copilot for predictive cash-flow forecasting and ledger anomaly detection.*

<p>
  <img src="https://img.shields.io/badge/Prediction_Accuracy-~97%25-00C6FF?style=flat-square&logo=target&logoColor=white"/>
  <img src="https://img.shields.io/badge/Pipeline-GPT_RAG-success?style=flat-square&logo=openai&logoColor=white"/>
  <img src="https://img.shields.io/badge/Backend-FastAPI-teal?style=flat-square&logo=fastapi&logoColor=white"/>
</p>

- 🧠 **Contextual RAG Pipelines:** Domain-adapted LLM agent querying structured balance sheets, invoices, and expense ledgers.
- 🎯 **Predictive Precision:** Reached **~97% prediction accuracy** on multi-month payroll projections and cash-burn simulations.
- 🚨 **Real-Time Anomaly Engine:** Outlier detection flagging unauthorized deviations and spend variance before reporting.

<details>
  <summary><b>🔍 Deep Dive: Architecture & Engineering</b></summary>

  - **Retrieval Architecture:** Chunking & embedding pipeline converting financial statements into dense vector representations for grounded answers.
  - **High-Throughput API:** Asynchronous FastAPI backend with strict Pydantic schemas and database connection pooling.
  - **Observability:** Token usage tracking, latency telemetry, and guardrails to prevent hallucination in financial summaries.
</details>

<br/>

<div align="center">
  <a href="https://github.com/sanchitmoh/CFO"><img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white"/></a>
  <a href="https://github.com/sanchitmoh/CFO"><img src="https://img.shields.io/badge/OpenAI-412991?style=flat-square&logo=openai&logoColor=white"/></a>
  <a href="https://github.com/sanchitmoh/CFO"><img src="https://img.shields.io/badge/PostgreSQL-316192?style=flat-square&logo=postgresql&logoColor=white"/></a>
  <a href="https://github.com/sanchitmoh/CFO"><img src="https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB"/></a>
  <a href="https://github.com/sanchitmoh/CFO"><img src="https://img.shields.io/badge/View_Repo_→-181717?style=flat-square&logo=github&logoColor=white"/></a>
</div>

</td>

<td width="50%" valign="top">

<div align="center">
  <a href="https://github.com/sanchitmoh/GSTENV">
    <img src="https://img.shields.io/badge/Project-GST_Agent_Environment-00C6FF?style=for-the-badge&logo=python&logoColor=white&labelColor=0F2027" width="100%"/>
  </a>
</div>

### 🧾 [GST Agent Environment](https://github.com/sanchitmoh/GSTENV)
> *OpenEnv simulation framework where autonomous agents execute complex tax reconciliation workflows.*

<p>
  <img src="https://img.shields.io/badge/Turnaround-Days_→_Minutes-00C6FF?style=flat-square&logo=clock&logoColor=white"/>
  <img src="https://img.shields.io/badge/Matching-Deterministic-success?style=flat-square"/>
  <img src="https://img.shields.io/badge/Environment-OpenEnv-orange?style=flat-square"/>
</p>

- ⚡ **Order-of-Magnitude Speedup:** Compressed standard Indian tax reconciliation cycles from **several days down to minutes**.
- 🧩 **Multi-Agent Deliberation:** Autonomous agents handling invoice parsing, Input Tax Credit (ITC) mismatch detection, and filing synthesis.
- ⚖️ **Deterministic Guardrails:** Hard mathematical rules for tax math, using LLMs only for fuzzy edge cases and reason-coded summaries.

<details>
  <summary><b>🔍 Deep Dive: Architecture & Engineering</b></summary>

  - **RL/Agent Environment:** Structured state-space mimicking real Indian GST portal rules, invoice schemas, and GSTR forms.
  - **Automated Matching:** Three-way matching between vendor invoices, purchase registers, and portal data with audit-ready exception codes.
  - **Modular Runtime:** Containerized Docker environment with HuggingFace integrations for offline evaluation.
</details>

<br/>

<div align="center">
  <a href="https://github.com/sanchitmoh/GSTENV"><img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white"/></a>
  <a href="https://github.com/sanchitmoh/GSTENV"><img src="https://img.shields.io/badge/Multi--Agent-FF6F00?style=flat-square"/></a>
  <a href="https://github.com/sanchitmoh/GSTENV"><img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white"/></a>
  <a href="https://github.com/sanchitmoh/GSTENV"><img src="https://img.shields.io/badge/HuggingFace-FFD21E?style=flat-square&logo=huggingface&logoColor=black"/></a>
  <a href="https://github.com/sanchitmoh/GSTENV"><img src="https://img.shields.io/badge/View_Repo_→-181717?style=flat-square&logo=github&logoColor=white"/></a>
</div>

</td>

</tr>
</table>

<details>
  <summary><b>🔥 Spotlight Project: AI-Powered 3-Way Reconciliation Agent (Razorpay / Banking)</b></summary>
  <br/>

  > Autonomous reconciliation system performing three-way matching between Razorpay transaction feeds, bank settlement statements, and internal ERP ledgers.

  - 🎯 **Hybrid Matching Engine:** Employs 100% deterministic rules for standard transactions; routes ambiguous edge-cases to LLM agents.
  - 🔍 **Explainability First:** Produces audit-ready, reason-coded exception logs rather than opaque verdicts.
  - 🔗 **[Explore sanchitmoh/Razorpay on GitHub →](https://github.com/sanchitmoh/Razorpay)**
</details>

<p align="center">
  <a href="https://github.com/sanchitmoh?tab=repositories">
    <img src="https://img.shields.io/badge/Explore_All_Repositories_→-00C6FF?style=for-the-badge&logo=github&logoColor=black&labelColor=0F2027"/>
  </a>
</p>

---

## 📈 GitHub Stats

<p align="center">
  <img
    height="170"
    src="https://github-readme-stats-eight-theta.vercel.app/api?username=sanchitmoh&show_icons=true&theme=tokyonight&hide_border=true&count_private=true&include_all_commits=true"
    alt="GitHub Stats"
  />
  <img
    height="170"
    src="https://streak-stats.demolab.com/?user=sanchitmoh&theme=tokyonight&hide_border=true"
    alt="GitHub Streak"
  />
</p>

<p align="center">
  <img
    height="170"
    src="https://github-readme-stats-eight-theta.vercel.app/api/top-langs/?username=sanchitmoh&layout=compact&theme=tokyonight&hide_border=true&langs_count=8"
    alt="Top Languages"
  />
</p>

---

## 🐍 Contribution Graph

<p align="center">
  <img
    src="https://raw.githubusercontent.com/sanchitmoh/sanchitmoh/gh-pages/github-contribution-grid-snake.svg"
    alt="GitHub Contribution Snake"
  />
</p>

---

<p align="center">
  <em>Backend systems that hold up under load — that's the job.</em>
</p>

<img
  src="https://capsule-render.vercel.app/api?type=waving&color=0:00C6FF,100:0F2027&height=100&section=footer"
  width="100%"
/>
