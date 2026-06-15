# State Street (state-street)

State Street Corporation is one of the world's largest financial services companies, headquartered in Boston, Massachusetts. Founded in 1792, State Street provides investment servicing, investment management, investment research, and trading services to institutional investors including mutual funds, collective investment funds, corporate and public retirement plans, insurance companies, foundations, and endowments. State Street manages approximately $4.7 trillion in assets under management through State Street Global Advisors and services nearly $40 trillion in assets under custody. The company operates the State Street Alpha front-to-back investment management platform, Fund Connect for ETF creation and redemption, and Charles River Development for investment management technology. State Street's developer portal at developer.statestreet.com provides OAuth 2.0-secured APIs enabling institutional clients to programmatically access portfolio data, transaction history, NAV calculations, analytics, and ETF order management. APIs follow REST conventions with OpenAPI 3.0 specifications, JSON data format, and JSON Schema documentation.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/state-street/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/state-street/refs/heads/main/apis.yml)

## Timestamps

- **Modified:** 2026-05-19

## APIs

### Alpha Data Platform API

The State Street Alpha Data Platform API provides institutional investment managers with programmatic access to the front-to-back Alpha investment management platform. Clients can retrieve portfolio holdings, positions, investable cash, pledged collateral, securities on loan, risk exposures, performance measurement, and transaction history in near real-time. Built on Snowflake and Microsoft Azure, the Alpha Data Platform enables intraday visibility across geographies, asset classes, and counterparties. Authentication uses OAuth 2.0 Client Credentials.

- **Human URL:** [https://developer.statestreet.com/api-overview](https://developer.statestreet.com/api-overview)
- **Base URL:** `https://api.statestreet.com/v1`

#### Tags

- Financial Services
- Investment Management
- Portfolio
- Data Platform
- Institutional

#### Properties

- [Documentation](https://developer.statestreet.com/documentation-usage)
- [OpenAPI](openapi/state-street-alpha-data-platform-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/state-street-alpha-data-platform.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/state-street-alpha-data-platform.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Fund Connect API

The State Street Fund Connect API enables authorized participants (APs), fund managers, and custodians to programmatically manage ETF creation and redemption orders through the Fund Connect platform. The API supports FIX protocol and XML for order submission, and has executed the first API-based ETF order in Australian-domiciled ETFs (2025). Fund Connect is a global online portal processing ETF transactions across major markets.

- **Human URL:** [https://developer.statestreet.com/](https://developer.statestreet.com/)
- **Base URL:** `https://api.statestreet.com/v1/fund-connect`

#### Tags

- Financial Services
- ETF
- Fund Management
- Order Management
- Institutional

#### Properties

- [Documentation](https://developer.statestreet.com/)
- [OpenAPI](openapi/state-street-fund-connect-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/state-street-fund-connect.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/state-street-fund-connect.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Investment Accounting API

The State Street Investment Accounting API provides institutional clients with access to portfolio accounting data including net asset value (NAV) calculations, position valuations, corporate actions processing, performance measurement, and attribution analysis. State Street services over 70 types of portfolios including mutual funds, insurance portfolios, alternatives, and pension funds.

- **Human URL:** [https://www.statestreet.com/us/en/solutions/investment-accounting](https://www.statestreet.com/us/en/solutions/investment-accounting)
- **Base URL:** `https://api.statestreet.com/v1/accounting`

#### Tags

- Financial Services
- Accounting
- NAV
- Performance
- Institutional

#### Properties

- [Documentation](https://developer.statestreet.com/documentation-usage)
- [Postman Collection](collections/state-street-alpha-data-platform.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/state-street-alpha-data-platform.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/state-street-fund-connect.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/state-street-fund-connect.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Performance Analytics API

The State Street Performance Analytics API (TrueView) provides institutional investors and asset managers with access to investment risk analytics, performance attribution, scenario analysis, and reporting. Enables portfolio managers to access benchmark-relative attribution, risk factor decomposition, and regulatory reporting data across all asset classes including fixed income, equities, derivatives, and alternatives.

- **Human URL:** [https://www.statestreet.com/us/en/asset-owner/solutions/performance-and-analytics](https://www.statestreet.com/us/en/asset-owner/solutions/performance-and-analytics)
- **Base URL:** `https://api.statestreet.com/v1/analytics`

#### Tags

- Financial Services
- Analytics
- Performance
- Risk
- Institutional

#### Properties

- [Documentation](https://developer.statestreet.com/documentation-usage)
- [Postman Collection](collections/state-street-alpha-data-platform.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/state-street-alpha-data-platform.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/state-street-fund-connect.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/state-street-fund-connect.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Sample Transactions API

The State Street Sample Transactions API is a reference and onboarding API provided in the developer portal to help new integration teams understand the authentication flow, request structure, and response format of State Street's API platform. Developers use this API to perform an initial successful API call and retrieve a sample dataset before progressing to production APIs.

- **Human URL:** [https://developer.statestreet.com/get-started-browser](https://developer.statestreet.com/get-started-browser)
- **Base URL:** `https://api.statestreet.com/v1`

#### Tags

- Financial Services
- Developer
- Reference
- Onboarding
- Sample

#### Properties

- [Documentation](https://developer.statestreet.com/get-started-browser)
- [Postman Collection](collections/state-street-alpha-data-platform.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/state-street-alpha-data-platform.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/state-street-fund-connect.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/state-street-fund-connect.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [GitHub Organization](https://github.com/statestreet)
- [Website](https://www.statestreet.com)
- [Developer  Portal](https://developer.statestreet.com)
- [A P I  Catalog](https://developer.statestreet.com/apis-list)
- [A P I  Overview](https://developer.statestreet.com/api-overview)
- [Documentation](https://developer.statestreet.com/documentation-usage)
- [A P I  Standards](https://developer.statestreet.com/api-platform-standards)
- [Getting Started](https://developer.statestreet.com/get-started-browser)
- [Support](mailto:api-support@statestreet.com)
- [LinkedIn](https://www.linkedin.com/company/state-street-corporation)
- [Twitter](https://twitter.com/StateStreet)
- [Alpha  Platform](https://www.statestreet.com/alpha)
- [Privacy Policy](https://www.statestreet.com/us/en/individual-investor/tools-and-resources/privacy-notice)
- [Terms of Service](https://www.statestreet.com/us/en/individual-investor/tools-and-resources/terms-and-conditions)
- [OpenAPI](openapi/state-street-alpha-data-platform-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [OpenAPI](openapi/state-street-fund-connect-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [JSON Schema](json-schema/state-street-portfolio-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/state-street-position-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](json-structure/state-street-portfolio-structure.json)
- [JSON-LD](json-ld/state-street-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [Vocabulary](vocabulary/state-street-vocabulary.yml)
- [Spectral Rules](rules/state-street-rules.yml)
