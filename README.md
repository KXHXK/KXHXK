<h1 align="center">🧠 AI Agent Engineering</h1>

<p align="center">
  Building reliable Agent runtimes, typed semantic harnesses, tool and knowledge boundaries,<br/>
  evaluation pipelines, failure recovery, and full-stack systems that make model behavior verifiable.
</p>

<p align="center">
  <a href="https://kxh-agent-portfolio.netlify.app/">
    <img src="https://img.shields.io/badge/AI_Agent_Portfolio-Engineering_Evidence-006B57?style=for-the-badge&logo=netlify&logoColor=white" alt="AI Agent engineering portfolio" />
  </a>
  <a href="https://github.com/KXHXK/opercerta">
    <img src="https://img.shields.io/badge/OperCerta-Agent_Runtime-111916?style=for-the-badge&logo=github&logoColor=white" alt="OperCerta repository" />
  </a>
  <a href="https://github.com/KXHXK/fieldpilot">
    <img src="https://img.shields.io/badge/FieldPilot-Typed_Harness-2B6F62?style=for-the-badge&logo=github&logoColor=white" alt="FieldPilot repository" />
  </a>
</p>

## 🔬 Featured Agent Systems

### 🛡️ [OperCerta](https://github.com/KXHXK/opercerta) — Controlled Agent Runtime

A recoverable, evaluable, and auditable Agent runtime for operational workflows.

- Single-root **LangGraph Agent Loop**: Model → ToolPolicy → MCP Observation → Model
- Typed Context/State, PostgreSQL Checkpoint/Replay, HITL approval binding, fact re-fetch, Verifier, and idempotent writes
- FastAPI, FastMCP, PostgreSQL/pgvector, Redis, React/SSE, OpenTelemetry, Docker, and CI
- Evidence: **42/42** fixed business contracts, **9/9** safe recovery traces, and **0 duplicate work orders** across 20 × 10 concurrent writes
- Redis reduced repeated MCP reads from **10 to 2 (-80%)**; fixed local scenarios reduced P50 by **58%–61%**
- 🌐 [Engineering showcase](https://opercerta-kxh.netlify.app) · 💻 [Source code](https://github.com/KXHXK/opercerta)

### 🧭 [FieldPilot](https://github.com/KXHXK/fieldpilot) — Typed Semantic Harness

A cross-city field-mission Agent that isolates LLM uncertainty at the natural-language boundary.

- A no-tool **PydanticAI Harness** converts untrusted text into a strict, confirmable MissionDraft
- Deterministic postchecks recompute clarifications, safety labels, and date normalization
- Bounded Beam Planner, Policy Engine, Independent Verifier, ExecutionCheckpoint, and suffix-only replanning
- Idempotent AgentRun, input fingerprints, usage limits, auditable traces, and no-fallback live evaluation gates
- Evidence: **15/15 Kimi K2.6 live**, state/safety **100%**, field precision **94.87%**, clarification precision **93.33%**
- 🌐 [Project showcase](https://fieldpilot-kxh.netlify.app/) · 💻 [Source code](https://github.com/KXHXK/fieldpilot)

## 🧩 Agent Engineering Focus

<table>
<tr>
<td width="50%" valign="top">

### 🔁 Runtime & State

Agent Loop, Context/State, Checkpoint/Replay, human approval, failure recovery, concurrency control, and idempotent side effects.

</td>
<td width="50%" valign="top">

### 🔌 Tools & Knowledge

Tool Calling, MCP, RAG, hybrid retrieval, citations, permission boundaries, policy checks, caching, and external provider ports.

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 📏 Evaluation & Observability

Versioned datasets, deterministic contracts, live-model gates, Trace, failure replay, latency/cost analysis, and regression tests.

</td>
<td width="50%" valign="top">

### 🧱 Full-Stack Productization

FastAPI, PostgreSQL, Redis, React/Vue, TypeScript, Docker, CI, cloud deployment, and operational documentation.

</td>
</tr>
</table>

## 🛠️ Technology Stack

<div align="center">

**Agent / AI**

![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=flat&logo=langchain&logoColor=white)
![PydanticAI](https://img.shields.io/badge/PydanticAI-E92063?style=flat&logo=pydantic&logoColor=white)
![MCP](https://img.shields.io/badge/MCP-000000?style=flat)
![RAG](https://img.shields.io/badge/RAG-2B6F62?style=flat)
![OpenTelemetry](https://img.shields.io/badge/OpenTelemetry-000000?style=flat&logo=opentelemetry&logoColor=white)

**Languages / Application**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)
![C#](https://img.shields.io/badge/C%23-512BD4?style=flat&logo=dotnet&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=flat&logo=react&logoColor=61DAFB)
![Vue.js](https://img.shields.io/badge/Vue.js-35495E?style=flat&logo=vuedotjs&logoColor=4FC08D)

**Data / Delivery**

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-FF4438?style=flat&logo=redis&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat&logo=githubactions&logoColor=white)
![Netlify](https://img.shields.io/badge/Netlify-00C7B7?style=flat&logo=netlify&logoColor=white)
![Render](https://img.shields.io/badge/Render-000000?style=flat&logo=render&logoColor=white)

</div>

## 🌍 Upstream Open-Source Engineering

**Eight focused contributions are merged** in established Agent and developer-tool projects. Personal repository work is excluded.

| Project | Stars | Engineering contribution | Status |
|:--|:--:|:--|:--:|
| [Cherry Studio #18475](https://github.com/CherryHQ/cherry-studio/pull/18475) | 50.4k | Removed a duplicate workspace-list request after creation while preserving the existing mutation-owned refresh and workspace selection flow. | ✅ Merged |
| [AgentScope #2178](https://github.com/agentscope-ai/agentscope/pull/2178) | 28.9k | Kept tool-response error states sticky across later interrupted or denied chunks and added regression coverage. | ✅ Merged |
| [Mastra #21154](https://github.com/mastra-ai/mastra/pull/21154) | 27.2k | Preserved the provider-selected response model on inference spans without overwriting the requested model. | ✅ Merged |
| [Microsoft Agent Framework #7324](https://github.com/microsoft/agent-framework/pull/7324) | 12.8k | Preserved table binding across consecutive declarative `EditTable` operations and added regression coverage. | ✅ Merged |
| [local-deep-research #5269](https://github.com/LearningCircuit/local-deep-research/pull/5269) | 8.9k | Unified Zotero progress and error feedback while preserving accessibility and XSS-safe rendering. | ✅ Merged |
| [Strands Agents Harness SDK #3627](https://github.com/strands-agents/harness-sdk/pull/3627) | 6.9k | Preserved token usage from hook-retried model calls so cost reporting and invocation limits remain accurate. | ✅ Merged |
| [Langroid #1072](https://github.com/langroid/langroid/pull/1072) | 4.1k | Fixed concurrent result selection so a fast empty result cannot cancel a slower valid result. | ✅ Merged |
| [A2A Java #999](https://github.com/a2aproject/a2a-java/pull/999) | 0.5k | Corrected interoperability test topology while preserving valid JSON-RPC and gRPC coverage. | ✅ Merged |

## 📐 Engineering Principles

- 🧠 **The model handles ambiguity; deterministic code decides correctness and side effects.**
- 🧾 **Metrics need datasets, scripts, runtime conditions, and commits—not just screenshots.**
- 🔒 **Public demos use synthetic or redacted data and expose no credentials or private systems.**
- 🧪 **Failure recovery, idempotency, policy checks, and evaluation are product behavior.**
- 🧱 **Agent engineering includes APIs, state, data, UI, deployment, and operations—not only model calls.**

## 🛰️ Broader Systems Background

Beyond Agent systems, repositories include C# serial/device communication tools, MATLAB signal-processing and imaging utilities, PDF report generation, and full-stack Web applications. These projects provide the systems, data, debugging, and delivery foundation behind the Agent work.
