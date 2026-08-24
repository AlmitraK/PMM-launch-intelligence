# PRD — Agent-Native Observability: SigNoz MCP + Noz

## Overview

SigNoz is expanding observability from a UI engineers manually query into an observability system that AI agents can work with directly.

This launch brings together two complementary experiences:

1. **SigNoz MCP Server** — lets external AI tools such as Claude Code, Cursor, Codex, VS Code/GitHub Copilot, Gemini CLI, and other MCP-compatible agents interact with SigNoz observability data using natural language.
2. **Noz** — SigNoz's in-product AI teammate, available inside the SigNoz UI for asking questions about telemetry and SigNoz, investigating issues, and helping create observability objects such as alerts and dashboards.

Together, these capabilities form the foundation of **agent-native observability**.

## Customer Problem

Observability workflows still require engineers to leave the context where they are working, open dashboards, know what data to inspect, construct queries, and manually correlate logs, metrics, traces, alerts, and surrounding engineering context.

As AI coding agents become part of engineering workflows, observability data also needs to be accessible to agents.

The product should reduce the friction between a question and the telemetry needed to answer it.

## Target Users

Primary:
- Platform Engineers
- SREs
- DevOps Engineers
- Backend / Application Engineers

Secondary:
- Engineering teams already using AI coding tools
- Support and other technical teams that need easier access to observability context

## Product Capabilities

### SigNoz MCP Server

The MCP server connects MCP-compatible AI assistants to SigNoz.

Users can use natural language to:
- query metrics
- search logs
- inspect traces
- work with alerts
- work with dashboards
- investigate service and production issues from an AI coding tool

For SigNoz Cloud, a hosted MCP endpoint is available without installing a server. Self-hosted users can run the open-source MCP server themselves.

### Noz

Noz is an AI teammate inside the SigNoz UI.

It:
- lives alongside the SigNoz interface
- understands the page the user is currently viewing
- answers questions using SigNoz telemetry and documentation
- helps investigate errors, traces, logs, and service behavior
- can help create alerts and dashboards
- can deep-link users back into SigNoz for deeper investigation

Noz is currently in beta.

## MCP vs. Noz

The two experiences serve different moments.

**Use Noz** when the workflow begins inside SigNoz and the user wants a zero-setup, context-aware assistant within the observability product.

**Use the MCP server** when the workflow begins outside SigNoz — for example in Claude Code, Cursor, or Codex — or when an agent needs to combine SigNoz telemetry with context from code and other engineering tools.

## Example Workflows

### Debug while coding

An engineer working in Claude Code can ask SigNoz about a slow endpoint in staging, inspect its traces, and identify expensive operations without leaving the development environment.

### Validate a deployment

After shipping code, an engineer can ask whether error rates or latency changed after the deployment and use production telemetry to validate the release.

### Investigate an incident

An engineer can begin with a symptom and let the agent query and correlate relevant observability signals instead of manually moving through dashboards.

### Build observability

Inside SigNoz, a user can ask Noz to create an alert or assemble a dashboard from a natural-language description.

## Product Thesis

Observability is becoming an interface for both humans and agents.

SigNoz's OpenTelemetry-native foundation and correlated logs, metrics, and traces provide agents with structured operational context. MCP makes that context available to external agents, while Noz brings AI-assisted workflows directly into SigNoz.

The broader product direction is **agent-native observability**: observability infrastructure designed so AI agents can investigate, reason over, and increasingly operate on telemetry alongside engineers.

## Launch Status

- SigNoz hosted MCP server: available to SigNoz Cloud users
- Self-hosted MCP server: available for self-hosted deployments
- Noz: beta
