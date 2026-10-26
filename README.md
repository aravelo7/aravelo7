# 姚淑慧 / aravelo7

**Software Engineering · AI Agents · Open Source**

Information Security undergraduate at **Hainan University**.  
Incoming Master's student at **Xidian University (2027)**.

I work primarily with **Java / Spring AI, Coding Agent runtimes, LLM evaluation, and developer tooling**, building reliable AI systems and software engineering infrastructure.

## Featured Projects

### [AgentPatchCheck](https://github.com/aravelo7/AgentPatchCheck)

**Coding Agent Runtime & Evaluation Harness**

A runtime and evaluation harness for repository-level Coding Agents, combining **controlled execution, tool use, independent verification, and trace-based evaluation**.

- Bounded Agent Runtime with isolated Git workspaces, constrained tools, execution budgets, and structured traces.
- Separates agent execution from correctness evaluation through independent verification and evaluator-backed assessment.
- Includes a read-only console for inspecting runs, patches, verification results, and benchmark outcomes.

**Benchmark:** **35/50 officially resolved (70.0%)**, **50/50 valid executions**, with zero harness-invalid or grading-invalid runs on the frozen HAL SWE-bench Verified Mini fixed-50 set.

[Research note: Runtime termination is not a correctness proxy →](https://github.com/aravelo7/AgentPatchCheck/blob/main/docs/research/runtime-termination-correctness-proxy.md)

### [MinDisclosure](https://github.com/aravelo7/MinDisclosure)

**Task- and Tool-Aware Minimum Disclosure for LLM Agents**

A research seed exploring how LLM agents can reduce sensitive-data exposure while preserving downstream task utility.

The project provides a frozen deterministic benchmark and an offline-validated LLM evaluation protocol for studying minimum-disclosure representations across Agent and Tool boundaries.

## Open Source Contributions

Selected contributions merged upstream:

- **LangChain4j**
  - [#6497](https://github.com/langchain4j/langchain4j/pull/6497) — Preserve dotted parameter names in MCP headers.
  - [#6116](https://github.com/langchain4j/langchain4j/pull/6116) — Fix failed agent execution finalization with asynchronous sibling completion.

- **Spring AI Alibaba**
  - [#4911](https://github.com/alibaba/spring-ai-alibaba/pull/4911) — Restore lifecycle error notifications for streaming nodes.
  - [#4925](https://github.com/alibaba/spring-ai-alibaba/pull/4925) — Preserve failing node attribution in streaming error callbacks.

- **MaxKB**
  - [#5280](https://github.com/1Panel-dev/MaxKB/pull/5280) — Mitigate XSS risks in exported chat HTML.
