# Hola, I'm Noel 👋

**AI Systems Builder · Agent Engineering · Business Automation**
Founder of [Signal Systems](https://signalsystems.es) · Alicante, Spain

I build AI-assisted software and agent systems for real work: agents that use tools, follow explicit workflows, preserve context, and leave evidence of what they did.

My background in factory and warehouse operations shapes how I approach software: clear responsibilities, controlled changes, useful checks, and a way to recover when something fails.

I'm building in public while deepening my software engineering skills. I use Claude Code, Codex and other AI tools to help implement my ideas; my focus is on problem definition, system design, orchestration, testing and iteration.

## What I'm building

A connected set of **agent-system building blocks**. They are separate projects today, at different stages of maturity—not a single turnkey platform yet.

```text
               Context & memory
                     │
 Business process → Agent + workflow → MCP tools → Business data
                     │                  │
                     ├── Evaluation & approvals
                     └── Local observability
```

### Featured projects

| Project                                                                                      | What it explores                                                                                                                                                                  |
| -------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [Motor Agéntico · Observability](https://github.com/noelaliaga/motor-agentico-observability) | Local, read-only dashboard for AI coding-agent activity, costs, installed vs. used capabilities, memory and nightly findings. Synthetic demo; not intended for remote deployment. |
| [Multiverso · Context Engine](https://github.com/noelaliaga/multiverso-context-engine)       | Persistent project context and a navigable filesystem graph so new agent sessions can resume with relevant information.                                                           |
| [MCP Logística](https://github.com/noelaliaga/mcp-logistica)                                 | Warehouse MCP server for orders and stock with constrained writes, clarification rules and database audit trails.                                                                 |
| [WMS Agent Evals](https://github.com/noelaliaga/wms-agent-evals)                             | Evaluates tool calls, ambiguity handling, grounded answers, database effects, cost and latency. Published runs are **offline/synthetic**, not live-model benchmarks.              |
| [ADK WMS Assistant](https://github.com/noelaliaga/adk-wms-assistant)                         | Google ADK assistant using the WMS MCP tools, with separate read/write paths, human approval and structured telemetry. Tested offline; not deployed.                              |
| [Agent CRM MCP](https://github.com/noelaliaga/agent-crm-mcp)                                 | Restricted CRM tools, Postgres-level permissions and audit logging, plus health checks informed by a documented silent-outage incident.                                           |
| [Content Engine Multiagent](https://github.com/noelaliaga/content-engine-multiagent)         | Five-stage content workflow with JSON Schema contracts, cross-step validation, QA gates and an offline demo using a fictional client.                                             |

## What I'm working on now

* **Agent harness:** task ownership, independent review, durable handoffs, recovery, permissions and evaluations. The main working environment is private and evolving; the public repos above document individual components and experiments.
* **Motor Agéntico redesign:** making agent roles, skills, workflows, memory, evidence and costs easier to inspect. New control surfaces are a design goal, not a capability of the current read-only public dashboard.
* **Reproducible business workflows:** exploring how to adapt agent systems to a company's processes without treating a demo as proof of production readiness.

## How I work

* **Ask before assuming.** Ambiguous requests should lead to clarification, not a confident write to the wrong record.
* **Bound what tools can do.** Permissions and database constraints matter more than a prompt saying “be careful.”
* **Review independently.** Separate implementation from review; verify a fixed commit and the original requirements.
* **Measure behavior, not just answers.** Record tool calls, state changes, failures and limitations; use negative controls in tests.
* **Document the real status.** Distinguish synthetic demos, offline tests, live usage and production deployment.

## More things I've built

* [Biblioteca de guías de IA](https://github.com/noelaliaga/guias-ia) · [Read the guides in Spanish](https://guias-ia.vercel.app) — practical lessons from building software with AI, including Git, reviews, security and deployment.
* [html-to-slides](https://github.com/noelaliaga/html-to-slides) — exports HTML carousels as Instagram-ready PNGs.

**Tools I work with:** TypeScript / JavaScript · Python · SQL / PostgreSQL · Next.js · Supabase · MCP · Claude Code · Codex · GitHub Actions · Playwright

## Let's connect

I'm interested in AI systems, applied agent engineering, business-process automation and opportunities to build useful software with strong operational safeguards.

[LinkedIn](https://www.linkedin.com/in/noelaliaga) · [Signal Systems](https://signalsystems.es) · [GitHub projects](https://github.com/noelaliaga?tab=repositories)
