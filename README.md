<div align="center">

# Atichat Chaisarn (Night / ไน🌙) — AI Systems Engineer Portfolio

[![Live Portfolio — GitHub Pages](https://img.shields.io/badge/Live_Portfolio-nakitadev.github.io-6366f1?style=for-the-badge&logo=github&logoColor=white)](https://nakitadev.github.io)
[![Live Mirror — Vercel](https://img.shields.io/badge/Vercel_Mirror-atichat--portfolio-000000?style=for-the-badge&logo=vercel&logoColor=white)](https://atichat-portfolio-nakitadevprojects.vercel.app)
[![Smart AI Facility](https://img.shields.io/badge/Live_SaaS-Smart_AI_Facility-10b981?style=for-the-badge&logo=fastapi&logoColor=white)](https://smart-ai-facility.vercel.app)
[![Hugging Face Spaces](https://img.shields.io/badge/HF_Spaces-Live_Agent_Demos-f59e0b?style=for-the-badge&logo=huggingface&logoColor=black)](https://huggingface.co/spaces/nakitadev/langchain-sidekick)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-atichat--ch-0a66c2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/atichat-ch)
[![Email](https://img.shields.io/badge/Email-atichat.cs%40gmail.com-06b6d4?style=for-the-badge&logo=gmail&logoColor=white)](mailto:atichat.cs@gmail.com)

**Engineering deterministic multi-agent workflows, hybrid RAG pipelines (`pgvector` + `BM25` RRF), and serverless AWS AI infrastructure.**

[🌐 Primary Live Site (`nakitadev.github.io`)](https://nakitadev.github.io) · [⚡ Vercel Edge Deployment](https://atichat-portfolio-nakitadevprojects.vercel.app) · [💻 GitHub (`@nakitadev`)](https://github.com/nakitadev)

</div>

---

## ✨ Interactive Portfolio Highlights

This zero-dependency, single-file interactive portfolio ([`index.html`](./index.html)) is engineered for sub-second load times and hands-on technical exploration:

| Interactive Feature | Engineering Implementation & UX | Shortcut / Trigger |
| :--- | :--- | :--- |
| **🌌 Neural Constellation Canvas** | Custom 60FPS HTML5 `<canvas>` particle network with cursor-reactive proximity edges and ambient radial spotlight tracking. | Mouse movement |
| **⌨️ `⌘K` Command Palette** | Global keyboard-driven launcher to jump across sections, filter projects, open live deployments (Vercel / HF Spaces), or copy contact info. | `⌘K` / `Ctrl+K` |
| **🔎 Live Stack Search & Tag Filter** | Instant client-side filtering across all 6 production systems by category (`Multi-Agent`, `Hybrid RAG`, `AWS Serverless`), slash-key search, or clickable tech badges. | `/` to focus search |
| **🧩 Architecture Blueprint Sandbox** | Interactive system stage inspecting exact node-by-node data flows, failure guardrails, and AWS cost optimizations (`1`, `2`, `3` hotkeys). | Keys `1` · `2` · `3` |
| **🤖 AI Digital Twin Terminal** | Conversational CLI shell with typewriter streaming, preset engineering flags (`--hybrid-rag`, `--s3-vector-cost`, `--civil-to-ai`), and free-text query parsing. | Interactive CLI |
| **📡 Live Agent Telemetry Inspector** | Interactive hero node graph detailing how the Planner, Hybrid Retriever, LangGraph Evaluator, and S3 Vector Store coordinate in production. | Click node rows |

---

## 🏗️ Flagship Production AI Systems (6 Architectures)

### 1. ALEX — Agentic Learning Equities Explainer
> **Category:** Multi-Agent Financial SaaS · AWS Serverless · Infrastructure-as-Code  
> **Repository:** [`github.com/nakitadev/alex-platform`](https://github.com/nakitadev/alex-platform)

```text
Next.js Client ──► API Gateway + FastAPI Lambda ──► AWS SQS Queue
                                                       │
                                                       ▼
                                          Planner / Orchestrator Agent
                                    ┌──────────┬───────┴───────┬──────────┐
                                    ▼          ▼               ▼          ▼
                                 Tagger    Reporter        Charter   Retirement
                                    └──────────┴───────┬───────┴──────────┘
                                                       ▼
                                  Amazon S3 Vectors + SageMaker Embeddings + RDS
```

- **Parallel Multi-Agent Fan-Out:** Replaced slow sequential chains with asynchronous **AWS SQS + Lambda** orchestration where a **Planner Agent** dispatches sub-tasks to 4 specialized financial agents (`Tagger`, `Reporter`, `Charter`, `Retirement`).
- **~90% Vector Cost Reduction:** Architected semantic memory on **Amazon S3 Vectors** paired with a serverless **SageMaker HuggingFace embedding endpoint**, eliminating $300+/month idle OpenSearch Serverless cluster overhead.
- **Modular Terraform & Observability:** Provisioned across 7 composable **Terraform** stacks with end-to-end **Langfuse** agent trace telemetry.

---

### 2. Smart AI Facility Management System
> **Category:** Production Hybrid RAG · Deterministic Tool Calling · Full-Stack AI  
> **Live App:** [`smart-ai-facility.vercel.app`](https://smart-ai-facility.vercel.app) · **Repository:** [`github.com/nakitadev/smart-ai-facility`](https://github.com/nakitadev/smart-ai-facility)

```text
User Query ──► Intent Router ──┬──► [SQL Tool-Call Pipeline] ──► Async SQLAlchemy 2.0 (Conflict-Safe UTC+7 DB)
                               │
                               └──► [Hybrid RAG Pipeline]    ──► pgvector Cosine ∪ PostgreSQL BM25 FTS
                                                                               │
                                                                               ▼
                                                                 Reciprocal Rank Fusion (RRF)
                                                                               │
                                                                               ▼
                                                                 Pydantic-Validated Grounded Citation
```

- **Hybrid RRF Retrieval:** Combines **PostgreSQL `pgvector`** semantic search with **PostgreSQL `tsvector` BM25** full-text search merged via **Reciprocal Rank Fusion (RRF)** so exact room codes, SOP numbers, and semantic concepts are retrieved together.
- **Reliability Guardrails:** Enforces strict **Pydantic** output validation with automated multi-model fallback retry chains across OpenRouter and **UTC+7 timezone-safe** booking conflict detection.
- **Production Engineering Rigor:** Containerized with **Docker**, backed by **81+ automated Pytest unit/integration tests**, and validated via **GitHub Actions CI/CD**.

---

### 3. LangChain Sidekick — Evaluator-Driven Autonomous Agent
> **Category:** Stateful Agent Graph · Self-Correcting Loop · Browser & REPL Automation  
> **Live Demo:** [`HF Space: nakitadev/langchain-sidekick`](https://huggingface.co/spaces/nakitadev/langchain-sidekick) · **Repository:** [`github.com/nakitadev/langchain-sidekick`](https://github.com/nakitadev/langchain-sidekick)

```text
User Goal + Success Criteria ──► LangGraph Worker Node ──► [Playwright MCP | Sandboxed Python REPL | Pushover]
                                          ▲                                        │
                                          │         Loop with Feedback             ▼
                                          └────────── Structured Evaluator Node (EvaluatorOutput)
```

- **Self-Verifying Cyclic State Graph:** Built on **LangGraph** with an explicit `Worker → Tools → Evaluator` cycle that prevents premature or hallucinated task completion.
- **Structured Grading Contract:** A dedicated **Evaluator Node** grades intermediate outputs against user-defined acceptance criteria using a strict Pydantic `EvaluatorOutput` schema, routing actionable feedback back to the Worker until criteria pass.
- **Multi-Tool Execution:** Integrates headless **Playwright MCP** browser navigation, sandboxed Python REPL execution, file tools, and Pushover alerts inside a live Gradio interface.

---

### 4. AI Engineering Studio — 4-Agent Software Team
> **Category:** Multi-Agent SDLC Automation · Hierarchical CrewAI · Docker Sandboxed QA  
> **Live Demo:** [`HF Space: nakitadev/ai-engineering-studio`](https://huggingface.co/spaces/nakitadev/ai-engineering-studio) · **Repository:** [`github.com/nakitadev/ai-engineering-studio`](https://github.com/nakitadev/ai-engineering-studio)

```text
Plain-English Spec ──► Engineering Lead (Architecture) ──► Backend Engineer (Core Logic)
                                                                   │
                                                                   ▼
ZIP Deliverable ◄── Frontend Engineer (Gradio UI) ◄── QA Engineer (Docker Sandbox Pytest)
```

- **4-Agent Hierarchical Pipeline:** Orchestrates **Engineering Lead, Backend Engineer, QA Engineer, and Frontend Engineer** agents across **Claude Sonnet** and **GPT-4o** using **CrewAI**.
- **Sandboxed Verification:** Executes generated Python modules and unit test suites inside isolated **Docker** containers before packaging downloadable full-stack ZIP deliverables.

---

### 5. Serverless AI Digital Twin on AWS
> **Category:** AWS Serverless · Amazon Bedrock (Nova) · OIDC CI/CD  
> **Repository:** [`github.com/nakitadev/digital-twin`](https://github.com/nakitadev/digital-twin)

```text
Client Request ──► Amazon CloudFront + S3 ──► API Gateway ──► FastAPI Lambda ──► Amazon Bedrock (Nova)
                                                                    │
                                                                    ▼
                                                        S3 Conversation Memory + Persona Context
```

- **Serverless Bedrock Architecture:** Powered by **Amazon Bedrock (Nova)** behind **API Gateway + AWS Lambda**, with persistent multi-turn session state stored in **Amazon S3**.
- **Zero-Secret Deployment:** Provisioned end-to-end with **Terraform** and deployed via **GitHub Actions** using **AWS IAM OIDC federation** (zero long-lived static AWS keys).

---

### 6. Healthcare Consultation Assistant SaaS
> **Category:** Cloud SaaS · Real-Time SSE Streaming · Clerk + Stripe Billing  
> **Repository:** [`github.com/nakitadev/healthcare-consultation-app`](https://github.com/nakitadev/healthcare-consultation-app)

```text
Doctor Input ──► Next.js + Clerk Auth + Stripe Gate ──► FastAPI SSE Stream ──► Structured Clinical Notes & Follow-Up
```

- **Low-Latency Clinical Streaming:** Streams structured visit summaries, differential action items, and patient-friendly follow-up emails in real time via **FastAPI Server-Sent Events (SSE)**.
- **Full SaaS Monetization & Auth:** Integrates **Clerk** authentication and **Stripe** subscription tier enforcement, containerized for **GCP Cloud Run** and **Vercel**.

---

## 🛠️ Production Engineering Toolkit

| Domain | Technologies & Patterns |
| :--- | :--- |
| **Agentic & LLM Orchestration** | `LangGraph` · `LangChain` · `OpenAI Agents SDK` · `CrewAI` · `Model Context Protocol (MCP)` · `AWS Bedrock (Nova / Claude)` · `OpenRouter Fallbacks` |
| **Hybrid RAG & Data Systems** | `PostgreSQL + pgvector` · `BM25 Full-Text Search` · `Reciprocal Rank Fusion (RRF)` · `Amazon S3 Vectors` · `Pydantic v2 Strict Schemas` · `PyMuPDF` |
| **Cloud, IaC & MLOps** | `AWS (Lambda, SQS, API Gateway, S3, SageMaker, CloudFront)` · `Terraform (IaC)` · `Docker Sandboxes` · `GitHub Actions (AWS OIDC)` · `GCP Cloud Run` · `Langfuse` |
| **Full-Stack & Quality** | `Python 3.12` · `FastAPI` · `SQLAlchemy 2.0 Async` · `TypeScript` · `Next.js 16` · `Playwright` · `Pytest (81+ Automated Tests)` · `Clerk` · `Stripe` |

---

## 🚀 Local Preview & Deployment

Because the portfolio is self-contained with zero build steps required, you can launch it immediately:

```bash
# Clone the repository
git clone https://github.com/nakitadev/nakitadev.github.io.git
cd nakitadev.github.io

# Serve locally on port 8000
python3 -m http.server 8000
```

Then open `http://localhost:8000` and press **`⌘K`** (or **`Ctrl+K`**) to open the interactive command palette, or **`/`** to search the tech stack.

---

## 📬 Contact & Availability

- **Name:** Atichat Chaisarn (Night / ไน🌙)
- **Education:** B.Eng. in Civil Engineering, **Chulalongkorn University** (GPA **3.59**, Second-Class Honors)
- **Location:** Bangkok, Thailand (`UTC+7`) — Available for AI Systems Engineer, LLM/RAG Engineer, and Full-Stack AI roles
- **Portfolio Links:** [nakitadev.github.io](https://nakitadev.github.io) · [atichat-portfolio-nakitadevprojects.vercel.app](https://atichat-portfolio-nakitadevprojects.vercel.app)
- **Direct Contact:** [atichat.cs@gmail.com](mailto:atichat.cs@gmail.com) · [LinkedIn (`atichat-ch`)](https://www.linkedin.com/in/atichat-ch) · [GitHub (`@nakitadev`)](https://github.com/nakitadev)
