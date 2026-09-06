# 姚淑慧 / aravelo7

**AI Agent · Backend Engineering**

I build AI agent systems, backend services, and evaluation infrastructure, with a focus on controlled execution, tool calling, verification, and reliable LLM application engineering.

## Featured Project

### [AgentPatchCheck](https://github.com/aravelo7/AgentPatchCheck)

**Coding Agent Runtime & Evaluation Harness** for controlled, repository-level software repair.

- Built a bounded Agent Runtime with multi-turn tool calling, state management, execution budgets, timeout/cancellation, and typed termination.
- Added isolated Git workspaces, constrained repository tools, independent verification, execution traces, and evaluation artifacts.
- Evaluated a frozen HAL SWE-bench Verified Mini fixed-50 configuration with the official evaluator: **35/50 officially resolved**, **50/50 valid executions**, with zero Harness-invalid or grading-invalid runs.
- Built a local read-only Runtime & Evaluation Console for inspecting real execution traces, verification results, artifacts, and benchmark analysis.

[View AgentPatchCheck →](https://github.com/aravelo7/AgentPatchCheck)

## Research Note

### [Auditing Runtime Termination as a Correctness Proxy for Coding Agents](https://github.com/aravelo7/AgentPatchCheck/blob/main/docs/research/runtime-termination-correctness-proxy.md)

An artifact-grounded analysis of runtime termination and independent correctness under one frozen coding-agent configuration.

The mechanical proxy `finished → resolved / non-finished → unresolved` misclassified **12/45 graded runs (26.7%)**, showing that runtime termination status should not be treated as a correctness verdict.

## Open Source Contributions

- **LangChain4j** — [#6116: fix(agentic): finalize failed executions after async sibling completion](https://github.com/langchain4j/langchain4j/pull/6116)
- **Spring AI Alibaba** — [#4911: fix(graph): notify lifecycle listener on streaming errors](https://github.com/alibaba/spring-ai-alibaba/pull/4911)
- **Spring AI Alibaba** — [#4925: fix(graph): preserve streaming node id in error callbacks](https://github.com/alibaba/spring-ai-alibaba/pull/4925)
- **MaxKB** — [#5280: fix: sanitize exported chat HTML content](https://github.com/1Panel-dev/MaxKB/pull/5280)

## Tech

**Backend:** Java · Spring Boot · Spring AI · Node.js

**AI / Agent:** Agent Runtime · Tool Calling · Agent Evaluation · RAG · MCP · Text2SQL

**Data & Infrastructure:** MySQL · PostgreSQL · Redis · Docker · Git

**Frontend / Tooling:** TypeScript · React · Vite
