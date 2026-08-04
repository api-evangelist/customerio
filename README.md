# Customer.io (customerio)

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

Customer.io is a customer messaging and marketing automation platform. Its APIs let teams pipe behavioral data in, manage people and their attributes, trigger campaigns and broadcasts, send transactional email, push, SMS, and in-app messages, and stream delivery activity back out via reporting webhooks. The surface spans the Track API (basic site-id + api-key auth), the App / Transactional API (Bearer), and the Pipelines / Data Pipelines CDP API.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/customerio/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/customerio/refs/heads/main/apis.yml)

## Tags

- Customer Messaging
- Marketing Automation
- Email
- CDP
- Transactional

## Timestamps

- **Created:** 2026-06-20
- **Modified:** 2026-06-20

## APIs

### Customer.io Track API

Behavioral tracking API for adding and updating people, sending customer and anonymous events, registering device tokens, and managing manual segment membership. Authenticated with HTTP Basic using site_id and api_key. Includes v2 entity and batch endpoints.

- **Human URL:** [https://docs.customer.io/integrations/api/track/](https://docs.customer.io/integrations/api/track/)
- **Base URL:** `https://track.customer.io/api/v1`

#### Tags

- Track
- People
- Events
- Devices
- Segments

#### Properties

- [Documentation](https://docs.customer.io/integrations/api/track/)
- [API Reference](https://docs.customer.io/integrations/api/track/)
- [OpenAPI](openapi/customerio-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/customerio.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/customerio.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Customer.io App / Transactional API

App API for sending transactional email, push, SMS, and in-app messages, triggering API-driven broadcasts, searching people, reading segments, campaigns and their metrics, listing messages, running exports, and managing collections. Authenticated with an App API key as a Bearer token.

- **Human URL:** [https://docs.customer.io/integrations/api/app/](https://docs.customer.io/integrations/api/app/)
- **Base URL:** `https://api.customer.io`

#### Tags

- Transactional
- Broadcasts
- Customers
- Campaigns
- Exports

#### Properties

- [Documentation](https://docs.customer.io/integrations/api/app/)
- [API Reference](https://docs.customer.io/integrations/api/app/)
- [OpenAPI](openapi/customerio-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/customerio.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/customerio.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Customer.io Pipelines / Data Pipelines CDP API

Segment-compatible customer data pipeline API with identify, track, page, screen, group, alias, and batch calls. Routes first-party behavioral and identity data into Customer.io and onward to destinations. Authenticated with a source write key as a Bearer token.

- **Human URL:** [https://docs.customer.io/integrations/api/cdp/](https://docs.customer.io/integrations/api/cdp/)
- **Base URL:** `https://cdp.customer.io/v1`

#### Tags

- CDP
- Pipelines
- Identify
- Track
- Batch

#### Properties

- [Documentation](https://docs.customer.io/integrations/api/cdp/)
- [API Reference](https://docs.customer.io/integrations/api/cdp/)
- [OpenAPI](openapi/customerio-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/customerio.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/customerio.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Customer.io Reporting API

App API endpoints that return message activity and metrics - per-campaign metrics, customer message history, and sent message listings - for analyzing messaging performance. Authenticated with an App API key as a Bearer token.

- **Human URL:** [https://docs.customer.io/integrations/api/app/](https://docs.customer.io/integrations/api/app/)
- **Base URL:** `https://api.customer.io`

#### Tags

- Reporting
- Metrics
- Analytics

#### Properties

- [Documentation](https://docs.customer.io/integrations/api/app/)
- [API Reference](https://docs.customer.io/integrations/api/app/)
- [OpenAPI](openapi/customerio-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)

### Customer.io Reporting Webhooks

Outbound reporting webhooks that POST real-time message activity events (email/sms/push/in-app delivered, opened, clicked, bounced, converted, unsubscribed, and more) as JSON to a customer-supplied HTTPS endpoint.

- **Human URL:** [https://docs.customer.io/integrations/api/webhooks/](https://docs.customer.io/integrations/api/webhooks/)
- **Base URL:** `https://docs.customer.io/integrations/api/webhooks/`

#### Tags

- Webhooks
- Events
- Reporting

#### Properties

- [Documentation](https://docs.customer.io/integrations/api/webhooks/)
- [API Reference](https://docs.customer.io/integrations/data-out/connections/webhooks/)

## Common Properties

- [GitHub Organization](https://github.com/customerio)
- [LinkedIn](https://www.linkedin.com/company/customer-io)
- [Website](https://customer.io)
- [Documentation](https://docs.customer.io)
- [Plans](plans/customerio-plans-pricing.yml)
- [Rate Limits](rate-limits/customerio-rate-limits.yml)
- [Fin Ops](finops/customerio-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
