# Hi, I'm aravelo7

**2027 Graduate | Backend Development · Test Development · AI Application Engineering**

I build backend services, automated validation workflows, and LLM-powered applications, with a focus on reliability, traceability, and secure engineering.

## Featured Project

### 巡迹 Trace — LLM-driven Content Review Workflow

An LLM-driven content review workflow focused on backend service design, rule lifecycle management, controlled read-only tool calling, and regression-oriented validation.

- Built authentication and review services covering OAuth callbacks, content import, review execution, result retrieval, and rule management
- Designed the Rule Lab workflow from sample selection and rule generation to replay validation and publishing
- Implemented a single-call LLM Planner with allowlisted read-only tools and trace visualization; the planner does not determine the final moderation result
- Added SQLite persistence, owner isolation, and targeted regression tests in an experimental branch
- Deployed backend services with Docker and served the frontend through Nginx, with release validation and rollback checks

**Tech:** Node.js · Express · React · TypeScript · SQLite · Docker · Nginx · LLM APIs

## Open-source Contribution

### MaxKB

Fixed an export-based XSS risk in the chat HTML export workflow by introducing allowlist-based HTML sanitization.

- Merged upstream PR: [1Panel-dev/MaxKB#5280](https://github.com/1Panel-dev/MaxKB/pull/5280)

## Quality Engineering

### ChatGPT / Codex

Reported a reproducible compatibility issue involving rich-text clipboard data and Chinese IME composition, supported by minimal reproduction steps and control tests.

- Public issue: [openai/codex#33824](https://github.com/openai/codex/issues/33824)

## Backend Practice

### Dianping Seckill System

A Spring Boot and Redis-based backend practice project covering caching, distributed locking, Lua scripts, Redis Stream, and high-concurrency service design.

- Repository: [dianping-seckill-system](https://github.com/aravelo7/dianping-seckill-system)

## Technical Stack

**Backend:** `Node.js` `Express` `Java` `Spring Boot` `Redis` `SQLite` `MySQL`

**Frontend:** `React` `TypeScript` `Vite`

**Engineering & Quality:** `Docker` `Nginx` `Git` `Linux` `API Testing` `Regression Testing` `Root Cause Analysis`

**Security:** `Secure Coding` `XSS Mitigation`
