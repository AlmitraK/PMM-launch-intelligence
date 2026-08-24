# SigNoz — Positioning Context

## Current positioning foundation

SigNoz is an OpenTelemetry-native, open-source observability platform that unifies logs, metrics, traces, and broader observability workflows while giving engineering teams predictable economics and deployment flexibility.

A useful high-level framing is:

**Unified observability on open standards — from modern applications and infrastructure to AI workloads.**

This file provides positioning context for launch planning. It is not a rigid messaging template. Specific launches should still start from the customer problem.

---

# Core positioning pillars

## 1. Unified Observability

### Customer problem
Observability is fragmented across tools and telemetry silos.

### SigNoz value
Bring logs, metrics, traces, APM, infrastructure context, alerts, and other telemetry into one platform.

### Proof direction
Show correlated workflows rather than merely claiming 'single pane of glass.'

Examples:

- traces → related logs
- logs → infrastructure context
- application performance → underlying request traces
- AI telemetry → surrounding application / infrastructure telemetry

### Avoid
Generic 'all-in-one' language without demonstrating why correlation changes troubleshooting.

---

## 2. OpenTelemetry + Open Source

### Customer problem
Proprietary agents and instrumentation create vendor lock-in and migration cost.

### SigNoz value
OpenTelemetry-native instrumentation gives customers greater portability and control.

### Supporting ideas
- open standards
- vendor-neutral instrumentation
- open-source product
- cloud or self-hosted deployment
- instrumentation as a long-term company asset

### Avoid
Treating OpenTelemetry purely as a feature. For many technical buyers it is an architectural choice.

---

## 3. Predictable Observability Economics

### Customer problem
Legacy observability pricing can be complicated and difficult to forecast, causing teams to restrict telemetry.

### SigNoz value
Usage-based pricing without host- or seat-based pricing can make observability economics easier to understand and manage.

### Supporting ideas
- transparent usage pricing
- no user-based pricing
- no host-based pricing
- ingestion controls
- migration from incumbent platforms

### Avoid
Making unsupported savings claims for an individual customer.

---

## 4. Enterprise-Ready Observability

### Customer problem
As observability expands across an organization, teams need security, access control, compliance, scale, support, migration, and deployment flexibility.

### SigNoz value
Provide a path from team-level observability to broader organizational standardization.

### Supporting ideas
- cloud and self-hosted deployment
- SOC 2 Type II
- HIPAA support / BAA where applicable
- RBAC / SSO capabilities
- data residency options
- migration support
- enterprise support and SLAs

### Avoid
Claiming enterprise readiness solely through a checklist. Tie enterprise capabilities to actual deployment and buying requirements.

---

## 5. AI / LLM Observability

### Customer problem
AI applications introduce new model and agent telemetry while still depending on databases, APIs, services, infrastructure, and traditional application components.

### SigNoz value
Observe AI workloads through OpenTelemetry and correlate them with the broader application stack rather than creating another isolated observability silo.

### Supporting ideas
- LLM calls and agent telemetry
- model latency / token and cost context where supported
- OpenTelemetry-based instrumentation
- correlation with application and infrastructure telemetry

### Avoid
Positioning SigNoz as an LLM-only observability tool.

---

## 6. Platform Consolidation

### Customer problem
Teams maintain combinations of Prometheus, Loki, Tempo, Grafana, ELK, APM vendors, and specialist tools.

### SigNoz value
Reduce operational overhead and troubleshooting fragmentation by consolidating observability workflows.

### Supporting ideas
- fewer backends to operate
- less context switching
- unified querying and dashboards
- correlation across telemetry

---

# Competitive framing

## Datadog / New Relic / legacy commercial observability

Potential differentiation:

- OpenTelemetry-native architecture
- open source
- usage-based economics
- cloud + self-hosted flexibility
- unified telemetry
- reduced proprietary instrumentation dependency

Do not position solely as 'cheaper Datadog.' The stronger story is architectural choice + unified workflow + economics.

## Grafana / Prometheus / Loki / Tempo and assembled OSS stacks

Potential differentiation:

- reduced operational burden
- one integrated product experience
- correlation across signals
- one backend / query experience
- managed cloud option alongside self-hosting

Do not dismiss these tools; many target users already understand and value them.

## Specialized observability tools

Potential differentiation:

- broad observability context
- fewer silos
- ability to correlate specialized workload telemetry with the rest of the stack

The tradeoff may be feature depth in specialized categories. Do not invent parity.

---

# Messaging principles

## Lead with the problem, not the feature

Weak:
> SigNoz now supports Feature X.

Better:
> Engineering teams struggle with X because Y. SigNoz now enables Z.

## Prefer workflows over adjectives

Weak:
> Powerful, seamless, next-generation observability.

Better:
> Move from a slow endpoint to its trace, related logs, and infrastructure context without switching tools.

## Be technically credible

The audience includes engineers. Claims should be specific enough to survive technical scrutiny.

## Use competitive positioning when it helps the buyer decide

Competitive framing is valuable when a launch changes the tradeoff versus Datadog, Grafana, New Relic, or another relevant alternative.

## Separate user value from enterprise value

A technical user may care about debugging speed.

A platform leader may care about standardization.

A CTO may care about cost, risk, and architecture.

A security team may care about data control and compliance.

The same feature can require different messages for each.

## Avoid generic AI language

When discussing AI, explain the actual workflow or telemetry problem being solved.

---

# Questions the Planner should answer before finalizing positioning

1. What changed for the customer?
2. Which ICP feels the pain most?
3. What job becomes easier or newly possible?
4. Why is SigNoz differentiated in solving it?
5. What proof supports the claim?
6. What alternative is the customer likely using today?
7. Is this primarily an adoption, displacement, expansion, or enterprise-standardization story?
8. What objection should the launch proactively answer?
