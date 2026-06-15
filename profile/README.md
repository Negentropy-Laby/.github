# Negentropy Lab

**Agent Infra / Runtime Architect building trustworthy, commercial-grade AI agents for regulated and complex real-world domains.**

I work on Agent Runtime, Tool System, Memory System, Evaluation, Observability, and LLM Safety - turning LLMs from one-off API calls into auditable, replayable, production-ready, and commercially deployable agent systems.

我专注于 Agent Runtime、Tool System、Memory System、Evaluation / Observability 与 LLM Safety，目标是将大模型从单次 API 调用推进为可运行、可审计、可评测、可复用的行业 Agent 系统。

---

## What I Build

| Layer | What I Build | Outcome |
|---|---|---|
| **Agent Infra / Eval** | Evaluation, Observability, Trace / Audit / Cost, Replay, Benchmark, Cost Governance | Make agents measurable, debuggable, and production-ready |
| **Agent Harness / Runtime** | Runtime Contract, RunState, Tool System, Memory Bank, Workflow Runtime, RuntimePolicyEngine | Make agents controllable, replayable, and auditable |
| **MaaS (Model-as-a-Service) / Industry Systems** | RAG / Agent workflows, Data Products, Benchmarks, Solution Packages | Package agents into deployable, reusable industry systems |

---

## Technical Core: Aby Assistant / Agent Harness

Aby Assistant is my experimental **Agent Harness / Runtime Contract Layer**.

It explores how to make agents stateful, governable, observable, and portable across **CLI**, **Daemon**, and **API / SDK** delivery modes.

**Core components**

- `RunState` - task state and lifecycle
- `ApprovalRequest` - human-in-the-loop approval
- `RuntimeEvent` - structured runtime event stream
- `TraceStore` - replayable execution trace
- `AgentBundle` - portable agent asset package
- `Agent Identity` - verifiable runtime identity
- `RuntimePolicyEngine` - allow / approve / deny governance
- `Trace / Audit / Cost` - observability and cost attribution

---

## Featured Case Study: Trustworthy Mobility Agent System

A case study on turning regulated mobility data into auditable AI agents.

The project explores how to transform multi-source mobility data into high-quality datasets and trustworthy agent workflows for:

- **ODD Expansion Assessment** - where, when, and under what conditions autonomous driving can operate
- **Operational Safety Monitoring** - whether fleets and operators are running safely and compliantly
- **Accident Evidence Chain** - what happened before, during, and after an incident

The system design includes:

- High-quality dataset factory
- Trusted data space, de-identification, and controlled data access
- ODD evaluation agents
- Operational safety monitoring agents
- Accident traceability agents
- Agent tool-call trajectory datasets
- Regulatory reports and data product APIs

该项目以智能驾驶为强监管行业样板，验证如何将一手运行数据、道路交通数据、气象环境数据、自动驾驶日志和监管处置数据，加工为可脱敏、可评测、可 Agent 调用、可监管决策的高质量数据集，并进一步形成行业 Benchmark、风险 API、事故证据包和可信 Agent 工具服务。

---

## Current Focus

- **Agent Runtime / Harness**: Runtime Contract, RunState, Tool System, Agent Identity, Workflow Runtime

- **Agent Evaluation / Observability**: Trace / Audit / Cost, task replay, benchmark, tool-call success rate, cost and latency monitoring

- **Memory & Context Management**: Core + Memory Bank, long-term memory, session context, context routing, memory recall strategy

- **LLM Safety & Governance**: RuntimePolicyEngine, tool approval, de-identification, zero-trust runtime boundary

- **Commercial-grade Industry Agents**: Turning high-value real-world scenarios into auditable workflows, benchmarks, data products, and reusable agent systems

---

## Featured Repositories

| Repository | Focus |
|---|---|
| `agent-runtime-contract` | Runtime Contract, RunState, RuntimeEvent, TraceStore, AgentBundle |
| `aby-assistant-harness` | CLI / Daemon / Workflow Runtime, Tool System, Memory, RuntimePolicyEngine |
| `agent-eval-observability` | Trace, Replay, Benchmark, Task Success, Tool-call Success, Cost |
| `memory-bank-context-runtime` | Core + Memory Bank, Session Context, Memory Routing |
| `runtime-policy-engine` | Tool Approval, De-identification, LLM Safety, Audit |
| `trustworthy-mobility-agent-case-study` | ODD Agent, Operational Safety Agent, Accident Traceability Agent, Data Products |

---

<details>
<summary><strong>Technical Keywords</strong></summary>

### Agent Runtime

RunState, RuntimeEvent, ApprovalRequest, TraceStore, AgentBundle, Agent Identity, Runtime Contract, Session / Conversation Management

### Tool System

MCP, ToolPluginManifest, Function / Tool Calling, Shell / File / Git / API Governance, Tool Approval, Error Replay

### Memory System

Core + Memory Bank, Long-term Memory, Session Context, Context Compression, Retrieval-Augmented Memory, User / Project Profile

### Evaluation / Observability

Trace / Audit / Cost, Benchmark, E2E Testing, Task Replay, Tool-call Success Rate, Task Success Rate, Latency, Cost, Output Quality

### Agent Infra / Platform

Agent Worker, API / SDK, Multi-agent Orchestration, Managed Agent, Runtime Sandbox, Multi-model Routing, Cost Governance

### Workflow / Scheduling

CLI, Daemon, Background Workers, Lease Heartbeat, Pipeline, Parallel, Phase, Failure Recovery, Long-running Task

### Multimodal / Cross-device

RuntimeEvent, Tool Result, GUI Agent, Device Capability Abstraction, Browser Automation, VLM Input, Cross-device Execution

### LLM Safety

Permission Approval, De-identification, Prompt Injection Defense, Path Isolation, Tool Approval, Rate Limiting, Zero-trust Runtime Boundary

### MaaS (Model-as-a-Service) / Solution Layer

RAG, Agent Workflow, Model Selection, Evaluation, Data Products, Industry Benchmark, Solution Package

</details>

---

## Contact

Open to selected conversations and collaborations around:

- Agent Infra / Runtime / Eval
- Tool System / Memory System
- LLM Safety & Governance
- Commercial-grade AI Agents
- Regulated industry AI systems

For collaboration or role discussions, please reach out via GitHub.
