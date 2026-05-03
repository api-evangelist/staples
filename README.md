# Staples

Staples is an American multinational office supply retail company that offers B2B procurement integration through Staples Business Advantage. The platform supports over 170 eProcurement system integrations including PunchOut catalogs, EDI, and REST-based procurement APIs for enterprise customers.

- **Website:** [https://www.staples.com](https://www.staples.com)
- **Business Advantage Portal:** [https://www.staplesadvantage.com/](https://www.staplesadvantage.com/)
- **eProcurement Integrations:** [https://www.staplesadvantage.com/learn/eprocurement-integrations](https://www.staplesadvantage.com/learn/eprocurement-integrations)
- **Privacy Policy:** [https://www.staples.com/sbd/cre/programs/privacy_policy/index.html](https://www.staples.com/sbd/cre/programs/privacy_policy/index.html)
- **Terms of Service:** [https://www.staples.com/sbd/cre/marketing/terms-and-conditions/](https://www.staples.com/sbd/cre/marketing/terms-and-conditions/)

## APIs

### Staples Advantage eProcurement API

The Staples Advantage eProcurement API enables enterprise procurement integration via PunchOut catalogs (cXML/OCI), EDI, and REST-based order management. Partners integrate with over 170 purchasing platforms including Ariba, Coupa, Jaggaer, Oracle, and NetSuite to streamline office supply procurement.

**Tags:** eProcurement, PunchOut, B2B, Office Supplies, Procurement

| Resource | URL |
|---|---|
| Documentation | [https://www.staplesadvantage.com/learn/eprocurement-integrations](https://www.staplesadvantage.com/learn/eprocurement-integrations) |
| Portal | [https://www.staplesadvantage.com/](https://www.staplesadvantage.com/) |
| OpenAPI | [openapi/staples-advantage-eprocurement-api-openapi.yml](openapi/staples-advantage-eprocurement-api-openapi.yml) |
| Spectral Rules | [rules/staples-rules.yml](rules/staples-rules.yml) |
| Capabilities | [capabilities/enterprise-procurement.yaml](capabilities/enterprise-procurement.yaml) |

### Staples Product Catalog API

The Staples Product Catalog API provides programmatic access to the Staples office supply catalog including product search, pricing, availability, and category browsing.

**Tags:** Catalog, Products, Retail, Commerce, Search

## OpenAPI Specifications

| API | File |
|---|---|
| Staples Advantage eProcurement API | [openapi/staples-advantage-eprocurement-api-openapi.yml](openapi/staples-advantage-eprocurement-api-openapi.yml) |

**Operations:** Search Products, List Categories, Get Product, List Orders, Create Order, Get Order, Get Account, List Cost Centers, Track Delivery, List Invoices, Get Invoice

## Capabilities

### Shared Definitions

| File | Description |
|---|---|
| [capabilities/shared/staples-advantage-api.yaml](capabilities/shared/staples-advantage-api.yaml) | Staples Advantage eProcurement API — catalog, ordering, and invoicing |

### Workflow Capabilities

| Capability | File | Description |
|---|---|---|
| Enterprise Procurement | [capabilities/enterprise-procurement.yaml](capabilities/enterprise-procurement.yaml) | Full procurement cycle: catalog search, ordering, delivery tracking, and invoice management |

## Spectral Rules

| File | Description |
|---|---|
| [rules/staples-rules.yml](rules/staples-rules.yml) | Spectral ruleset enforcing Staples API conventions |

## JSON Schemas

| Schema | File |
|---|---|
| Product | [json-schema/staples-product-schema.json](json-schema/staples-product-schema.json) |
| Order | [json-schema/staples-order-schema.json](json-schema/staples-order-schema.json) |

## JSON Structures

| Structure | File |
|---|---|
| Product | [json-structure/staples-product-structure.json](json-structure/staples-product-structure.json) |

## JSON-LD Context

| File | Description |
|---|---|
| [json-ld/staples-context.jsonld](json-ld/staples-context.jsonld) | JSON-LD context mapping Staples procurement concepts to schema.org vocabulary |

## Examples

| Example | File |
|---|---|
| Search Products | [examples/staples-search-products-example.json](examples/staples-search-products-example.json) |
| Create Order | [examples/staples-create-order-example.json](examples/staples-create-order-example.json) |

## Vocabulary

| File | Description |
|---|---|
| [vocabulary/staples-vocabulary.yml](vocabulary/staples-vocabulary.yml) | Domain vocabulary for Staples B2B procurement, eProcurement, and enterprise ordering concepts |

## Maintainers

**FN:** API Evangelist

**Email:** info@apievangelist.com
