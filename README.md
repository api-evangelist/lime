# Lime

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

Lime is a San Francisco–based shared electric vehicle company that operates e-scooters and e-bikes across more than 280 cities in 30+ countries. Riders unlock and pay for vehicles through the Lime mobile app; cities and transit agencies receive operational data via standardized public feeds. Lime publishes per-city public GBFS (General Bikeshare Feed Specification) 2.2 feeds covering system information, station information, station status, free (dockless) bike status, and vehicle types under the Lime Public GBFS Terms. Lime also publishes MDS Extensions on GitHub — an open-source aggregation layer that sits on top of the MDS Provider standard for sharing k-anonymized operational data with regulators. There is no public, commercially licensable rider/booking API; the rider-facing endpoints at web-production.lime.bike are private to the Lime app. Integrations with trip-planning surfaces (Google Maps, Uber, Moovit, Citymapper) and city permit dashboards are delivered through the GBFS and MDS feeds.

**Areas:** Shared Mobility · Micromobility · Electric Scooters · Electric Bikes · E-Bikes · E-Scooter · Transportation · Urban Mobility · GBFS · MDS · Smart Cities · Transit

## Lime on APIs.io

Everything profiled for Lime is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/lime/](https://apis.io/providers/lime/)** — or go straight to one of the APIs or properties below.

### APIs (6)

- [Lime Free Bike Status API](https://apis.io/apis/lime/lime-free-bike-status-api/) — The Free Bike Status API from Lime — 1 operation(s) for free bike status.
- [Lime Gbfs.json API](https://apis.io/apis/lime/lime-gbfs-json-api/) — The Gbfs.json API from Lime — 1 operation(s) for gbfs.json.
- [Lime Station Information API](https://apis.io/apis/lime/lime-station-information-api/) — The Station Information API from Lime — 1 operation(s) for station information.
- [Lime Station Status API](https://apis.io/apis/lime/lime-station-status-api/) — The Station Status API from Lime — 1 operation(s) for station status.
- [Lime System Information API](https://apis.io/apis/lime/lime-system-information-api/) — The System Information API from Lime — 1 operation(s) for system information.
- [Lime Vehicle Types API](https://apis.io/apis/lime/lime-vehicle-types-api/) — The Vehicle Types API from Lime — 1 operation(s) for vehicle types.

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Lime Agentic Access](https://apis.io/agentic-access/lime/lime-agentic-access/)

#### Collections (7)

Postman and Open Collection request collections.

- [Lime GBFS Public Feed Free Bike Status API](https://apis.io/collections/lime/open-lime-free-bike-status-api/)
- [Lime GBFS Public Feed](https://apis.io/collections/lime/open-lime-gbfs/)
- [Lime GBFS Public Feed Free Bike Status Gbfs.json API](https://apis.io/collections/lime/open-lime-gbfs-json-api/)
- [Lime GBFS Public Feed Free Bike Status Station Information API](https://apis.io/collections/lime/open-lime-station-information-api/)
- [Lime GBFS Public Feed Free Bike Status Station Status API](https://apis.io/collections/lime/open-lime-station-status-api/)
- [Lime GBFS Public Feed Free Bike Status System Information API](https://apis.io/collections/lime/open-lime-system-information-api/)
- [Lime GBFS Public Feed Free Bike Status Vehicle Types API](https://apis.io/collections/lime/open-lime-vehicle-types-api/)

#### Security (2)

Authentication, trust centre, and vulnerability disclosure.

- [Lime Domain Security](https://apis.io/security/lime/lime-domain-security/)
- [Lime Vulnerability Disclosure](https://apis.io/security/lime/lime-vulnerability-disclosure/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://www.li.me)
- [Support](https://help.li.me)
- [Blog](https://www.li.me/blog)
- [Terms of service](https://www.li.me/legal/user-agreement)
- [Privacy policy](https://www.li.me/legal/privacy-policy)
- [GitHub](https://github.com/limebike)

## API Evangelist rating

**Kin Score 32.7** — thin · rubric 0.24.0 · scored 2026-10-17

| Facet | Score |
|---|---|
| Discoverability | 58.0 |
| Contract quality | 44.7 |
| Contract governance | 0.0 |
| Operational transparency | 2.6 |
| Developer ergonomics | 16.7 |
| Access clarity | 57.1 |

**Agent readiness 17.1** — agent-aware

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
| Reversibility Documented | na |
| MCP Server | — |
| Auth Clarity | — |
| Idempotency | na |
| Error Semantics | — |
| OpenAPI Examples | — |
| Rate Limit Signal | — |
| Event Surface Described | — |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | na |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |

**Regulatory alignment 19.6** — Horizontal (data, software, accessibility, platform)

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/lime/](https://apis.io/providers/lime/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Lime: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/lime/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
