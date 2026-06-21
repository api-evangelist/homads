# Homads (homads)

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
