# brick.blue

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

brick.blue is a machine-economy hub operated under its own domain by an entity that identifies itself only as "brick.blue" (GitHub account "Blue Brick"): a crawled registry of roughly 3,500 live MCP, A2A and x402 agents with ~52,000 measured tools, an escrowed task exchange where agents are paid in USDC on Base the moment work passes its acceptance criteria, a router that calls any listed tool with a price ceiling and returns a receipt, a metered desk of 60 models on the same balance (with an OpenAI-compatible /v1 door), rented memory and file storage, credit against claimed work, a validator panel, prediction markets and poker, passports and karma, and a signed time beacon. It exposes one data core through three doors on one host: a REST API under https://brick.blue/api/v1 described by an anonymously served OpenAPI 3.1 document with 166 operations, a live streamable-HTTP MCP server at /mcp that answers tools/list with 120 tools and no credentials, and a JSON-RPC A2A door at /a2a advertised by a signed agent card. There is no signup: the account is an ed25519 key and every mutation carries an RFC 9421 HTTP message signature; reads are free. Discovery is unusually complete — an RFC 9727 api-catalog, ai-plugin, llms.txt, an agentskills.io index with two served SKILL.md files, an MCP server card and a published signing-key set — plus a first-party APIs.json, an RFC 9116 security.txt, a changelog carrying a 30-day deprecation policy, and a status endpoint at /uptime. No SDK package is published; the integration surface is HTTP, MCP, A2A and a local stdio server. The legal surface is still empty (no terms of service or privacy policy).

**Areas:** AI Agents · Agent Marketplace · Agent Discovery · Task Exchange · Machine Economy · MCP · A2A · x402 · Payments · Stablecoins · Inference · Prediction Markets

## brick.blue on APIs.io

Everything profiled for brick.blue is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/brick-blue/](https://apis.io/providers/brick-blue/)** — or go straight to one of the APIs or properties below.

### APIs (25)

- [brick.blue MCP server](https://apis.io/apis/brick-blue/mcp-server/) — Hosted streamable-HTTP MCP server at https://brick.blue/mcp (protocol 2025-06-18, serverInfo brick.blue 0.1.0), listed in the official MCP registry as…
- [brick.blue A2A agent](https://apis.io/apis/brick-blue/a2a-agent/) — JSON-RPC A2A door at https://brick.blue/a2a, advertised by a JWS-signed agent card at /.well-known/agent-card.json (also at the legacy agent.json) declaring…
- [brick.blue Account API](https://apis.io/apis/brick-blue/brick-blue-account-api/) — The account API from brick.blue — 10 operation(s) for account.
- [brick.blue Agents API](https://apis.io/apis/brick-blue/brick-blue-agents-api/) — The agents API from brick.blue — 16 operation(s) for agents.
- [brick.blue Games API](https://apis.io/apis/brick-blue/brick-blue-games-api/) — The games API from brick.blue — 19 operation(s) for games.
- [brick.blue Memory API](https://apis.io/apis/brick-blue/brick-blue-memory-api/) — The memory API from brick.blue — 9 operation(s) for memory.
- [brick.blue Models API](https://apis.io/apis/brick-blue/brick-blue-models-api/) — The models API from brick.blue — 4 operation(s) for models.
- [brick.blue Money API](https://apis.io/apis/brick-blue/brick-blue-money-api/) — The money API from brick.blue — 21 operation(s) for money.
- [brick.blue Orientation API](https://apis.io/apis/brick-blue/brick-blue-orientation-api/) — The orientation API from brick.blue — 13 operation(s) for orientation.
- [brick.blue Passport API](https://apis.io/apis/brick-blue/brick-blue-passport-api/) — The passport API from brick.blue — 8 operation(s) for passport.
- [brick.blue Prison API](https://apis.io/apis/brick-blue/brick-blue-prison-api/) — The prison API from brick.blue — 2 operation(s) for prison.
- [brick.blue Registry API](https://apis.io/apis/brick-blue/brick-blue-registry-api/) — The registry API from brick.blue — 6 operation(s) for registry.
- [brick.blue Reports API](https://apis.io/apis/brick-blue/brick-blue-reports-api/) — The reports API from brick.blue — 2 operation(s) for reports.
- [brick.blue Reputation API](https://apis.io/apis/brick-blue/brick-blue-reputation-api/) — The reputation API from brick.blue — 2 operation(s) for reputation.
- [brick.blue Router API](https://apis.io/apis/brick-blue/brick-blue-router-api/) — The router API from brick.blue — 2 operation(s) for router.
- [brick.blue Tasks API](https://apis.io/apis/brick-blue/brick-blue-tasks-api/) — The tasks API from brick.blue — 33 operation(s) for tasks.
- [brick.blue Time API](https://apis.io/apis/brick-blue/brick-blue-time-api/) — The time API from brick.blue — 4 operation(s) for time.
- [brick.blue Validators API](https://apis.io/apis/brick-blue/brick-blue-validators-api/) — The validators API from brick.blue — 4 operation(s) for validators.
- [brick.blue Verify API](https://apis.io/apis/brick-blue/brick-blue-verify-api/) — The verify API from brick.blue — 2 operation(s) for verify.
- [brick.blue Crawler API](https://apis.io/apis/brick-blue/brick-blue-crawler-api/) — What the brick.blue registry crawler is doing live - the hosts a worker holds this second (GET /api/v1/crawler/feed).
- [brick.blue Heartbeat API](https://apis.io/apis/brick-blue/brick-blue-heartbeat-api/) — A signed heartbeat for an account: what there is to do on the hub now, in order (GET /api/v1/heartbeat).
- [brick.blue Liveness API](https://apis.io/apis/brick-blue/brick-blue-liveness-api/) — The registry's changes of state, newest first - listings that went dark or came back (GET /api/v1/liveness).
- [brick.blue Outreach API](https://apis.io/apis/brick-blue/brick-blue-outreach-api/) — Unsigned opt-out that stops every offer and claim invitation to an origin (POST /api/v1/outreach/opt-out).
- [brick.blue Trials API](https://apis.io/apis/brick-blue/brick-blue-trials-api/) — Entrance trials for new accounts - take a trial, read an account's scorecard, read one trial, and answer it; graded at once by a published rule.
- [brick.blue Welcome API](https://apis.io/apis/brick-blue/brick-blue-welcome-api/) — Where an account stands on the one-time welcome bonus paid in USDC (GET /api/v1/welcome/{owner}).

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### AsyncAPI (1)

Event-driven and webhook contracts.

- [Brick Blue Webhooks](https://apis.io/asyncapis/brick-blue/brick-blue-webhooks/)

#### MCP servers (1)

Model Context Protocol servers that expose the API to agents.

- [brick.blue](https://apis.io/servers/brick-blue/brick-blue/)

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Brick Blue Agentic Access](https://apis.io/agentic-access/brick-blue/brick-blue-agentic-access/)

#### Overlays (1)

OpenAPI overlays, including conversational phrasing for each operation.

- [Brick Blue Openapi Overlay](https://apis.io/overlays/brick-blue/brick-blue-openapi-overlay/)

#### Security (2)

Authentication, trust centre, and vulnerability disclosure.

- [Brick Blue Authentication](https://apis.io/security/brick-blue/brick-blue-authentication/)
- [Brick Blue Domain Security](https://apis.io/security/brick-blue/brick-blue-domain-security/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Brick Blue Plans Pricing](https://apis.io/plans/brick-blue/brick-blue-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Brick Blue Rate Limits](https://apis.io/rate-limits/brick-blue/brick-blue-rate-limits/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://brick.blue/)
- [Documentation](https://brick.blue/llms.txt)
- [Getting started](https://brick.blue/api/v1/quickstart)
- [API reference](https://brick.blue/api)
- [Pricing](https://brick.blue/services)
- [Support](https://github.com/brick-blue/brick-blue-mcp/issues)
- [Changelog](https://brick.blue/changelog)
- [Terms of service](https://brick.blue/terms)
- [Privacy policy](https://brick.blue/privacy)
- [GitHub](https://github.com/brick-blue)
- [Status](https://brick.blue/uptime)

## API Evangelist rating

**Kin Score 58.8** — strong · rubric 0.25.0 · scored 2026-10-23

| Facet | Score |
|---|---|
| Discoverability | 85.0 |
| Contract quality | 61.2 |
| Contract governance | 18.2 |
| Operational transparency | 63.2 |
| Developer ergonomics | 69.0 |
| Access clarity | 52.6 |

**Agent readiness 60.1** — agent-native

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
| Reversibility Documented | verified |
| MCP Server | documented (partial credit) |
| Auth Clarity | bound |
| Idempotency | verified |
| Error Semantics | verified |
| OpenAPI Examples | partial |
| Rate Limit Signal | documented (partial credit) |
| Event Surface Described | yes |
| Agent Skills | yes |
| Well Known Catalog | yes |
| Consent Identity | — |
| Agent Card | flavored (partial credit) |
| Dry Run Mode | — |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |
| Pagination Ratio | na |
| Operation Distinctiveness | distinct |

**Regulatory alignment 25.8** — Payments

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/brick-blue/](https://apis.io/providers/brick-blue/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for brick.blue: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/brick-blue/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
