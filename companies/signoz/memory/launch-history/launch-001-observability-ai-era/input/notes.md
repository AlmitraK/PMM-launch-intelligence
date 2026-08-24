# Launch Notes — Actual GTM Execution

## Important Context

This file records how the launch was actually planned and executed. It should be treated as human GTM context, not as historical performance learning.

## MCP Launch

Internal classification in the launch tracker: **Tier 3**.

Go-live target in the tracker: late April 2026.

### Website
- update relevant website content
- update product dropdown and homepage
- add CTA on AI page
- create/update dedicated page and imagery
- add internal links from 10+ relevant/high-performing pages
- publish hosted MCP changelog
- update support articles and FAQs
- use top-page banner/pill CTA where appropriate

### Email / Existing Users
- product-update email to paid customers first
- broader database email planned afterward
- descending-MRR sequencing discussed for paid accounts
- Pylon broadcast to existing users
- in-product communication considered after AI-assistant launch

### Content
- technical announcement blog
- 8 MCP docs/use-case pieces completed, with additional pieces planned
- 3–5 deeper user-centric posts grouped around benefits, features, and use cases
- launch and educational videos
- one video per use case
- Reddit distribution
- YouTube distribution
- social posts across LinkedIn and X for 2–3 weeks

### Messaging Direction Used
A major content theme was:

**Development and observability have historically been siloed. Bring observability into where developers and agents already work.**

Supporting ideas:
- no context switching
- no tool swapping
- observability in-context
- concrete benefits and use cases rather than feature-only messaging

### Customer Proof
Kernel was identified as a strong proof point:
- internal agent can be tagged during incidents
- agent connects to SigNoz MCP
- queries metrics / telemetry
- posts analysis in Slack
- workflows include customer triage, incidents, and post-launch monitoring
- non-technical teams can also use agent workflows to inspect production data

## MCP Measurement Plan

### Primary — Existing Users
Goal: drive MCP adoption among existing users.

Tracked baseline noted in launch plan: approximately 86 users.
Target discussed: approximately 120–130.

Primary distribution:
- email
- in-app / existing-user communication

Measurement:
- MCP adoption
- email / website CTR where attributable
- product usage through Mixpanel

### Secondary — New Users
Goal: use launch content to drive new-user interest.

Measurement:
- launch blog views
- docs views
- landing-page views
- website CTR
- signup conversion target discussed: ~1% from views
- YouTube impressions

## Noz / AI Assistant Launch

Alpha target: late May 2026.
GA target in tracker: mid-June 2026.

### Pre-Launch
- pricing-page update
- comparison-tab update
- new imagery
- agent-native page
- paid-user in-product update
- Pylon communication
- prospect email depending on platform readiness
- sneak-peek video and social posts

### GA / Post-Launch
- internal linking
- changelog
- technical announcement blog
- paid-user product update
- GitHub
- docs for AI-assistant use cases
- 3–5 deeper content pieces
- social distribution for 2–3 weeks
- product how-to / educational videos
- Reddit
- Pylon broadcast on GA
- YouTube distribution
- remove early-access language from website

### Adoption Flow Considered
The launch plan included a signup/access workflow:
1. user signs up for AI Assistant on the website
2. acknowledge request by email
3. check whether the user already has an account
4. enable the feature for eligible existing accounts
5. for new users, provision / onboard and then enable the feature
6. send confirmation once access is available

Agent-native observability was also considered for inclusion in onboarding emails.

## Broader Narrative Used

The final umbrella narrative expanded beyond only MCP + Noz:

**Building observability for the AI era: agent-native and AI-scale telemetry.**

The narrative connected four shipped product updates:
1. SigNoz Cloud MCP
2. Noz
3. agent-native dashboards
4. AI-scale trace detail view

The two market shifts used to support the narrative were:
- agents are becoming primary users of telemetry
- LLM calls are adding new signals and multiplying telemetry volume

The umbrella promise used in the launch content:

**A platform agents can run and engineers can trust, at any scale. OpenTelemetry-native. Predictable bills.**

## Important Constraint for Agent 1

Do not infer from this execution plan that every future AI launch should use the same tactics.

This is evidence of how this launch was run, not yet evidence that the tactics worked.
