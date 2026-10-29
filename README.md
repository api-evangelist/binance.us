# Binance.US

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

Binance.US (operated by BAM Trading Services, Inc.) is a U.S.-regulated digital asset marketplace offering spot trading, staking, OTC and custodial services across 100+ cryptocurrencies. Its public developer program exposes a signed REST API at api.binance.us covering exchange and system information, market and trade data, user account data, spot order management (including OCO and cancel-replace), wallet deposits and withdrawals, dust conversion, referrals, staking, OTC quoting, Custodial Solution and Credit Line endpoints, plus a functionally equivalent WebSocket API and real-time WebSocket market-data and user-data streams. Authentication is HMAC SHA-256 request signing with an X-MBX-APIKEY header, and the platform publishes a full error-code registry, symbol/exchange filter rules, weighted IP and order rate limits, and a dated changelog in its official GitHub documentation repository.

**Areas:** Company · Cryptocurrency · Digital Assets · Exchange · Trading · Market Data · Financial Services · WebSocket · Custody · Staking · Real-Time

## Binance.US on APIs.io

Everything profiled for Binance.US is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/binance.us/](https://apis.io/providers/binance.us/)** — or go straight to one of the APIs or properties below.

### APIs (3)

- [Binance.US REST API](https://apis.io/apis/binance.us/rest-api/) — The Binance.US REST API is the primary programmatic interface to the exchange. It exposes general system and exchange information, market and trade data…
- [Binance.US WebSocket API](https://apis.io/apis/binance.us/websocket-api/) — The Binance.US WebSocket API is a request/response API delivered over a persistent WebSocket connection at wss://ws-api.binance.us/ws-api/v3. It is…
- [Binance.US WebSocket Streams](https://apis.io/apis/binance.us/websocket-streams/) — Binance.US WebSocket Streams deliver real-time market data and account events over persistent WebSocket connections at wss://stream.binance.us:9443. Market…

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### AsyncAPI (2)

Event-driven and webhook contracts.

- [Binance.US WebSocket API](https://apis.io/asyncapis/binance.us/binance.us-websocket-api-asyncapi/)
- [Binance.US WebSocket Streams](https://apis.io/asyncapis/binance.us/binance.us-websocket-streams-asyncapi/)

#### Event channels (14)

Individual events and webhooks the provider emits.

- [{listenKey}](https://apis.io/channels/binance.us/listenkey/)
- [!miniTicker@arr](https://apis.io/channels/binance.us/miniticker-arr/)
- [{symbol}@aggTrade](https://apis.io/channels/binance.us/symbol-aggtrade/)
- [{symbol}@bookTicker](https://apis.io/channels/binance.us/symbol-bookticker/)
- [{symbol}@depth](https://apis.io/channels/binance.us/symbol-depth/)
- [{symbol}@depth{levels}](https://apis.io/channels/binance.us/symbol-depth-levels/)
- [{symbol}@kline_{interval}](https://apis.io/channels/binance.us/symbol-kline-interval/)
- [{symbol}@miniTicker](https://apis.io/channels/binance.us/symbol-miniticker/)
- [{symbol}@ticker](https://apis.io/channels/binance.us/symbol-ticker/)
- [{symbol}@ticker_{windowSize}](https://apis.io/channels/binance.us/symbol-ticker-windowsize/)
- [{symbol}@trade](https://apis.io/channels/binance.us/symbol-trade/)
- [!ticker@arr](https://apis.io/channels/binance.us/ticker-arr/)
- [!ticker_{windowSize}@arr](https://apis.io/channels/binance.us/ticker-windowsize-arr/)
- [/ws-api/v3](https://apis.io/channels/binance.us/ws-api-v3/)

#### Security (4)

Authentication, trust centre, and vulnerability disclosure.

- [Binance.Us Authentication](https://apis.io/security/binance.us/binance.us-authentication/)
- [Binance.Us Domain Security](https://apis.io/security/binance.us/binance.us-domain-security/)
- [Binance.Us Trust Center](https://apis.io/security/binance.us/binance.us-trust-center/)
- [Binance.Us Vulnerability Disclosure](https://apis.io/security/binance.us/binance.us-vulnerability-disclosure/)

#### Rate limits (1)

Published request limits.

- [Binance.Us Rate Limits](https://apis.io/rate-limits/binance.us/binance.us-rate-limits/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://www.binance.us)
- [Documentation](https://docs.binance.us/)
- [Getting started](https://docs.binance.us/#introduction)
- [API reference](https://docs.binance.us/#rest-api)
- [Pricing](https://www.binance.us/fees)
- [Sign up](https://www.binance.us/register)
- [Support](https://support.binance.us/en)
- [Blog](https://blog.binance.us/)
- [Security](https://www.binance.us/.well-known/security.txt)
- [Compliance](https://www.binance.us/compliance)
- [Terms of service](https://www.binance.us/terms-of-use)
- [Privacy policy](https://www.binance.us/privacy-policy)
- [GitHub](https://github.com/binance-us)
- [Status](https://www.binance.us/status)

## API Evangelist rating

**Kin Score 49.9** — developing · rubric 0.25.0 · scored 2026-10-23

| Facet | Score |
|---|---|
| Discoverability | 78.6 |
| Contract quality | 42.2 |
| Contract governance | 18.2 |
| Operational transparency | 44.7 |
| Developer ergonomics | 47.6 |
| Access clarity | 60.5 |

**Agent readiness 21.9** — agent-aware

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | — |
| Reversibility Documented | — |
| MCP Server | — |
| Auth Clarity | bearer (partial credit) |
| Idempotency | — |
| Error Semantics | documented (partial credit) |
| OpenAPI Examples | — |
| Rate Limit Signal | documented (partial credit) |
| Event Surface Described | derived (partial credit) |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |
| Pagination Ratio | na |
| Operation Distinctiveness | na |

**Regulatory alignment 33.3** — Securities & Market Data

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/binance.us/](https://apis.io/providers/binance.us/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Binance.US: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/binance.us/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
