<div align="center">

<img src="./assets/profile-header.gif" alt="Animated profile banner for Yunus Arda Güney: AI agents, backend systems, and engineering" width="100%" />

</div>

# Yunus Arda Güney

<p align="left">
  <strong>Electrical & Electronics Engineering student at İzmir Kâtip Çelebi University.</strong><br/>
  I build <strong>autonomous AI agents</strong>, <strong>verifiable execution runtimes</strong>, <strong>local-first assistants</strong>, <strong>embedded systems & edge computing</strong>, and <strong>data-driven backend systems</strong>.
</p>

<p align="left">
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript" />
  <img src="https://img.shields.io/badge/C-A8B9CC?style=flat-square&logo=c&logoColor=white" alt="C" />
  <img src="https://img.shields.io/badge/MCP-Model_Context_Protocol-6C5CE7?style=flat-square" alt="MCP" />
  <img src="https://img.shields.io/badge/Qdrant-Vector_DB-DC2626?style=flat-square&logo=qdrant&logoColor=white" alt="Qdrant" />
  <img src="https://img.shields.io/badge/Ollama-Local_LLMs-000000?style=flat-square&logo=ollama&logoColor=white" alt="Ollama" />
  <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" alt="FastAPI" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" alt="Docker" />
  <br/>
  <img src="https://img.shields.io/badge/Raspberry%20Pi-C51A4A?style=flat-square&logo=raspberrypi&logoColor=white" alt="Raspberry Pi" />
  <img src="https://img.shields.io/badge/ESP32-E7352C?style=flat-square&logo=espressif&logoColor=white" alt="ESP32" />
  <img src="https://img.shields.io/badge/STM32-03234B?style=flat-square&logo=stmicroelectronics&logoColor=white" alt="STM32" />
  <img src="https://img.shields.io/badge/Arduino-00979D?style=flat-square&logo=arduino&logoColor=white" alt="Arduino" />
  <img src="https://img.shields.io/badge/macOS%20%7C%20Linux-000000?style=flat-square&logo=apple&logoColor=white" alt="macOS and Linux" />
</p>

---

## ⚡ Featured Open-Source Projects

### 🎙️ [ARDA Suite](https://github.com/yunusarda-sudo/arda-suite)
> **Local-first assistant infrastructure, verifiable bounded agent execution, and persistent shared memory.**

- **Jarvis Desktop:** macOS menu bar voice assistant with instant push-to-talk (`⌘⇧A`), floating Wispr Flow-style dictation (`⌘⇧D`), and headless Linux/Raspberry Pi background daemon.
- **Verifiable Bounded Execution:** Deterministic `AUTO / CONFIRM / DENY` tool permission gates, step verification, and tamper-evident audit logs.
- **Shared Memory Service:** Standalone long-term vector memory daemon powered by [mem0](https://github.com/mem0ai/mem0) and [Qdrant](https://qdrant.tech/) with standardized Model Context Protocol (MCP) HTTP endpoint.

[📂 Repository](https://github.com/yunusarda-sudo/arda-suite) · [📐 Architecture](https://github.com/yunusarda-sudo/arda-suite#architecture--components) · [📑 Specifications](https://github.com/yunusarda-sudo/arda-suite/tree/main/apps/jarvis/docs/specs)

---

### 🔍 [Pickable](https://github.com/yunusarda-sudo/pickable)
> **Multi-source website analysis engine combining AI agent-readiness and marketing signals.**

- High-throughput scraper and analyzer resilient against protected URL barriers and provider rate limits.
- Concurrent multi-provider checks, SQLite persistence, and structured REST / MCP interfaces for agent workflows.

[📂 Repository](https://github.com/yunusarda-sudo/pickable) · [⚙️ Orchestrator](https://github.com/yunusarda-sudo/pickable/blob/main/app/orchestrator.py) · [🧪 Tests](https://github.com/yunusarda-sudo/pickable/tree/main/tests)

---

## 🌐 Open-Source Contributions & AI Agent Ecosystem Impact

Active contributor to premier autonomous AI agents, Model Context Protocol (MCP), and web agent runtimes:

| Ecosystem / Project | Pull Request | Contribution Focus & Highlights |
| :--- | :--- | :--- |
| **[modelcontextprotocol/inspector](https://github.com/modelcontextprotocol/inspector)** | [#2719](https://github.com/modelcontextprotocol/inspector/issues/2719) / [`1e45133e`](https://github.com/yunusarda-sudo/inspector/commit/1e45133e3b09d60223838f06bf38405a2e3ab114) | Isolated CLI test suites from developer's real `~/.mcp-inspector` OAuth state with temp dirs and runtime guards (Official Anthropic MCP repo). TypeScript, Vitest, 614 tests. |
| **[coderamp-labs/gitingest](https://github.com/coderamp-labs/gitingest)** | [#611](https://github.com/coderamp-labs/gitingest/pull/611) | Preserved notebook cells on image-only `display_data` outputs lacking `text/plain` and supported string outputs (Fixes #608). Python, Pytest. |
| **[All-Hands-AI/OpenHands](https://github.com/All-Hands-AI/OpenHands)** | [#18609](https://github.com/All-Hands-AI/OpenHands/pull/18609) | Prioritized draft validation errors over historical test runs in Agent Canvas (Fixes #18601). TypeScript, React, Vitest. |
| **[PrefectHQ/fastmcp](https://github.com/PrefectHQ/fastmcp)** | [#5795](https://github.com/PrefectHQ/fastmcp/pull/5795) | Propagated public metadata in built-in file, directory, and HTTP resources (Fixes #5777). Python, `prek`, 371 tests. |
| **[browser-use/browser-use](https://github.com/browser-use/browser-use)** | [#6126](https://github.com/browser-use/browser-use/pull/6126) | Filtered non-positive and out-of-bounds coordinates in DOM paint order for vision web agents (Fixes #5987). Python, Cubic AI approved. |
| **[Muvon/octomind](https://github.com/Muvon/octomind)** | [#177](https://github.com/Muvon/octomind/pull/177) | Implemented `serde_ignored` unknown key diagnostics and TOML scalar-after-table trap detection in validate mode (Fixes #165). Rust. |
| **[coderamp-labs/gitingest](https://github.com/coderamp-labs/gitingest)** | [#610](https://github.com/coderamp-labs/gitingest/pull/610) | Enforced `max_file_size` limits on single-file ingestion with diagnostic `ValueError` exceptions (Fixes #609). Python, Pytest. |
| **[XAGI-Lab/melra](https://github.com/XAGI-Lab/melra)** | [#235](https://github.com/XAGI-Lab/melra/pull/235) | Resolved popup adoption race conditions during `tab_new` via `WeakSet` and async event queues (Fixes #233). TypeScript, DCO signoff. |
| **[kitsuno-ai/agentic-job-search-eu](https://github.com/kitsuno-ai/agentic-job-search-eu)** | [#3](https://github.com/kitsuno-ai/agentic-job-search-eu/pull/3) | Implemented Kaplan-Meier delayed entry (left-truncation) survival analysis and minimal Git diff object serialization. Python. |
| **[cremind-ai/cremind](https://github.com/cremind-ai/cremind)** | [#178](https://github.com/cremind-ai/cremind/pull/178) | Built deterministic unit test harness for MCP stdio and HTTP connection transports and auth lifecycle. Python, Pytest. |
| **[taskade/mcp](https://github.com/taskade/mcp)** | [#103](https://github.com/taskade/mcp/pull/103) | Built reproducible unit test suite for OpenAPI schema codegen, parameter unification, and Zod constraint compilation. TypeScript, Vitest. |
| **[radioso-ai/radioso](https://github.com/radioso-ai/radioso)** | [#1559](https://github.com/radioso-ai/radioso/pull/1559) | Hardened worker failure telemetry to omit reports for expected permanent job errors. Python. |
| **[Human-Agent-Society/CORAL](https://github.com/Human-Agent-Society/CORAL)** | [#282](https://github.com/Human-Agent-Society/CORAL/pull/282) | Hardened gateway configuration override security for multi-agent social simulations. Python. |

---

## 🚀 Products & Ventures

- 📅 [**Randevuo**](https://randevuo.com.tr/) — Autonomous WhatsApp-based AI appointment booking agents for service businesses.
- 💼 [**Solveny**](https://solveny.tech/) ([solveny.dev](https://solveny.dev)) — Custom AI agent implementations and enterprise workflow automation.
- ⚡ [**MODÜ-GRID**](https://modu-grid.com/) — IoT & AI-driven energy consumption optimization for commercial facilities.
- 🎓 **OPVIA** — Student opportunity, internship & competition discovery platform.

---

## 📬 Connect

- 🌐 **Website:** [solveny.dev](https://solveny.dev)
- 💻 **GitHub:** [@yunusarda-sudo](https://github.com/yunusarda-sudo)
- 📍 **Location:** Izmir, Türkiye
