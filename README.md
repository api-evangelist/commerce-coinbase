# Coinbase Commerce

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

Coinbase Commerce is a merchant crypto payment solution enabling businesses to accept cryptocurrency payments natively. The platform provides a REST API for creating payment charges, managing hosted checkouts, accessing payment metadata, configuring webhooks, and tracking crypto payment status across charge lifecycle events. Supports Bitcoin, Ethereum, USDC, and other major cryptocurrencies with 1% per-transaction fees and no monthly or setup costs.

**Areas:** Crypto Payments · Cryptocurrency · Payment Gateway · Commerce · Bitcoin · Ethereum · USDC · Webhook · Charges · Checkout

## Coinbase Commerce on APIs.io

Everything profiled for Coinbase Commerce is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/commerce-coinbase/](https://apis.io/providers/commerce-coinbase/)** — or go straight to one of the APIs or properties below.

### APIs (4)

- [Coinbase Commerce Charges API](https://apis.io/apis/commerce-coinbase/commerce-coinbase-charges-api/) — Create and retrieve crypto payment charges
- [Coinbase Commerce Checkouts API](https://apis.io/apis/commerce-coinbase/commerce-coinbase-checkouts-api/) — Create and manage single-use hosted payment checkouts
- [Coinbase Commerce Events API](https://apis.io/apis/commerce-coinbase/commerce-coinbase-events-api/) — Retrieve charge-related webhook events
- [Coinbase Commerce Webhooks API](https://apis.io/apis/commerce-coinbase/commerce-coinbase-webhooks-api/) — Checkout lifecycle event notifications

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Commerce Coinbase Agentic Access](https://apis.io/agentic-access/commerce-coinbase/commerce-coinbase-agentic-access/)

#### JSON Schema (2)

The data models the API reads and writes.

- [Charge](https://apis.io/schemas/commerce-coinbase/charge/)
- [Checkout](https://apis.io/schemas/commerce-coinbase/checkout/)

#### JSON-LD (1)

Linked-data contexts for the provider's vocabulary.

- [context Context](https://apis.io/jsonld/commerce-coinbase/context/)

#### Examples (5)

Example requests and responses.

- [Charge Response](https://apis.io/examples/commerce-coinbase/charge-response/)
- [Checkout Response](https://apis.io/examples/commerce-coinbase/checkout-response/)
- [Create Charge Request](https://apis.io/examples/commerce-coinbase/create-charge-request/)
- [Create Checkout Request](https://apis.io/examples/commerce-coinbase/create-checkout-request/)
- [Webhook Checkout Payment Success](https://apis.io/examples/commerce-coinbase/webhook-checkout-payment-success/)

#### Collections (3)

Postman and Open Collection request collections.

- [Coinbase Commerce Charges API](https://apis.io/collections/commerce-coinbase/open-commerce-coinbase-charges-api/)
- [Coinbase Commerce Charges Checkouts API](https://apis.io/collections/commerce-coinbase/open-commerce-coinbase-checkouts-api/)
- [Coinbase Commerce Charges Events API](https://apis.io/collections/commerce-coinbase/open-commerce-coinbase-events-api/)

#### Governance rules (1)

Spectral rulesets for the provider's contracts.

- [Coinbase Commerce — jsonschema rules](https://apis.io/rules/commerce-coinbase/commerce-coinbase-jsonschema-spectral-rules/)

#### Security (3)

Authentication, trust centre, and vulnerability disclosure.

- [Commerce Coinbase Authentication](https://apis.io/security/commerce-coinbase/commerce-coinbase-authentication/)
- [Commerce Coinbase Domain Security](https://apis.io/security/commerce-coinbase/commerce-coinbase-domain-security/)
- [Commerce Coinbase Vulnerability Disclosure](https://apis.io/security/commerce-coinbase/commerce-coinbase-vulnerability-disclosure/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Plans](https://apis.io/plans/commerce-coinbase/plans/)

#### Rate limits (1)

Published request limits.

- [Rate Limits](https://apis.io/rate-limits/commerce-coinbase/rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [Finops](https://apis.io/finops/commerce-coinbase/finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://commerce.coinbase.com)
- [Documentation](https://commerce.coinbase.com/docs/api)
- [Pricing](https://help.coinbase.com/en/commerce/getting-started/fees)
- [Support](https://help.coinbase.com/en/commerce)
- [Blog](https://www.coinbase.com/blog)
- [Terms of service](https://commerce.coinbase.com/legal/user-agreement)
- [Privacy policy](https://www.coinbase.com/legal/privacy)
- [Status](https://status.coinbase.com)

## API Evangelist rating

**Kin Score 36.1** — thin · rubric 0.24.0 · scored 2026-10-17

| Facet | Score |
|---|---|
| Discoverability | 66.1 |
| Contract quality | 56.5 |
| Contract governance | 9.8 |
| Operational transparency | 15.8 |
| Developer ergonomics | 45.2 |
| Access clarity | 15.8 |

**Agent readiness 34.8** — agent-ready

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
| Reversibility Documented | documented (partial credit) |
| MCP Server | — |
| Auth Clarity | bearer (partial credit) |
| Idempotency | verified |
| Error Semantics | — |
| OpenAPI Examples | partial |
| Rate Limit Signal | documented (partial credit) |
| Event Surface Described | yes |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |

**Regulatory alignment 24.1** — Payments

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/commerce-coinbase/](https://apis.io/providers/commerce-coinbase/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Coinbase Commerce: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/commerce-coinbase/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
