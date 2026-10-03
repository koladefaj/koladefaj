## Hi, I'm Kolade 👋

**Backend & AI Infrastructure Engineer** working on distributed systems, reliability, and LLM training/inference infrastructure.

Recent open-source work includes contributions to **AReaL**, **LiteLLM**, and **vLLM**, alongside building fault-tolerant backend and AI systems.

---

### Open Source

**[AReaL](https://github.com/areal-project/AReaL)** — Distributed LLM training & RL infrastructure

- [#1564](https://github.com/areal-project/AReaL/pull/1564) — Fixed per-pipeline-parallel weight synchronization on the SGLang backend so mismatched Megatron/vLLM pipeline-parallel configurations can train correctly.
- [#1154](https://github.com/areal-project/AReaL/pull/1154) — Replaced manually parsed request data with validated Pydantic models.
- [#1179](https://github.com/areal-project/AReaL/pull/1179) — Refactored Flask/FastAPI blueprint boundaries and application architecture.

**[LiteLLM](https://github.com/BerriAI/litellm)**

- [#30644](https://github.com/BerriAI/litellm/pull/30644) — Fixed Redis parameter discovery through decorated client methods and runtime type coercion for environment/Helm configuration.


**Sandhi AI**

- Worked on distributed task reliability with Celery and Redis: queue isolation, atomic Lua admission control, circuit breakers, retries, and overload protection.

**WebTech Network**

- Removed import-time Redis side effects and introduced dependency injection through the FastAPI application lifecycle.

---

### Projects

**[Relier](https://github.com/getrelier/relier)** — Fault-tolerant reliability layer for Celery.

- 100% task delivery across 10,000 tasks under 10 simultaneous worker SIGKILLs vs. 99.07% with vanilla Celery.
- Reduced graceful-shutdown task failures from 91.6% to 0%.
- Implements heartbeats, task resurrection, Redis/Lua idempotency, leases, and fencing.

```bash
pip install relier
```

**Gia** — Real-time voice AI and long-term memory system.

- Reduced voice time-to-first-audio from ~10s p99 to 4–6s.
- Achieved ~1.1s speech-to-speech on an OpenAI Realtime path.
- Reduced intent classification from ~1.4s to 40–60ms using a distilled classifier.

**Phalanx** — Distributed fraud detection and ML inference platform.

- 0.43ms ONNX model inference.
- Zero-downtime ONNX model hot-swapping.
- Selective LLM routing for BLOCK/REVIEW decisions.

**Engram** — RAG and document intelligence platform.

- Improved context precision from 0.762 → 0.883.
- Improved faithfulness from 0.841 → 0.892.
- Hybrid retrieval, re-ranking, and confidence-gated corrective RAG.

---

### Stack

**Languages:** Python · SQL · JavaScript · Protobuf

**Systems:** FastAPI · Celery · Redis/Lua · gRPC · PostgreSQL · Docker

**AI/ML:** ONNX Runtime · LiteLLM · LlamaIndex · pgvector · Weaviate

**Observability:** OpenTelemetry · Langfuse

**Cloud:** AWS

---

### Connect

[LinkedIn](https://linkedin.com/in/kolade-fajimi-1504b8246) · [X](https://x.com/akoladefaj) · [Email](mailto:fajimikolade@gmail.com)
