# SAP Sales and Distribution (SD) (sap-sales-and-distribution-sd)

APIs for SAP Sales and Distribution module covering sales orders, pricing, delivery, billing, and customer management processes within SAP S/4HANA. These OData-based APIs enable integration with external applications for end-to-end order-to-cash operations including sales document management, logistics execution, billing, and credit management.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/sap-sales-and-distribution-sd/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/sap-sales-and-distribution-sd/refs/heads/main/apis.yml)

## Scope

- **Type:** Index

## Tags

- Distribution
- ERP
- OData
- S/4HANA
- Sales
- SAP

## Timestamps

- **Created:** 2024-01-01
- **Modified:** 2026-05-19

## APIs

### Sales Order API

Create, read, update, and delete sales orders in SAP S/4HANA. This OData service (API_SALES_ORDER_SRV) supports full CRUD operations on sales order headers, items, partners, pricing elements, and schedule lines. Sales orders are created using deep insert requests.

- **Human URL:** [https://api.sap.com/api/API_SALES_ORDER_SRV/overview](https://api.sap.com/api/API_SALES_ORDER_SRV/overview)
- **Base URL:** `https://sandbox.api.sap.com/s4hanacloud/sap/opu/odata/sap/API_SALES_ORDER_SRV`

#### Tags

- OData
- Order Management
- S/4HANA
- Sales Orders

#### Properties

- [Documentation](https://api.sap.com/api/API_SALES_ORDER_SRV/overview)
- [OpenAPI](openapi/sap-sd-sales-order-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/sap-sd-sales-order.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sap-sd-sales-order.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/sap-sd-sales-order-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/sap-sd-sales-order-item-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](json-structure/sap-sd-sales-order-structure.json)
- [JSON-LD](json-ld/sap-sd-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [Examples](examples/sap-sd-list-sales-orders-example.json)
- [Examples](examples/sap-sd-create-sales-order-example.json)

### Customer Master Data API

Manage customer master data including addresses, contact information, and business partner details in SAP S/4HANA. Provides access to business partner records used across SAP S/4HANA modules.

- **Human URL:** [https://api.sap.com/api/API_BUSINESS_PARTNER/overview](https://api.sap.com/api/API_BUSINESS_PARTNER/overview)
- **Base URL:** `https://sandbox.api.sap.com/s4hanacloud/sap/opu/odata/sap/API_BUSINESS_PARTNER`

#### Tags

- Business Partner
- Customer Data
- Master Data
- OData

#### Properties

- [Documentation](https://api.sap.com/api/API_BUSINESS_PARTNER/overview)
- [OpenAPI](openapi/sap-sd-customer-master-data-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/sap-sd-customer-master-data.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sap-sd-customer-master-data.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/sap-sd-business-partner-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON-LD](json-ld/sap-sd-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)

### Outbound Delivery API

Create and manage outbound deliveries, goods issue, and shipping documents. Supports delivery creation with reference to sales orders and subsequent logistics processing including goods issue posting.

- **Human URL:** [https://api.sap.com/api/API_OUTBOUND_DELIVERY_SRV_0002/overview](https://api.sap.com/api/API_OUTBOUND_DELIVERY_SRV_0002/overview)
- **Base URL:** `https://sandbox.api.sap.com/s4hanacloud/sap/opu/odata/sap/API_OUTBOUND_DELIVERY_SRV`

#### Tags

- Delivery
- Logistics
- OData
- Shipping

#### Properties

- [Documentation](https://api.sap.com/api/API_OUTBOUND_DELIVERY_SRV_0002/overview)
- [OpenAPI](openapi/sap-sd-outbound-delivery-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/sap-sd-outbound-delivery.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sap-sd-outbound-delivery.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/sap-sd-outbound-delivery-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON-LD](json-ld/sap-sd-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)

### Billing Document API

Create and manage billing documents, invoices, credit memos, and debit memos. Enables billing document processing as part of the order-to-cash cycle in SAP S/4HANA including cancellation.

- **Human URL:** [https://api.sap.com/api/OP_API_BILLING_DOCUMENT_SRV/overview](https://api.sap.com/api/OP_API_BILLING_DOCUMENT_SRV/overview)
- **Base URL:** `https://sandbox.api.sap.com/s4hanacloud/sap/opu/odata/sap/API_BILLING_DOCUMENT_SRV`

#### Tags

- Billing
- Credit Memo
- Invoice
- OData

#### Properties

- [Documentation](https://api.sap.com/api/OP_API_BILLING_DOCUMENT_SRV/overview)
- [OpenAPI](openapi/sap-sd-billing-document-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/sap-sd-billing-document.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sap-sd-billing-document.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/sap-sd-billing-document-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](json-structure/sap-sd-billing-document-structure.json)
- [JSON-LD](json-ld/sap-sd-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)

### Pricing API

Calculate prices, discounts, and surcharges based on pricing conditions. Manages sales pricing condition records used to determine prices in sales documents within SAP S/4HANA.

- **Human URL:** [https://api.sap.com/api/API_SLSPRCGCONDITIONRECORD_SRV/overview](https://api.sap.com/api/API_SLSPRCGCONDITIONRECORD_SRV/overview)
- **Base URL:** `https://sandbox.api.sap.com/s4hanacloud/sap/opu/odata/sap/API_SLSPRCGCONDITIONRECORD_SRV`

#### Tags

- Conditions
- Discount
- OData
- Pricing

#### Properties

- [Documentation](https://api.sap.com/api/API_SLSPRCGCONDITIONRECORD_SRV/overview)
- [OpenAPI](openapi/sap-sd-pricing-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/sap-sd-pricing.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sap-sd-pricing.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/sap-sd-pricing-condition-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON-LD](json-ld/sap-sd-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)

### Sales Quotation API

Create and manage sales quotations and customer inquiries. Supports the complete quotation lifecycle from creation through approval and conversion to sales orders.

- **Human URL:** [https://api.sap.com/api/API_SALES_QUOTATION_SRV/overview](https://api.sap.com/api/API_SALES_QUOTATION_SRV/overview)
- **Base URL:** `https://sandbox.api.sap.com/s4hanacloud/sap/opu/odata/sap/API_SALES_QUOTATION_SRV`

#### Tags

- OData
- Pre-Sales
- Quotation
- Sales Document

#### Properties

- [Documentation](https://api.sap.com/api/API_SALES_QUOTATION_SRV/overview)
- [OpenAPI](openapi/sap-sd-sales-quotation-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/sap-sd-sales-quotation.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sap-sd-sales-quotation.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON-LD](json-ld/sap-sd-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)

### Credit Management API

Manage customer credit limits, credit exposure, and credit checks in SAP S/4HANA. Enables automated credit risk assessment during sales order processing.

- **Human URL:** [https://api.sap.com/api/API_CREDIT_MANAGEMENT/overview](https://api.sap.com/api/API_CREDIT_MANAGEMENT/overview)
- **Base URL:** `https://sandbox.api.sap.com/s4hanacloud/sap/opu/odata/sap/API_CREDIT_MANAGEMENT`

#### Tags

- Credit
- Finance
- OData
- Risk Management

#### Properties

- [Documentation](https://api.sap.com/api/API_CREDIT_MANAGEMENT/overview)
- [OpenAPI](openapi/sap-sd-credit-management-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/sap-sd-credit-management.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sap-sd-credit-management.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON-LD](json-ld/sap-sd-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)

### Material Master API

Access material master data including product information, availability, and pricing. Provides read and write access to product records used across procurement, manufacturing, and sales processes.

- **Human URL:** [https://api.sap.com/api/API_PRODUCT_SRV/overview](https://api.sap.com/api/API_PRODUCT_SRV/overview)
- **Base URL:** `https://sandbox.api.sap.com/s4hanacloud/sap/opu/odata/sap/API_PRODUCT_SRV`

#### Tags

- Master Data
- Material
- OData
- Product

#### Properties

- [Documentation](https://api.sap.com/api/API_PRODUCT_SRV/overview)
- [OpenAPI](openapi/sap-sd-material-master-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/sap-sd-material-master.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sap-sd-material-master.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/sap-sd-product-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON-LD](json-ld/sap-sd-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)

### Credit Memo Request API

Create, read, update, and delete credit memo requests. Enables approval or denial of credit memo requests that require authorization before processing.

- **Human URL:** [https://api.sap.com/api/API_CREDIT_MEMO_REQUEST_SRV/overview](https://api.sap.com/api/API_CREDIT_MEMO_REQUEST_SRV/overview)
- **Base URL:** `https://sandbox.api.sap.com/s4hanacloud/sap/opu/odata/sap/API_CREDIT_MEMO_REQUEST_SRV`

#### Tags

- Billing
- Credit Memo
- OData
- Sales Document

#### Properties

- [Documentation](https://api.sap.com/api/API_CREDIT_MEMO_REQUEST_SRV/overview)
- [OpenAPI](openapi/sap-sd-credit-memo-request-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/sap-sd-credit-memo-request.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sap-sd-credit-memo-request.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON-LD](json-ld/sap-sd-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)

### Debit Memo Request API

Create, read, update, and delete debit memo requests. Supports the full lifecycle of debit memo requests used to charge customers for additional amounts.

- **Human URL:** [https://api.sap.com/api/API_DEBIT_MEMO_REQUEST_SRV/overview](https://api.sap.com/api/API_DEBIT_MEMO_REQUEST_SRV/overview)
- **Base URL:** `https://sandbox.api.sap.com/s4hanacloud/sap/opu/odata/sap/API_DEBIT_MEMO_REQUEST_SRV`

#### Tags

- Billing
- Debit Memo
- OData
- Sales Document

#### Properties

- [Documentation](https://api.sap.com/api/API_DEBIT_MEMO_REQUEST_SRV/overview)
- [OpenAPI](openapi/sap-sd-debit-memo-request-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/sap-sd-debit-memo-request.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sap-sd-debit-memo-request.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON-LD](json-ld/sap-sd-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)

### Sales Contract API

Create and manage sales contracts including quantity contracts and value contracts. Supports contract lifecycle management from creation through fulfillment tracking.

- **Human URL:** [https://api.sap.com/api/API_SALES_CONTRACT_SRV/overview](https://api.sap.com/api/API_SALES_CONTRACT_SRV/overview)
- **Base URL:** `https://sandbox.api.sap.com/s4hanacloud/sap/opu/odata/sap/API_SALES_CONTRACT_SRV`

#### Tags

- Agreement
- OData
- S/4HANA
- Sales Contract

#### Properties

- [Documentation](https://api.sap.com/api/API_SALES_CONTRACT_SRV/overview)
- [OpenAPI](openapi/sap-sd-sales-contract-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/sap-sd-sales-contract.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sap-sd-sales-contract.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON-LD](json-ld/sap-sd-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)

### Sales Inquiry API

Read sales inquiries from SAP S/4HANA. Provides access to sales inquiry documents used in the pre-sales process to capture customer interest in products or services.

- **Human URL:** [https://api.sap.com/api/API_SALES_INQUIRY_SRV/overview](https://api.sap.com/api/API_SALES_INQUIRY_SRV/overview)
- **Base URL:** `https://sandbox.api.sap.com/s4hanacloud/sap/opu/odata/sap/API_SALES_INQUIRY_SRV`

#### Tags

- OData
- Pre-Sales
- S/4HANA
- Sales Inquiry

#### Properties

- [Documentation](https://api.sap.com/api/API_SALES_INQUIRY_SRV/overview)
- [OpenAPI](openapi/sap-sd-sales-inquiry-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/sap-sd-sales-inquiry.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sap-sd-sales-inquiry.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON-LD](json-ld/sap-sd-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)

### Sales Scheduling Agreement API

Manage sales scheduling agreements in SAP S/4HANA. Scheduling agreements define delivery schedules for recurring deliveries of materials to customers over a specified period.

- **Human URL:** [https://api.sap.com/api/API_SALES_SCHEDULING_AGREEMENT/overview](https://api.sap.com/api/API_SALES_SCHEDULING_AGREEMENT/overview)
- **Base URL:** `https://sandbox.api.sap.com/s4hanacloud/sap/opu/odata/sap/API_SALES_SCHEDULING_AGREEMENT`

#### Tags

- Logistics
- OData
- Sales Contract
- Scheduling Agreement

#### Properties

- [Documentation](https://api.sap.com/api/API_SALES_SCHEDULING_AGREEMENT/overview)
- [OpenAPI](openapi/sap-sd-sales-scheduling-agreement-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/sap-sd-sales-scheduling-agreement.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sap-sd-sales-scheduling-agreement.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON-LD](json-ld/sap-sd-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)

### Customer Return API

Create, read, update, and delete customer returns in SAP S/4HANA. Supports integration with customer return processing including SAP Advanced Returns Management using deep insert requests.

- **Human URL:** [https://api.sap.com/api/API_CUSTOMER_RETURN_SRV/overview](https://api.sap.com/api/API_CUSTOMER_RETURN_SRV/overview)
- **Base URL:** `https://sandbox.api.sap.com/s4hanacloud/sap/opu/odata/sap/API_CUSTOMER_RETURN_SRV`

#### Tags

- Customer Returns
- OData
- Reverse Logistics
- S/4HANA

#### Properties

- [Documentation](https://api.sap.com/api/API_CUSTOMER_RETURN_SRV/overview)
- [OpenAPI](openapi/sap-sd-customer-return-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/sap-sd-customer-return.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sap-sd-customer-return.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/sap-sd-customer-return-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON-LD](json-ld/sap-sd-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)

### Customer Returns Delivery API

Manage customer returns deliveries in SAP S/4HANA. Enables processing of inbound deliveries related to customer returns, including goods receipt and inspection.

- **Human URL:** [https://api.sap.com/api/OP_API_CUSTOMER_RETURN_DELIVERY_SRV_0002/overview](https://api.sap.com/api/OP_API_CUSTOMER_RETURN_DELIVERY_SRV_0002/overview)
- **Base URL:** `https://sandbox.api.sap.com/s4hanacloud/sap/opu/odata/sap/API_CUSTOMER_RETURN_DELIVERY_SRV_0002`

#### Tags

- OData
- Returns Delivery
- Reverse Logistics
- Shipping

#### Properties

- [Documentation](https://api.sap.com/api/OP_API_CUSTOMER_RETURN_DELIVERY_SRV_0002/overview)
- [OpenAPI](openapi/sap-sd-customer-returns-delivery-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/sap-sd-customer-returns-delivery.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sap-sd-customer-returns-delivery.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON-LD](json-ld/sap-sd-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)

### Customer Material API

Manage customer-material information records that link customer-specific material numbers to internal material numbers. Supports the sales process by mapping customer part numbers to SAP materials.

- **Human URL:** [https://api.sap.com/api/API_CUSTOMER_MATERIAL_SRV/overview](https://api.sap.com/api/API_CUSTOMER_MATERIAL_SRV/overview)
- **Base URL:** `https://sandbox.api.sap.com/s4hanacloud/sap/opu/odata/sap/API_CUSTOMER_MATERIAL_SRV`

#### Tags

- Customer Material
- Master Data
- OData
- Sales

#### Properties

- [Documentation](https://api.sap.com/api/API_CUSTOMER_MATERIAL_SRV/overview)
- [OpenAPI](openapi/sap-sd-customer-material-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/sap-sd-customer-material.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sap-sd-customer-material.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON-LD](json-ld/sap-sd-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)

### Inbound Delivery API

Create and manage inbound deliveries in SAP S/4HANA. Supports creation of inbound deliveries with reference to sales documents and manages batch-split items for existing deliveries.

- **Human URL:** [https://api.sap.com/api/API_INBOUND_DELIVERY_SRV_0002/overview](https://api.sap.com/api/API_INBOUND_DELIVERY_SRV_0002/overview)
- **Base URL:** `https://sandbox.api.sap.com/s4hanacloud/sap/opu/odata/sap/API_INBOUND_DELIVERY_SRV_0002`

#### Tags

- Inbound Delivery
- Logistics
- OData
- Warehouse

#### Properties

- [Documentation](https://api.sap.com/api/API_INBOUND_DELIVERY_SRV_0002/overview)
- [OpenAPI](openapi/sap-sd-inbound-delivery-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/sap-sd-inbound-delivery.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sap-sd-inbound-delivery.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON-LD](json-ld/sap-sd-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)

## Common Properties

- [Arazzo Workflows](arazzo/) — [Arazzo Specification](https://spec.openapis.org/arazzo/latest.html)
- [Portal](https://api.sap.com)
- [Documentation](https://help.sap.com/docs/SAP_S4HANA_CLOUD)
- [Website](https://www.sap.com)
- [Getting Started](https://developers.sap.com/tutorials.html)
- [Authentication](https://help.sap.com/docs/SAP_S4HANA_CLOUD/0f69f8fb28ac4bf48d2b57b9637e81fa/)
- [Blog](https://community.sap.com/t5/c-khhcw49343/SD+%28Sales+and+Distribution%29/pd-p/209057551571413566377230676804921)
- [Status Page](https://www.sap.com/about/trust-center/cloud-service-status.html)
- [Support](https://support.sap.com)
- [Terms of Service](https://www.sap.com/about/agreements/product-use-and-support-terms.html)
- [Privacy Policy](https://www.sap.com/about/legal/privacy.html)
- [GitHub Organization](https://github.com/SAP)
- [Community](https://community.sap.com)
- [Login](https://accounts.sap.com)
- [Sign Up](https://developers.sap.com)
- [SDK](https://sap.github.io/cloud-sdk/)
- [SDK](https://github.com/SAP/cloud-sdk-js)
- [Spectral Rules](rules/sap-sd-rules.yml)
- [Capabilities](capabilities/order-to-cash.yaml)
- [Capabilities](capabilities/customer-management.yaml)
- [Vocabulary](vocabulary/sap-sd-vocabulary.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
