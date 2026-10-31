# OptionsAhoy

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

AlphaLatitude Inc. is a Sunnyvale, California C-corporation (founded March 2026) that builds OptionsAhoy, an equity-compensation optimization product for individual investors: multi-year, multi-state tax planning for incentive stock options and the alternative minimum tax, non-qualified stock options, restricted stock units, qualified small business stock, single-stock concentration, protective-put and collar hedging, and selling equity to fund a cash goal. The paid platform is an invite-only beta; the eight calculators behind it are published free and keyless as in-browser tools and as three agent surfaces on one host — an 11-operation OpenAPI 3.1.0 REST API at https://optionsahoy.com/api/v1, a remote MCP server at https://optionsahoy.com/mcp (eight annotated tools, also shipped as the optionsahoy-mcp npm stdio package and a Claude Desktop bundle), and an A2A 0.3.0 agent card at /.well-known/agent-card.json with eight skills. The engine is deterministic (no model inference) and the provider publishes a verification page reproducing its federal and state tax math against IRS Rev. Proc. 2025-32, PSL Tax-Calculator and OpenTaxSolver.

**Areas:** Equity Compensation · Tax · Stock Options · Financial Planning · Personal Finance · Fintech · Calculators · MCP · A2A · Agent-Native · Deterministic · United States

## OptionsAhoy on APIs.io

Everything profiled for OptionsAhoy is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/optionsahoy-com/](https://apis.io/providers/optionsahoy-com/)** — or go straight to one of the APIs or properties below.

### APIs (11)

- [OptionsAhoy MCP Server](https://apis.io/apis/optionsahoy-com/optionsahoy-mcp-server/) — Remote Model Context Protocol server at https://optionsahoy.com/mcp (Streamable HTTP, protocol version 2024-11-05, serverInfo OptionsAhoy 1.10.2, no…
- [OptionsAhoy Equity Planner (A2A Agent)](https://apis.io/apis/optionsahoy-com/optionsahoy-a2a-agent/) — Agent2Agent (A2A) protocol surface: an agent card served from https://optionsahoy.com/.well-known/agent-card.json (protocolVersion 0.3.0, JSONRPC transport,…
- [OptionsAhoy Concentration API](https://apis.io/apis/optionsahoy-com/optionsahoy-com-concentration-api/) — Single-stock concentration risk
- [OptionsAhoy Discovery API](https://apis.io/apis/optionsahoy-com/optionsahoy-com-discovery-api/) — API inventory
- [OptionsAhoy Equity Funding API](https://apis.io/apis/optionsahoy-com/optionsahoy-com-equityfunding-api/) — Goal-funded equity-to-cash liquidation planning
- [OptionsAhoy Hedging API](https://apis.io/apis/optionsahoy-com/optionsahoy-com-hedging-api/) — Protective put, collar, and put spread pricing
- [OptionsAhoy ISO API](https://apis.io/apis/optionsahoy-com/optionsahoy-com-iso-api/) — Incentive stock options
- [OptionsAhoy NSO API](https://apis.io/apis/optionsahoy-com/optionsahoy-com-nso-api/) — Non-qualified stock options
- [OptionsAhoy QSBS API](https://apis.io/apis/optionsahoy-com/optionsahoy-com-qsbs-api/) — Section 1202 qualification
- [OptionsAhoy RSU API](https://apis.io/apis/optionsahoy-com/optionsahoy-com-rsu-api/) — Restricted stock units
- [OptionsAhoy Rsu Lot Optimize API](https://apis.io/apis/optionsahoy-com/optionsahoy-com-rsulotoptimize-api/) — The RsuLotOptimize API from OptionsAhoy — 1 operation(s) for rsulotoptimize.

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### MCP servers (1)

Model Context Protocol servers that expose the API to agents.

- [optionsahoy-com-mcp.yml](https://apis.io/servers/optionsahoy-com/optionsahoy-com-mcp-yml/)

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Optionsahoy Com Agentic Access](https://apis.io/agentic-access/optionsahoy-com/optionsahoy-com-agentic-access/)

#### Overlays (1)

OpenAPI overlays, including conversational phrasing for each operation.

- [Optionsahoy Com Openapi Overlay](https://apis.io/overlays/optionsahoy-com/optionsahoy-com-openapi-overlay/)

#### Security (3)

Authentication, trust centre, and vulnerability disclosure.

- [Optionsahoy Com Authentication](https://apis.io/security/optionsahoy-com/optionsahoy-com-authentication/)
- [Optionsahoy Com Domain Security](https://apis.io/security/optionsahoy-com/optionsahoy-com-domain-security/)
- [Optionsahoy Com Vulnerability Disclosure](https://apis.io/security/optionsahoy-com/optionsahoy-com-vulnerability-disclosure/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Optionsahoy Com Plans Pricing](https://apis.io/plans/optionsahoy-com/optionsahoy-com-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Optionsahoy Com Rate Limits](https://apis.io/rate-limits/optionsahoy-com/optionsahoy-com-rate-limits/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://optionsahoy.com/)
- [Documentation](https://optionsahoy.com/for-agents)
- [Getting started](https://optionsahoy.com/use-from-ai-assistants)
- [API reference](https://optionsahoy.com/for-agents/api)
- [Pricing](https://optionsahoy.com/for-agents)
- [Support](https://github.com/AlvisoOculus/optionsahoy-mcp/issues)
- [Changelog](https://optionsahoy.com/for-agents)
- [Terms of service](https://optionsahoy.com/terms)
- [Privacy policy](https://optionsahoy.com/privacy)
- [GitHub](https://github.com/AlvisoOculus)

## API Evangelist rating

**Kin Score 53.9** — developing · rubric 0.25.0 · scored 2026-10-23

| Facet | Score |
|---|---|
| Discoverability | 75.0 |
| Contract quality | 50.7 |
| Contract governance | 18.2 |
| Operational transparency | 28.9 |
| Developer ergonomics | 72.6 |
| Access clarity | 52.6 |

**Agent readiness 50.2** — agent-ready (gated down from agent-native)

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | yes |
| Reversibility Documented | — |
| MCP Server | documented (partial credit) |
| Auth Clarity | bearer (partial credit) |
| Idempotency | documented (partial credit) |
| Error Semantics | derived (partial credit) |
| OpenAPI Examples | verified |
| Rate Limit Signal | documented (partial credit) |
| Event Surface Described | — |
| Agent Skills | yes |
| Well Known Catalog | — |
| Consent Identity | yes |
| Agent Card | conformant |
| Dry Run Mode | — |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |
| Pagination Ratio | na |
| Operation Distinctiveness | distinct |

**Regulatory alignment 38.2** — Horizontal (data, software, accessibility, platform)

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/optionsahoy-com/](https://apis.io/providers/optionsahoy-com/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for OptionsAhoy: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/optionsahoy-com/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
