# Launch Intelligence System

## Core loop

**Agent 1 — Planner → human approval → Agent 2 — Operator + Verifier → human/publish → Agent 3 — Learner → memory proposal → memory promotion layer → next launch.**

Agents communicate through structured launch state and files, not free-form agent-to-agent chat.

## Memory scopes

1. **Launch memory** — facts, outcomes, observations from one launch.
2. **Company memory** — repeated patterns across comparable launches for one company.
3. **Global memory** — cross-company patterns; weak prior only.

### Precedence
For planning: current PRD / explicit company truth > company context > approved company memory > relevant launch history > global memory.

For execution: approved Agent 1 strategy > approved execution inputs > company execution memory > relevant launch examples > global memory.

## Learning confidence

- 1 comparable launch = Observation
- 2–3 similar comparable launches = Hypothesis
- 4+ consistent comparable launches = Emerging Learning

Agent 3 proposes memory writes; the orchestrator/memory layer decides promotion.

## Canonical state
Each launch has a `launch.json` spine plus human-readable markdown and machine-readable JSON outputs.
