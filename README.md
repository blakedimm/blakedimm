# Hi, I'm Artyom
**Backend, Systems & AI Infrastructure Engineer | Python & .NET**

Focused on building reliable backend architectures, high-performance systems software, asynchronous distributed pipelines, and deterministic AI/LLM integration layers. Experienced in building custom language runtimes, high-load Telegram platforms, financial data engines, and production-ready microservices.

---

### Tech Stack

- **Core & Systems:** C# (.NET 10), Python (Asyncio, FastAPI, Celery, Aiogram 3)
- **Architecture & Compilers:** Bytecode VMs, Single-pass Pratt Parsing, AST/Lexing, Clean Architecture, Distributed Systems
- **Databases & Caching:** PostgreSQL, Redis, SQLite, pgvector, SQLAlchemy 2.0 / Alembic, asyncpg
- **Infrastructure & Tooling:** Docker, Docker Compose, Linux / Bash, Git, GitHub Actions (CI/CD)
- **AI & Reasoning:** Neuro-Symbolic Systems, RAG Pipelines, Context Engineering, Knowledge Graphs, MCP / Tool Calling

---

### Highlighted Projects

#### [Umbra (.umb)](https://github.com/blakedimm/umbra)
*High-performance, dynamically-typed programming language and stack-based bytecode virtual machine built from scratch in modern C# (.NET 10) with zero external dependencies.*

- **Hand-written Compiler Pipeline:** Single-pass top-down operator precedence (Pratt) parser compiling directly into compact bytecode chunks with 16-bit jump backpatching (`OpJump`, `OpLoop`) and compile-time loop desugaring.
- **Multi-Frame Stack VM:** Custom runtime executing bytecode using pre-allocated call frames (`FramesMax = 64`) and flat value stack with relative local slot indexing.
- **Language Features:** Strict mutability semantics (`let` vs `mut`), first-class closures, pipeline operator (`|>`), nested dynamic collections with Python-style negative indexing, and native FFI bindings.
- **Ecosystem & Tooling:** Includes an interactive REPL, built-in acceptance test harness, official VS Code syntax extension, and a procedural dungeon generator showcase (**Aether**).
- **Stack:** C# / .NET 10, Bytecode VM Architecture, Pratt Parser, Custom Lexer.

#### [deribit-tracker](https://github.com/blakedimm/deribit-tracker)
*Production-ready crypto market-data ingestion and analytics REST API for Deribit.*

- **Clean Layered Architecture:** Decoupled layers (API, Services, Repositories, Clients) on FastAPI with asyncpg and managed Alembic migrations.
- **Resilient Ingestion:** Background polling pipeline via Celery + Celery Beat + Redis; transparently absorbs exchange rate-limits and network dropouts without losing tasks.
- **Performance & Precision:** Exact financial math (`NUMERIC(18, 8)` / `Decimal`) and composite indexing (`ticker, timestamp DESC`) delivering 15–25 ms read latency.
- **Zero-Leak Networking:** Resilient `aiohttp` client with aggressive timeout controls; covered by 28 unit and integration tests executing under 1 second.
- **Stack:** Python 3.10+, FastAPI, PostgreSQL, Celery, Redis, Docker Compose, Pytest.

#### [CognitiveEngine](https://github.com/blakedimm/CognitiveEngine)
*Experimental neuro-symbolic cognitive architecture and hybrid RAG engine designed to eliminate LLM hallucinations.*

- Implements deterministic verification layers using hybrid knowledge graphs and vector search.
- Solves context drift and structural logic inconsistencies across multi-step AI reasoning chains.
- **Stack:** .NET 10 / C#, Vector Embeddings, Knowledge Representation.

#### [Eliza](https://github.com/blakedimm/Eliza)
*Autonomous Windows desktop AI copilot, agentic protocol executor, and voice assistant.*

- **Action Protocol Parser:** Translates natural language LLM outputs into sandboxed, deterministic OS commands.
- **Low-Latency Streaming:** Zero-lag streaming transport supporting local open-weight runtimes (LM Studio, Ollama) and cloud providers.
- **OS Orchestration:** Low-level Win32 interop, window management, process orchestration, and native audio synthesis.
- **Stack:** C# / .NET 10, Win32 API, Streaming HTTP.

#### Umbreliana Engine
*High-load asynchronous Telegram service featuring a virtual economy and payment pipelines.*

- Integrated payment webhooks with cryptographic signature verification and strict idempotency handling.
- Scalable Finite State Machine (FSM), distributed caching, and normalized schema designed for high-concurrency event loops.
- **Stack:** Python, Aiogram 3, PostgreSQL, Redis, Docker.

---

### Local Inference & Hardware Lab

- **CPU:** Intel Core i5-14400F
- **GPU:** NVIDIA GeForce RTX 5060 Ti (16 GB VRAM)
- **RAM:** 32 GB DDR4
- **Storage:** 1 TB NVMe SSD

---

### Connect With Me

- **Telegram:** [@yaser7141](https://t.me/yaser7141)
- **Email:** [ggg131379@gmail.com](mailto:ggg131379@gmail.com)
