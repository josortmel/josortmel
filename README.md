# José Antonio Ortiz Melo — AI engineer · multi-agent systems

<p align="center">
  <img src="hero-combined.gif" alt="EcoDB + Eco Relay — AI memory infrastructure and inter-session messaging" width="100%">
</p>

I build memory infrastructure for AI agents, and I direct teams of agents to ship it. Based in Sevilla.

EcoDB and the projects below were built the way I work: one human holding the architecture and the calls, directing specialized AI agents (design, backend, QA, security) that each own their craft. I care about systems that hold up in production, not demos: real benchmarks, real isolation, real governance.

## What I've built

### [EcoDB](https://github.com/josortmel/EcoDB) — collective AI memory infrastructure

Shared memory for teams of agents. A 10-stage retrieval pipeline (GAMR) over a knowledge graph in PostgreSQL, with cross-modal search (a text query finds images and vice versa), multi-tenant isolation, role-based governance, and a desktop dashboard.

- **Recall@5 of 0.92** on LoCoMo (ACL 2024); full GAMR pipeline under **50 ms p95**
- Knowledge  graph on **Apache AGE** (Cypher inside Postgres), ~100 canonical predicates
- **32 MCP tools** + 30+ REST endpoints; in production since May 2026

`Python · FastAPI · PostgreSQL/pgvector · Apache AGE · Docker · Jina embeddings · MCP · React · Electron`

### [Eco Relay](https://github.com/josortmel/eco-relay) — real-time messaging between agent sessions

Direct messages, rooms, and presence so independent AI agent sessions can coordinate on the same machine. Persistent delivery, IRC-style ephemeral rooms.

## Stack

Backend: Python, FastAPI, PostgreSQL (pgvector, Apache AGE), Docker.
AI: embeddings (Jina v4), GLiNER NER, cross-encoder reranking, MCP.
Frontend: TypeScript, React, Electron, Tailwind.

## Reach me

- Email: [peportmel@gmail.com](mailto:peportmel@gmail.com)
- LinkedIn: [josortmel](https://www.linkedin.com/in/josortmel/)
