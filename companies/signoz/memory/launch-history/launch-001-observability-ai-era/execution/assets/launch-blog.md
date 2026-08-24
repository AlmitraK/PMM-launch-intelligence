# Launch Blog

# Building observability for the AI era: agent-native and AI-scale

AI is reshaping observability in two directions at once.

The first is easy to see in development workflows. Engineers are increasingly working through coding and operational agents. An agent can write code, refactor a service, or help investigate a failure — but the production context it needs often still lives behind a separate observability workflow.

The second shift comes from the software being observed. LLM and agent workloads introduce model calls, tool use, databases, token streaming, and new attributes into the application path. That creates larger, more complex traces and more telemetry overall.

SigNoz is evolving for both shifts.

We’re bringing four shipped capabilities together under one product direction: **observability for the AI era — agent-native and AI-scale.**

## 1. SigNoz MCP: bring production telemetry into agent workflows

SigNoz MCP exposes logs, metrics, traces, and alerts to MCP-compatible clients such as Claude Code, Cursor, Codex, and custom internal agents.

The important part is not MCP as a protocol by itself. The useful part is the workflow it unlocks.

### Debug from where you build

A developer investigating a production issue from a coding agent can give that agent access to the same telemetry used by the engineering team instead of manually moving snippets between tools.

### Start incident triage with an agent

Kernel is an early example in the supplied launch material: an internal agent can be brought into the incident workflow, query SigNoz through MCP, and return analysis into Slack.

**[BLOCKER: Exact Kernel wording and usage rights must be confirmed before publication.]**

### Validate what you just shipped

An engineer or agent can use telemetry after a deployment to inspect health and investigate regressions without treating production validation as a completely separate workflow.

### Investigate customer issues

Teams can also use agent workflows to inspect telemetry when customers report a problem, reducing the amount of context an engineer has to gather manually before an investigation starts.

### Build custom operational agents

Because MCP can expose SigNoz telemetry to compatible clients, teams can build internal workflows around their own operational triggers and context.

## 2. Noz: make AI another interface to observability

MCP brings SigNoz into external agent workflows. Noz brings an AI interface into SigNoz itself.

Noz lets engineers work with telemetry using natural language. Based on the current launch inputs, workflows include querying logs, metrics, and traces, explaining dashboards, comparing telemetry around deployments, finding bottleneck spans, and creating dashboards or alerts.

The objective is not to replace the engineer. It is to reduce the friction between a question and the telemetry needed to answer it.

**[BLOCKER: Confirm current GA / preview status and exact supported actions before publication.]**

## 3. Agent-native dashboards need dependable structure

An AI-generated artifact is only useful if the output is predictable enough to trust.

SigNoz dashboards use a strict, validated schema based on the CNCF Perses specification, with a defined hierarchy across pages, sections, panels, queries, and variables.

That structure matters for agent workflows because agents reason more reliably when the system exposes consistent fields and validated formats rather than ad hoc UI state.

It also reflects a broader architectural point: SigNoz is OpenTelemetry-native. The same open telemetry foundation used by engineers can become structured context for agents.

## 4. AI workloads also change the scale of observability

Agent-native workflows are only one half of the shift.

LLM applications can create significantly more telemetry than traditional request paths because a single user interaction can traverse model inference, tool calls, retrieval, databases, token streaming, and surrounding services.

Internal SigNoz data referenced in this launch shows AI-native companies generating approximately **2.4× more telemetry**.

**[BLOCKER: Verify methodology and approved public wording.]**

The updated trace-detail experience is designed around increasingly large traces. The supplied product brief cites:

- flame-graph rendering up to 100,000 spans in one load;
- sampling beyond 100,000 spans;
- waterfall support for unlimited spans;
- a 75% reduction in memory allocations;
- attribute-based search;
- improved error highlighting;
- LLM-specific filtering and fields.

**[BLOCKER: Verify exact current performance claims before publication.]**

## 5. Why these four updates belong together

It would be easy to launch MCP, Noz, dashboards, and trace improvements as four unrelated features.

But they point to the same architectural change.

### Agents need access to telemetry
MCP exposes production context to external agents.

### Engineers need an AI interface
Noz gives engineers a natural-language path into the telemetry system.

### Agent-created artifacts need structure
Validated dashboard schemas make automated creation more dependable.

### AI workloads need observability that can handle their scale
The trace experience has to work with larger traces and new AI-specific signals.

Together, these form the direction we mean by **agent-native + AI-scale observability.**

## 6. Humans stay in control

There is a difference between the product direction we are building toward and what has shipped today.

This launch includes SigNoz Cloud MCP, Noz, agent-native dashboard architecture, and AI-scale trace improvements.

Automated investigations triggered by alerts, autonomous always-on monitoring, deeper correlation with code changes / PRs / deployments, and other future agent-native capabilities are roadmap direction and should not be read as generally available functionality today.

That boundary matters. Production systems need useful automation, but they also need reliability and explicit human control.

## The direction

Observability was designed for a world where humans were the only users of telemetry and application traces followed relatively predictable paths.

That world is changing.

Agents are becoming part of software development and operations. AI workloads are creating more and different telemetry.

SigNoz is building for both.

> **A platform agents can run and engineers can trust, at any scale. OpenTelemetry-native. Predictable bills.**

**Try SigNoz MCP → [FINAL TRACKED URL REQUIRED]**  
**Explore Noz → [FINAL TRACKED URL REQUIRED]**
