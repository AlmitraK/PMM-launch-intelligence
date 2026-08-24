# Launch Page

## H1
# Observability for the AI era: agent-native and AI-scale

## Subhead
AI is changing both who uses telemetry and how much telemetry modern software produces. SigNoz is evolving for both — giving agents structured access to production telemetry while helping engineers investigate AI-scale workloads on one OpenTelemetry-native observability platform.

**Primary CTA:** Try SigNoz MCP  
**Secondary CTA:** Explore Noz

---

## AI changes observability in two directions

| Shift | What changes | What engineering teams need |
|---|---|---|
| **Agents become telemetry users** | Coding and operational agents increasingly participate in debugging and production workflows | Structured access to real logs, metrics, traces, and alerts |
| **AI workloads create more telemetry** | LLM calls add model inference, tool calls, token streaming, databases, and new attributes into traces | An observability experience that handles larger traces and AI-specific signals without creating another silo |

---

## Bring observability where developers and agents already work

SigNoz MCP exposes observability data to MCP-compatible clients such as Claude Code, Cursor, Codex, and custom internal agents.

Instead of copying telemetry out of your observability tool and pasting it into an agent, the agent can work with the same production context your engineers use.

### Use cases

#### 1. Debug production from your coding agent
**User:** Developer / SRE  
**Trigger:** A regression, error, or unexpected production behavior  
**Workflow:** Ask the coding agent to query SigNoz telemetry through MCP while you investigate.  
**Why it matters:** Keep the debugging workflow close to where development work is already happening.

#### 2. Start incident triage with an agent
**User:** SRE / Platform Engineer  
**Trigger:** An incident occurs  
**Workflow:** An internal agent queries relevant telemetry and returns evidence into the incident workflow.  
**Proof:** Kernel has used an internal agent with SigNoz MCP for incident triage. **[EXACT CUSTOMER WORDING / APPROVAL REQUIRED.]**

#### 3. Validate a deployment
**User:** Developer / Platform Engineer  
**Trigger:** A new version ships  
**Workflow:** Query production health, compare relevant telemetry, and investigate regressions after deployment.  
**Why it matters:** Make production validation part of the development loop.

#### 4. Investigate customer issues
**User:** Technical support / engineering team  
**Trigger:** A customer reports a problem  
**Workflow:** Use an MCP-compatible agent to inspect relevant logs and telemetry.  
**Why it matters:** Reduce the manual context-gathering required before technical investigation begins.

#### 5. Work with telemetry in natural language
**User:** Engineer  
**Trigger:** You need an answer, dashboard explanation, query, or supported observability task  
**Workflow:** Ask Noz inside SigNoz.  
**Why it matters:** Use AI as another interface into the same observability system rather than creating a separate AI-only experience.

#### 6. Investigate very large AI traces
**User:** AI-native engineer / SRE  
**Trigger:** An LLM or agent workflow creates a large, complex trace  
**Workflow:** Inspect large trace structures, search attributes, and work with LLM-specific fields.  
**Proof:** Current launch inputs cite flame-graph rendering up to 100,000 spans in one load, sampling beyond that, unlimited-span waterfall support, and reduced memory allocations. **[VERIFY EXACT PUBLIC CLAIMS BEFORE PUBLISHING.]**

---

## Make AI an interface to observability

Noz is SigNoz's in-product AI interface.

Depending on current product availability, supported workflows include asking questions across logs, metrics, and traces, explaining dashboards or current-screen data, comparing telemetry around deployments, finding bottleneck spans, and creating dashboards or alerts through natural-language requests.

**[VERIFY CURRENT GA / PREVIEW STATUS BEFORE PUBLISHING.]**

---

## Structure matters when agents use telemetry

Agent workflows are only as dependable as the context they receive.

SigNoz is OpenTelemetry-native, giving teams standardized telemetry semantics rather than tying their observability data to proprietary instrumentation.

Our dashboard architecture also uses a strict validated schema based on the CNCF Perses specification, designed to make dashboard creation and modification more predictable for both agents and humans.

---

## Built for AI-scale telemetry

AI-native applications do not only introduce new signals. They can materially increase telemetry volume.

Internal SigNoz data referenced in the launch brief shows AI-native companies generating approximately **2.4× more telemetry**. **[VERIFY METHODOLOGY / PUBLIC WORDING.]**

The updated trace experience is designed for that reality, with improvements for large traces, attribute search, error visibility, span navigation, and LLM-specific fields.

---

## One telemetry foundation for humans and agents

MCP, Noz, agent-native dashboards, and AI-scale traces are not four disconnected AI features.

They are parts of one direction:

> **An OpenTelemetry-native observability platform where humans and agents can work over the same production context, at AI scale.**

Humans stay in control. Roadmap capabilities such as autonomous always-on monitoring and deeper code-to-deploy correlation should not be interpreted as shipped functionality today.

**Primary CTA:** Try SigNoz MCP — [FINAL URL REQUIRED]  
**Secondary CTA:** Explore Noz — [FINAL URL REQUIRED]
