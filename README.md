# 姚淑慧 / aravelo7

**AI Agent · Software Systems · Backend Engineering**

🎓 **2027 Graduate Applicant — Open to graduate research opportunities**

Information Security undergraduate at Hainan University.

Research interests: **AI Agents · Coding Agents · LLM Systems · Intelligent Software Engineering · Agent Security**

> Currently looking for potential graduate advisors and research opportunities for Fall 2027.\
> 目前正在联系 2027 级推免导师，欢迎 AI Agent、软件系统、智能软件工程及相关交叉方向的老师交流。

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

### [Auditing Runtime Termination as a Resolution Proxy: A Frozen Coding-Agent Case Study](https://github.com/aravelo7/AgentPatchCheck/blob/main/docs/research/runtime-termination-correctness-proxy.md)

A follow-up empirical audit derived from APC's frozen fixed-50 runs, examining whether typed runtime termination can substitute for evaluator-derived resolution.

The mechanical proxy `finished → resolved / non-finished → unresolved` disagreed with the official evaluator on **12/45 binary-outcome runs (≈26.7%)**, with errors in both directions. The analysis supports separating runtime telemetry from evaluator verdicts while retaining termination reasons as diagnostic signals.

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
