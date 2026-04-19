# Temenos Transact APIs (temenos-transact)
Core banking APIs from Temenos Transact, providing comprehensive banking functionality including accounts, transactions, payments, loans, and customer management.

**URL:** [Visit APIs.json URL](https://www.temenos.com/products/transact/)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Banking, Core Banking, Digital Banking, Enterprise, Financial Services, Fintech

## Timestamps

- **Created:** 2024
- **Modified:** 2026-04-18

## APIs

### Temenos Transact Core Banking API
RESTful APIs for core banking operations including account management, customer data, transactions, and payment processing.

**Human URL:** [https://www.temenos.com/products/transact/](https://www.temenos.com/products/transact/)

#### Tags:

 - Accounts, Banking, Core Banking, Customers, Payments, Transactions

#### Properties

- [Documentation](https://developer.temenos.com/transact/documentation)
- [OpenAPI](https://developer.temenos.com/transact/openapi.json)
- [Authentication](https://developer.temenos.com/transact/authentication)
- [Sandbox](https://sandbox.temenos.com/transact)
- [SDK](https://developer.temenos.com/transact/sdks)
- [TermsOfService](https://www.temenos.com/terms-of-service/)
- [PrivacyPolicy](https://www.temenos.com/privacy-policy/)
- [Support](https://support.temenos.com)
- [StatusPage](https://status.temenos.com)
- [ChangeLog](https://developer.temenos.com/transact/changelog)
- [OpenAPI](openapi/temenos-transact-core-banking-openapi.yml)
- [JSONSchema](json-schema/temenos-transaction-schema.json)
- [JSONLD](json-ld/temenos-transact-context.jsonld)

### Temenos Transact Microservices APIs
APIs for Temenos Transact microservices including callback registry, configuration management, user entitlements, and service orchestration.

**Human URL:** [https://developer.temenos.com/transact-microservice-apis](https://developer.temenos.com/transact-microservice-apis)

#### Tags:

 - Configuration, Entitlements, Microservices, Orchestration

#### Properties

- [Documentation](https://developer.temenos.com/transact-microservice-apis)

### Temenos Transact Data Hub APIs
High-performance APIs built on the near real-time Analytics Data Store and Operational Data Store from Temenos Transact Data Hub.

**Human URL:** [https://developer.temenos.com/transact-data-hub](https://developer.temenos.com/transact-data-hub)

#### Tags:

 - Analytics, Data Hub, Data Store, Reporting

#### Properties

- [Documentation](https://developer.temenos.com/transact-data-hub)

### Temenos Operational Data Store APIs
APIs built on the near real-time Operational Data Store from Temenos Transact Data Hub.

**Human URL:** [https://developer.temenos.com/operational-data-store](https://developer.temenos.com/operational-data-store)

#### Tags:

 - Data Streams, ETL, Operational Data, Real-Time

#### Properties

- [Documentation](https://developer.temenos.com/operational-data-store)

## Common Properties

- [Portal](https://developer.temenos.com/)
- [GettingStarted](https://developer.temenos.com/article/sandbox-quick-guide)
- [Documentation](https://developer.temenos.com/guides)
- [Blog](https://www.temenos.com/blog/the-modern-developer-portal/)
- [SignUp](https://tcsp-signup.temenos.com/signup/communityregistration)
- [GitHubOrganization](https://github.com/temenostech)
- [Support](https://support.temenos.com)
- [TermsOfService](https://www.temenos.com/terms-of-service/)
- [PrivacyPolicy](https://www.temenos.com/privacy-policy/)

## Features

| Name | Description |
|------|-------------|
| Arrangement Architecture | Modular, component-based framework enabling reusable product components across retail, corporate, treasury, wealth, and Islamic banking. |
| Multi-Currency Support | Full support for multi-currency accounts, payments, and exchange rate management with ISO 4217 compliance. |
| KYC and AML Compliance | Built-in customer verification, AML checks, and compliance tracking for regulatory requirements. |
| Real-Time Payments | Support for SEPA, SWIFT, ACH, RTGS, and domestic clearing payment types with real-time processing. |
| Product Catalog | Configurable product catalog with conditions, eligibility criteria, and arrangement details for banking products. |

## Use Cases

| Name | Description |
|------|-------------|
| Digital Banking | Build digital banking apps with account management, transaction history, and payment initiation APIs. |
| Open Banking | Enable third-party access to banking data and payment services through standardized APIs. |
| Loan Origination | Automate loan application, credit assessment, and disbursement workflows through API integration. |
| Customer Onboarding | Streamline customer registration with KYC verification, account opening, and beneficiary setup. |

## Integrations

| Name | Description |
|------|-------------|
| Payment Networks | Integration with SWIFT, SEPA, ACH, and domestic clearing networks for cross-border and local payments. |
| Card Processing | Integration with card issuance and processing networks for debit and credit card operations. |
| Regulatory Reporting | Integration with regulatory bodies for compliance reporting, AML screening, and KYC verification. |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [Temenos Transact Core Banking API](openapi/temenos-transact-core-banking-openapi.yml)

### JSON Schema

- [Temenos Transact Core Banking Schemas](json-schema/)

### JSON-LD

- [Temenos Transact Context](json-ld/temenos-transact-context.jsonld)
- [Temenos Transact Core Banking Context](json-ld/temenos-transact-core-banking-context.jsonld)

## Capabilities

Naftiko capabilities organized as shared per-API definitions composed into customer-facing workflows.

### Shared Per-API Definitions

- [Core Banking API](capabilities/shared/core-banking.yaml) -- 30 operations for account, customer, payment, deposit, loan, card, and reference data management

### Workflow Capabilities

| Workflow | APIs Combined | Tools | Persona |
|----------|--------------|-------|---------|
| [Digital Banking](capabilities/digital-banking.yaml) | Core Banking | 21 | Digital Banking Developer |

## Rules

- [Temenos Transact Spectral Rules](rules/temenos-transact-spectral-rules.yml)

## Vocabulary

- [Temenos Transact Vocabulary](vocabulary/temenos-transact-vocabulary.yaml)

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
