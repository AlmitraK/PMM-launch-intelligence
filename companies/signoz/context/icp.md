# SigNoz — ICP and Buyer Context

## Overview

SigNoz serves engineering organizations that need observability across modern applications and infrastructure. The strongest ICP patterns in current internal research cluster around four archetypes.

---

## ICP 1 — AI-Native Scaling Startup

### Typical company
Small to mid-sized startup, often roughly 10–50 employees and around Series A/B stage.

### Typical roles
- CTO
- Head of Engineering
- Founding Engineer

### Problems
- diagnosing latency across complex AI / voice / data pipelines
- fragmented browser-to-backend visibility
- fear of observability bill shock while scaling
- observability competing with core product development for engineering time

### Motivations
- fast time-to-value
- low-friction setup
- OpenTelemetry and vendor neutrality
- ability to scale observability without unpredictable economics

### Common objections
- maturity of specialized LLM or frontend capabilities
- perceived OpenTelemetry setup complexity

---

## ICP 2 — Fragmented-Stack Platform Team

### Typical company
Mid-market to enterprise organization, often with 100–1,000+ engineers.

### Typical roles
- Platform Engineer
- SRE Lead
- VP Engineering

### Problems
- maintaining multiple observability backends
- switching between logs, metrics, and traces during incidents
- fragmented telemetry and troubleshooting blind spots
- low developer adoption of complicated internal observability stacks
- operational and cognitive overhead

### Motivations
- single observability interface
- correlation across telemetry
- OpenTelemetry standardization
- lower MTTR
- reduced tool sprawl

### Common objections
- migration overhead
- parity with specialized incumbent features
- RUM / synthetics / security capability gaps

---

## ICP 3 — Incumbent-Cost / Datadog-Burned Organization

### Typical company
Large mid-market or enterprise engineering organization.

### Typical roles
- SRE Director
- Director of Operations
- DevOps Manager
- Engineering leadership

### Problems
- opaque or complicated observability pricing
- unpredictable bills
- teams suppressing telemetry because of cost
- proprietary instrumentation and vendor lock-in
- dissatisfaction with incumbent vendor economics or support

### Motivations
- predictable usage-based economics
- observability cost consolidation
- OpenTelemetry standardization
- vendor independence

### Common objections
- migration of dashboards and alerts
- feature parity with established observability suites
- specialized monitoring requirements

---

## ICP 4 — B2B Infrastructure / Platform-as-a-Product Team

### Typical company
Mid-market infrastructure or B2B services company, often roughly 50–500 employees.

### Typical roles
- Platform Engineer
- SRE Lead
- Infrastructure Architect

### Problems
- client data isolation
- multi-tenancy and RBAC requirements
- compliance / regional deployment requirements
- maintaining self-hosted ELK or Grafana stacks
- need to expose observability inside their own customer experience

### Motivations
- programmable observability
- APIs and embeddability
- self-hosting / deployment control
- lower maintenance burden
- partnership with an observability vendor

### Common objections
- multi-tenancy maturity
- scalability proof
- enterprise controls

---

# Buyer hierarchy

## Technical user / evaluator

Typical roles:

- DevOps Engineer
- Application Engineer / Application Lead
- Backend Engineer
- SRE
- Platform Engineer

They care about:

- setup
- querying
- debugging workflow
- telemetry coverage
- UX
- integrations
- feature parity

## Champion

Often:

- Lead Platform Engineer
- SRE Lead
- Founding Engineer
- senior Backend Engineer

They lead evaluation, define technical success criteria, and advocate internally.

## Economic buyer

Often:

- CTO
- VP Engineering
- Platform leadership

They care about:

- product maturity
- total cost
- scalability
- long-term architecture
- migration risk
- support
- vendor strategy

## Enterprise gatekeepers

### Security / Compliance
Care about security posture, SOC 2, HIPAA where relevant, data residency, deployment architecture, access control, and contractual requirements.

### Procurement / Finance
Care about contract structure, predictability, volume economics, renewal timing, and commercial terms.

---

# Common buying journey

## 1. Discovery / displacement

The organization recognizes an observability problem or begins evaluating an alternative to an incumbent stack.

## 2. Technical evaluation / POC

Teams validate SigNoz using a subset of workloads or production telemetry and define success criteria.

## 3. Technical win

The team establishes sufficient functionality, performance, integration, and workflow fit.

## 4. Security / legal

Enterprise requirements become gating criteria.

## 5. Commercial decision

Pricing, contract structure, procurement, support, and SLAs become central.

## 6. Expansion / standardization

A successful initial deployment can broaden across workloads, teams, telemetry types, and organizational use cases.

---

# Messaging themes from internal ICP work

Six recurring themes appear in internal research:

1. Unified observability
2. AI / LLM workload observability
3. TCO advantage over legacy vendors
4. Open source + OpenTelemetry
5. Enterprise / platform readiness
6. Integrations

These are themes, not automatically the message for every launch. The Planner should determine which theme is relevant to the specific product change and ICP.

# Guidance for the Launch Planner

For every launch, explicitly identify:

- primary ICP
- primary persona
- technical user
- champion
- economic buyer, if relevant
- buyer stage affected
- core pain
- desired outcome
- likely objection

Do not treat 'developer' or 'engineering team' as a sufficiently specific ICP.
