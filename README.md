# encarapi-com

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

EnCarAPI provides a REST API delivering Korean used-car market data from Encar, KB Chachacha, and K Car. Over 300,000 deduplicated vehicle listings, inspection reports, accident history, dealer information, and price history are available in real-time JSON responses. Plans start at €149/month with unlimited access to listings, photos, specifications, and market statistics, plus optional add‑ons for Chinese market data.

**Areas:** Automotive · Data · Korean · Cars · API

## encarapi-com on APIs.io

Everything profiled for encarapi-com is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/encarapi-com/](https://apis.io/providers/encarapi-com/)** — or go straight to one of the APIs or properties below.

### APIs (9)

- [encarapi-com Archive API](https://apis.io/apis/encarapi-com/encarapi-com-archive-api/) — Business/Scale; trials get a daily preview of 100 lookups. Removed listings with their last known data, earlier versions of inspection reports and insurance…
- [encarapi-com Catalog API](https://apis.io/apis/encarapi-com/encarapi-com-catalog-api/) — Search & list vehicles
- [encarapi-com Discovery API](https://apis.io/apis/encarapi-com/encarapi-com-discovery-api/) — Filter facets & valid values
- [encarapi-com Equipment API](https://apis.io/apis/encarapi-com/encarapi-com-equipment-api/) — Business/Scale (and trials). Used excavators from 굴삭기나라 (direct-nara.co.kr), Korea's dedicated construction-equipment marketplace: crawler and wheeled…
- [encarapi-com Leasing API](https://apis.io/apis/encarapi-com/encarapi-com-leasing-api/) — Lease-takeover (리스) and rental (렌트) listings - same shape and filters as /api/catalog, kept separate because these price by monthly payment, not a purchase…
- [encarapi-com Sync API](https://apis.io/apis/encarapi-com/encarapi-com-sync-api/) — Business/Scale. Trials can test the change feed (last 7 days) and bulk lookups (1,000 ids per day), but not the full export. Hold a local copy of the…
- [encarapi-com Taxonomy API](https://apis.io/apis/encarapi-com/encarapi-com-taxonomy-api/) — Downloadable make/model/badge lists (CSV). Fetch once, cache for a day, and drive your dropdowns from these - no offline mapping, no per-click facet calls.
- [encarapi-com Trucks API](https://apis.io/apis/encarapi-com/encarapi-com-trucks-api/) — Business/Scale (and trials). Encar's truck, bus and special-vehicle marketplace (화물·특장·버스): cargo trucks (Porter, Bongo, Mighty, Xcient ...), wing bodies,…
- [encarapi-com Vehicle API](https://apis.io/apis/encarapi-com/encarapi-com-vehicle-api/) — Per-vehicle detail, history & inspection

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Encarapi Com Agentic Access](https://apis.io/agentic-access/encarapi-com/encarapi-com-agentic-access/)

#### JSON Schema (5)

The data models the API reads and writes.

- [CatalogResponse](https://apis.io/schemas/encarapi-com/encarapi-com-catalog-response/)
- [EnumsResponse](https://apis.io/schemas/encarapi-com/encarapi-com-enums-response/)
- [InspectionResponse](https://apis.io/schemas/encarapi-com/encarapi-com-inspection-response/)
- [ModelSearchResponse](https://apis.io/schemas/encarapi-com/encarapi-com-model-search-response/)
- [RecordResponse](https://apis.io/schemas/encarapi-com/encarapi-com-record-response/)

#### JSON-LD (1)

Linked-data contexts for the provider's vocabulary.

- [Encarapi Com Context](https://apis.io/jsonld/encarapi-com/encarapi-com-context/)

#### Governance rules (1)

Spectral rulesets for the provider's contracts.

- [encarapi-com API Rules](https://apis.io/rules/encarapi-com/encarapi-com-rules/)

#### Security (2)

Authentication, trust centre, and vulnerability disclosure.

- [Encarapi Com Authentication](https://apis.io/security/encarapi-com/encarapi-com-authentication/)
- [Encarapi Com Domain Security](https://apis.io/security/encarapi-com/encarapi-com-domain-security/)

#### OAuth scopes (1)

The permissions the API asks for.

- [Encarapi Com Scopes](https://apis.io/scopes/encarapi-com/encarapi-com-scopes/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Encarapi Com Plans Pricing](https://apis.io/plans/encarapi-com/encarapi-com-plans-pricing/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://encarapi.com/)
- [Documentation](https://api.encarapi.com/reference)
- [API reference](https://api.encarapi.com/reference)
- [Pricing](https://encarapi.com/#pricing)
- [Support](https://t.me/innqtech)
- [GitHub](https://github.com/ThatMojo)

## API Evangelist rating

**Kin Score 51.9** — developing · rubric 0.25.0 · scored 2026-10-30

| Facet | Score |
|---|---|
| Discoverability | 65.0 |
| Contract quality | 61.7 |
| Contract governance | 70.9 |
| Operational transparency | 5.3 |
| Developer ergonomics | 56.4 |
| Access clarity | 38.9 |

**Agent readiness 52.9** — agent-ready (gated down from agent-native)

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | unknown |
| Reversibility Documented | — |
| MCP Server | documented (partial credit) |
| Auth Clarity | served (partial credit) |
| Idempotency | — |
| Error Semantics | derived (partial credit) |
| OpenAPI Examples | verified |
| Rate Limit Signal | — |
| Event Surface Described | — |
| Agent Skills | unknown |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | served (partial credit) |
| Protected Resource Metadata | verified |
| Dynamic Client Registration | yes |
| Agentic Commerce | — |
| Pagination Ratio | paginated |
| Operation Distinctiveness | distinct |

**Regulatory alignment 26.5** — Horizontal (data, software, accessibility, platform)

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/encarapi-com/](https://apis.io/providers/encarapi-com/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for encarapi-com: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/encarapi-com/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
