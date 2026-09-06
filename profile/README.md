<div align="center">

<img src="https://avatars.githubusercontent.com/u/102830577?s=200&v=4" alt="Dev Art Solutions Logo" width="120" />

# Dev Art Solutions

**We build AI and agent systems that ship to production — language-agnostic, not just demos.**

[Website](https://devart.solutions) · [GitHub](https://github.com/Dev-Art-Solutions)

</div>

---

## What we build

Dev Art Solutions is a family-run engineering studio building production-oriented AI systems, developer tools, and automation platforms.

Our focus:

- LLM integrations into existing software
- Local / on-premise AI infrastructure (Ollama)
- Conversational and agentic systems
- Workflow and process automation
- Open-source developer tooling and SDKs

We care about practical AI that runs inside real products — across whatever stack the product needs (.NET, Node, React, Angular).

---

## Products

### TradeAudit

A desktop trading intelligence platform for MetaTrader 5 traders: R-multiple risk accounting, strategy-vs-execution compliance analysis, behavioral/emotional discipline detection (FOMO, revenge trading, overtrading), quantitative research (Monte Carlo, Risk of Ruin, bootstrap intervals), and interactive candlestick trade replay.

Stack: Python · PySide6 (Qt6) · SQLite / SQLAlchemy · MetaTrader5 SDK
Repository: [TradeAudit](https://github.com/Dev-Art-Solutions/TradeAudit)

---

### MT5 RiskGuard

A lightweight, strategy-agnostic MetaTrader 5 Expert Advisor that continuously monitors account risk and exposes deterministic `SAFE`, `RESTRICTED`, `BLOCKED`, and `EMERGENCY` states. It enforces configurable daily-loss, per-position risk, trade-count, open-position, trading-session, and spread policies with restart-safe state and opt-in scoped liquidation.

Stack: MQL5 · MetaTrader 5 · GitHub Actions
Repository: [MT5 RiskGuard](https://github.com/Dev-Art-Solutions/RiskGuard)

---

### SamsaraForge

A platform for deliberate personal progress: long-term AI memory, task automation, and psychological profiling (IQ, EQ, Big Five) with real scoring logic. Integrates [OpenClaw](https://openclaw.ai) as an external agent service.

Stack: Next.js · PostgreSQL · Ollama / OpenAI · OpenClaw
Live: [samsaraforge.com](https://samsaraforge.com/)

### Dev Smart Academy

A learning platform that tracks where you make mistakes and automatically schedules practice on your weak points. Connects to OpenClaw to auto-generate content, code snippets, and diagrams.

Stack: Angular · PostgreSQL · AI quiz engine · OpenClaw
Live: [dev-smart.academy](https://dev-smart.academy/)

---

## Open-source projects

### EvoMesh

An open-source, local-first, self-evolving multi-agent environment. Agents live inside a shared environment, communicate through an asynchronous message layer, acquire reusable skills, maintain persistent state, and can create new agent definitions. The v0.1 foundation isolates candidate generations and preserves last-known-good rollback metadata while promotion remains human-controlled.

EvoMesh works directly with Ollama and other local OpenAI-compatible endpoints; it can also use InferHub as an optional local/self-hosted model provider.

Repository: [EvoMesh](https://github.com/Dev-Art-Solutions/EvoMesh) · [Documentation](https://evomesh.devart.solutions)

---

### OllamaClient

A .NET client library for integrating with Ollama APIs in C# applications — local LLM integrations, ASP.NET Core apps, streaming chat, and developer tooling.

Repository: [OllamaClient](https://github.com/Dev-Art-Solutions/OllamaClient)

---

### InferHub

[#inferhub](#inferhub)

A self-hosted LLM inference mesh in .NET. One Ollama-compatible API in front, a pool of GPU worker nodes behind it — run the hub where you have no GPU, run the nodes where you do.

Useful for:

- pooling GPUs across several machines behind one stable endpoint
- serving LLMs from behind a home router, with no port forwarding
- letting existing Ollama clients, scripts, and editor plugins keep working unchanged
- pluggable inference backends (Ollama first; vLLM, llama.cpp and others can slot in later)

Built on our own [OllamaClient](https://github.com/Dev-Art-Solutions/OllamaClient).

Repository: [InferHub](https://github.com/Dev-Art-Solutions/InferHub)

---

### InferHub.Clients

A set of typed .NET clients for talking to an InferHub coordinator from C#. Dependency-injection friendly, `System.Text.Json` under the hood, and designed for lightweight integration with InferHub services.

Repository: [InferHub.Clients](https://github.com/Dev-Art-Solutions/InferHub.Clients)

---

### SmoothLingua

An open-source conversational AI framework for building agents, intent recognition, rules, and conversation flows.

Repository: [SmoothLingua](https://github.com/Dev-Art-Solutions/SmoothLingua) · [SmoothLingua.Api](https://github.com/Dev-Art-Solutions/SmoothLingua.Api)

---

## Engineering focus

We build AI systems that are reliable, extensible, maintainable, observable, and production-ready.

Tools we work with:

```
AI / Agents     Local LLMs · Agent systems · RAG · Ollama · InferHub · OpenClaw
Backend         .NET / ASP.NET Core · C# · Python · Node · REST APIs
Frontend        React · Next.js · Angular · TypeScript
Infra           Docker · CI/CD · PostgreSQL · SQLite
```
