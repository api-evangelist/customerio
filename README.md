# Customer.io (customerio)

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
