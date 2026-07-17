# Hi, I'm aravelo7

**2027 届 | 后端开发 · 测试开发 · AI 应用工程**

2027 Graduate | Backend Development · Test Development · AI Application Engineering

专注于后端服务、自动化验证和 LLM Workflow 工程，重视系统可靠性、可追踪性与安全编码。

I build backend services, automated validation workflows, and LLM-powered applications, with a focus on reliability, traceability, and secure engineering.

## 代表项目 / Featured Project

### 巡迹 Trace — LLM 驱动的内容审核 Workflow

围绕内容审核场景构建的 LLM Workflow 系统，覆盖后端服务、规则生命周期管理、受控只读工具调用和回归验证。

- 完成鉴权、OAuth 回调、内容导入、审核执行、结果查询和规则管理等后端接口
- 构建 Rule Lab 的规则生成、回放验证、发布与运行配置流程
- 实现单次 LLM Planner 驱动的白名单只读工具调用和 Trace 展示
- Planner 仅生成调查链路，不直接决定最终审核结果
- 在实验分支中完成 SQLite 持久化、Owner 隔离和定向回归验证
- 完成 Docker、Nginx、前端构建和生产部署相关实践

**Tech:** `Node.js` `Express` `React` `TypeScript` `SQLite` `Docker` `Nginx` `LLM API`

## 开源贡献 / Open-source Contribution

### MaxKB

修复聊天记录 HTML 导出流程中的导出型 XSS 风险，通过白名单方式清理 `marked` 输出内容，并限制危险标签、事件属性和不安全 URL Scheme。

Fixed an export-based XSS risk in the chat HTML export workflow by introducing allowlist-based HTML sanitization.

- Merged PR: [1Panel-dev/MaxKB#5280](https://github.com/1Panel-dev/MaxKB/pull/5280)

## 质量工程实践 / Quality Engineering

### ChatGPT / Codex

通过手动输入、直接富文本粘贴、记事本纯文本中转及中英文输入对照，定位并提交了中文 IME 与富文本剪贴板交互异常的可复现缺陷报告。

Reported a reproducible compatibility issue involving rich-text clipboard data and Chinese IME composition.

- Public Issue: [openai/codex#33824](https://github.com/openai/codex/issues/33824)

## 后端实践 / Backend Practice

### Dianping Seckill System

基于 Spring Boot、Redis 和 MySQL 的后端实践项目，覆盖缓存、分布式锁、Lua 脚本、Redis Stream 和高并发业务设计。

A Spring Boot and Redis-based backend practice project covering caching, distributed locking, Lua scripts, Redis Stream, and high-concurrency service design.

- Repository: [dianping-seckill-system](https://github.com/aravelo7/dianping-seckill-system)

## 技术栈 / Technical Stack

**Backend**

`Node.js` `Express` `Java` `Spring Boot` `Redis` `SQLite` `MySQL`

**Frontend**

`React` `TypeScript` `Vite`

**Engineering & Quality**

`Docker` `Nginx` `Git` `Linux` `REST API` `API Testing` `Regression Testing` `Root Cause Analysis`

**Security**

`Secure Coding` `XSS Mitigation`
