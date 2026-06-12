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

### OllamaClient

A .NET client library for integrating with Ollama APIs in C# applications — local LLM integrations, ASP.NET Core apps, streaming chat, and developer tooling.

Repository: [OllamaClient](https://github.com/Dev-Art-Solutions/OllamaClient)

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

### SmoothLingua

An open-source conversational AI framework for building agents, intent recognition, rules, and conversation flows.

Repository: [SmoothLingua](https://github.com/Dev-Art-Solutions/SmoothLingua) · [SmoothLingua.Api](https://github.com/Dev-Art-Solutions/SmoothLingua.Api)

---

## Engineering focus

We build AI systems that are reliable, extensible, maintainable, observable, and production-ready.

Tools we work with:

```
AI / Agents     LLM integrations · OpenClaw · RAG · Ollama · OpenAI-compatible APIs
Backend         .NET / ASP.NET Core · C# · Node · REST APIs
Frontend        React · Next.js · Angular · TypeScript
Infra           Docker · CI/CD · PostgreSQL
```
