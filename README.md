# Launch Intelligence

A learning system for product marketing launches.

> **Plan the launch → execute distribution → measure outcomes → learn → make the next launch smarter.**

## Repo layout

- `agents/` — permanent Agent 1/2/3 operating instructions
- `shared/schemas/` — canonical data contracts
- `shared/global-memory/` — cross-company priors (initially empty)
- `companies/<company>/context/` — stable company context
- `companies/<company>/memory/company-learnings.json` — approved company-level memory
- `companies/<company>/memory/launch-history/` — complete launch records
- `app/` — Replit/frontend/orchestration implementation
- `tests/` — regression audits

## Current example

`companies/signoz/memory/launch-history/launch-001-observability-ai-era/` is the first canonical SigNoz launch record. It contains approved strategy, draft Agent 2 test assets, the verifier result, tracking schema, placeholders for actual outcomes, and launch-level learning candidates.

## Important rules

- Never invent missing metrics, URLs, baselines, capabilities, or customer proof.
- Company-specific confidential data never enters global memory.
- Agent 3 does not directly promote memory.
- Human gates remain between strategy, execution, and publication in the MVP.
- Regression audits are mandatory whenever agent/system requirements change.
