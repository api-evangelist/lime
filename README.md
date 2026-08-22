# Lime (lime)

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

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/lime/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/lime/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Provider
- **Access:** 3rd-Party

## Tags

- Shared Mobility
- Micromobility
- Electric Scooters
- Electric Bikes
- E-Bikes
- E-Scooters
- Transportation
- Urban Mobility
- GBFS
- MDS
- Smart Cities
- Transit

## Timestamps

- **Created:** 2026-05-25
- **Modified:** 2026-05-25

## APIs

### Lime GBFS Public Feed

Public GBFS 2.2 feed exposing the real-time location, vehicle type, battery level, and rental URLs for Lime's free-floating e-scooters and e-bikes per operating city. Each city system has its own auto-discovery endpoint at /api/partners/v2/gbfs/{city}/gbfs.json, which lists the sub-feeds — system_information, station_information, station_status, free_bike_status, and vehicle_types. Use is governed by the Lime Public GBFS Terms. 46+ city systems are registered in the MobilityData GBFS index, including Paris, London, Berlin, Hamburg, Rome, Madrid, Vienna, Tel Aviv, Calgary, Ottawa, Vancouver, Atlanta, Arlington, and others.

- **Human URL:** [https://www.li.me/legal/public-gbfs-terms](https://www.li.me/legal/public-gbfs-terms)

#### Tags

- GBFS
- Shared Mobility
- Micromobility
- Real Time

#### Properties

- [Documentation](https://www.li.me/legal/public-gbfs-terms)
- [Documentation](https://github.com/MobilityData/gbfs/blob/master/gbfs.md)
- [OpenAPI](openapi/lime-gbfs-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/lime-gbfs.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/lime-gbfs.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Discovery](https://data.lime.bike/api/partners/v2/gbfs/paris/gbfs.json)

## Common Properties

- [Website](https://www.li.me)
- [About](https://www.li.me/about)
- [Newsroom](https://www.li.me/newsroom)
- [Careers](https://www.li.me/careers)
- [Contact](https://www.li.me/contact-us)
- [Support](https://help.li.me)
- [Terms of Service](https://www.li.me/legal/user-agreement)
- [Privacy Policy](https://www.li.me/legal/privacy-policy)
- [G B F S Terms](https://www.li.me/legal/public-gbfs-terms)
- [Sustainability](https://www.li.me/sustainability)
- [Safety](https://www.li.me/safety)
- [GitHub Organization](https://github.com/limebike)
- [Data Sharing](https://github.com/limebike/data-sharing)
- [LinkedIn](https://www.linkedin.com/company/limebike)
- [Twitter](https://twitter.com/limebike)
- [Instagram](https://www.instagram.com/li.me)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
