# Hi, I'm Artyom
### Backend & AI Systems Developer | Python & .NET

Focused on building reliable backend architectures, asynchronous distributed systems, and deterministic AI/LLM integration layers. Experienced in building high-load Telegram services, RAG pipelines, and end-to-end containerized microservices.

---

### Tech Stack

- **Core & Backend:** Python (Asyncio, FastAPI, Celery, Aiogram 3), C# (.NET 10)
- **Databases & Caching:** PostgreSQL, Redis, SQLite, pgvector, SQLAlchemy 2.0 / Alembic
- **Infrastructure & DevOps:** Docker, Docker Compose, Linux / Bash, Git, GitHub Actions (CI/CD)
- **AI & Integration:** RAG pipelines, LLM APIs (Claude, OpenAI), Knowledge Graphs, Context Engineering, Tool Calling / MCP

---

### Highlighted Projects

#### [deribit-tracker](https://github.com/blakedimm/deribit-tracker)
> Production-ready crypto market-data ingestion and analytics REST API for Deribit.
- Layered clean architecture (API, Services, Repositories, Clients) on FastAPI with asyncpg and Alembic migrations.
- Isolated background ingestion worker via Celery + Celery Beat + Redis; handles exchange rate-limits and network hiccups without dropping tasks.
- Precise financial arithmetic (`NUMERIC(18, 8)` / `Decimal`), composite indexing `(ticker, timestamp DESC)` for 15–25 ms read queries.
- Zero-leak network client on `aiohttp` with strict timeout controls to eliminate hanging sockets; fully covered by 28 unit/integration tests running under 1s.
- **Stack:** Python 3.10+, FastAPI, PostgreSQL, Celery, Redis, Docker Compose, Pytest.

#### [CognitiveEngine](https://github.com/blakedimm/CognitiveEngine)
> Neuro-symbolic cognitive architecture and hybrid RAG engine designed to eliminate LLM hallucinations.
- Implements deterministic verification layers using knowledge graphs and vector search.
- Solves context drift and logic inconsistencies in multi-step AI reasoning.
- **Stack:** .NET 10 / C#, Vector Embeddings, Knowledge Representation.

#### [Eliza](https://github.com/blakedimm/eliza)
> Autonomous Windows desktop AI copilot, agentic protocol executor, and voice assistant.
- Custom strict action protocol parser transforming natural language LLM outputs into sandboxed OS actions.
- Zero-lag streaming client supporting both local open-weights engines (LM Studio, Ollama) and cloud providers.
- Low-level system automation (Win32 interop, window management, process orchestration) and native voice synthesis.
- **Stack:** C# / .NET 10, Win32 API, Streaming HTTP.

#### Umbreliana Engine (Production Telegram Ecosystem)
> High-load asynchronous Telegram service with virtual economy and payment pipelines.
- Integrated payment gateways with strict webhook validation, signature verification, and idempotency guarantees.
- Scalable state machine (FSM), distributed caching, and clean relational schema under continuous production load.
- **Stack:** Python, Aiogram 3, PostgreSQL, Redis, Docker.

---

### Local Inference & Dev Environment

- **Workstation:** Intel Core i5-14400F | NVIDIA RTX 5060 Ti (16 GB VRAM) | 32 GB RAM | 1 TB NVMe SSD

---

### Connect With Me

- **Telegram:** [@yaser7141](https://t.me/yaser7141)
- **Email:** ggg131379@gmail.com
