# Hi, I'm Jayadeep Gopinath 👋

<div align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=22&pause=1000&color=2563EB&center=true&vCenter=true&width=620&lines=Backend+%26+Distributed+Systems+Engineer;Go+%7C+Python+%7C+Node.js+%7C+PostgreSQL+%7C+Redis;Shipped+notification-system-go+%E2%80%94+170+req%2Fs%2C+p50+17ms;M.S.+Computer+Science+%40+IIT+Chicago;IEEE+Published+%C2%B7+KSCST+Recognized" alt="Typing SVG" />
</div>

---

## 🧑‍💻 About Me
- 🎓 **M.S. Computer Science** @ Illinois Institute of Technology, Chicago *(Aug 2025 – May 2027)*
- 🌱 Deepening: **Distributed Systems · Backend Engineering in Go · System Design · DSA**
- 🏆 **IEEE Xplore Published** (IJTRE, Jan 2024) | Project recognized by **Govt. of Karnataka (KSCST)**
- 💼 Seeking **Summer 2026 / Fall 2026 SWE Internships** *(F-1 CPT eligible - no H-1B sponsorship required)*
- 📫 Reach me: **jg@hawk.illinoistech.edu** | [LinkedIn](https://www.linkedin.com/in/jayadeep-gopinath)

---

## 🛠️ Tech Stack
**Languages**
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat&logo=openjdk&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![Go](https://img.shields.io/badge/Go-00ADD8?style=flat&logo=go&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat&logo=cplusplus&logoColor=white)
![C#](https://img.shields.io/badge/C%23-239120?style=flat&logo=csharp&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)
![C](https://img.shields.io/badge/C-A8B9CC?style=flat&logo=c&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)
![PHP](https://img.shields.io/badge/PHP-777BB4?style=flat&logo=php&logoColor=white)

**Backend & APIs**
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat&logo=node.js&logoColor=white)
![Express.js](https://img.shields.io/badge/Express.js-000000?style=flat&logo=express&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=flat&logo=flask&logoColor=white)
![REST APIs](https://img.shields.io/badge/REST_APIs-FF6C37?style=flat&logo=postman&logoColor=white)
![gRPC](https://img.shields.io/badge/gRPC-244C5A?style=flat&logo=grpc&logoColor=white)

**Frontend**
![React](https://img.shields.io/badge/React-61DAFB?style=flat&logo=react&logoColor=black)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)

**Databases**
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-336791?style=flat&logo=postgresql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat&logo=mongodb&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat&logo=mysql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat&logo=redis&logoColor=white)

**Cloud & Infrastructure**
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat&logo=githubactions&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat&logo=amazonaws&logoColor=white)
![GCP](https://img.shields.io/badge/GCP-4285F4?style=flat&logo=googlecloud&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat&logo=linux&logoColor=black)
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=flat&logo=prometheus&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=flat&logo=grafana&logoColor=white)

**Testing & Tooling**
![pytest](https://img.shields.io/badge/pytest-0A9EDC?style=flat&logo=pytest&logoColor=white)
![k6](https://img.shields.io/badge/k6_Load_Testing-7D64FF?style=flat&logo=k6&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white)

**AI & ML**
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat&logo=pytorch&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat&logo=scikitlearn&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat&logo=langchain&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=flat&logo=openai&logoColor=white)

---

## 🚀 Featured Projects

### ⚡ [Notification-system-go](https://github.com/JD1359/Notification-system-go) - Distributed Multi-Channel Notification Service
> **Go · Redis Streams · PostgreSQL · Docker · Prometheus · Grafana · GitHub Actions** · *MIT-licensed*

- REST API + worker pool with **Redis Streams consumer groups for at-least-once delivery**
- **Sustained 170 req/s with p50 latency 17ms** in k6 load tests (40,866 requests); identified Postgres pool saturation as next optimization target
- Exponential-backoff retries with **dead-letter queue**, **idempotency** via client-supplied keys, **per-channel token-bucket rate limiting**
- Multi-stage Docker build + docker-compose stack (Postgres + Redis + API + 3 workers + Prometheus + Grafana); GitHub Actions CI green

### 🔥 [CodePulse](https://github.com/JD1359/codepulse) - Distributed Code Execution & Automated Test Validation
> **Node.js · React · Socket.io · Docker · Redis · Python**

- Sandboxed Docker code execution engine with CPU/memory resource limits and configurable timeouts
- Python-based automated execution pipelines validating code correctness across **5 languages**
- RESTful APIs with JWT auth + rate limiting sustaining **500+ concurrent sessions** under load testing
- Redis Pub/Sub for real-time state sync; MongoDB compound indexes for **sub-50ms query performance**

### 🏥 [Naari Shakthi](https://github.com/JD1359/naari-shakthi) - AI-Powered Healthcare Platform
> **React · Node.js · Python Flask · MongoDB · REST APIs** · **🏆 Govt. of Karnataka (KSCST) Recognized** · **📜 IEEE Published**

- Integrated Python ML service via REST APIs for real-time health risk predictions; outputs validated against clinical benchmarks with automated assertion checks
- Role-based access control, input validation, rate-limited endpoints; full system architecture documented for KSCST institutional deployment review
- **IEEE-published research** based on this project (IJTRE Vol. II, Jan 2024)

### 🤖 [LangChain Conversational Agent](https://github.com/JD1359/langchain-conversational-agent)
> **Python · LangChain · OpenRouter · Tavily API · Conversational Memory**

- AI agent with real-time web search, math evaluation, and tool calling
- Maintains conversation context window with persistent memory

### 📈 [Gold Price Predictor](https://github.com/JD1359/gold-price-predictor) - ML Regression Pipeline
> **Python · scikit-learn · pandas · matplotlib**

- Built and evaluated **4 regression models** (Linear, Ridge, Random Forest, Gradient Boosting) with strict temporal ordering to prevent data leakage
- Automated validation reporting **MAE, RMSE, R²**; feature-engineering pipeline (rolling averages, momentum, lag features)

### 🚂 [Railway Reservation System](https://github.com/JD1359/railway-reservation-system)
> **PHP · MySQL · JavaScript · CSS3**

- Full-stack booking platform with seat selection, auth, and admin dashboard

---

## 📝 Publications

**[Smart Sanitary Pad and Medicine Vending Machine with Automated Dispensing, Disposal, and Notification System](https://ijtre.com/wp-content/uploads/2024/01/2023110517-1.pdf)**
*IJTRE Volume II Issue 5 · IJTRE Xplore Digital Library · January 2024 · ISSN: 2347-4718*

---

## 🏆 Recognition

- 🥇 **Govt. of Karnataka — KSCST** (Karnataka State Council for Science and Technology) for *Naari Shakthi* healthcare project, 2024
- 📜 **IJTRE Xplore Digital Library** publication, January 2024

---

<div align="center">
  <i>Open to <b>Summer 2026 / Fall 2026 SWE Internships</b> · F-1 CPT eligible · No H-1B sponsorship required for internship</i><br/><br/>
  <a href="mailto:jg@hawk.illinoistech.edu">📧 jg@hawk.illinoistech.edu</a> ·
  <a href="https://www.linkedin.com/in/jayadeep-gopinath">💼 LinkedIn</a> ·
  <a href="https://github.com/JD1359">🐙 GitHub</a>
</div>
