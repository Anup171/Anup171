<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=220&section=header&text=Anup%20Bhandarkar&fontSize=42&fontColor=ffffff&animation=fadeIn&fontAlignY=38&desc=AI%20Engineer%20%7C%20Full%20Stack%20Developer%20%7C%20Agentic%20Systems%20Builder&descAlignY=55&descAlign=50" width="100%"/>

<a href="https://git.io/typing-svg">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&pause=1000&color=A78BFA&center=true&vCenter=true&width=600&lines=Building+Agentic+AI+Systems;LangGraph+%7C+LangChain+%7C+LLMs;Full+Stack+MERN+Developer;250%2B+DSA+Problems+Solved" alt="Typing SVG" />
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

### 🪶 About Me

I'm a **Computer Science (Data Science) undergraduate** at BMS College of Engineering, Bengaluru, engineering intelligent systems at the intersection of **agentic AI, large language models, and full-stack product development**.

My focus is architecting **multi-agent orchestration systems** — coordinating LLM agents through stateful graphs to autonomously plan, retrieve, verify, and synthesize information into reliable, citation-backed outputs. Alongside this, I build **production-grade full-stack and distributed backend systems** — from generative AI platforms to real-time notification infrastructure — with a product-engineering mindset: clean REST APIs, resilient data pipelines, and interfaces designed for real users.

**Currently Open To:**
- 🚀 Software Engineering Internships (Full Stack / Backend)
- 🤖 AI/ML & Agentic Systems Research Roles
- 🌱 Open Source Collaboration in LLM tooling
- 🧠 Applied ML & Data Science opportunities

---

### 🛠️ Tech Stack

**Languages**
<p> <img src="https://skillicons.dev/icons?i=java,c,cpp,python,js,mysql" /> </p>

**Frontend**
<p> <img src="https://skillicons.dev/icons?i=react,html,css,tailwind" /> </p>

**Backend & Databases**
<p> <img src="https://skillicons.dev/icons?i=nodejs,express,fastapi,mongodb,mysql,redis,postman" /> </p>

**AI / ML**
<p> <img src="https://skillicons.dev/icons?i=pytorch,tensorflow,sklearn" /> </p>

**Cloud, DevOps & Tooling**
<p> <img src="https://skillicons.dev/icons?i=git,github,docker,aws,vscode,cloudinary" /> </p>

---

### 🧠 AI / ML Expertise

<div align="center">

| Domain | Details |
|---|---|
| **Large Language Models (LLMs)** | Multi-agent orchestration, prompt design, structured output generation |
| **Agentic AI** | LangGraph `StateGraph` pipelines, checkpointing, crash-recovery workflows |
| **Natural Language Processing** | Embeddings, semantic search, `SentenceTransformers` |
| **Generative AI** | Image generation pipelines, prompt-to-output MERN integrations |
| **Prompt Engineering** | Role-based agent prompting, credibility-aware synthesis |
| **Deep Learning & Classical ML** | PyTorch, TensorFlow, Scikit-learn pipelines, cross-validation, feature engineering |

</div>

---

### 🚀 Featured Projects

<details>
<summary><b>🧩 Veritas AI — Autonomous Multi-Agent Research System</b></summary>
<br/>

Architected an autonomous multi-agent research system using LangGraph's `StateGraph`, coordinating **4 specialized agents** (Planner, Searcher, Synthesizer, Writer) to autonomously plan, search, and synthesize web sources into citation-backed reports.

| Aspect | Detail |
|---|---|
| **Stack** | Python, Docker, LangGraph, LangChain, Chainlit, Pydantic, httpx |
| **Scale** | 4-agent coordinated pipeline |
| **Performance** | SQLite-based checkpointing for resumable sessions |
| **Security** | Source credibility scoring engine (0–100 scale) |
| **Impact** | Citation-backed reports exportable in MD / HTML / TXT |
| **Repository** | [github.com/Anup171/Veritas-AI](https://github.com/Anup171/Veritas-AI) |

Designed a **source credibility scoring engine** evaluating domain authority, HTTPS, and content signals to filter low-trust sources and resolve contradictions via a credibility hierarchy. Implemented production-reliability patterns including a **circuit breaker** for external service failures, exponential backoff retries, and crash-recoverable workflow checkpointing. Containerized the Chainlit interface with Docker, enabling persistent caching, report storage, and exports in Markdown, HTML, and TXT formats.

</details>

<details>
<summary><b>🔔 NotifyX — Distributed Real-Time Notification Platform</b></summary>
<br/>

Engineered a distributed real-time notification platform enabling asynchronous, idempotent, and low-latency delivery at scale, with automatic recovery from worker crashes and service restarts.

| Aspect | Detail |
|---|---|
| **Stack** | Node.js, Express.js, BullMQ, Redis, MongoDB, Socket.io |
| **Scale** | 10K requests/min global rate limit, 50 requests/min per user |
| **Performance** | Sub-50ms delivery latency via Redis Pub/Sub |
| **Security** | SHA-256 hashed, per-user scoped API key management |
| **Impact** | Zero duplicate notifications across retries and crashes |
| **Repository** | [github.com/Anup171/NotifyX](https://github.com/Anup171/NotifyX) |

Implemented asynchronous job processing with **BullMQ** using 5-retry exponential backoff and a Dead Letter Queue for failed jobs. Designed a **two-layer idempotency mechanism** combining Redis `SETNX` locks with a MongoDB sparse unique index to prevent duplicate notifications across retries, worker crashes, and service restarts. Built offline synchronization so pending notifications are automatically delivered once a client reconnects, and enforced sliding-window rate limiting alongside a secure, scoped API key system.

</details>

<details>
<summary><b>🎨 Prompt2Pixel — Full Stack Generative AI Platform</b></summary>
<br/>

Designed and deployed a full-stack MERN generative AI application enabling users to generate AI images from text prompts and publish them to a shared community feed.

| Aspect | Detail |
|---|---|
| **Stack** | React, Node.js, Express, MongoDB, Pollinations AI, Cloudinary |
| **Scale** | 4 RESTful API endpoints, 50 curated prompt templates |
| **Performance** | 500ms debounced search |
| **Security** | Cloudinary-managed asset storage |
| **Impact** | Shared community image feed with metadata & download tracking |
| **Repository** | [github.com/Anup171/Prompt2Pixel](https://github.com/Anup171/Prompt2Pixel) |

Built RESTful endpoints for prompt submission, image metadata, debounced search, and downloads, with Cloudinary integration for scalable media storage.

</details>

<details>
<summary><b>📊 Loan Approval & Customer Risk Prediction</b></summary>
<br/>

Built an end-to-end ML classification pipeline on 4,269 loan applications with 13 features, using feature engineering, `StandardScaler`, one-hot encoding, and stratified sampling for class balance.

| Aspect | Detail |
|---|---|
| **Stack** | Python, Scikit-learn, Pandas, Matplotlib, Seaborn |
| **Scale** | 4,269 applications, 13 features, 5 models benchmarked |
| **Performance** | 98.36% Accuracy, 99.77% ROC-AUC (Gradient Boosting) |
| **Security** | N/A |
| **Impact** | CIBIL score identified as 80.23% dominant predictor |
| **Repository** | [github.com/Anup171/Loan-approval-prediction](https://github.com/Anup171/Loan-approval-prediction) |

Benchmarked 5 models via 5-fold cross-validation and selected Gradient Boosting based on top performance, with feature importance analysis surfacing CIBIL score as the dominant predictor of risk.

</details>

---

### 🏆 Achievements

<div align="center">

| Recognition | Details |
|---|---|
| 🥇 **Competitive Programming** | 250+ DSA problems solved (arrays, trees, graphs, DP); LeetCode contest rating **1450** |
| 🔥 **Consistency Badges** | Earned 50-day and 100-day LeetCode streak badges |
| 🎓 **Academic Excellence** | CGPA **9.31/10** at BMS College of Engineering |
| 📘 **Pre-University Excellence** | **97.1%** in Karnataka PUC (II PUC) |

</div>

---

### 📜 Certifications

**IIT Madras**

[![IIT Madras](https://img.shields.io/badge/IIT%20Madras-Foundational%20Level%20in%20Programming%20%26%20Data%20Science-6D28D9?style=flat-square&logo=googlescholar&logoColor=white)](https://drive.google.com/file/d/1MV3KronPTnfHy9_sHomTTiCRoBtcAn1T/view?pli=1)

**HackerRank**

[![HackerRank](https://img.shields.io/badge/HackerRank-SQL%20(Intermediate)-2EC866?style=flat-square&logo=hackerrank&logoColor=white)](https://www.hackerrank.com/certificates/158f42f38081)

---

### 💻 Coding Profiles

<div align="center">

<a href="https://leetcode.com/u/Anup_S/"><img src="https://img.shields.io/badge/LeetCode-1450%20Rating-FFA116?style=for-the-badge&logo=leetcode&logoColor=black&labelColor=1e1b2e" /></a>
<a href="https://www.hackerrank.com/certificates/158f42f38081"><img src="https://img.shields.io/badge/HackerRank-SQL%20Certified-2EC866?style=for-the-badge&logo=hackerrank&logoColor=white&labelColor=1e1b2e" /></a>

</div>

---

### 📈 GitHub Analytics

<div align="center">

<img src="https://streak-stats.demolab.com/?user=Anup171&theme=radical&hide_border=true&background=0d1117&ring=7C3AED&fire=A78BFA&currStreakLabel=A78BFA" width="60%" />

</div>

---

### 📊 Contribution Activity

<div align="center">

<img src="https://github-readme-activity-graph.vercel.app/graph?username=Anup171&theme=react-dark&hide_border=true&bg_color=0d1117&color=A78BFA&line=7C3AED&point=ffffff" width="95%" />

</div>

---

### 🐍 Contribution Snake

<div align="center">

<img src="https://raw.githubusercontent.com/Anup171/Anup171/output/github-contribution-grid-snake-dark.svg" width="95%" />

</div>

---

### 🔭 Current Focus

```yaml
Learning:
  - Advanced multi-agent orchestration patterns
  - Distributed systems & scalable backend architecture
  - Deep learning model optimization

Building:
  - Production-grade agentic AI research tools
  - Distributed, real-time backend systems
  - Full stack generative AI applications

Exploring:
  - Retrieval-Augmented Generation (RAG) architectures
  - LLM evaluation & credibility scoring frameworks

Open To:
  - Software Engineering Internships
  - AI/ML Research Collaborations
  - Open Source Contributions
```

---

### 📬 Connect With Me

<div align="center">

<a href="mailto:anupbhandarkar171@gmail.com"><img src="https://img.shields.io/badge/Gmail-6D28D9?style=for-the-badge&logo=gmail&logoColor=white" /></a>
<a href="https://www.linkedin.com/in/anup-bhandarkar/"><img src="https://img.shields.io/badge/LinkedIn-7C3AED?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
<a href="https://github.com/Anup171"><img src="https://img.shields.io/badge/GitHub-4C1D95?style=for-the-badge&logo=github&logoColor=white" /></a>

</div>

---

<div align="center">

_"Build systems that reason, not just respond."_

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=120&section=footer" width="100%"/>

</div>
