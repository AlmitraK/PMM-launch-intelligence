# Launch Plan — SigNoz: Observability for the AI Era

> **Agent 1 output contract:** This is the execution-ready launch strategy produced from the PRD + company/ICP context + outside-in launch research.  
> **Design rule:** Tables first. Prose only where synthesis is required.  
> **Boundary:** Agent 1 decides strategy. Agent 2 executes. Agent 3 measures and learns.

---

## 1. Launch Overview

| Field | Decision |
|---|---|
| **Launch** | Observability for the AI Era: Agent-Native + AI-Scale |
| **Strategic narrative** | AI is changing both **who uses telemetry** (agents) and **the scale/type of telemetry produced** (LLM + agent workloads). SigNoz is evolving for both shifts. |
| **Commercial motion** | Drive adoption and discovery of shipped capabilities, especially SigNoz MCP and Noz, while establishing the broader AI-era product direction. |
| **Narrative tier** | **Tier 1** — meaningful product/category direction, not a single-feature announcement |
| **Primary ICP** | Platform / SRE teams and AI-native engineering teams adopting coding or operational agents |
| **Primary personas** | Platform Engineer, SRE, DevOps Engineer, Backend/Application Engineer |
| **Secondary personas** | CTO / VP Engineering / Platform leadership |
| **Primary CTA** | Try/configure SigNoz MCP or use Noz, depending on asset/audience |
| **Key guardrail** | Separate shipped capabilities from roadmap. Do not imply autonomous investigation / always-on monitoring / full code-to-deploy correlation are shipped. |

### Launch-level success scorecard

| Metric role | Metric | Baseline | Target | Time window |
|---|---|---:|---:|---|
| **Primary outcome** | MCP / Noz adoption or activation | TBD — required input | TBD — required input | TBD |
| Leading indicator | Launch/relevant page visits | TBD | Directional lift vs comparable baseline | Launch window |
| Leading indicator | Docs / use-case content visits | TBD | Directional lift | Launch window |
| Leading indicator | Email CTR | Historical comparable send | Directional lift | Send window |
| Distribution | LinkedIn / external impressions | Historical comparable posts | Directional lift | Launch + 1–3 weeks |
| Downstream | Qualified UTM visits | Historical comparable launch | Directional lift | Launch + 1–3 weeks |
| Downstream | Signups from tracked launch traffic | Historical comparable launch | Directional lift | Launch + 1–3 weeks |

**Rule:** Never manufacture a baseline or target. Use `TBD` / `NA` when current data is not available.

---

## 2. Audience, Buyer & Job Priority

| Priority | Audience | Role in motion | Core problem | Desired outcome | Likely objection |
|---|---|---|---|---|---|
| 1 | Platform Engineer / SRE | Technical user + evaluator | Agent workflows lack production context; observability remains a separate workflow | Let agents and humans investigate the same structured telemetry | “MCP is just another integration” |
| 2 | Backend / App Engineer using AI coding tools | User | Context switching between Claude Code/Cursor and observability | Investigate production without leaving the development workflow | “I can already paste logs into my AI tool” |
| 3 | AI-native engineering team | ICP | AI workloads create much larger, more complex traces | Observe AI workloads alongside app/infrastructure telemetry | “Is this just LLM observability?” |
| 4 | CTO / VP Eng / Platform leader | Champion / economic buyer | AI increases delivery velocity and operational complexity | Standardize on an architecture that can support humans + agents at scale | “How mature / differentiated is this?” |

---

## 3. Launch Narrative & Message Hierarchy

| Layer | Message | Proof |
|---|---|---|
| **Category frame** | **Observability for the AI era: agent-native and AI-scale.** | Four shipped product updates support the direction |
| **H1** | **Bring observability where developers and agents already work.** | MCP-compatible access to logs, metrics, traces and alerts |
| **H2** | **Make AI an interface to observability.** | Noz natural-language investigation, dashboard explanation, dashboard/alert creation |
| **H3** | **Build observability for AI-scale telemetry.** | 2.4× more telemetry observed among AI-native SigNoz companies; large-trace UX |
| **Architecture proof** | Agents need structured, consistent telemetry—not brittle copied context. | OpenTelemetry-native foundation + validated dashboard schema |
| **Trust proof** | Humans remain in control. | Shipped capabilities vs roadmap explicitly separated |
| **Economic proof** | AI-era telemetry growth should not make observability economics unpredictable. | Usage-based / predictable-bill positioning |

### Required launch use cases

| Use case | User | Trigger | Workflow | Product proof |
|---|---|---|---|---|
| Debug production from Claude Code / Cursor / Codex | Developer / SRE | Error / regression during development | Agent queries SigNoz telemetry from coding environment | MCP |
| Agent-led incident triage | SRE / Platform | Incident fires | Internal agent queries telemetry and posts evidence back into incident workflow | MCP + Kernel example |
| Post-deployment validation | Developer / Platform | New release ships | Check health / compare before-after telemetry | MCP / Noz |
| Customer issue investigation | Support-adjacent technical team | Customer reports issue | Agent inspects logs/telemetry without deep manual query work | MCP |
| Natural-language observability | Engineer | Need answer / dashboard / alert | Ask Noz instead of manually navigating/querying | Noz |
| Investigate large AI traces | AI-native engineer | LLM/agent workflow degrades | Inspect high-span traces + AI-specific attributes | AI-scale trace view |

---

# 4. Competitive Launch Intelligence — Outside-In Research

**Requirement:** For Tier 1 launches, research 3–5 relevant launches. Use actual launch/blog/docs pages. For each competitor: detailed teardown + exactly **3 actionable learnings**. Then show how the research changes our launch narrative and tactics.

## 4.1 Dash0 — “Observability for the AI Era” / Agent0 GA

| Field | Launch teardown |
|---|---|
| **Launch / date** | “From OpenTelemetry-Native to Observability for the AI Era” — Jun 1, 2026; Agent0 GA follow-up — Jun 3, 2026 |
| **Product / strategic move** | Repositioned Dash0 from “OpenTelemetry-native observability” to “Observability for the AI Era”; made Agent0 GA |
| **Narrative / hook** | Coding agents are accelerating the SDLC; the “back half” of software operations must become agentic too |
| **Target audience** | Developers, SRE/platform teams, engineering leaders adopting coding agents |
| **Key messages** | OTel is foundation, not destination; humans + agents operate software together; Agent0 moves beyond chat toward multi-agent production workflows |
| **Proof / evidence** | Customer count, recognizable customers, OTel foundation, GitHub/Linear integrations, PR generation, task-based pricing |
| **Launch assets visible** | Founder/CEO POV blog; product GA blog; supporting product/docs content |
| **Distribution pattern** | Large category-level POV followed immediately by concrete product proof |
| **Pre-launch** | Existing Agent0 beta / prior Agent0 announcement established product context |
| **Launch** | Category repositioning + GA announcement in tightly sequenced posts |
| **Post-launch** | Continued posts expanding into coding insights, agent platform and “beyond observability” |
| **CTA** | Try Agent0 / read docs |
| **Links** | https://www.dash0.com/blog/from-opentelemetry-native-to-observability-for-the-ai-era  •  https://www.dash0.com/blog/observability-for-the-ai-era-starts-here-agent0-is-ga |

### 3 learnings from Dash0

| # | Learning | Implication for SigNoz |
|---|---|---|
| 1 | **“Observability for the AI Era” is already occupied narrative territory.** | Use the frame, but do not treat it as differentiation. |
| 2 | **A category-level POV becomes credible when followed by concrete shipped product proof.** | Tie the umbrella story directly to MCP + Noz + dashboard architecture + large-trace UX. |
| 3 | **Dash0 is leaning aggressively into autonomy / production-agent territory.** | SigNoz should not try to win by making larger autonomy claims; differentiate with unified telemetry, structured OTel foundation, human control and real workflows. |

---

## 4.2 New Relic — MCP Server / Agentic Platform

| Field | Launch teardown |
|---|---|
| **Launch / date** | MCP support — Jun 11, 2025; MCP Server — Nov 4, 2025; Agentic Platform preview — Feb 24, 2026 |
| **Product / strategic move** | Added MCP visibility/support, launched an MCP server to connect agents to observability, then expanded the story into an Agentic Platform |
| **Narrative / hook** | Observability must evolve from passive monitoring as software and operations become agentic |
| **Target audience** | Developers, SRE/operations teams, AI application builders |
| **Key messages** | Standardized bridge between AI agents and observability; reduce integration sprawl; agents can retrieve context and perform observability workflows |
| **Proof / evidence** | MCP tools, partner ecosystem, NRQL translation, integrations with AI development environments |
| **Launch assets visible** | News/product blog, documentation “what’s new,” partner announcement (e.g. AWS/Kiro), product preview content |
| **Distribution pattern** | Product announcement + documentation + ecosystem/partner reinforcement |
| **Pre-launch** | Earlier MCP monitoring/support established category relevance |
| **Launch** | MCP Server announcement + preview/docs |
| **Post-launch** | Expanded partner integrations and broader Agentic Platform narrative |
| **CTA** | Enable preview / get started / read docs |
| **Links** | https://newrelic.com/blog/news/new-relic-ai-mcp-server-launch  •  https://docs.newrelic.com/whats-new/2025/11/whats-new-11-05-mcp-server/  •  https://newrelic.com/blog/ai/advancing-observability-into-the-agentic-era  •  https://newrelic.com/blog/news/new-relic-ai-aws |

### 3 learnings from New Relic

| # | Learning | Implication for SigNoz |
|---|---|---|
| 1 | **MCP alone is becoming table stakes across observability vendors.** | Lead with workflows and architecture, not “we have MCP.” |
| 2 | **Partner/ecosystem launches extend credibility and distribution.** | Test MCP-client / ecosystem amplification rather than relying only on owned channels. |
| 3 | **The story can expand from one integration into a broader platform direction over time.** | Use MCP as one proof point inside the agent-native direction, not the entire narrative. |

---

## 4.3 Weaviate — Weaviate Agents

| Field | Launch teardown |
|---|---|
| **Launch / date** | “Meet Weaviate Agents” — Mar 4, 2025; Query Agent — Mar 5, 2025; follow-on agent releases afterward |
| **Product / strategic move** | Introduced a suite of purpose-built agents, then followed the umbrella announcement with specific agent launches |
| **Narrative / hook** | AI developers are held back by fragmented tools and complex data workflows; purpose-built agents simplify orchestration |
| **Target audience** | AI developers, data/ML engineers, builders of generative AI applications |
| **Key messages** | Move from database interaction toward intent-driven workflows; agents are domain experts over Weaviate APIs + customer data |
| **Proof / evidence** | Concrete e-commerce examples, technical preview access, sandbox availability, tutorials/docs |
| **Launch assets visible** | Product vision blog; next-day product-specific blog; docs; quickstart/tutorials; subsequent agent-specific content |
| **Distribution pattern** | Umbrella narrative → individual product/use-case stories → technical education |
| **Pre-launch** | Educational content defining agents and agentic workflows |
| **Launch** | Vision announcement followed immediately by Query Agent product detail |
| **Post-launch** | Transformation Agent, Personalization Agent, tutorials, developer enablement |
| **CTA** | Try preview / sandbox / quickstart |
| **Links** | https://weaviate.io/blog/weaviate-agents  •  https://weaviate.io/blog/query-agent  •  https://weaviate.io/developers/agents |

### 3 learnings from Weaviate

| # | Learning | Implication for SigNoz |
|---|---|---|
| 1 | **A strong umbrella launch can still give each product its own use-case story.** | Keep “agent-native + AI-scale” as umbrella, but create focused MCP / Noz / large-trace follow-on content. |
| 2 | **Technical enablement is part of launch distribution, not just documentation.** | Post-launch docs/how-to/tutorial content should be a planned motion. |
| 3 | **Specific workflows make abstract agent narratives understandable.** | Use incident triage, post-deployment checks and customer issue investigation as central proof. |

---

## 4.4 PlanetScale — Metal GA

| Field | Launch teardown |
|---|---|
| **Launch / date** | “Announcing PlanetScale Metal” — Mar 11, 2025 |
| **Product / strategic move** | GA of a new database node class based on locally attached NVMe |
| **Narrative / hook** | Fundamental improvement in relational database performance/cost ratio |
| **Target audience** | Database/platform engineers and technical leaders |
| **Key messages** | Faster queries + materially better economics; available now |
| **Proof / evidence** | 5T queries, 5PB storage, up to 65% lower p99 latency, 53% cost savings vs Aurora |
| **Launch assets visible** | Core launch blog plus multiple customer stories / technical proof links |
| **Distribution pattern** | Concise announcement with quantified proof and customer evidence doing much of the persuasion |
| **Pre-launch** | Product had already been in production with customers for ~3 months |
| **Launch** | GA announcement centered on measured outcomes and availability |
| **Post-launch** | Customer-specific proof and technical “how we built it” content |
| **CTA** | Use Metal / learn how it works |
| **Links** | https://planetscale.com/blog/announcing-metal |

### 3 learnings from PlanetScale

| # | Learning | Implication for SigNoz |
|---|---|---|
| 1 | **Technical buyers respond to hard product proof more than adjectives.** | Make 2.4× telemetry, large-trace limits, memory improvements and customer workflows highly visible. |
| 2 | **Customers can carry the launch story.** | Kernel should be a first-class launch proof point, not a footnote. |
| 3 | **A strong technical launch can be concise if the evidence is strong.** | Avoid bloating the umbrella narrative; let workflow + performance proof do the work. |

---

## 4.5 Cross-Competitor Synthesis → Our Launch Decisions

| Cross-market insight | Decision for SigNoz |
|---|---|
| “AI era” / “agentic observability” language is increasingly common | **Do not differentiate on the category phrase alone.** |
| MCP is becoming a standard access mechanism | **Do not make MCP itself the hero; make the workflow it unlocks the hero.** |
| Strong technical launches combine category POV with concrete proof | **Use the broad agent-native + AI-scale narrative, anchored in four shipped capabilities.** |
| Competitors frequently sequence umbrella story → product detail → education | **Use a multi-week launch, not a one-day announcement.** |
| Technical workflow examples outperform abstract AI descriptions | **Center incident triage, developer-in-agent workflow, post-deployment validation and large AI traces.** |
| Customer evidence materially increases technical credibility | **Use Kernel prominently, subject to approval.** |
| Partner/ecosystem activity can extend technical reach | **Test MCP ecosystem / client-adjacent amplification.** |
| Quantified product proof is powerful for infrastructure audiences | **Surface 2.4× telemetry, trace scale and memory improvements wherever relevant.** |

### Narrative chosen because of the research

| Decision | Chosen direction |
|---|---|
| **Category frame** | Observability for the AI era |
| **Distinctive architecture** | **Agent-native + AI-scale on one OpenTelemetry-native telemetry foundation** |
| **Workflow hero** | Bring production telemetry into the places developers and agents already work |
| **Trust posture** | Human control; explicit shipped-vs-roadmap boundary |
| **Proof hierarchy** | Customer workflow → product capability → architecture → performance/scale |
| **Launch style** | Umbrella launch followed by product/use-case education over 2–3 weeks |

---

# 5. Proof & Advocates Plan

| Proof type | Proof available | Narrative job | Best use | Status / approval |
|---|---|---|---|---|
| Customer | Kernel agent-led incident triage | Makes agent-native workflow real | Launch page, blog, social, customer amplification | Confirm exact quote / approval |
| Product | MCP → logs, metrics, traces, alerts | Shows external agent access | Page, blog, demo, docs | Shipped |
| Product | Noz natural-language workflows | Shows AI as interface to observability | Page, blog, email, video | Confirm GA/current availability |
| Architecture | OpenTelemetry-native telemetry | Shows structured shared foundation | Page/blog/founder POV | Approved company positioning |
| Architecture | Validated dashboard schema / Perses | Shows dependable agent-created artifacts | Technical blog / engineer post | Verify current shipped state |
| Scale | ~2.4× telemetry in AI-native companies | Establishes AI-scale problem | Launch narrative / blog | Verify methodology / wording |
| Performance | 100K-span flame graph; unlimited waterfall; 75% fewer allocations | Concrete technical proof | Blog, page, engineer content | Verify exact current values |
| Economics | Predictable usage pricing | Connects telemetry growth to cost | Leadership / prospect narrative | Use without unsupported savings claims |

---

# 6. Distribution Surface Research

| Surface | Audience reached | Why relevant | Evidence / precedent | Decision |
|---|---|---|---|---|
| Website / launch page | Existing + new evaluators | Canonical narrative + conversion point | Used historically; standard across comparable launches | **Must** |
| Launch blog | Technical evaluators | Category reasoning + proof | Strong pattern across Dash0, New Relic, Weaviate, PlanetScale | **Must** |
| Docs / use-case guides | High-intent developers | Converts interest into usage | New Relic + Weaviate heavily reinforce via docs | **Must** |
| Email — customer | Existing users | Adoption | Existing SigNoz launch precedent | **Must** |
| Email — prospect | Qualified prospects | Evaluation | Existing precedent | **Should** |
| In-product / Pylon | Existing users | Direct adoption | Existing SigNoz precedent | **Must** |
| Company LinkedIn | Existing market audience | Announcement reach | Standard launch surface | **Must** |
| Founder / exec LinkedIn | Technical/leadership audience | Category POV / credibility | Dash0 founder-led POV is strong precedent | **Should** |
| Engineer / DevRel LinkedIn | Practitioner audience | Technical credibility | Strong fit for infrastructure | **Should** |
| Customer amplification | Borrowed technical trust | Extends reach beyond owned audience | PlanetScale-style customer proof; Kernel available | **Should / Test** |
| Partner / MCP ecosystem | Agent-tool users | High ICP overlap | New Relic uses partner integration reinforcement | **Test** |
| Community / Reddit | Practitioners | External discovery | Existing SigNoz precedent | **Test** |
| YouTube / technical video | Developers | Demonstrates workflow | Existing SigNoz precedent | **Should** |
| Technical creator | External practitioner audience | Borrowed reach | No internal performance evidence | **Test selectively** |
| Paid newsletter | Concentrated technical audience | Incremental reach | No internal evidence | **Test if ICP overlap is credible** |
| Paid social / TL ads | Expand reach of strongest POV | Scaled distribution | No internal evidence | **Test**, not default |

---

# 7. Promotion Coverage Plan

| Motion | Must | Should | Test | Not needed by default |
|---|---|---|---|---|
| Owned web | Launch/relevant page, blog, docs | Changelog / deeper use-case content | — | — |
| Lifecycle | Customer email / in-product | Prospect email | Segment-specific nurture | Broad generic database blast |
| Social | Company LinkedIn | Founder + technical-team POV | Thought-leadership paid amplification | Posting identical copy everywhere |
| Customer | Approved customer proof | Customer amplification kit | Additional advocate activation | Unapproved logos/quotes |
| Partner/ecosystem | — | — | MCP-client / integration amplification | Generic partner outreach |
| Community | — | — | 1–2 high-fit SRE/platform communities | Mass community posting |
| Creator | — | — | 1–2 technical creators | Large generic influencer program |
| Paid | — | — | Paid newsletter / TL ad where ICP fit is strong | Broad paid reach |

---

# 8. Phased Launch Tactics — Execution Brief for Agent 2

## 8.1 Pre-launch

| Motion | Tactic / deliverable | Audience | Surface | Priority | Narrative job | CTA | Proof needed | Owner type |
|---|---|---|---|---|---|---|---|---|
| Research | Final competitive teardown + source links | Internal PMM | Internal | **Must** | Validate narrative + tactics | — | External research | Agent 1 / PMM |
| Messaging | Final launch narrative / message hierarchy | Internal | Internal | **Must** | Align all assets | — | MRD + research | PMM |
| Customer proof | Confirm Kernel quote/use rights | External technical ICP | Customer | **Must** | Third-party credibility | — | Customer approval | PMM / Customer |
| Website | Launch page brief | Evaluators | Website | **Must** | Canonical umbrella story | Try MCP / Noz | Product + customer proof | PMM → Agent 2 |
| Content | Launch blog brief | Technical market | Blog | **Must** | Explain market shift + proof | Docs / Try | Technical proof | PMM → Agent 2 |
| Docs | MCP / Noz / use-case doc plan | High-intent users | Docs | **Must** | Enable adoption | Configure / Try | Technical details | PMM + DevRel |
| Lifecycle | Customer email brief | Existing users | Email | **Must** | Adoption | Try/configure | Use cases | PMM → Agent 2 |
| Lifecycle | Prospect email brief | Prospects | Email | **Should** | Evaluation | Read / Try | Narrative + proof | PMM → Agent 2 |
| Social | Founder POV brief | Market / leaders | LinkedIn | **Should** | Category POV | Read | Market shift | PMM → Agent 2 |
| Social | Engineer / DevRel brief | Practitioners | LinkedIn | **Should** | Technical credibility | Docs / Try | Workflow proof | PMM → Agent 2 |
| Amplification | Customer amplification kit | Borrowed audience | Customer social | **Should/Test** | External proof + reach | Read | Approved proof | PMM → Agent 2 |
| Ecosystem | Identify 3–5 MCP/client amplification opportunities | Agent-tool users | Ecosystem | **Test** | Reach expansion | Try | Integration relevance | PMM / Growth |
| Measurement | UTM + canonical destination plan | All tracked traffic | Tracking | **Must** | Make downstream learning possible | — | Naming convention | Agent 2 / Ops |
| Internal | Sales/support FAQ / internal briefing decision | GTM teams | Internal | **Should** | Readiness | — | Claims / availability | PMM |

## 8.2 Launch

| Motion | Tactic / deliverable | Audience | Surface | Priority | Narrative job | CTA | Proof needed | Owner type |
|---|---|---|---|---|---|---|---|---|
| Website | Publish launch page | Evaluators | Website | **Must** | Canonical story | Try MCP / Noz | All approved proof | Web |
| Content | Publish umbrella launch blog | Technical market | Blog | **Must** | Explain two AI shifts | Docs / Try | Product + scale proof | Content / PMM |
| Social | Company announcement | Technical ICP | LinkedIn | **Must** | Reach + announcement | Read / Try | Core launch proof | Social |
| Social | Founder / exec POV | Leaders + practitioners | LinkedIn | **Should** | Market/category POV | Read | Outside-in shift | Founder / PMM |
| Social | Engineer / DevRel technical post | Practitioners | LinkedIn | **Should** | Show workflow / technical depth | Docs / Try | Product proof | DevRel |
| Lifecycle | Customer email | Existing users | Email | **Must** | Adoption | Configure / use | Concrete workflows | Lifecycle |
| Lifecycle | Prospect email | Evaluators | Email | **Should** | Create interest | Read / Try | Market shift + proof | Lifecycle |
| Product | In-product / Pylon update | Existing users | Product | **Must** | Direct activation | Try feature | Availability | Product marketing |
| Customer | Kernel proof / amplification | External technical audience | Customer/social | **Should** | Trust | Read / Try | Approved quote | Customer + PMM |
| Ecosystem | MCP/client partner amplification | Agent-tool users | Partner | **Test** | Borrowed reach | Try | Integration fit | Partnerships |
| Video | Short workflow demo | Developers | YouTube/social | **Should** | Make capability tangible | Try / docs | Demo environment | DevRel |

## 8.3 Post-launch — Weeks 1–3

| Motion | Tactic / deliverable | Audience | Surface | Priority | Narrative job | CTA | Measurement |
|---|---|---|---|---|---|---|---|
| Use-case education | “Debug production from Claude Code/Cursor” | Developers | Blog/docs/social | **Must** | Workflow depth | Configure MCP | Views → UTM visits → activation |
| Use-case education | Incident-triage / Kernel workflow | SRE / Platform | Blog/social/video | **Should** | Customer proof | Try MCP | Exposure → visits |
| Product education | Noz workflow content | Existing + prospects | Blog/docs/social | **Must** | Adoption | Use Noz | Visits → product usage |
| Technical proof | AI-scale trace deep dive | AI-native engineers | Blog/engineer social | **Should** | Scale credibility | Explore trace UX | Visits / engagement |
| Customer | Re-share / customer-led content | External audience | Social | **Should/Test** | Borrowed trust | Read / Try | Incremental exposure / visits |
| Community | 1–2 relevant practitioner communities | SRE/platform/dev | Community | **Test** | External reach | Read / docs | Views → UTM visits |
| Creator | Workflow demo / technical discussion | Practitioner audience | Creator channels | **Test** | Borrowed reach | Try / docs | Exposure → UTM visits |
| Paid | Amplify best-performing POV / use-case | ICP | Paid social / newsletter | **Test** | Scale proven message | Visit / Try | Impressions → visits → signups |
| Internal | Sales/support reinforcement | GTM teams | Internal | **Should** | Equip conversations | — | Qualitative feedback |
| Learning handoff | Package actual metrics for Agent 3 | Internal | Data | **Must** | Close learning loop | — | Channel exposure + visits + signups |

---

# 9. Agent 2 Asset Brief

| Asset | Required? | Audience | Narrative job | Core message | Primary CTA | Timing |
|---|---|---|---|---|---|---|
| Launch page | **Must** | Evaluators | Canonical umbrella narrative | Agent-native + AI-scale on OTel foundation | Try MCP / Noz | Launch |
| Launch blog | **Must** | Technical market | Explain market shift + product proof | AI changes users + scale of telemetry | Docs / Try | Launch |
| Company LinkedIn | **Must** | Technical ICP | Announcement + reach | Four shipped capabilities under one direction | Read / Try | Launch |
| Founder LinkedIn POV | **Should** | Leaders + practitioners | Category POV | Observability has to change as software becomes agentic | Read | Launch |
| Engineer / DevRel LinkedIn | **Should** | Practitioners | Technical credibility | Concrete workflow / architecture | Docs / Try | Launch / +1 |
| Customer email | **Must** | Existing users | Adoption | Here is what you can do now | Configure / use | Launch |
| Prospect email | **Should** | Prospects | Evaluation | Why AI-era observability matters | Read / Try | Launch / +1–2 |
| Customer amplification kit | **Test / Should** | Kernel/customer audience | Third-party proof | Real incident workflow | Read / Try | Launch/+1 |
| Technical video | **Should** | Developers | Demonstrate workflow | Agent queries real telemetry | Try | Launch/+1 week |
| Partner/community package | **Test** | External audiences | Reach expansion | Adapted use-case story | Read / Try | +1–3 weeks |

**Agent 2 rule:** Do not change the strategy. Execute the approved narrative, proof hierarchy, audience, CTA and distribution choices.

---

# 10. Reach Expansion Plan

| Lever | Why it can add incremental reach | Recommendation | Measurement |
|---|---|---|---|
| Kernel/customer amplification | Reaches a trusted external technical audience | **Should** | Customer-post exposure → UTM visits |
| MCP ecosystem/client adjacency | High relevance to Claude Code/Cursor/Codex users | **Test** | Partner exposure → UTM visits |
| Founder / technical-team POV | Adds personal credibility beyond company feed | **Should** | Impressions → UTM visits |
| High-fit SRE/platform communities | Reaches practitioners outside owned audience | **Test** | Post views → UTM visits |
| Technical creators | Borrowed practitioner trust | **Test selectively** | Views/impressions → UTM visits |
| Paid newsletter | Concentrated technical ICP possible | **Test if fit is strong** | Delivered/opens → UTM visits |
| Thought-leadership paid amplification | Scales a message proven organically | **Test after organic signal** | Impressions → visits → signups |

---

# 11. Internal / Field / Partner Enablement Check

| Enablement item | Decision | Why |
|---|---|---|
| Internal launch brief | **Must** | Align product, marketing, sales/support on shipped claims |
| Sales FAQ / objection handling | **Should** | “MCP is table stakes,” “is this autonomous?” and “is this only LLM obs?” will arise |
| Support / CS briefing | **Should** | Existing-user adoption is part of the motion |
| Product docs | **Must** | Launch interest must convert into setup |
| Demo / demo script | **Should** | Workflow is easier to understand when demonstrated |
| Partner briefing | **Test / as needed** | Only if MCP/client ecosystem amplification is real |
| Pricing / packaging FAQ | **Only if launch changes packaging** | Do not create unnecessary collateral |
| Analyst / press outreach | **Not default** | Only if there is a credible Tier-1 external story + relationship |

---

# 12. Open Questions / Human Approval Gates

| Gate | Required before |
|---|---|
| Confirm current MCP / Noz adoption baseline | Final measurement plan |
| Confirm current Noz availability / GA vs preview | Publishing any asset |
| Confirm Kernel quote, logo and workflow usage rights | Customer-proof assets |
| Verify 2.4× telemetry claim wording/methodology | Public launch content |
| Verify trace-scale / memory performance claims | Public launch content |
| Confirm primary CTA + destination URLs | Agent 2 generates final tracked URLs |
| Confirm UTM naming convention | Distribution execution |
| Confirm 3–5 realistic ecosystem/community opportunities | Reach-expansion execution |
| Human approves MRD + Launch Plan | Agent 2 execution starts |

---

## Final handoff

**Agent 1 output → Agent 2 input**

Agent 2 receives:
1. approved MRD;
2. this Launch Plan;
3. approved proof / claims;
4. customer approvals;
5. required/optional asset table;
6. CTA + canonical destinations;
7. distribution decisions;
8. tracking conventions.

> **Agent 1 decides. Agent 2 executes + verifies. Agent 3 measures + learns.**
