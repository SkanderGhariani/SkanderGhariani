# Hi, I'm Skander Ghariani

Software engineer from Tunis focused on backend development and applied AI.

Most of my recent work is around self-hosted LLMs: running local models with `llama.cpp` and building backend services and agents around them.

## Experience

### AI Engineer — CURE: The AI-Pharmacy-Platform *(Jan 2025 – Dec 2025, Remote)*
- Built a production order extraction pipeline using a self-hosted, quantized Mistral 7B (`llama.cpp`) to convert German pharmacy call transcripts into structured orders.
- Developed **CureSearch**, an embeddings-based product search system using Node.js and MongoDB.
- Integrated the platform with Uber Eats, Wolt, and Lieferando.

### Research Intern — Dracodes *(Jun 2024 – Jul 2024)*
- Researched parameter-efficient fine-tuning methods for LLMs, including LoRA, Delta-LoRA, and KronA.

### Full Stack Developer — MCM Tunisia *(Sep 2023 – Dec 2023)*
- Built and deployed MERN stack web applications.

## Projects

### [voicebrain](https://github.com/SkanderGhariani/voicebrain)
A self-hosted multilingual voice-notes assistant for Telegram: local Whisper transcription, `llama.cpp` structured extraction with JSON-schema grammar, semantic search, and RAG.

### [tabletalk](https://github.com/SkanderGhariani/tabletalk)
An agent that answers plain-language questions about a SQLite database: LangGraph state machine with run_sql / run_python / ask_user tools, a sqlglot query guard on a read-only connection, sandboxed Python for charts, and an MCP server for Claude Code. Runs on a local Qwen2.5-7B via `llama.cpp`. Evaluated on a 100-question Spider sample (67% execution accuracy) plus a behaviour suite (prompt injection, write refusal, tool-call budgets).

### [pgbatch](https://github.com/SkanderGhariani/pgbatch)
A batch job queue on PostgreSQL: HTTP API, workers that claim jobs with SKIP LOCKED and leases, retries with backoff, and fenced completion. A crash test kills workers at random during a 10,000-job batch: 0 jobs lost, 0 completed twice.

## Skills

**AI/ML:** LLMs, Agents (LangGraph, tool calling, MCP), Embeddings & Semantic Search, RAG, Evals, `llama.cpp`, GGUF Quantization

**Languages:** Python, TypeScript, JavaScript

**Backend:** Node.js, Express, FastAPI, MongoDB

**Frontend:** React, Angular

**DevOps:** Docker, AWS, GitHub Actions

## Education

**B.S. Software Engineering**
South Mediterranean University (MedTech) *(2021 – 2025)*

## Connect

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/skander-ghariani-637a8a298/)
