# Gelato (gelato)

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
