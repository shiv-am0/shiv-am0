# Shivam Srivastava

### Backend & Applied AI Engineer

I build reliable backend systems and practical AI products with Python. My work
focuses on API design, data-intensive services, distributed messaging, and RAG
systems that are secure, observable, and useful beyond a demo.

I enjoy reasoning about the parts that make software dependable in production:
failure modes, idempotency, authentication, data modeling, concurrency, and
clear operational boundaries.

[![Portfolio](https://img.shields.io/badge/Portfolio-Visit-111827?style=flat-square&logo=vercel&logoColor=white)](https://shivam-srv.vercel.app/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/shivam-0/)
[![Email](https://img.shields.io/badge/Email-Contact-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:shivam.sriv.com@gmail.com)

## Selected projects

### [CodeLens](https://github.com/shiv-am0/CodeLens) — AI-powered codebase intelligence

A full-stack developer tool that analyzes public GitHub repositories and
generates architecture documentation, API summaries, diagrams, and grounded
Q&A through a RAG pipeline.

- Built the API with **FastAPI**, async **SQLAlchemy**, **PostgreSQL**, and **pgvector**.
- Supports hosted **OpenAI** models and local **Ollama** models behind one provider interface.
- Designed an embeddings and retrieval pipeline for repository-aware conversations.
- Added encrypted owner-managed API keys, rate limits, bounded analysis concurrency,
  and fail-closed production configuration.
- Runs as a containerized stack with **Next.js**, **Docker Compose**, and **Nginx**.

### [ChatPulse](https://github.com/shiv-am0/chat-pulse) — distributed real-time chat backend

A Django REST platform and Python CLI that separates message acceptance,
durable processing, persistence, and real-time delivery.

- Built authenticated APIs with **Django**, **Django REST Framework**, and JWT.
- Used **Kafka** as the asynchronous message boundary, **PostgreSQL** for durable
  storage, and **Redis** for caching and Pub/Sub delivery.
- Implemented replay-aware message consumption, duplicate protection, cursor
  pagination, token refresh, and Redis-to-database fallbacks.
- Packaged a cross-platform terminal client with **Typer**, **Rich**, and **httpx**.
- Added automated deployment, package publishing, and installer checks with
  **GitHub Actions**.

## Engineering toolkit

| Area | Technologies and practices |
| --- | --- |
| Backend | Python, Django, Django REST Framework, FastAPI, REST APIs, Pydantic, SQLAlchemy |
| Applied AI | OpenAI API, RAG, embeddings, vector search, prompt design, local LLMs with Ollama |
| Data & messaging | PostgreSQL, pgvector, Redis, Kafka, data modeling, transactions, idempotency |
| Infrastructure | Docker, Docker Compose, Nginx, GitHub Actions, AWS, Linux, Git |
| Reliability & security | Testing, rate limiting, authentication, secret encryption, failure-path design |

## How I approach engineering

- Start with the simplest architecture that satisfies the requirements.
- Treat retries, partial failure, duplicate delivery, and dependency outages as
  normal operating conditions—not edge cases.
- Keep API, business logic, and persistence boundaries explicit and testable.
- Evaluate AI systems as software systems: retrieval quality, hallucination risk,
  latency, cost, security, and graceful degradation all matter.

## Currently focused on

- Production-oriented RAG and LLM-backed applications
- Scalable Python APIs and asynchronous processing
- PostgreSQL performance, distributed-system reliability, and cloud deployment

I am open to backend and applied AI engineering opportunities where I can build
useful systems, learn deeply, and contribute to strong engineering teams.
