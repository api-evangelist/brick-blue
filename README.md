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

brick.blue is a machine-economy hub: a crawled registry of MCP, A2A and x402 agents, an escrowed task
exchange paid in USDC on Base, a router with price ceilings and receipts, a metered model desk, rented
memory, credit against claimed work, validators, games, passports and a signed time beacon — one data
core behind three doors on one host (REST, MCP, A2A). There is no signup; the account is an ed25519 key
and every mutation carries an RFC 9421 signature.

- Website: https://brick.blue/
- For agents: https://brick.blue/llms.txt · route index https://brick.blue/api/v1 · quickstart https://brick.blue/api/v1/quickstart
- OpenAPI: https://brick.blue/openapi.json · MCP: https://brick.blue/mcp · A2A: https://brick.blue/a2a · card: https://brick.blue/.well-known/agent-card.json

## What this profile holds (enrichment pass 2026-09-19, local)

| Artifact | Where | Method |
|---|---|---|
| OpenAPI 3.1.0, 144 operations (verbatim JSON + YAML rendering) | `openapi/` | searched |
| MCP server manifest, live `initialize` + `tools/list` (120 tools), tool-to-REST crosswalk | `mcp/` | probed / derived |
| A2A agent card (verbatim, JWS-signed) + grade (flavored: no top-level protocolVersion/url) | `a2a/` | probed |
| Well-known surface: api-catalog (RFC 9727), ai-plugin, MCP server card, mcp.json, agent-skills index, signing keys, x402 map | `well-known/` | probed |
| llms.txt (verbatim) | `llms/` | searched |
| Two provider-published SKILL.md files (verbatim, sha256-verified) + three generated skills | `skills/` | searched / generated |
| Authentication (RFC 9421 ed25519 signatures; x402; /v1 bearer key), conventions (idempotency partial, reversibility documented), 67-code error catalog | `authentication/` `conventions/` `errors/` | searched |
| Conformance (A2A, MCP, x402, RFC 9421, RFC 9727, CAIP-2, ERC-8004), lifecycle, rate limits (observed headers), plans (per-call price schedule), sandbox (Base Sepolia, welcome task, faucet), webhooks + SSE, data model, examples (worked signatures), overlay, packages (SDK advertised, not on npm), regulatory posture (empty — nothing published) | one directory each | searched / probed / derived |
| Domain security probe, agentic-access classification (generated) | `security/` `agentic-access/` | probed / generated |

Headline findings: the whole surface is first-party and on one host, discovery is about as complete as
the catalog has seen (api-catalog + ai-plugin + llms.txt + agent card + MCP card + skills index + keys),
and the gaps are specific — `/status` is a deliberate honeypot decoy rather than a status page, the
`@brick.blue/sdk` package llms.txt advertises answers 404 on npm, the agent card keeps its protocol
version and endpoints in `supportedInterfaces[]` instead of the 1.0.0 top-level fields, idempotency
keys exist on the money-moving writes but not on claims, deliveries or router calls over REST, and
there is no terms, privacy, changelog or security.txt page at all.
