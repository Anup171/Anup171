<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=220&section=header&text=Anup%20Bhandarkar&fontSize=42&fontColor=ffffff&animation=fadeIn&fontAlignY=38&desc=CSE%20(Data%20Science)%20Undergraduate%20%7C%20Backend%20Engineering%20%7C%20Agentic%20AI&descAlignY=55&descAlign=50" width="100%" alt="Anup Bhandarkar banner"/>

<a href="https://git.io/typing-svg">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&pause=1000&color=A78BFA&center=true&vCenter=true&width=650&lines=Building+Reliable+Backend+Systems;FastAPI+%7C+PostgreSQL+%7C+Node.js;LangGraph+%7C+LangChain+%7C+Agentic+AI;300%2B+DSA+Problems+Solved" alt="Typing SVG" />
</a>

<br/>

![CGPA](https://img.shields.io/badge/CGPA-9.31%2F10-6D28D9?style=flat-square&labelColor=1e1b2e)
![PUC](https://img.shields.io/badge/PUC-97.1%25-7C3AED?style=flat-square&labelColor=1e1b2e)
![Location](https://img.shields.io/badge/Location-Bengaluru%2C%20India-4C1D95?style=flat-square&labelColor=1e1b2e)

<br/>

<a href="https://www.linkedin.com/in/anup-bhandarkar/"><img src="https://skillicons.dev/icons?i=linkedin" height="40" alt="LinkedIn" /></a>&nbsp;&nbsp;
<a href="mailto:anupbhandarkar171@gmail.com"><img src="https://skillicons.dev/icons?i=gmail" height="40" alt="Email" /></a>&nbsp;&nbsp;
<a href="https://github.com/Anup171"><img src="https://skillicons.dev/icons?i=github" height="40" alt="GitHub" /></a>

<br/><br/>

![Profile Views](https://komarev.com/ghpvc/?username=Anup171&color=6D28D9&style=for-the-badge&label=PROFILE+VIEWS)
![Followers](https://img.shields.io/github/followers/Anup171?style=for-the-badge&color=7C3AED&labelColor=1e1b2e&label=FOLLOWERS)
![Stars](https://img.shields.io/github/stars/Anup171?style=for-the-badge&color=4C1D95&labelColor=1e1b2e&label=STARS)

</div>

---

### 👋 About Me

I'm a **Computer Science and Engineering (Data Science) undergraduate** at **BMS College of Engineering, Bengaluru**, pursuing a B.E. since September 2024. I build backend and full-stack systems alongside agentic AI applications, with a focus on reliability, clear APIs, and useful product experiences.

My projects span **fault-tolerant uptime monitoring**, **multi-agent research with citation-backed synthesis**, and **real-time notification delivery**. I enjoy working across system design, asynchronous services, data stores, and LLM-powered workflows.

**Areas of Interest:**
- Software engineering: backend and full-stack systems
- Distributed systems, reliability, and API design
- Agentic AI, RAG, and LLM applications

---

### 🎓 Education

| Program | Institution | Result | Period |
|---|---|---|---|
| B.E. in Computer Science and Engineering (Data Science) | BMS College of Engineering, Bengaluru | CGPA: 9.31/10 | Sep. 2024 – Present |
| Karnataka Pre-University Course (II PUC) | Deeksha CFL PU College, Bengaluru | 97.1% | Apr. 2023 – Mar. 2024 |

---

### 🛠️ Tech Stack

**Languages**

<p><img src="https://skillicons.dev/icons?i=java,cpp,py,js" alt="Java, C++, Python, JavaScript" /></p>

Java · C++ · Python · JavaScript · SQL

**Backend & APIs**

<p><img src="https://skillicons.dev/icons?i=nodejs,express,fastapi,postman" alt="Node.js, Express, FastAPI, Postman" /></p>

REST APIs · JWT · WebSockets · Socket.IO · Pydantic

**Databases & Caching**

<p><img src="https://skillicons.dev/icons?i=postgresql,mysql,mongodb,redis" alt="PostgreSQL, MySQL, MongoDB, Redis" /></p>

**Frontend**

<p><img src="https://skillicons.dev/icons?i=react" alt="React" /></p>

**Cloud, DevOps & Tooling**

<p><img src="https://skillicons.dev/icons?i=docker,aws,githubactions,git,github" alt="Docker, AWS, GitHub Actions, Git, GitHub" /></p>

**AI / LLM Systems**

LangChain · LangGraph · Agentic AI (Multi-Agent Systems) · Retrieval-Augmented Generation (RAG) · Prompt Engineering · Embeddings · Vector Databases · SentenceTransformers

**Core CS**

Data Structures & Algorithms · Object-Oriented Programming · System Design · Operating Systems · DBMS · Computer Networks · Computer Organization and Architecture

---

### 🧠 AI & Systems Expertise

<div align="center">

| Area | Experience |
|---|---|
| **Agentic AI** | LangGraph workflows coordinating four specialized agents |
| **Research & RAG** | Multi-step planning, source credibility scoring, citation-backed synthesis (APA, IEEE) |
| **Backend Systems** | FastAPI and Node.js services, asynchronous workers, REST APIs, WebSockets |
| **Reliability** | PostgreSQL row-level locking and leases, circuit breakers, retries, SQLite checkpointing |
| **Data & Caching** | PostgreSQL, MySQL, MongoDB, Redis, idempotent deduplication, TTL-based caching |
| **LLM Applications** | OpenRouter integration, token and cost telemetry, deterministic fallbacks |

</div>

---

### 🚀 Featured Projects

<details open>
<summary><b>⏱️ PulseWatch — Uptime Monitoring & Incident Platform</b></summary>
<br/>

Built a scalable, fault-tolerant uptime monitoring system with an asynchronous probe engine, a distributed job scheduler, incident detection, and LLM-assisted root-cause summaries.

| Aspect | Detail |
|---|---|
| **Stack** | FastAPI, Python, PostgreSQL, Asyncio, React.js, OpenRouter |
| **Probing** | 20 concurrent async probes over HTTP/TCP at 15-second intervals, with SSRF protection and SSL certificate monitoring |
| **Scheduling** | PostgreSQL `SELECT ... FOR UPDATE SKIP LOCKED` with 30-second leases, achieving 0% duplicate checks across horizontally scaled replicas |
| **Incident Detection** | State machine (3 consecutive failures, 10-second re-probe) that cut 95% of false-positive alerts; notifications via REST webhooks to multiple channels |
| **AI** | Root-cause summaries from 5-stage HTTP telemetry in under 1.5 seconds, backed by a 100% deterministic fallback |
| **Links** | [Live Demo](https://pulse-watch-xi.vercel.app) · [Repository](https://github.com/Anup171/PulseWatch) |

</details>

<details open>
<summary><b>🧩 Veritas AI — Autonomous Multi-Agent Research System</b></summary>
<br/>

Built a multi-agent research platform with LangGraph and LangChain that orchestrates four autonomous agents to plan research objectives and produce structured, cited reports.

| Aspect | Detail |
|---|---|
| **Stack** | Python, LangGraph, LangChain, Docker, Chainlit, Pydantic |
| **Research** | Plans 3–5 objectives and generates 8-section reports with APA and IEEE citations |
| **Credibility** | 0–100 source scoring across 50+ trusted domains; filters sources below 40 and prioritizes high-authority data (70+) for conflict resolution |
| **Resilience** | 3-state circuit breaker (5-failure threshold, 30-second reset) and SQLite checkpointing, enabling 100% state recovery after process crashes |
| **Efficiency** | MD5-keyed caching layer (7-day TTL) to cut redundant LLM calls; real-time token and cost monitoring; containerized with Docker |
| **Links** | [Live Demo](https://veritas-ai-xkah.onrender.com) · [Repository](https://github.com/Anup171/Veritas-AI) |

</details>

<details open>
<summary><b>🔔 NotifyX — Real-Time Notification Platform</b></summary>
<br/>

Built an event-driven, asynchronous notification service in Node.js and Express.js with idempotent delivery, WebSocket messaging, offline sync, and multi-tenant API-key authentication.

| Aspect | Detail |
|---|---|
| **Stack** | Node.js, Express.js, Socket.IO, Redis, MongoDB, JWT |
| **Ingestion** | Uses `setImmediate` to decouple ingestion and return `202 Accepted` in under 5ms |
| **Idempotency** | Two-tier deduplication with Redis `SETNX` (24-hour TTL) and a MongoDB unique index, preventing duplicate deliveries across network retries |
| **Delivery** | Real-time in-app messages over Socket.IO WebSockets at sub-50ms latency, with offline queue reconciliation and Redis cache-aside for unread counts |
| **Security & Limits** | SHA-256 hashed API keys on a multi-tenant REST API; rate limiting at 10K requests/min globally and 50 requests/min per user, plus quiet-hour scheduling |
| **Links** | [Live Demo](https://notify-x-ten.vercel.app) · [Repository](https://github.com/Anup171/NotifyX) |

</details>

---

### 🏆 Achievements & Certifications

<div align="center">

| Recognition | Details |
|---|---|
| 🧩 **Competitive Programming** | Solved 300+ DSA problems across arrays, trees, graphs, and DP; earned 50-day and 100-day LeetCode consistency badges |
| 🚀 **Dell Futureminds AI Hackathon** | Shortlisted |
| 🇮🇳 **Smart India Hackathon (SIH)** | Selected to represent BMSCE after clearing college-level qualifiers |
| 🎓 **Academic Excellence** | CGPA **9.31/10** at BMS College of Engineering |
| 📘 **Pre-University Excellence** | **97.1%** in Karnataka II PUC |

</div>

**IIT Madras**

[![IIT Madras](https://img.shields.io/badge/IIT%20Madras-Foundational%20Level%20in%20Programming%20%26%20Data%20Science-6D28D9?style=flat-square)](https://drive.google.com/file/d/1MV3KronPTnfHy9_sHomTTiCRoBtcAn1T/view?pli=1)

Completed the Foundational Level certification in Programming and Data Science, covering Python, statistics, and core CS concepts.

---

### 💻 Coding Profiles

<div align="center">

<a href="https://leetcode.com/u/Anup_S/"><img src="https://img.shields.io/badge/LeetCode-300%2B%20Problems%20Solved-FFA116?style=for-the-badge&logo=leetcode&logoColor=black&labelColor=1e1b2e" alt="LeetCode" /></a>

</div>

---

### 📈 GitHub Analytics

<div align="center">

<img src="https://streak-stats.demolab.com/?user=Anup171&theme=radical&hide_border=true&background=0d1117&ring=7C3AED&fire=A78BFA&currStreakLabel=A78BFA" width="60%" alt="GitHub streak stats" />

</div>

---

### 🔭 Engineering Focus

- Reliable asynchronous backend services and API design
- PostgreSQL-backed worker coordination and monitoring workflows
- Multi-agent research, RAG, and citation-backed synthesis
- Real-time notification delivery and system resilience

---

### 📬 Connect With Me

<div align="center">

<a href="mailto:anupbhandarkar171@gmail.com"><img src="https://skillicons.dev/icons?i=gmail" height="40" alt="Email" /></a>&nbsp;&nbsp;
<a href="https://www.linkedin.com/in/anup-bhandarkar/"><img src="https://skillicons.dev/icons?i=linkedin" height="40" alt="LinkedIn" /></a>&nbsp;&nbsp;
<a href="https://github.com/Anup171"><img src="https://skillicons.dev/icons?i=github" height="40" alt="GitHub" /></a>

</div>

---

<div align="center">

_"Build reliable systems that reason and respond."_

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=120&section=footer" width="100%" alt="footer"/>

</div>
