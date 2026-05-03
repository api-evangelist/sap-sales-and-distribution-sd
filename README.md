# SAP Sales and Distribution (SD)

APIs for SAP Sales and Distribution module covering sales orders, pricing, delivery, billing, and customer management processes within SAP S/4HANA. These OData-based APIs enable integration with external applications for end-to-end order-to-cash operations.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/sap-sales-and-distribution-sd/refs/heads/main/apis.yml)

- **Website:** https://www.sap.com
- **Documentation:** https://help.sap.com/docs/SAP_S4HANA_CLOUD
- **API Portal:** https://api.sap.com
- **Community:** https://community.sap.com

## Scope

- **Type:** Index
- **Position:** Consuming
- **Access:** 3rd-Party

## Tags

SAP, S/4HANA, Sales, Distribution, ERP, OData, Order-to-Cash

## Timestamps

- **Created:** 2024-01-01
- **Modified:** 2026-05-02

## APIs

### Sales Order API

Create, read, update, and delete sales orders in SAP S/4HANA via the API_SALES_ORDER_SRV OData service. Supports full CRUD on sales order headers, items, partners, pricing elements, and schedule lines.

**Human URL:** https://api.sap.com/api/API_SALES_ORDER_SRV/overview

**Tags:** Sales Orders, Order Management, OData, S/4HANA

**Properties**

- [Documentation](https://api.sap.com/api/API_SALES_ORDER_SRV/overview)
- [OpenAPI](openapi/sap-sd-sales-order-openapi.yml)
- [JSONSchema](json-schema/sap-sd-sales-order-schema.json)
- [JSONSchema](json-schema/sap-sd-sales-order-item-schema.json)
- [JSONStructure](json-structure/sap-sd-sales-order-structure.json)
- [JSONLD](json-ld/sap-sd-context.jsonld)

### Customer Master Data API

Manage customer master data including addresses, contact information, and business partner details in SAP S/4HANA.

**Human URL:** https://api.sap.com/api/API_BUSINESS_PARTNER/overview

**Tags:** Business Partner, Customer Data, Master Data, OData

**Properties**

- [Documentation](https://api.sap.com/api/API_BUSINESS_PARTNER/overview)
- [OpenAPI](openapi/sap-sd-customer-master-data-openapi.yml)
- [JSONSchema](json-schema/sap-sd-business-partner-schema.json)
- [JSONLD](json-ld/sap-sd-context.jsonld)

### Outbound Delivery API

Create and manage outbound deliveries, goods issue, and shipping documents for logistics execution.

**Human URL:** https://api.sap.com/api/API_OUTBOUND_DELIVERY_SRV_0002/overview

**Tags:** Delivery, Logistics, OData, Shipping

**Properties**

- [Documentation](https://api.sap.com/api/API_OUTBOUND_DELIVERY_SRV_0002/overview)
- [OpenAPI](openapi/sap-sd-outbound-delivery-openapi.yml)
- [JSONSchema](json-schema/sap-sd-outbound-delivery-schema.json)
- [JSONLD](json-ld/sap-sd-context.jsonld)

### Billing Document API

Create and manage billing documents, invoices, credit memos, and debit memos as part of the order-to-cash cycle.

**Human URL:** https://api.sap.com/api/OP_API_BILLING_DOCUMENT_SRV/overview

**Tags:** Billing, Invoice, Credit Memo, OData

**Properties**

- [Documentation](https://api.sap.com/api/OP_API_BILLING_DOCUMENT_SRV/overview)
- [OpenAPI](openapi/sap-sd-billing-document-openapi.yml)
- [JSONSchema](json-schema/sap-sd-billing-document-schema.json)
- [JSONStructure](json-structure/sap-sd-billing-document-structure.json)
- [JSONLD](json-ld/sap-sd-context.jsonld)

### Pricing API

Calculate prices, discounts, and surcharges using pricing condition records in SAP S/4HANA.

**Human URL:** https://api.sap.com/api/API_SLSPRCGCONDITIONRECORD_SRV/overview

**Tags:** Pricing, Conditions, Discount, OData

**Properties**

- [Documentation](https://api.sap.com/api/API_SLSPRCGCONDITIONRECORD_SRV/overview)
- [OpenAPI](openapi/sap-sd-pricing-openapi.yml)
- [JSONSchema](json-schema/sap-sd-pricing-condition-schema.json)
- [JSONLD](json-ld/sap-sd-context.jsonld)

### Sales Quotation API

Create and manage sales quotations through the complete quotation lifecycle from creation to order conversion.

**Human URL:** https://api.sap.com/api/API_SALES_QUOTATION_SRV/overview

**Tags:** Quotation, Pre-Sales, Sales Document, OData

**Properties**

- [Documentation](https://api.sap.com/api/API_SALES_QUOTATION_SRV/overview)
- [OpenAPI](openapi/sap-sd-sales-quotation-openapi.yml)
- [JSONLD](json-ld/sap-sd-context.jsonld)

### Credit Management API

Manage customer credit limits, credit exposure, and credit checks for automated credit risk assessment.

**Human URL:** https://api.sap.com/api/API_CREDIT_MANAGEMENT/overview

**Tags:** Credit, Finance, Risk Management, OData

**Properties**

- [Documentation](https://api.sap.com/api/API_CREDIT_MANAGEMENT/overview)
- [OpenAPI](openapi/sap-sd-credit-management-openapi.yml)
- [JSONLD](json-ld/sap-sd-context.jsonld)

### Material Master API

Access material master data including product information, availability, and pricing across SAP processes.

**Human URL:** https://api.sap.com/api/API_PRODUCT_SRV/overview

**Tags:** Material, Product, Master Data, OData

**Properties**

- [Documentation](https://api.sap.com/api/API_PRODUCT_SRV/overview)
- [OpenAPI](openapi/sap-sd-material-master-openapi.yml)
- [JSONSchema](json-schema/sap-sd-product-schema.json)
- [JSONLD](json-ld/sap-sd-context.jsonld)

### Credit Memo Request API

Create, read, update, and delete credit memo requests with approval workflow support.

**Human URL:** https://api.sap.com/api/API_CREDIT_MEMO_REQUEST_SRV/overview

**Tags:** Credit Memo, Billing, Sales Document, OData

**Properties**

- [Documentation](https://api.sap.com/api/API_CREDIT_MEMO_REQUEST_SRV/overview)
- [OpenAPI](openapi/sap-sd-credit-memo-request-openapi.yml)
- [JSONLD](json-ld/sap-sd-context.jsonld)

### Debit Memo Request API

Create, read, update, and delete debit memo requests for additional customer charges.

**Human URL:** https://api.sap.com/api/API_DEBIT_MEMO_REQUEST_SRV/overview

**Tags:** Debit Memo, Billing, Sales Document, OData

**Properties**

- [Documentation](https://api.sap.com/api/API_DEBIT_MEMO_REQUEST_SRV/overview)
- [OpenAPI](openapi/sap-sd-debit-memo-request-openapi.yml)
- [JSONLD](json-ld/sap-sd-context.jsonld)

### Sales Contract API

Create and manage quantity and value contracts for recurring customer deliveries.

**Human URL:** https://api.sap.com/api/API_SALES_CONTRACT_SRV/overview

**Tags:** Sales Contract, Agreement, OData, S/4HANA

**Properties**

- [Documentation](https://api.sap.com/api/API_SALES_CONTRACT_SRV/overview)
- [OpenAPI](openapi/sap-sd-sales-contract-openapi.yml)
- [JSONLD](json-ld/sap-sd-context.jsonld)

### Sales Inquiry API

Access sales inquiry documents for pre-sales customer interest tracking.

**Human URL:** https://api.sap.com/api/API_SALES_INQUIRY_SRV/overview

**Tags:** Sales Inquiry, Pre-Sales, OData, S/4HANA

**Properties**

- [Documentation](https://api.sap.com/api/API_SALES_INQUIRY_SRV/overview)
- [OpenAPI](openapi/sap-sd-sales-inquiry-openapi.yml)
- [JSONLD](json-ld/sap-sd-context.jsonld)

### Sales Scheduling Agreement API

Manage scheduling agreements for recurring material deliveries to customers over time.

**Human URL:** https://api.sap.com/api/API_SALES_SCHEDULING_AGREEMENT/overview

**Tags:** Scheduling Agreement, Logistics, Sales Contract, OData

**Properties**

- [Documentation](https://api.sap.com/api/API_SALES_SCHEDULING_AGREEMENT/overview)
- [OpenAPI](openapi/sap-sd-sales-scheduling-agreement-openapi.yml)
- [JSONLD](json-ld/sap-sd-context.jsonld)

### Customer Return API

Process customer returns and reverse logistics using SAP Advanced Returns Management.

**Human URL:** https://api.sap.com/api/API_CUSTOMER_RETURN_SRV/overview

**Tags:** Customer Returns, Reverse Logistics, OData, S/4HANA

**Properties**

- [Documentation](https://api.sap.com/api/API_CUSTOMER_RETURN_SRV/overview)
- [OpenAPI](openapi/sap-sd-customer-return-openapi.yml)
- [JSONSchema](json-schema/sap-sd-customer-return-schema.json)
- [JSONLD](json-ld/sap-sd-context.jsonld)

### Customer Returns Delivery API

Manage inbound deliveries for customer returns including goods receipt and inspection.

**Human URL:** https://api.sap.com/api/OP_API_CUSTOMER_RETURN_DELIVERY_SRV_0002/overview

**Tags:** Returns Delivery, Reverse Logistics, Shipping, OData

**Properties**

- [Documentation](https://api.sap.com/api/OP_API_CUSTOMER_RETURN_DELIVERY_SRV_0002/overview)
- [OpenAPI](openapi/sap-sd-customer-returns-delivery-openapi.yml)
- [JSONLD](json-ld/sap-sd-context.jsonld)

### Customer Material API

Manage customer-specific material information records linking customer part numbers to internal materials.

**Human URL:** https://api.sap.com/api/API_CUSTOMER_MATERIAL_SRV/overview

**Tags:** Customer Material, Master Data, Sales, OData

**Properties**

- [Documentation](https://api.sap.com/api/API_CUSTOMER_MATERIAL_SRV/overview)
- [OpenAPI](openapi/sap-sd-customer-material-openapi.yml)
- [JSONLD](json-ld/sap-sd-context.jsonld)

### Inbound Delivery API

Create and manage inbound deliveries with reference to sales documents and batch-split items.

**Human URL:** https://api.sap.com/api/API_INBOUND_DELIVERY_SRV_0002/overview

**Tags:** Inbound Delivery, Logistics, Warehouse, OData

**Properties**

- [Documentation](https://api.sap.com/api/API_INBOUND_DELIVERY_SRV_0002/overview)
- [OpenAPI](openapi/sap-sd-inbound-delivery-openapi.yml)
- [JSONLD](json-ld/sap-sd-context.jsonld)

## OpenAPI Specifications

- [openapi/sap-sd-billing-document-openapi.yml](openapi/sap-sd-billing-document-openapi.yml) — SAP SD Billing Document API
- [openapi/sap-sd-credit-management-openapi.yml](openapi/sap-sd-credit-management-openapi.yml) — SAP SD Credit Management API
- [openapi/sap-sd-credit-memo-request-openapi.yml](openapi/sap-sd-credit-memo-request-openapi.yml) — SAP SD Credit Memo Request API
- [openapi/sap-sd-customer-master-data-openapi.yml](openapi/sap-sd-customer-master-data-openapi.yml) — SAP SD Customer Master Data API
- [openapi/sap-sd-customer-material-openapi.yml](openapi/sap-sd-customer-material-openapi.yml) — SAP SD Customer Material API
- [openapi/sap-sd-customer-return-openapi.yml](openapi/sap-sd-customer-return-openapi.yml) — SAP SD Customer Return API
- [openapi/sap-sd-customer-returns-delivery-openapi.yml](openapi/sap-sd-customer-returns-delivery-openapi.yml) — SAP SD Customer Returns Delivery API
- [openapi/sap-sd-debit-memo-request-openapi.yml](openapi/sap-sd-debit-memo-request-openapi.yml) — SAP SD Debit Memo Request API
- [openapi/sap-sd-inbound-delivery-openapi.yml](openapi/sap-sd-inbound-delivery-openapi.yml) — SAP SD Inbound Delivery API
- [openapi/sap-sd-material-master-openapi.yml](openapi/sap-sd-material-master-openapi.yml) — SAP SD Material Master API
- [openapi/sap-sd-outbound-delivery-openapi.yml](openapi/sap-sd-outbound-delivery-openapi.yml) — SAP SD Outbound Delivery API
- [openapi/sap-sd-pricing-openapi.yml](openapi/sap-sd-pricing-openapi.yml) — SAP SD Pricing API
- [openapi/sap-sd-sales-contract-openapi.yml](openapi/sap-sd-sales-contract-openapi.yml) — SAP SD Sales Contract API
- [openapi/sap-sd-sales-inquiry-openapi.yml](openapi/sap-sd-sales-inquiry-openapi.yml) — SAP SD Sales Inquiry API
- [openapi/sap-sd-sales-order-openapi.yml](openapi/sap-sd-sales-order-openapi.yml) — SAP SD Sales Order API
- [openapi/sap-sd-sales-quotation-openapi.yml](openapi/sap-sd-sales-quotation-openapi.yml) — SAP SD Sales Quotation API
- [openapi/sap-sd-sales-scheduling-agreement-openapi.yml](openapi/sap-sd-sales-scheduling-agreement-openapi.yml) — SAP SD Sales Scheduling Agreement API

## Capabilities

### Shared Definitions

- [capabilities/shared/sales-order.yaml](capabilities/shared/sales-order.yaml) — Sales Order consumed definition (13 operations)
- [capabilities/shared/billing-document.yaml](capabilities/shared/billing-document.yaml) — Billing Document consumed definition (3 operations)
- [capabilities/shared/customer-master-data.yaml](capabilities/shared/customer-master-data.yaml) — Customer Master Data consumed definition (4 operations)
- [capabilities/shared/outbound-delivery.yaml](capabilities/shared/outbound-delivery.yaml) — Outbound Delivery consumed definition (4 operations)
- [capabilities/shared/pricing.yaml](capabilities/shared/pricing.yaml) — Pricing consumed definition (5 operations)
- [capabilities/shared/credit-management.yaml](capabilities/shared/credit-management.yaml) — Credit Management consumed definition (3 operations)

### Workflow Capabilities

| Capability | Description | APIs | Tools |
|-----------|-------------|------|-------|
| [order-to-cash.yaml](capabilities/order-to-cash.yaml) | End-to-end order-to-cash: sales orders, deliveries, billing, pricing | Sales Order + Outbound Delivery + Billing + Pricing | 12 |
| [customer-management.yaml](capabilities/customer-management.yaml) | Customer and credit management: business partners, credit limits | Customer Master Data + Credit Management | 7 |

## Rules

- [rules/sap-sd-rules.yml](rules/sap-sd-rules.yml) — Spectral ruleset enforcing SAP OData naming conventions and documentation standards

## JSON Schema

- [json-schema/sap-sd-billing-document-schema.json](json-schema/sap-sd-billing-document-schema.json)
- [json-schema/sap-sd-business-partner-schema.json](json-schema/sap-sd-business-partner-schema.json)
- [json-schema/sap-sd-customer-return-schema.json](json-schema/sap-sd-customer-return-schema.json)
- [json-schema/sap-sd-outbound-delivery-schema.json](json-schema/sap-sd-outbound-delivery-schema.json)
- [json-schema/sap-sd-pricing-condition-schema.json](json-schema/sap-sd-pricing-condition-schema.json)
- [json-schema/sap-sd-product-schema.json](json-schema/sap-sd-product-schema.json)
- [json-schema/sap-sd-sales-order-item-schema.json](json-schema/sap-sd-sales-order-item-schema.json)
- [json-schema/sap-sd-sales-order-schema.json](json-schema/sap-sd-sales-order-schema.json)

## JSON Structure

- [json-structure/sap-sd-sales-order-structure.json](json-structure/sap-sd-sales-order-structure.json) — SAP SD Sales Order entity structure
- [json-structure/sap-sd-billing-document-structure.json](json-structure/sap-sd-billing-document-structure.json) — SAP SD Billing Document entity structure

## JSON-LD

- [json-ld/sap-sd-context.jsonld](json-ld/sap-sd-context.jsonld) — SAP SD linked data context

## Examples

- [examples/sap-sd-list-sales-orders-example.json](examples/sap-sd-list-sales-orders-example.json) — List sales orders with OData query options
- [examples/sap-sd-create-sales-order-example.json](examples/sap-sd-create-sales-order-example.json) — Create a new sales order with deep insert

## Vocabulary

- [vocabulary/sap-sd-vocabulary.yml](vocabulary/sap-sd-vocabulary.yml) — SAP SD domain vocabulary covering order-to-cash, logistics, billing, pricing, and credit management terms

## Common Properties

- [Portal](https://api.sap.com)
- [Documentation](https://help.sap.com/docs/SAP_S4HANA_CLOUD)
- [Website](https://www.sap.com)
- [Getting Started](https://developers.sap.com/tutorials.html)
- [Authentication](https://help.sap.com/docs/SAP_S4HANA_CLOUD/0f69f8fb28ac4bf48d2b57b9637e81fa/)
- [Community](https://community.sap.com)
- [Support](https://support.sap.com)
- [Status](https://www.sap.com/about/trust-center/cloud-service-status.html)
- [GitHub Organization](https://github.com/SAP)
- [SDK](https://sap.github.io/cloud-sdk/)
- [Terms of Service](https://www.sap.com/about/agreements/product-use-and-support-terms.html)
- [Privacy Policy](https://www.sap.com/about/legal/privacy.html)

## Maintainers

**FN:** Kin Lane  
**Email:** kin@apievangelist.com
