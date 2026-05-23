<div align="center">

# Gautam Kumar

**Backend Engineer** · NIT Agartala '26 · Electrical Engineering → Systems that Ship

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/gautam-oss)
[![Gmail](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:gautamkumarnita@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/gautam-oss)

</div>

---

## About Me

I started in Electrical Engineering. Somewhere along the way, I got obsessed with backend systems — distributed task queues, async APIs, CI/CD pipelines — and never looked back.

I've built and **shipped** production-grade projects using Python, FastAPI, Django, Celery, Redis, and Docker, with real deployments on AWS and Render. My engineering background makes me think in systems, not just features.

> *I don't just write code — I build it, ship it, and own it end-to-end.*

---

## 💼 Experience

### Backend Developer Intern — SyntexHub *(Apr–May 2026, Remote)* · [View Project ↗](https://github.com/gautam-oss/distributed-task-queue)

- Built a **distributed task queue** using Celery + Redis + FastAPI with priority-based routing (high / default / low), concurrent execution, and exponential backoff retry logic
- Developed a **real-time monitoring dashboard** with WebSocket-driven live stats, Chart.js throughput visualization, and a Celery worker inspector with active/reserved/scheduled task tables and one-click task revocation
- Containerized the full stack using **Docker Compose** (6 services) locally and on Render cloud; integrated **Upstash Redis (TLS/SSL)** as managed broker and result backend

---

## 🚀 Projects

### 🛒 PyMart — Async Multi-Vendor E-commerce Platform

A production-grade marketplace REST API built on FastAPI with a React 18 frontend.

- **API & Auth:** FastAPI (Python 3.12) + SQLAlchemy 2.x with JWT access/refresh token rotation, RBAC, and `SELECT FOR UPDATE` concurrency control preventing checkout race conditions
- **Payments & Async:** Razorpay integration with HMAC-SHA256 webhook verification and idempotency handling; Celery + Redis async task queue delivering order confirmations via Resend API in **<50ms**
- **Search & Storage:** Elasticsearch full-text product search with relevance scoring; AWS S3 (ap-south-1) for Pillow-optimized image storage
- **Data Layer:** PostgreSQL with Alembic migrations and composite indexes; Redis for cart (atomic `HINCRBY`), API caching (TTL invalidation), and rate limiting
- **Frontend & DevOps:** React 18 + TypeScript + Zustand + React Query; 5-service Docker Compose setup; GitHub Actions CI/CD with **105 pytest-asyncio tests at >80% coverage**


---

## 🛠️ Tech Stack

**Languages**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnubash&logoColor=white)
![C](https://img.shields.io/badge/C-00599C?style=flat-square&logo=c&logoColor=white)

**Frameworks & Libraries**

![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Django](https://img.shields.io/badge/Django-092E20?style=flat-square&logo=django&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white)
![Celery](https://img.shields.io/badge/Celery-37814A?style=flat-square&logo=celery&logoColor=white)
![SQLAlchemy](https://img.shields.io/badge/SQLAlchemy-D71F00?style=flat-square&logo=sqlalchemy&logoColor=white)

**Databases & Caching**

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=flat-square&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-4EA94B?style=flat-square&logo=mongodb&logoColor=white)
![Elasticsearch](https://img.shields.io/badge/Elasticsearch-005571?style=flat-square&logo=elasticsearch&logoColor=white)

**DevOps & Cloud**

![Docker](https://img.shields.io/badge/Docker-2CA5E0?style=flat-square&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=github-actions&logoColor=white)
![AWS](https://img.shields.io/badge/AWS_(S3,_ECR,_RDS,_EC2)-FF9900?style=flat-square&logo=amazonaws&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=flat-square&logo=nginx&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)

---

## 🏆 Achievements & Certifications

- 🥇 **Best Final Year Project** — "Non-Invasive Glucose Monitoring", Dept. of Electrical Engineering, NIT Agartala
- 🐳 **Docker Certified Associate (DCA)** — Docker Inc.
- 🏅 **OpenAI Academy × NxtWave Buildathon** — Selected for the 2-day Delhi Regional edition
- 🧬 **AI-Driven RNA Therapeutics** — 5-day intensive on computational drug design; siRNA efficacy prediction & ML pipelines, NIT Agartala

---

## 🎭 Beyond Code

**Vice-President, SPIC MACAY Heritage Club — NIT Agartala**  
Led cultural initiatives, coordinated heritage events, and managed a 20+ member student team.

---

## 📫 Let's Connect

- 📧 [gautamkumarnita@gmail.com](mailto:gautamkumarnita@gmail.com)
- 💼 [linkedin.com/in/gautam-oss](https://linkedin.com/in/gautam-oss)
- 🐙 [github.com/gautam-oss](https://github.com/gautam-oss)
- 📍 Bikramganj, Rohtas, Bihar

---

<div align="center">
  <i>Open to backend / DevOps roles where I can build real systems, ship fast, and keep growing.</i>
</div>
