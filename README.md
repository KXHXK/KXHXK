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

**Twelve contributions have been accepted upstream** across established Agent and developer-tool projects: 11 directly merged PRs plus one Langroid fix merged through a maintainer PR with authorship retained. Personal repository work is excluded.

| Project | Stars | Engineering contribution |
|:--|:--:|:--|
| [DeerFlow #4804](https://github.com/bytedance/deer-flow/pull/4804) | 80.1k | Scoped bootstrap memory reads and writes to the selected custom Agent instead of leaking setup facts into the default memory bucket, with regression coverage. |
| [Cherry Studio #18475](https://github.com/CherryHQ/cherry-studio/pull/18475) | 50.4k | Removed a duplicate workspace-list request after creation while preserving the existing mutation-owned refresh and workspace selection flow. |
| [AgentScope #2178](https://github.com/agentscope-ai/agentscope/pull/2178) | 28.9k | Kept tool-response error states sticky across later interrupted or denied chunks and added regression coverage. |
| [Mastra #21154](https://github.com/mastra-ai/mastra/pull/21154) | 27.2k | Preserved the provider-selected response model on inference spans without overwriting the requested model. |
| [Microsoft Agent Framework #7324](https://github.com/microsoft/agent-framework/pull/7324) | 12.8k | Preserved table binding across consecutive declarative `EditTable` operations and added regression coverage. |
| [OpenSandbox #1519](https://github.com/opensandbox-group/OpenSandbox/pull/1519) | 12.6k | Replenished stale idle sandbox slots immediately after asynchronous cleanup and added deterministic Kotlin regression coverage. |
| [local-deep-research #5269](https://github.com/LearningCircuit/local-deep-research/pull/5269) | 8.9k | Unified Zotero progress and error feedback while preserving accessibility and XSS-safe rendering. |
| [OGX #6395](https://github.com/ogx-ai/ogx/pull/6395) | 8.4k | Documented supported search rankers in the generated API schema and added regression coverage for the description contract. |
| [Strands Agents Harness SDK #3627](https://github.com/strands-agents/harness-sdk/pull/3627) | 6.9k | Preserved token usage from hook-retried model calls so cost reporting and invocation limits remain accurate. |
| [Langroid #1072](https://github.com/langroid/langroid/pull/1072) | 4.1k | Fixed concurrent result selection so a fast empty result cannot cancel a slower valid result; the maintainer PR retained KXH authorship. |
| [A2A Java #999](https://github.com/a2aproject/a2a-java/pull/999) | 0.5k | Corrected interoperability test topology while preserving valid JSON-RPC and gRPC coverage. |
| [DevOps AI Toolkit / dot-ai #754](https://github.com/vfarcic/dot-ai/pull/754) | 0.3k | Fixed local embedding-model configuration in both normal and prefetched Helm paths, including the maintainer-requested test refinement. |

### Current PR Status

As of **August 17, 2026**, 31 external PRs remain open. The recently active review queue is summarized below; the remaining PRs have no unanswered maintainer request.

| Pull request | Current state | Next step |
|:--|:--|:--|
| [Qwen Code #9045](https://github.com/QwenLM/qwen-code/pull/9045) | Four review findings addressed; automated re-review is running | Await re-review |
| [LobeHub #18260](https://github.com/lobehub/lobehub/pull/18260) | Updated from `canary`; maintainer edits enabled | Await maintainer-owned CI and review |
| [OpenHands #16576](https://github.com/OpenHands/OpenHands/pull/16576) | Human evidence completed; ready for review | Await maintainer review |
| [LiteLLM #36745](https://github.com/BerriAI/litellm/pull/36745) | Mergeable with required checks passing | Complete CLA signature, then await review |
| [Mastra #21368](https://github.com/mastra-ai/mastra/pull/21368) | Requested changes addressed; no unresolved threads | Await re-review |

## 📐 Engineering Principles

- 🧠 **The model handles ambiguity; deterministic code decides correctness and side effects.**
- 🧾 **Metrics need datasets, scripts, runtime conditions, and commits—not just screenshots.**
- 🔒 **Public demos use synthetic or redacted data and expose no credentials or private systems.**
- 🧪 **Failure recovery, idempotency, policy checks, and evaluation are product behavior.**
- 🧱 **Agent engineering includes APIs, state, data, UI, deployment, and operations—not only model calls.**

## 🛰️ Broader Systems Background

Beyond Agent systems, repositories include C# serial/device communication tools, MATLAB signal-processing and imaging utilities, PDF report generation, and full-stack Web applications. These projects provide the systems, data, debugging, and delivery foundation behind the Agent work.
