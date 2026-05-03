# United Rentals (united-rentals)

United Rentals is the world's largest equipment rental company, headquartered in Stamford, Connecticut. The company provides a broad selection of APIs to simplify the procure-to-pay lifecycle for equipment rentals. United Rentals offers system integration through its Total Control platform, supporting EDI, cXML, JSON, and flat-file formats to connect with customer procurement and ERP systems for punch-out ordering, fleet management, and automated invoicing.

**URL:** [View APIs.json](https://raw.githubusercontent.com/api-evangelist/united-rentals/refs/heads/main/apis.yml)

## Scope

- **Type:** Company
- **Position:** Consuming
- **Access:** 3rd-Party

## Tags

- Equipment Rental
- Procurement
- Supply Chain
- Construction
- Fortune 500

## Timestamps

- **Created:** 2026-03-21
- **Modified:** 2026-05-03

## APIs

### United Rentals Total Control Integration API

United Rentals provides a broad selection of APIs to simplify the procure-to-pay lifecycle for equipment rentals. The Total Control platform supports integration via EDI, cXML, JSON, spreadsheet, and flat-file formats. Supports punch-out catalog ordering, rental reservations, fleet management, automated invoicing, PO management, and bill pay.

- **Human URL:** [https://www.unitedrentals.com/services/online-services/total-control/system-integration](https://www.unitedrentals.com/services/online-services/total-control/system-integration)
- **Base URL:** https://api.unitedrentals.com/v1

#### Properties

| Type | URL |
|---|---|
| Documentation | [https://www.unitedrentals.com/services/online-services/total-control/system-integration](https://www.unitedrentals.com/services/online-services/total-control/system-integration) |
| Total Control Platform | [https://www.unitedrentals.com/services/online-services/total-control](https://www.unitedrentals.com/services/online-services/total-control) |
| OpenAPI | [united-rentals-total-control-openapi.yml](openapi/united-rentals-total-control-openapi.yml) |

## Common Properties

| Type | URL |
|---|---|
| Website | [https://www.unitedrentals.com](https://www.unitedrentals.com) |
| Total Control | [https://www.unitedrentals.com/services/online-services/total-control](https://www.unitedrentals.com/services/online-services/total-control) |
| Digital Solutions | [https://www.unitedrentals.com/solutions/digital-solutions](https://www.unitedrentals.com/solutions/digital-solutions) |
| Investor Relations | [https://ir.unitedrentals.com](https://ir.unitedrentals.com) |
| LinkedIn | [https://www.linkedin.com/company/united-rentals](https://www.linkedin.com/company/united-rentals) |
| X | [https://twitter.com/UnitedRentals](https://twitter.com/UnitedRentals) |

## Artifacts

### OpenAPI Specifications

- [openapi/united-rentals-total-control-openapi.yml](openapi/united-rentals-total-control-openapi.yml) — Total Control API covering equipment, rentals, fleet, invoices, and locations (13 operations)

### Spectral Rules

- [rules/united-rentals-rules.yml](rules/united-rentals-rules.yml) — Spectral ruleset for United Rentals API conventions

### Naftiko Capabilities

- [capabilities/equipment-rental.yaml](capabilities/equipment-rental.yaml) — Unified equipment rental and fleet management workflow (13 MCP tools)
- [capabilities/shared/united-rentals-total-control.yaml](capabilities/shared/united-rentals-total-control.yaml) — Shared per-API Total Control definition

### JSON Schema

- [json-schema/united-rentals-rental-schema.json](json-schema/united-rentals-rental-schema.json) — Rental order schema
- [json-schema/united-rentals-invoice-schema.json](json-schema/united-rentals-invoice-schema.json) — Invoice schema

### JSON Structure

- [json-structure/united-rentals-rental-structure.json](json-structure/united-rentals-rental-structure.json) — Rental order data structure

### JSON-LD Context

- [json-ld/united-rentals-context.jsonld](json-ld/united-rentals-context.jsonld) — Linked data context with schema.org mappings

### Examples

- [examples/united-rentals-total-control-listEquipment-example.json](examples/united-rentals-total-control-listEquipment-example.json)
- [examples/united-rentals-total-control-createRental-example.json](examples/united-rentals-total-control-createRental-example.json)
- [examples/united-rentals-total-control-listInvoices-example.json](examples/united-rentals-total-control-listInvoices-example.json)

### Vocabulary

- [vocabulary/united-rentals-vocabulary.yml](vocabulary/united-rentals-vocabulary.yml) — Domain vocabulary (procure-to-pay, cXML, EDI, punch-out, fleet management, etc.)

## Maintainers

**FN:** API Evangelist

**Email:** info@apievangelist.com
