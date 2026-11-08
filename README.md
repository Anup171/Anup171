<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=220&section=header&text=Anup%20Bhandarkar&fontSize=42&fontColor=ffffff&animation=fadeIn&fontAlignY=38&desc=CSE%20(Data%20Science)%20Undergraduate%20%7C%20Backend%20Engineering%20%7C%20Agentic%20AI&descAlignY=55&descAlign=50" width="100%"/>

<a href="https://git.io/typing-svg">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&pause=1000&color=A78BFA&center=true&vCenter=true&width=650&lines=Building+Reliable+Backend+Systems;FastAPI+%7C+PostgreSQL+%7C+Node.js;LangGraph+%7C+LangChain+%7C+Agentic+AI;300%2B+DSA+Problems+Solved" alt="Typing SVG" />
</a>

<br/>

![CGPA](https://img.shields.io/badge/CGPA-9.31%2F10-6D28D9?style=flat-square&labelColor=1e1b2e)
![PUC](https://img.shields.io/badge/PUC-97.1%25-7C3AED?style=flat-square&labelColor=1e1b2e)
![Location](https://img.shields.io/badge/Location-Bengaluru%2C%20India-4C1D95?style=flat-square&labelColor=1e1b2e)

<br/>

<a href="https://www.linkedin.com/in/anup-bhandarkar/"><img src="https://img.shields.io/badge/LinkedIn-6D28D9?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
<a href="mailto:anupbhandarkar171@gmail.com"><img src="https://img.shields.io/badge/Email-7C3AED?style=for-the-badge&logo=gmail&logoColor=white" /></a>
<a href="https://github.com/Anup171"><img src="https://img.shields.io/badge/GitHub-4C1D95?style=for-the-badge&logo=github&logoColor=white" /></a>

<br/><br/>

![Profile Views](https://komarev.com/ghpvc/?username=Anup171&color=6D28D9&style=for-the-badge&label=PROFILE+VIEWS)
![Followers](https://img.shields.io/github/followers/Anup171?style=for-the-badge&color=7C3AED&labelColor=1e1b2e&label=FOLLOWERS)
![Stars](https://img.shields.io/github/stars/Anup171?style=for-the-badge&color=4C1D95&labelColor=1e1b2e&label=STARS)

</div>

---

### 👋 About Me

I'm a **Computer Science and Engineering (Data Science) undergraduate** at **BMS College of Engineering, Bengaluru**, pursuing a B.E. since September 2024. I build backend and full-stack systems alongside agentic AI applications, with a focus on reliability, clear APIs, and useful product experiences.

My projects span **multi-agent research and citation-backed synthesis**, **PostgreSQL-coordinated uptime monitoring**, and **real-time notification delivery**. I enjoy working across system design, asynchronous services, data stores, and LLM-powered workflows.

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

<p><img src="https://skillicons.dev/icons?i=java,cpp,python,js" /></p>

Java · C++ · Python · JavaScript · SQL

**Frontend**

<p><img src="https://skillicons.dev/icons?i=react" /></p>

React.js

**Backend & APIs**

Node.js · Express.js · FastAPI · REST APIs · JWT · WebSockets · Socket.IO · Pydantic

**Databases & Caching**

PostgreSQL · MySQL · MongoDB · Redis

**AI / ML & LLM Systems**

LangChain · LangGraph · Agentic AI (Multi-Agent Systems) · Retrieval-Augmented Generation (RAG) · Prompt Engineering · Embeddings · Vector Databases · SentenceTransformers

**Cloud, DevOps & Tooling**

Docker · AWS · GitHub Actions (CI/CD) · Git · GitHub · Postman

**Core CS**

Data Structures & Algorithms · Object-Oriented Programming · System Design · Operating Systems · DBMS · Computer Networks · Computer Organization and Architecture

---

### 🧠 AI & Systems Expertise

<div align="center">

| Area | Experience |
|---|---|
| **Agentic AI** | LangGraph workflows coordinating four autonomous research agents |
| **Research & RAG** | Research planning, source credibility scoring, and citation-backed reports |
| **Backend Systems** | FastAPI and Node.js services, asynchronous workers, REST APIs, and WebSockets |
| **Reliability** | PostgreSQL job scheduling and leases, circuit breakers, and SQLite checkpointing |
| **Data & Caching** | PostgreSQL, MySQL, MongoDB, Redis, and TTL-based caching |
| **LLM Applications** | OpenRouter integration, token and cost monitoring, and deterministic fallbacks |

</div>

---

### 🚀 Featured Projects

<details>
<summary><b>⏱️ PulseWatch — Uptime Monitoring & Incident Platform</b></summary>
<br/>

Built a fault-tolerant uptime monitoring system with concurrent HTTP/TCP probes, distributed scheduling, incident detection, webhook notifications, and LLM-assisted root-cause summaries.

| Aspect | Detail |
|---|---|
| **Stack** | FastAPI, Python, PostgreSQL, Asyncio, React.js, OpenRouter |
| **Monitoring** | 20 concurrent async probes over HTTP/TCP at 15-second intervals, with SSRF protection and SSL certificate monitoring |
| **Scheduling** | PostgreSQL row-level locking with `SELECT ... FOR UPDATE SKIP LOCKED` and 30-second leases; 0% duplicate checks across horizontally scaled replicas |
| **Incident detection** | Three consecutive failures followed by a 10-second re-probe, reducing false-positive alerts by 95% |
| **AI** | Root-cause summaries from five-stage HTTP telemetry in under 1.5 seconds, with a 100% deterministic fallback |
| **Notifications** | REST webhooks to multiple channels |
| **Repository** | [github.com/Anup171/PulseWatch](https://github.com/Anup171/PulseWatch) |

</details>

<details>
<summary><b>🧩 Veritas AI — Autonomous Multi-Agent Research System</b></summary>
<br/>

Built a LangGraph and LangChain research platform that coordinates four agents to plan research objectives and produce structured reports with academic citations.

| Aspect | Detail |
|---|---|
| **Stack** | Python, LangGraph, LangChain, Docker, Chainlit, Pydantic |
| **Research** | Plans 3–5 objectives and generates eight-section reports with APA and IEEE citations |
| **Credibility** | Scores sources from 0–100 across 50+ trusted domains; filters sources below 40 and prioritizes scores of 70 or higher |
| **Resilience** | Three-state circuit breaker with a five-failure threshold and 30-second reset; SQLite checkpointing with 100% state recovery after process crashes |
| **Efficiency** | MD5-keyed cache with a seven-day TTL; real-time token and cost monitoring |
| **Repository** | [github.com/Anup171/Veritas-AI](https://github.com/Anup171/Veritas-AI) |

</details>

<details>
<summary><b>🔔 NotifyX — Real-Time Notification Platform</b></summary>
<br/>

Built an event-driven, asynchronous notification service with idempotent delivery, WebSocket messaging, offline queue reconciliation, and API-key authentication.

| Aspect | Detail |
|---|---|
| **Stack** | Node.js, Express.js, Socket.IO, Redis, MongoDB, JWT |
| **Ingestion** | Uses `setImmediate` to decouple ingestion and return `202 Accepted` in under 5ms |
| **Idempotency** | Redis `SETNX` with a 24-hour TTL plus a MongoDB unique index to prevent duplicate deliveries across network retries |
| **Delivery** | In-app WebSocket messages in under 50ms, offline queue reconciliation, and Redis cache-aside for unread counts |
| **Security & Limits** | Multi-tenant REST API with SHA-256 hashed API keys, rate limits of 10K requests/min globally and 50 requests/min per user, plus quiet-hour scheduling |
| **Repository** | [github.com/Anup171/NotifyX](https://github.com/Anup171/NotifyX) |

</details>

---

### 🏆 Achievements & Certifications

<div align="center">

| Recognition | Details |
|---|---|
| 🧩 **Competitive Programming** | Solved 300+ DSA problems across arrays, trees, graphs, and dynamic programming; earned 50-day and 100-day LeetCode streak badges |
| 🚀 **Dell Futureminds AI Hackathon** | Shortlisted |
| 🇮🇳 **Smart India Hackathon (SIH)** | Selected to represent BMSCE after clearing college-level qualifiers |
| 🎓 **Academic Excellence** | CGPA **9.31/10** at BMS College of Engineering |
| 📘 **Pre-University Excellence** | **97.1%** in Karnataka PUC (II PUC) |

</div>

**IIT Madras**

[![IIT Madras](https://img.shields.io/badge/IIT%20Madras-Foundational%20Level%20in%20Programming%20%26%20Data%20Science-6D28D9?style=flat-square&logo=googlescholar&logoColor=white)](https://drive.google.com/file/d/1MV3KronPTnfHy9_sHomTTiCRoBtcAn1T/view?pli=1)

Completed the Foundational Level certification in Programming and Data Science, covering Python, statistics, and core CS concepts.

---

### 💻 Coding Profiles

<div align="center">

<a href="https://leetcode.com/u/Anup_S/"><img src="https://img.shields.io/badge/LeetCode-300%2B%20Problems%20Solved-FFA116?style=for-the-badge&logo=leetcode&logoColor=black&labelColor=1e1b2e" /></a>

</div>

---

### 📈 GitHub Analytics

<div align="center">

<img src="https://github-readme-streak-stats-eight.vercel.app/?user=Anup171&theme=radical&hide_border=true&background=0d1117&ring=7C3AED&fire=A78BFA&currStreakLabel=A78BFA" width="60%" />

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

<a href="mailto:anupbhandarkar171@gmail.com"><img src="https://img.shields.io/badge/Gmail-6D28D9?style=for-the-badge&logo=gmail&logoColor=white" /></a>
<a href="https://www.linkedin.com/in/anup-bhandarkar/"><img src="https://img.shields.io/badge/LinkedIn-7C3AED?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
<a href="https://github.com/Anup171"><img src="https://img.shields.io/badge/GitHub-4C1D95?style=for-the-badge&logo=github&logoColor=white" /></a>

</div>

---

<div align="center">

_"Build reliable systems that reason and respond."_

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=120&section=footer" width="100%"/>

</div>
