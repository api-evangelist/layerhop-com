# LayerHop

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

LayerHop is a non-custodial cross‑chain swapping platform that lets users move assets across 71 blockchain networks. It aggregates quotes from providers like Jupiter, Relay, deBridge and others, showing fees, routes and execution times. Users sign transactions directly from their wallets, and the service charges a small fee (0.10‑0.15%). The platform also offers a REST API and SDKs for developers to integrate swapping functionality.

**Areas:** Blockchain · Swapping · Cross-chain · DeFi · Non-custodial

## LayerHop on APIs.io

Everything profiled for LayerHop is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/layerhop-com/](https://apis.io/providers/layerhop-com/)** — or go straight to one of the APIs or properties below.

### APIs (37)

- [LayerHop Admin API](https://apis.io/apis/layerhop-com/layerhop-com-admin-api/) — Operator-only partner registry, fee ledger and business reports (D-020). Every admin route returns 404 unless the operator sets `ADMIN_TOKEN` or the owner…
- [LayerHop Alerts API](https://apis.io/apis/layerhop-com/layerhop-com-alerts-api/) — Telegram alerts from the web app (D-040): the app parks a price or followed-wallet alert as a short-lived draft and opens the LayerHop Telegram bot with…
- [LayerHop Assets API](https://apis.io/apis/layerhop-com/layerhop-com-assets-api/) — Chains, tokens, USD prices and wallet balances: every chain and token LayerHop's providers can route, for chain and token pickers and balance displays.
- [LayerHop Auth API](https://apis.io/apis/layerhop-com/layerhop-com-auth-api/) — Wallet sign-in (SIWE for EVM, the same message format for Solana) for the developer dashboard. Sets an HttpOnly `lh_session` cookie. These routes exist only…
- [LayerHop Checkout API](https://apis.io/apis/layerhop-com/layerhop-com-checkout-api/) — Pay with any token: a merchant creates a checkout session (an amount in USDC or USDT on one chain, paid to their address) and shares its hosted link. The…
- [LayerHop Dashboard API](https://apis.io/apis/layerhop-com/layerhop-com-dashboard-api/) — Developer dashboard: API keys, usage, request logs, orders, webhooks and the partner profile. Every route needs the `lh_session` cookie (401 otherwise).…
- [LayerHop Deposit addresses API](https://apis.io/apis/layerhop-com/layerhop-com-deposit-addresses-api/) — Swap or bridge by sending tokens to an address, without connecting a wallet (beta). Each deposit becomes an order (`quoteId` starting with `dep_`,…
- [LayerHop Discovery API](https://apis.io/apis/layerhop-com/layerhop-com-discovery-api/) — Public, read-only discovery data: the cross-chain price gap radar, the new chain radar and the unclaimed airdrop checker.
- [LayerHop Earn API](https://apis.io/apis/layerhop-com/layerhop-com-earn-api/) — Fund any app and the stablecoin yield router: where popular apps' deposits land (`GET /v1/fund/targets`), a user's Polymarket bridge address, current USDC /…
- [LayerHop Ecosystem API](https://apis.io/apis/layerhop-com/layerhop-com-ecosystem-api/) — "Built on LayerHop" (layerhop.com/ecosystem): projects submit themselves; an admin reviews each submission before it is listed. Public, no key.
- [LayerHop Gas station API](https://apis.io/apis/layerhop-com/layerhop-com-gas-station-api/) — Refuel up to 10 chains with native gas from one transaction (source: Gas.zip). Off unless the deployment sets `GAS_STATION_ENABLED=1`; every route answers…
- [LayerHop Internal API](https://apis.io/apis/layerhop-com/layerhop-com-internal-api/) — Used by layerhop.com itself, not part of the supported API: no SDK method, no Postman entry, and it may change without notice. Exists only when the operator…
- [LayerHop Invoices API](https://apis.io/apis/layerhop-com/layerhop-com-invoices-api/) — Bill a customer by email: line items in a settlement stablecoin, a hosted invoice page (`https://layerhop.com/invoice/{id}`) where they pay with any token…
- [LayerHop Launch API](https://apis.io/apis/layerhop-com/layerhop-com-launch-api/) — LayerHop Launch (D-039): metadata and images LayerHop hosts for Solana tokens created on app.layerhop.com. The Create page uploads the token's name, symbol,…
- [LayerHop Limit orders API](https://apis.io/apis/layerhop-com/layerhop-com-limit-orders-api/) — Limit orders (beta): sell a token once it reaches your price, with an optional expiry. On Solana through Jupiter Trigger (on-chain order, partial fills); on…
- [LayerHop Market data API](https://apis.io/apis/layerhop-com/layerhop-com-market-data-api/) — Market data for **Berachain** and **Robinhood Chain** from LayerHop's own indexer, read from the chain (Kodiak v2 / v3 and BEX on Berachain; Uniswap v2 / v3…
- [LayerHop Meta API](https://apis.io/apis/layerhop-com/layerhop-com-meta-api/) — Liveness.
- [LayerHop Orders API](https://apis.io/apis/layerhop-com/layerhop-com-orders-api/) — Build, submit and track the transaction for a quote.
- [LayerHop Partner program API](https://apis.io/apis/layerhop-com/layerhop-com-partner-program-api/) — Apply to the LayerHop partner program (layerhop.com/partners): wallets, apps, bots and communities that want to send swaps through LayerHop. Public, no key.…
- [LayerHop Pay links API](https://apis.io/apis/layerhop-com/layerhop-com-pay-links-api/) — Personal pay links (`https://layerhop.com/to/<name>`): anyone pays a person from any chain and token; the person receives their preferred token on their…
- [LayerHop Payouts API](https://apis.io/apis/layerhop-com/layerhop-com-payouts-api/) — Bulk payouts: pay up to 100 people from one wallet and one token. The API checks and groups the rows and builds same-chain transfer batches; every…
- [LayerHop Plans API](https://apis.io/apis/layerhop-com/layerhop-com-plans-api/) — Paid developer plans (Free, Pro, Scale; names, prices and limits are set by the operator). **Off unless the operator runs the API with `PLANS_LIVE=1`**:…
- [LayerHop Quotes API](https://apis.io/apis/layerhop-com/layerhop-com-quotes-api/) — Ask every provider for a price.
- [LayerHop Recover API](https://apis.io/apis/layerhop-com/layerhop-com-recover-api/) — Stuck native-bridge withdrawals: Arbitrum One / Nova and OP Stack withdrawals to Ethereum whose second step (Arbitrum: claim; OP Stack: prove, then…
- [LayerHop Recurring orders API](https://apis.io/apis/layerhop-com/layerhop-com-recurring-orders-api/) — Solana recurring buys through Jupiter Recurring (beta): deposit a budget once and Jupiter buys a token with it at a fixed interval (every day, every week,…
- [LayerHop Referrals API](https://apis.io/apis/layerhop-com/layerhop-com-referrals-api/) — Referral attribution (D-038): a quote can name the wallet that referred the user (`referrer`), and the order built from it records that wallet. Referrals…
- [LayerHop Safety API](https://apis.io/apis/layerhop-com/layerhop-com-safety-api/) — Community safety tools: explain a transaction or signature request before signing it (`POST /v1/preview`, read-only simulation) and community scam reports…
- [LayerHop Social API](https://apis.io/apis/layerhop-com/layerhop-com-social-api/) — Copy trading and swap by reply (D-046): a public feed of swaps by wallets that opted in with a signed message, and the Farcaster bot's webhook. Every swap…
- [LayerHop Splits API](https://apis.io/apis/layerhop-com/layerhop-com-splits-api/) — Split the bill (`https://layerhop.com/split/<id>`): one person is owed a total in one token on one chain; each participant pays their share from any chain…
- [LayerHop Status API](https://apis.io/apis/layerhop-com/layerhop-com-status-api/) — Public platform status, the data behind status.layerhop.com.
- [LayerHop Subscriptions API](https://apis.io/apis/layerhop-com/layerhop-com-subscriptions-api/) — Recurring billing in crypto. A wallet can't be charged automatically, so each period LayerHop issues an invoice for the subscription and emails its pay…
- [LayerHop Tip jars API](https://apis.io/apis/layerhop-com/layerhop-com-tip-jars-api/) — Tip jar counters for the embeddable "Tip me in crypto" card (`https://layerhop.com/tip/<name>`): how many wallets tipped an address through a tip jar.…
- [LayerHop Track API](https://apis.io/apis/layerhop-com/layerhop-com-track-api/) — "Where's my money?": look up any bridge or aggregator transfer by its source transaction (EVM hash or Solana signature), not only LayerHop orders. Detects…
- [LayerHop Transparency API](https://apis.io/apis/layerhop-com/layerhop-com-transparency-api/) — Public, aggregate-only data about how LayerHop's routes perform: per provider, how fills compared with their quotes and how our quotes compared with each…
- [LayerHop Usage API](https://apis.io/apis/layerhop-com/layerhop-com-usage-api/) — Usage and errors of the API key's own account and mode, per hour or day: request counts by endpoint group and status class, p50 / p95 latency, error-code…
- [LayerHop Webhooks API](https://apis.io/apis/layerhop-com/layerhop-com-webhooks-api/) — Developer tools for webhooks with an API key: stream your account's events to your laptop (`layerhop listen`), trigger sample events in test mode (`layerhop…
- [LayerHop X402 API](https://apis.io/apis/layerhop-com/layerhop-com-x402-api/) — HTTP 402 pay-per-request in USDC (Coinbase's open x402 protocol, v1 and v2): payment requirements for your resources and a facilitator (`verify`, `settle`)…

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### AsyncAPI (1)

Event-driven and webhook contracts.

- [Layerhop Com Webhooks](https://apis.io/asyncapis/layerhop-com/layerhop-com-webhooks/)

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [LayerHop Agentic Access](https://apis.io/agentic-access/layerhop-com/layerhop-com-agentic-access/)

#### JSON Schema (6)

The data models the API reads and writes.

- [AdminDevelopers](https://apis.io/schemas/layerhop-com/layerhop-com-admin-developers/)
- [AdminRevenue](https://apis.io/schemas/layerhop-com/layerhop-com-admin-revenue/)
- [FillerStats](https://apis.io/schemas/layerhop-com/layerhop-com-filler-stats/)
- [QuoteRequestBody](https://apis.io/schemas/layerhop-com/layerhop-com-quote-request-body/)
- [Subscription](https://apis.io/schemas/layerhop-com/layerhop-com-subscription/)
- [TxPreview](https://apis.io/schemas/layerhop-com/layerhop-com-tx-preview/)

#### JSON-LD (1)

Linked-data contexts for the provider's vocabulary.

- [Layerhop Com Context](https://apis.io/jsonld/layerhop-com/layerhop-com-context/)

#### Governance rules (1)

Spectral rulesets for the provider's contracts.

- [LayerHop API Rules](https://apis.io/rules/layerhop-com/layerhop-com-rules/)

#### Security (2)

Authentication, trust centre, and vulnerability disclosure.

- [LayerHop Authentication](https://apis.io/security/layerhop-com/layerhop-com-authentication/)
- [LayerHop Domain Security](https://apis.io/security/layerhop-com/layerhop-com-domain-security/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [LayerHop Plans Pricing](https://apis.io/plans/layerhop-com/layerhop-com-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [LayerHop Rate Limits](https://apis.io/rate-limits/layerhop-com/layerhop-com-rate-limits/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://layerhop.com/)
- [Documentation](https://docs.layerhop.com/)
- [Getting started](https://docs.layerhop.com/quickstart)
- [API reference](https://docs.layerhop.com/api-reference)
- [Pricing](https://layerhop.com/pricing)
- [Changelog](https://docs.layerhop.com/changelog)
- [Blog](https://layerhop.com/blog)
- [Terms of service](https://layerhop.com/terms)
- [Privacy policy](https://layerhop.com/privacy)
- [Status](https://status.layerhop.com)

## API Evangelist rating

**Kin Score 68.1** — exemplar · rubric 0.27.0 · scored 2026-11-15

| Facet | Score |
|---|---|
| Discoverability | 66.1 |
| Contract quality | 71.3 |
| Contract governance | 79.1 |
| Operational transparency | 58.4 |
| Developer ergonomics | 66.0 |
| Access clarity | 60.0 |

**Agent readiness 50.5** — agent-ready (gated down from agent-native)

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | unknown |
| Reversibility Documented | — |
| MCP Server | documented (partial credit) |
| Auth Clarity | bearer (partial credit) |
| Idempotency | documented (partial credit) |
| Error Semantics | verified |
| OpenAPI Examples | verified |
| Rate Limit Signal | verified |
| Event Surface Described | unknown |
| Agent Skills | unknown |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |
| Pagination Ratio | — |
| Operation Distinctiveness | distinct |
| MCP Tool Quality | na |

**Regulatory alignment 24.5** — Horizontal (data, software, accessibility, platform)

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/layerhop-com/](https://apis.io/providers/layerhop-com/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for LayerHop: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/layerhop-com/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
