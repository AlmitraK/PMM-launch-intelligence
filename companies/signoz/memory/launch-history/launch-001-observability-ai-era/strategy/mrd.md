# MRD — SigNoz: Observability for the AI Era

## 1. Market problem

AI is changing observability in two directions at once.

First, engineers increasingly work through coding and operational agents. Those agents need direct, structured access to production telemetry instead of forcing engineers to leave their development environment, open an observability UI, and manually translate context back into the agent workflow.

Second, LLM and agent workloads generate materially more telemetry and new classes of signals. A single AI workflow can span model inference, tool calls, databases, token streaming, and surrounding application infrastructure. SigNoz internal data cited in the product brief shows AI-native companies generating approximately 2.4× more telemetry.

The resulting market need is not simply “AI observability.” Engineering teams need an observability platform that can serve both humans and agents, while handling larger traces and AI-specific telemetry without creating another isolated monitoring silo.

## 2. Primary market / ICP

### Primary ICP
**AI-native scaling engineering teams** and **platform/SRE teams actively adopting coding or operational agents.**

These teams are the strongest fit because they face both sides of the shift:
- agent-driven development and operations;
- increasing telemetry volume and complexity;
- pressure to reduce context switching during debugging;
- a need for structured, vendor-neutral telemetry;
- concern about observability cost as telemetry volume grows.

### Primary persona
Platform Engineer / SRE / DevOps Engineer.

### Technical users
Platform Engineers, SREs, DevOps Engineers, Backend/Application Engineers, and engineering teams using Claude Code, Cursor, Codex, or custom agents.

### Champion
Lead Platform Engineer, SRE Lead, Founding Engineer, or senior backend engineer.

### Economic buyer
CTO, VP Engineering, or Platform leadership when the capability becomes part of a broader observability standardization decision.

## 3. Jobs to be done

### JTBD 1 — Investigate production from the agent workflow
**When I am building or operating software through an AI agent, give that agent structured production telemetry so it can investigate without forcing me to switch tools.**

### JTBD 2 — Use natural language as an observability interface
**When I am inside SigNoz, let me ask for the telemetry or observability task I need instead of manually navigating and constructing every query.**

### JTBD 3 — Handle AI-scale traces
**When AI workloads create very large traces, let me investigate them without the observability UI becoming the bottleneck.**

### JTBD 4 — Investigate AI workloads in full application context
**When an LLM or agent workflow degrades, let me inspect AI-specific attributes alongside the application and infrastructure telemetry around it rather than using a separate AI-only monitoring silo.**

### JTBD 5 — Build repeatable agent-led operational workflows
**When incidents, customer issues, or post-launch checks occur, let my internal agents query telemetry and return evidence into the workflow where my team already works.**

## 4. Market alternatives and competitive context

The broad observability market includes Datadog, New Relic, Grafana-based stacks, Prometheus/Loki/Tempo combinations, Splunk, and specialist observability products.

For this launch, **Dash0 is the most relevant narrative comparator** because it also combines OpenTelemetry-native observability with MCP, AI-assisted observability, and an “Observability for the AI Era” direction.

This means the following are **not sufficient differentiation on their own**:
- “AI-native observability”;
- “Observability for the AI Era”;
- MCP support;
- OpenTelemetry + agents;
- natural-language investigation.

SigNoz should therefore avoid trying to out-claim competitors on autonomy. The differentiation needs to come from the combination of product proof, architecture, and operational workflows.

## 5. Positioning

### Category frame
**Observability for the AI era: agent-native and AI-scale.**

### Positioning statement
For engineering teams adopting AI agents and operating AI-native workloads, SigNoz is an OpenTelemetry-native observability platform that gives agents structured access to production telemetry while giving engineers a unified system for investigating both traditional and AI workloads at scale.

Unlike an AI assistant layered over a separate or fragmented observability stack, SigNoz combines agent access, an in-product AI interface, structured dashboards, and AI-scale trace workflows over the same OpenTelemetry-native telemetry foundation.

### Core promise
**A platform agents can run and engineers can trust, at any scale. OpenTelemetry-native. Predictable bills.**

## 6. Message hierarchy

### Message 1 — Bring observability where developers and agents already work
SigNoz MCP exposes logs, metrics, traces, and alerts to MCP-compatible clients such as Claude Code, Cursor, Codex, and custom internal agents.

**Proof:** Kernel uses an internal agent during incidents to query SigNoz telemetry and post analysis into Slack. Other observed workflows include post-launch monitoring and customer triage.

### Message 2 — Make AI an interface to observability
Noz lets engineers ask questions across logs, metrics, and traces in natural language and perform tasks such as explaining dashboards, comparing telemetry before and after deployments, identifying bottleneck spans, and creating dashboards or alerts.

### Message 3 — Build observability for AI-scale telemetry
AI-native teams generate more telemetry and larger traces. SigNoz’s trace experience supports flame-graph rendering up to 100,000 spans in one load, sampling beyond that threshold, unlimited-span waterfall views, reduced memory allocations, attribute search, and LLM-specific filtering.

### Message 4 — Give agents structured telemetry rather than brittle context
OpenTelemetry matters because agents reason better over consistent schemas and fields. SigNoz’s OpenTelemetry-native architecture and validated dashboard schema provide structured inputs for both humans and agents.

## 7. Differentiation and proof

The strongest launch differentiation is the **combination**, not any individual AI feature:

1. One OpenTelemetry-native telemetry foundation across traditional and AI workloads.
2. External agent access through MCP.
3. An in-product AI interface through Noz.
4. Structured, validated dashboard architecture intended to produce dependable agent-generated output.
5. Trace UX designed for very large AI-generated traces.
6. Human control alongside agent operation.
7. Predictable usage-based economics as telemetry volume increases.
8. Real customer workflows rather than only roadmap claims.

## 8. Product boundaries / claims guardrail

The launch must clearly separate shipped capability from product direction.

### Shipped
- SigNoz Cloud MCP;
- Noz;
- agent-native dashboard architecture;
- AI-scale trace-detail improvements.

### Direction / roadmap — do not present as shipped
- alert-triggered automated investigations;
- autonomous always-on monitoring;
- deeper correlation with code changes, PRs, and deploys;
- richer agent-native alert APIs and LLM-specific trace details.

## 9. Key objections / risks

1. **“Everyone has an AI assistant now.”**  
   Answer with the unified agent-native + AI-scale architecture and concrete workflows, not generic AI language.

2. **“MCP is not differentiation.”**  
   Agree implicitly: MCP is access infrastructure. Differentiate on what agents can access, the telemetry structure underneath, and the workflows it enables.

3. **“Is this just LLM observability?”**  
   No. AI telemetry remains connected to broader application and infrastructure observability.

4. **“Are autonomous operations already available?”**  
   No. Keep future automated investigation and monitoring explicitly as roadmap direction.

5. **“Can the platform handle AI-driven telemetry growth?”**  
   Lead with the specific trace-scale improvements and internal 2.4× telemetry observation rather than generic scalability claims.

## 10. Strategic conclusion

The strongest market story is larger than MCP or Noz individually:

> **AI changes both who uses observability and the scale/type of telemetry observability must handle. SigNoz is adapting the platform for both shifts.**

The launch should therefore establish the **agent-native + AI-scale** product direction while using the four shipped product updates as concrete proof.
