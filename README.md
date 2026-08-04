# Homads (homads)

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
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Homads is an Austin-based mid-term rental marketplace connecting hosts and guests for furnished stays of 30 days or longer. The platform pairs rental listings with neighborhood-matching technology to help relocating professionals, travelers, and people in transition find a place to live. Homads is primarily a consumer and host web application; it does not publish a public developer API. Its rental inventory is exposed to property managers through channel-manager partners (for example Hostfully) via private connectivity, not a documented public API.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/homads/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/homads/refs/heads/main/apis.yml)

> Note on API availability: As of 2026-06-21, Homads does not offer a public developer API, API reference, OpenAPI document, or SDK. The entries below document Homads' real product surfaces and human-facing URLs. The OpenAPI document defines no paths and accurately records the absence of a public API. No endpoints are fabricated.

## Tags

- Rental
- Mid-Term Rental
- Real Estate
- Marketplace
- Neighborhood Data

## Timestamps

- **Created:** 2026-06-21
- **Modified:** 2026-06-21

## APIs

### Homads Rental Market Data

The Homads marketplace surface for searching and browsing mid-term (30+ day) furnished rental listings by location, dates, and neighborhood. As of the catalog date this is a consumer-facing web product; Homads does not publish a public developer API or API reference for programmatic access to rental market data. Listing inventory reaches property managers through private channel-manager integrations rather than a documented public API.

- **Human URL:** [https://homads.com/](https://homads.com/)
- **Base URL:** `https://homads.com`

#### Tags

- Rental
- Market Data
- Listings
- Mid-Term Rental

#### Properties

- [Documentation](https://homads.com/)
- [OpenAPI](openapi/homads-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/homads.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/homads.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Homads Rent Comparison

The neighborhood-matching and side-by-side rental comparison experience Homads provides to help guests compare furnished mid-term rentals across neighborhoods during a relocation. This is delivered through the Homads web application; no public developer API, documented endpoints, or rent-comp data feed is published for programmatic consumption as of the catalog date.

- **Human URL:** [https://homads.com/](https://homads.com/)
- **Base URL:** `https://homads.com`

#### Tags

- Rent Comparison
- Neighborhood Data
- Relocation
- Search

#### Properties

- [Documentation](https://homads.com/)
- [OpenAPI](openapi/homads-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/homads.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/homads.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/homads)
- [Website](https://homads.com/)
- [Documentation](https://homads.com/)
- [Plans](plans/homads-plans-pricing.yml)
- [Rate Limits](rate-limits/homads-rate-limits.yml)
- [Fin Ops](finops/homads-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
