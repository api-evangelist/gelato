# Gelato (gelato)

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

Gelato operates a global, distributed print-on-demand production network that lets ecommerce sellers produce and ship products locally in 30+ countries. The Gelato API exposes REST endpoints across dedicated subdomains for orders, the product catalog, pricing and stock, shipment methods, ecommerce store products and templates, plus webhooks - all authenticated with an X-API-KEY header.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/gelato/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/gelato/refs/heads/main/apis.yml)

## Tags

- Print on Demand
- Ecommerce
- Fulfillment
- Distributed Production
- Orders

## Timestamps

- **Created:** 2026-06-25
- **Modified:** 2026-06-25

## APIs

### Gelato Orders API

Create, retrieve, search, patch (draft to order), quote, and cancel print-on-demand orders for fulfillment through Gelato's global production network, using the v4 Orders endpoints under order.gelatoapis.com.

- **Human URL:** [https://dashboard.gelato.com/docs/orders/](https://dashboard.gelato.com/docs/orders/)
- **Base URL:** `https://order.gelatoapis.com`

#### Tags

- Orders
- Fulfillment
- Print on Demand

#### Properties

- [Documentation](https://dashboard.gelato.com/docs/orders/)
- [API Reference](https://dashboard.gelato.com/docs/orders/v4/create/)
- [OpenAPI](openapi/gelato-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/gelato.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/gelato.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Gelato Product Catalog API

List and retrieve product catalogs, search products within a catalog, and fetch individual product and cover-dimension details from the v3 Product Catalog endpoints under product.gelatoapis.com.

- **Human URL:** [https://dashboard.gelato.com/docs/products/](https://dashboard.gelato.com/docs/products/)
- **Base URL:** `https://product.gelatoapis.com`

#### Tags

- Product Catalog
- Catalogs
- Products

#### Properties

- [Documentation](https://dashboard.gelato.com/docs/products/)
- [API Reference](https://dashboard.gelato.com/docs/products/catalog/list/)
- [OpenAPI](openapi/gelato-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/gelato.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/gelato.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Gelato Prices and Stock API

Retrieve quantity-based prices for a product and check regional stock availability for stock-able products via the v3 prices and stock endpoints under product.gelatoapis.com.

- **Human URL:** [https://dashboard.gelato.com/docs/products/prices/](https://dashboard.gelato.com/docs/products/prices/)
- **Base URL:** `https://product.gelatoapis.com`

#### Tags

- Prices
- Stock
- Availability

#### Properties

- [Documentation](https://dashboard.gelato.com/docs/products/prices/)
- [API Reference](https://dashboard.gelato.com/docs/products/stock/region-availability/)
- [OpenAPI](openapi/gelato-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/gelato.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/gelato.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Gelato Shipment API

List the shipment methods Gelato provides - with type, tracking support, and supported countries - optionally filtered by destination country, via the v1 shipment endpoint under shipment.gelatoapis.com.

- **Human URL:** [https://dashboard.gelato.com/docs/shipment/methods/](https://dashboard.gelato.com/docs/shipment/methods/)
- **Base URL:** `https://shipment.gelatoapis.com`

#### Tags

- Shipment
- Shipping Methods
- Logistics

#### Properties

- [Documentation](https://dashboard.gelato.com/docs/shipment/methods/)
- [API Reference](https://dashboard.gelato.com/docs/shipment/methods/)
- [OpenAPI](openapi/gelato-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/gelato.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/gelato.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Gelato Ecommerce API

Manage connected store products and templates - list and get store products, create products from a template, and retrieve template details - via the v1 ecommerce endpoints under ecommerce.gelatoapis.com.

- **Human URL:** [https://dashboard.gelato.com/docs/ecommerce/products/list/](https://dashboard.gelato.com/docs/ecommerce/products/list/)
- **Base URL:** `https://ecommerce.gelatoapis.com`

#### Tags

- Ecommerce
- Stores
- Templates

#### Properties

- [Documentation](https://dashboard.gelato.com/docs/ecommerce/products/list/)
- [API Reference](https://dashboard.gelato.com/docs/ecommerce/products/create-from-template/)
- [OpenAPI](openapi/gelato-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/gelato.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/gelato.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Gelato Webhooks API

Subscribe to JSON event callbacks for order and store-product lifecycle changes - including order_status_updated, order_item_status_updated, and store_product_template_created/updated/deleted events posted to your endpoint URL.

- **Human URL:** [https://dashboard.gelato.com/docs/webhooks/](https://dashboard.gelato.com/docs/webhooks/)
- **Base URL:** `https://dashboard.gelato.com/docs`

#### Tags

- Webhooks
- Events
- Notifications

#### Properties

- [Documentation](https://dashboard.gelato.com/docs/webhooks/)
- [API Reference](https://dashboard.gelato.com/docs/webhooks/)
- [OpenAPI](openapi/gelato-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/gelato.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/gelato.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/gelato-com)
- [Website](https://www.gelato.com)
- [Documentation](https://dashboard.gelato.com/docs/)
- [Plans](plans/gelato-plans-pricing.yml)
- [Rate Limits](rate-limits/gelato-rate-limits.yml)
- [Fin Ops](finops/gelato-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
