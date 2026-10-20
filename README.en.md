<div align="center">
  <img src="assets/header.svg" alt="frank — Backend / AI Application Engineer · PersonalOS data flow" width="100%" />
</div>

---

### About me

- 🔭 Building **[PersonalOS](https://github.com/rushChen131/personalOS)**: a personal life operating system where the journal is the only authored input — everything else (memories, reports) is derived from it
- 🧩 Interested in: RAG retrieval quality, agent tool-permission boundaries, event-driven architecture
- 🌱 Leveling up on: observability and LLM evaluation — the boring fundamentals
- 💬 Happy to talk about: Python / FastAPI, and the unglamorous details of shipping LLM features

### Tech stack

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![pgvector](https://img.shields.io/badge/pgvector-336791?style=flat-square&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![LLM](https://img.shields.io/badge/LLM%20%2F%20RAG-412991?style=flat-square&logo=openai&logoColor=white)

### Projects

**[PersonalOS](https://github.com/rushChen131/personalOS)** · A personal life operating system
The journal is the single authored input; a `JournalCreated` event fans out into embedding and memory distillation, and chat agents reach data only through permission-checked tools. One codebase supports a zero-dependency local path (SQLite, in-process bus) and a production-shaped full stack (PostgreSQL + pgvector / Redis / MinIO).

<img src="assets/personalos-arch.svg" alt="PersonalOS architecture: journal → event fan-out → memory distillation / periodic reports" width="100%" />

`FastAPI` `Next.js 15` `PostgreSQL + pgvector` `Redis` `SSE` `Multi-agent orchestration`

**[NutriMind-AI](https://github.com/rushChen131/NutriMind-AI-backend)** · AI recipe assistant
Taro mini-program frontend + RAG retrieval (Chroma) + an OpenAI-compatible LLM, implemented end-to-end from a PRD to acceptance. Frontend lives in a [separate repo](https://github.com/rushChen131/NutriMind-AI-frond).

`Taro` `FastAPI` `Chroma` `RAG` `LLM`

### GitHub

<div align="center">

<img height="150" src="https://github-readme-stats.vercel.app/api?username=rushChen131&show_icons=true&hide_border=true&include_all_commits=true&theme=default" alt="GitHub stats" />
<img height="150" src="https://github-readme-stats.vercel.app/api/top-langs/?username=rushChen131&layout=compact&hide_border=true&hide=html,css" alt="Top languages" />

</div>

---

<div align="center">
<sub>Turn complexity into one simple thing — it's easier to maintain.</sub>
</div>

---

> [中文版](README.md)
