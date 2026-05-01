<h1 align="center">Hey, I'm Priyanshu 👋</h1>

<p align="center">
  <b>Backend & AI Engineer</b> &nbsp;·&nbsp; Building production AI systems since before it was cool &nbsp;·&nbsp; Open to Remote & Bengaluru
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/priyanshu-pratap-singh-84bb692b7">
    <img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=flat&logo=linkedin" />
  </a>
  &nbsp;
  <a href="https://github.com/Priyanshu-pps007/ARCA">
    <img src="https://img.shields.io/badge/Currently%20Building-ARCA-orange?style=flat" />
  </a>
</p>

---

## What I Do

I build the infrastructure that makes AI agents actually work in production — not demos, not notebooks.

At **Svahnar**, I built their entire AI platform from scratch: a multi-agent orchestration system on LangGraph, 40+ MCP tool integrations (HubSpot, Notion, Calendly, Slack, Reddit...), Redis pub/sub SSE streaming, multi-LLM model registry across OpenAI, AWS Bedrock (Qwen, DeepSeek, Llama), and a multi-tenant backend serving real paying customers.

When something breaks at 2am in a multi-agent pipeline, I'm the one who finds the silent tool call failure and fixes it.

---

## Core Stack

**Backend**

![Python](https://img.shields.io/badge/Python-Expert-3776AB?style=flat&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-production-009688?style=flat&logo=fastapi&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-pgvector%20%7C%20RLS-4169E1?style=flat&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-pub%2Fsub%20%7C%20cache-DC382D?style=flat&logo=redis&logoColor=white)
![Celery](https://img.shields.io/badge/Celery-async%20tasks-37814A?style=flat)
![Docker](https://img.shields.io/badge/Docker-containerization-2496ED?style=flat&logo=docker&logoColor=white)

**AI / LLM**

![LangGraph](https://img.shields.io/badge/LangGraph-stateful%20agents-FF6B35?style=flat)
![LangChain](https://img.shields.io/badge/LangChain-orchestration-1C3C3C?style=flat)
![MCP](https://img.shields.io/badge/MCP-40%2B%20integrations-6E40C9?style=flat)
![RAG](https://img.shields.io/badge/RAG-pgvector%20%7C%20Qdrant%20%7C%20BGE--M3-8B5CF6?style=flat)
![AWS Bedrock](https://img.shields.io/badge/AWS%20Bedrock-Qwen%20%7C%20Llama%20%7C%20DeepSeek-FF9900?style=flat&logo=amazonaws&logoColor=white)

---

## Projects

### 🔮 [ARCA](https://github.com/Priyanshu-pps007/ARCA) — AI Agent Runtime with Semantic Memory
> *"Most agent platforms give you execution. ARCA gives you execution + memory."*

Agents that compound intelligence across runs — not reset. Natural language → deployed agent in under 60 seconds.
Built on FastAPI · LangGraph · Celery · pgvector (IVFFlat) · BGE-M3 · 14-table PostgreSQL schema with RLS.

**The moat:** a three-tier memory layer (episodic → semantic → procedural) that persists per-tenant across runs.

`FastAPI` `LangGraph` `pgvector` `BGE-M3` `Celery` `Docker` `PostgreSQL` `Multi-tenant`

---

### 🎮 [ESCAPE](https://github.com/Priyanshu-pps007/ESCAPE) — Agent-Driven CLI Adventure Game
A living narrative engine, not a pre-written game. Pick a genre → LangGraph agents build your storyline, milestones, and background audio in real time.

Demonstrates: stateful multi-agent orchestration · HITL via `interrupt()` · async/threading concurrency · token management with summarization middleware.

▶️ [Watch the demo](https://www.youtube.com/watch?v=vREN9k8WfZc)

`LangGraph` `LangChain` `Groq` `Qwen3-32B` `asyncio` `threading` `HITL`

---

### 🎙️ [VoiceRAG](https://github.com/Priyanshu-pps007/-Voice-RAG-Web-search-Agent-) — Voice-First Multi-Agent RAG Assistant
Speak a question → system decides: answer directly, retrieve from your private docs, or search the web live.

The hard parts: barge-in interruption via `AudioContext` RMS energy monitoring, sentence-buffered TTS over WebSocket, multi-agent routing with cost hierarchy (direct < RAG < web), per-user Qdrant HNSW vector isolation.

`FastAPI` `LangChain` `Qdrant` `HNSW` `BGE-M3` `Tavily` `Next.js` `WebSocket` `TTS`

---

### 🎬 [PopcornPick](https://github.com/Priyanshu-pps007/PopcornPick) — Movie Discovery App
Real-time movie search with genre filtering, infinite scroll auto-load, and personal bucketlist — powered by the TMDB API. Shows live IMDB ratings, genres, and full movie details on click.

`Next.js` `TypeScript` `TMDB API` `Tailwind CSS`

---

## What I'm Looking For

AI Engineer or Backend Engineer roles at **AI-first startups** — teams that are shipping, not planning.

- ✅ Anywhere in India
- ✅ Bengaluru / Relocatable
- ✅ India or global companies hiring in India

If you're building an AI product and need someone who's built multi-agent systems, RAG pipelines, and async backends in production — let's talk.

**LinkedIn →** [priyanshu-pratap-singh](https://www.linkedin.com/in/priyanshu-pratap-singh-84bb692b7)

---

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=Priyanshu-pps007&show_icons=true&theme=dark&hide_border=true&count_private=true" height="150" />
  &nbsp;&nbsp;
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Priyanshu-pps007&layout=compact&theme=dark&hide_border=true" height="150" />
</p>
