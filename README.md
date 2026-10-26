# 姚淑慧 / aravelo7

**Software Engineering · AI Agents · Open Source**

Information Security undergraduate at Hainan University.

I build AI-powered developer tools, backend systems, and evaluation infrastructure, with a focus on **Coding Agents, reliable LLM applications, controlled execution, and software verification**.

## Featured Projects

### [AgentPatchCheck](https://github.com/aravelo7/AgentPatchCheck)

**Coding Agent Runtime & Evaluation Harness**

An open-source platform for controlled, repository-level software repair and independent evaluation.

- **Agent Runtime:** Bounded agent execution with multi-turn tool calling, state management, execution budgets, timeout handling, and cancellation.
- **Execution & Verification:** Git worktree isolation, constrained repository tools, independent verification, structured execution traces, and evaluation artifacts.
- **Evaluation Console:** A read-only interface for exploring agent runs, patches, verification results, and benchmark outcomes.

**Benchmark:** Achieved **35/50 officially resolved (70.0%)** with **50/50 valid executions** and zero harness-invalid or grading-invalid runs on the frozen HAL SWE-bench Verified Mini fixed-50 set.

*Evaluated using deepseek-v4-flash + AgentPatchCheck Runtime/tooling + frozen execution policy. This is not a full SWE-bench Verified score or a model-only result.*

### [MinDisclosure](https://github.com/aravelo7/MinDisclosure)

**Task- and Tool-Aware Minimum Disclosure for LLM Agents**

A research-oriented benchmark exploring how LLM agents can minimize sensitive-data exposure while preserving task utility.

- Studies task-aware disclosure representations at Agent and Tool boundaries.
- Compares raw disclosure, stable tokenization, and oracle minimum-disclosure strategies.
- Provides a frozen deterministic benchmark and an offline-validated LLM experiment protocol; live-model evaluation results are not yet available.

### [Codex Agent Skills](https://github.com/aravelo7/codex-agent-skills)

**Reusable Skills for AI-Assisted Software Engineering**

A collection of reusable Codex skills for practical software engineering workflows, emphasizing root-cause analysis, minimal changes, explicit error handling, and avoiding unnecessary abstractions.

## Research & Evaluation

### [When Runtime Termination Is Not a Correctness Proxy](https://github.com/aravelo7/AgentPatchCheck/blob/main/docs/research/runtime-termination-correctness-proxy.md)

An empirical analysis based on AgentPatchCheck's frozen benchmark runs.

- Investigated the relationship between agent termination states and independently evaluated software-repair correctness.
- Found **12/45 disagreements (26.7%)** between a mechanical termination-based classification and official evaluator outcomes.
- Highlighted the importance of separating runtime completion signals from correctness evaluation.

## Open Source Contributions

Selected contributions merged into upstream main branches:

- **LangChain4j**
  - [#6497](https://github.com/langchain4j/langchain4j/pull/6497) — Preserve dotted parameter names in MCP headers.
  - [#6116](https://github.com/langchain4j/langchain4j/pull/6116) — Fix failed agent execution finalization with asynchronous sibling completion.

- **Agentic Spring AI**
  - [#1](https://github.com/agentic-ai-java/argi-extensions/pull/1) — Fix Redis checkpoint retention behavior.

- **Spring AI Alibaba**
  - [#4911](https://github.com/alibaba/spring-ai-alibaba/pull/4911) — Restore lifecycle error notifications for streaming nodes.
  - [#4925](https://github.com/alibaba/spring-ai-alibaba/pull/4925) — Preserve failing node attribution in streaming error callbacks.

- **MaxKB**
  - [#5280](https://github.com/1Panel-dev/MaxKB/pull/5280) — Mitigate XSS risks in exported chat HTML.

## Tech Stack

**Backend:** Java · Spring Boot · Spring AI · Node.js · Python

**AI / Agent:** Agent Runtime · Tool Calling · MCP · RAG · Text2SQL · Agent Evaluation

**Databases & Infrastructure:** MySQL · PostgreSQL · Redis · Docker · Git

**Frontend & Tooling:** TypeScript · React · Vite

---

*Interested in building reliable AI systems, developer tools, and open-source software.*
