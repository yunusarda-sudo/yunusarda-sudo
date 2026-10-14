# Yunus Arda Güney

**I build AI systems that do more than generate responses: they execute tasks, interact with tools, persist state, and handle failure.**

I build local-first AI agents and backend systems, with a focus on bounded execution, tool permissions, persistent state, and failure recovery. I am an Electrical and Electronics Engineering student who learns by designing, shipping, and testing real systems.

I aim to make important engineering decisions inspectable in code, and to distinguish tested behavior from experimental work.

## Selected work

### [ARDA Suite](https://github.com/yunusarda-sudo/arda-suite) — Local-first assistant infrastructure

Jarvis, experimental ARDA Core/Hermes runtime modules, and an optional Shared Memory service in one repository, with separate environments and deployment lifecycles.

- Permission-aware tool execution with **AUTO / CONFIRM / DENY** paths, per-step verification, and audit logs.
- Experimental task coordination and provider integration, with maturity limits stated in the README.
- Optional shared memory through authenticated MCP transport and Qdrant-backed storage.

**Inspect the implementation:** [permission policy](https://github.com/yunusarda-sudo/arda-suite/blob/main/apps/jarvis/arda/agent_permission.py) · [execution bridge](https://github.com/yunusarda-sudo/arda-suite/blob/main/apps/jarvis/arda/execution_bridge.py) · [MCP transport](https://github.com/yunusarda-sudo/arda-suite/blob/main/services/memory/mcp_transport.py) · [architecture and limits](https://github.com/yunusarda-sudo/arda-suite/blob/main/README.md).

**Status:** ARDA/Hermes remain experimental. The focused memory-installer CI check passes; the full combined test suites and live Raspberry Pi behavior are not yet validated.

### [Pickable](https://github.com/yunusarda-sudo/pickable) — Evidence-oriented website analysis

A Python backend that combines independent readiness and marketing signals, normalizes findings, and preserves uncertainty when a source is unavailable.

- Public-URL fetching with SSRF checks, DNS/IP pinning, and redirect handling.
- Independent adapters with fault isolation, bounded retries, and source-specific status.
- SQLite persistence, startup interruption handling, REST, and optional MCP interfaces.

**Inspect the implementation:** [safe fetch](https://github.com/yunusarda-sudo/pickable/blob/main/app/safe_fetch.py) · [orchestrator](https://github.com/yunusarda-sudo/pickable/blob/main/app/orchestrator.py) · [storage](https://github.com/yunusarda-sudo/pickable/blob/main/app/storage.py) · [tests](https://github.com/yunusarda-sudo/pickable/tree/main/tests).

## How I approach engineering

| Question | What I look for |
| --- | --- |
| Can a system cause side effects? | Explicit permissions, trust boundaries, observable actions, and safe failure paths. |
| Does it recover from interruptions? | Durable state, clear lifecycle transitions, restart behavior, and idempotency. |
| Is the result reliable? | Reproducible tests, source-level evidence, and honest unknown states. |
| Is a feature complete? | A demonstrated end-to-end workflow, not only a specification or passing unit tests. |

## Currently exploring

Agent evaluation, constrained tool use, provider reliability, memory boundaries, and practical edge-device operation. My public repositories include work in progress; known limitations and unverified integrations are documented rather than omitted.

---

**Start here:** [ARDA Suite](https://github.com/yunusarda-sudo/arda-suite) for agent infrastructure · [Pickable](https://github.com/yunusarda-sudo/pickable) for backend reliability and safe external data retrieval.
