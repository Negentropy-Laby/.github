# Negentropy Lab

**Building governed, memory-aware, evidence-backed Agent systems for human-agent collaboration.**

Negentropy Lab explores how AI agents can move beyond one-off prompts and become
long-lived collaborators: governed by project constitutions, coordinated through
workflows, grounded in memory, constrained by policy, and audited through evidence.

我们关注的不是“让 Agent 自由执行更多动作”，而是让 Agent 在真实项目和真实业务中
可协作、可治理、可审计、可回放、可持续演进。

---

## What We Build

| Layer | Project | Core Idea |
|---|---|---|
| **Human-Agent Governance** | [`Constitution-Driven-Development`](https://github.com/Negentropy-Laby/Constitution-Driven-Development) | Turn a Claude Code session into a governed development team with laws, roles, gates, memory, and evidence. |
| **GitHub-Native Collaboration Runtime** | [`OpenSlack`](https://github.com/Negentropy-Laby/OpenSlack) | Let heterogeneous agents discover tasks, claim work, open PRs, request approval, and preserve collaboration memory. |
| **Local-First Business Agent Runtime** | [`OpenDoge`](https://github.com/Negentropy-Laby/OpenDoge) | Run financial research agents locally with market scans, portfolio/risk checks, evidence-backed runs, and slot-based extensions. |

Together, these projects form a practical path toward **human-agent symbiosis**:

```text
Project Constitution
        ↓
Workflow & Agent Roles
        ↓
GitHub-native Task / PR Collaboration
        ↓
Local-first Agent Runtime
        ↓
Evidence, Memory, Approval, Replay
        ↓
Human-guided Self-Evolution
```

---

## Project 1: Constitution-Driven-Development

[`Constitution-Driven-Development`](https://github.com/Negentropy-Laby/Constitution-Driven-Development) is a Claude Code governance template.

It turns a single AI coding session into a governed development team with:

* **53 specialized agents**
* **74 slash-command skills**
* **12 hooks**
* **16 rules**
* **80 templates**
* a T0-T3 `memory_bank/` project brain
* phase gates, review workflows, audit evidence, and release checks

### Design Philosophy

AI coding is powerful, but an unconstrained chat session has no project law,
no architecture memory, no quality gate, and no audit trail.

CDD introduces a project constitution:

```text
T0 Core       → current laws and current state
T1 Axioms     → why the project is designed this way
T2 Execution  → what should happen next
T3 Archive    → what evidence proves it
```

### First Commands

```text
/constitute
/help
/cdd-status
/project-stage-detect
/gate-check
```

CDD is collaborative rather than autonomous: the human owner makes binding
decisions; agents ask questions, draft artifacts, run reviews, and request
approval before important writes or advancement.

---

## Project 2: OpenSlack

[`OpenSlack`](https://github.com/Negentropy-Laby/OpenSlack) is a workflow-first
agent collaboration workbench for GitHub-native human-agent teams.

It lets heterogeneous agents act like governed contributors:

```text
Workflow → Agent Work → PRMS Review → Human Approval → Merge
         → Collaboration Memory → Evidence Projection
```

### What It Does

* discovers tasks from GitHub Issues
* claims work using deterministic git ref locks
* works in isolated worktrees
* submits output through Pull Requests
* runs PR Review & Merge Steward checks
* routes natural-language operator requests through typed actions
* maintains collaboration activity, handoffs, decisions, rooms, and conversations
* preserves projection-ready evidence for external authority or control planes

### Status

OpenSlack is currently a **Developer Preview**. Its GitHub-backed autonomous
task loop has been verified end-to-end. Its planned Negentropy-Lab slot surface
is external, evidence-only, projection-only, and not an authority writer.

---

## Project 3: OpenDoge

[`OpenDoge`](https://github.com/Negentropy-Laby/OpenDoge) is a local-first,
slot-based financial research agent runtime.

It combines:

* market scans
* research memos
* portfolio and risk checks
* evidence-backed agent runs
* local CLI / daemon / Web / SDK / MCP surfaces
* slot-based tools, models, data sources, workflows, UI panels, watchers, eval
  suites, and governance policies

### Runtime Shape

OpenDoge has three runtime levels:

```text
Level 1: Embedded CLI / local session
Level 2: Daemon gateway
Level 3: SDK / platform
```

The canonical runtime path is:

```text
doge.bootstrap.processes
  → persisted runtime
  → /v1 routes
  → SDK / Web / CLI clients
```

### Product Modules

OpenDoge is organized around four product modules:

| Module        | Focus                                |
| ------------- | ------------------------------------ |
| **Market**    | market intelligence and scans        |
| **Portfolio** | portfolio and risk context           |
| **Quant**     | data lab and quantitative workflows  |
| **Research**  | research memos, evidence, and claims |

### Maturity

OpenDoge is **Local Alpha** and **not production ready**. It is
production-shaped — with `/v1`, RuntimeKernel, SDKs, Web workspace, and slot
surfaces — but it does not claim Stable, GA, or Production Ready status.

---

## Architecture Thesis

Negentropy Lab projects share a common architecture direction:

### 1. Constitution before autonomy

Agents need laws, roles, gates, and evidence before they can be trusted with
long-running work.

### 2. Collaboration before full automation

Human approval, PR review, handoff, and decision records are first-class
workflow objects.

### 3. Runtime contracts before product scale

Sessions, runs, events, artifacts, approvals, traces, costs, and evidence should
be structured and replayable.

### 4. Memory is not chat history

Project memory should be layered, tagged, queryable, reviewed, and distilled
into reusable knowledge, workflows, and skills.

### 5. Slots over monoliths

Tools, models, data sources, workflows, documents, UI panels, watchers, evals,
and policies should become governed extension facets rather than hard-coded
application logic.

---

## Human-Agent Symbiosis

The long-term vision is not to replace human builders.

It is to build systems where:

* humans define goals, values, constraints, and final decisions;
* agents explore, draft, test, review, and execute bounded work;
* memory preserves what the team learns;
* evidence explains why decisions were made;
* approvals separate suggestions from irreversible actions;
* runtime contracts make work replayable and accountable;
* every project becomes a learning system.

```text
Human judgment
    + Agent execution
    + Project memory
    + Runtime governance
    + Evidence replay
    = Human-Agent Symbiosis
```

---

## Current Focus

* Agent Runtime & Workflow Governance
* Claude Code / Codex / GitHub-native collaboration
* Local-first Agent systems
* Runtime contracts, approvals, traces, and evidence
* Memory Bank and project governance
* Slot-based extension systems
* Eval, replay, and human-in-the-loop review

---

## Current Boundaries

These repositories are active research and engineering projects.

* `Constitution-Driven-Development` has a v0.1.0 stable template release and
  customer delivery baseline.
* `OpenSlack` is a Developer Preview. Its GitHub-native collaboration loop is
  verified E2E; its Negentropy-Lab slot contribution is planned,
  projection-only, and not an authority writer.
* `OpenDoge` is Local Alpha and explicitly not production ready. It is
  production-shaped, but Stable, GA, and Production Ready claims are forbidden
  while `production_ready: false` and `stable_declaration: forbidden` remain
  true.

Use them as reference implementations, architecture experiments, and workflow
templates for governed human-agent systems.
