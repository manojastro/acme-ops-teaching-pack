# Acme Ops: learn-by-building teaching pack

The shared prompt pack behind the seven "mock-first AI operations" projects (all built around a fictional
company, Acme Retail Ltd, with synthetic data). It turns an AI coding agent (OpenCode) into a teacher that builds
each project in milestones while making sure the learner understands every part.

## Files

| File | Purpose |
|---|---|
| `00-START-HERE.md` | How to use the pack |
| `AGENTS.md` | "Learn-by-Building Mode": the agent's teaching rules, the PLAN, BUILD, LEARNER TASK, TEST loop, and a 3-level hint ladder. It encodes the learner profile (IT service-desk background, new to Python AI engineering) |
| `P0-ticketsort.md` | L1 ticket-triage API |
| `P1-opscopilot.md` | Citation-grounded RAG over KEDB/SOPs |
| `P2-agentjudge.md` | Eval harness and CI quality gate |
| `P3-mcp-ops-bridge.md` | Mock ITSM plus MCP server |
| `P4-incident-commander.md` | LangGraph incident agent with human approval |
| `P5-ai-gateway.md` | AI gateway (keys, budgets, routing, guardrails) |
| `P6-changeguard.md` | Change-risk investigator and CAB release gate |
| `opencode-prompts/.opencode/commands/` | OpenCode slash commands: `/breakit`, `/checkpoint`, `/explain`, `/interview`, `/quiz`, `/recap` |
| `opencode-prompts.zip` | The same pack as a zip |

## Use

Copy `AGENTS.md` and the `.opencode/` folder into the root of a project repo, then give OpenCode the matching `P*.md` prompt.

The finished projects: [ticketsort](https://github.com/manojastro/ticketsort), [opscopilot](https://github.com/manojastro/opscopilot),
[agentjudge](https://github.com/manojastro/agentjudge), [mcp-ops-bridge](https://github.com/manojastro/mcp-ops-bridge),
[incident-commander](https://github.com/manojastro/incident-commander), [acme-ai-gateway](https://github.com/manojastro/acme-ai-gateway),
[changeguard](https://github.com/manojastro/changeguard).
