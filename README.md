# State Street

State Street Corporation is one of the world's largest financial services companies, headquartered in Boston, Massachusetts. Founded in 1792, State Street provides investment servicing, investment management, investment research, and trading services to institutional investors including mutual funds, collective investment funds, corporate and public retirement plans, insurance companies, foundations, and endowments. State Street manages approximately $4.7 trillion in assets under management through State Street Global Advisors and services nearly $40 trillion in assets under custody. The company's developer portal at developer.statestreet.com provides OAuth 2.0-secured APIs with OpenAPI 3.0 specifications enabling institutional clients to programmatically access portfolio data, analytics, and ETF order management.

**Website:** [https://www.statestreet.com](https://www.statestreet.com)  
**Developer Portal:** [https://developer.statestreet.com](https://developer.statestreet.com)

## APIs

### Alpha Data Platform API

Provides institutional investment managers with programmatic access to the front-to-back Alpha investment management platform. Retrieve portfolio positions, investable cash, risk exposures, performance measurement, and transaction history in near real-time.

- **Documentation:** [https://developer.statestreet.com/documentation-usage](https://developer.statestreet.com/documentation-usage)
- **OpenAPI:** [openapi/state-street-alpha-data-platform-openapi.yml](openapi/state-street-alpha-data-platform-openapi.yml)

### Fund Connect API

Enables authorized participants (APs) and fund managers to programmatically manage ETF creation and redemption orders through the Fund Connect platform, supporting all major global markets.

- **Documentation:** [https://developer.statestreet.com](https://developer.statestreet.com)
- **OpenAPI:** [openapi/state-street-fund-connect-openapi.yml](openapi/state-street-fund-connect-openapi.yml)

### Investment Accounting API

Provides portfolio accounting data including NAV calculations, position valuations, corporate actions processing, performance measurement, and attribution analysis for over 70 portfolio types.

- **Documentation:** [https://developer.statestreet.com/documentation-usage](https://developer.statestreet.com/documentation-usage)

### Performance Analytics API

TrueView risk analytics providing investment risk analytics, performance attribution, scenario analysis, and reporting for benchmark-relative attribution and regulatory reporting.

- **Documentation:** [https://developer.statestreet.com/documentation-usage](https://developer.statestreet.com/documentation-usage)

### Sample Transactions API

Reference onboarding API for developers to test authentication flow, request structure, and response format before accessing production APIs.

- **Documentation:** [https://developer.statestreet.com/get-started-browser](https://developer.statestreet.com/get-started-browser)

## Artifacts

### OpenAPI Specifications

| API | File |
|-----|------|
| Alpha Data Platform API | [openapi/state-street-alpha-data-platform-openapi.yml](openapi/state-street-alpha-data-platform-openapi.yml) |
| Fund Connect API | [openapi/state-street-fund-connect-openapi.yml](openapi/state-street-fund-connect-openapi.yml) |

### JSON Schema

| Schema | File |
|--------|------|
| Portfolio | [json-schema/state-street-portfolio-schema.json](json-schema/state-street-portfolio-schema.json) |
| Position | [json-schema/state-street-position-schema.json](json-schema/state-street-position-schema.json) |

### JSON Structure

| Structure | File |
|-----------|------|
| Portfolio | [json-structure/state-street-portfolio-structure.json](json-structure/state-street-portfolio-structure.json) |

### JSON-LD Context

| Context | File |
|---------|------|
| State Street | [json-ld/state-street-context.jsonld](json-ld/state-street-context.jsonld) |

### Examples

| Example | File |
|---------|------|
| List Portfolio Positions | [examples/state-street-list-portfolio-positions-example.json](examples/state-street-list-portfolio-positions-example.json) |

### Spectral Rules

| Ruleset | File |
|---------|------|
| State Street | [rules/state-street-rules.yml](rules/state-street-rules.yml) |

### Naftiko Capabilities

| Capability | Description |
|-----------|-------------|
| [Portfolio Management](capabilities/portfolio-management.yaml) | Unified workflow combining Alpha Data Platform and Fund Connect for institutional portfolio management, positions, transactions, performance, risk analytics, and ETF order management (12 tools) |

**Shared Definitions:**

| Shared | File |
|--------|------|
| Alpha Data Platform | [capabilities/shared/alpha-data-platform.yaml](capabilities/shared/alpha-data-platform.yaml) |
| Fund Connect | [capabilities/shared/fund-connect.yaml](capabilities/shared/fund-connect.yaml) |

### Vocabulary

| Vocabulary | File |
|-----------|------|
| State Street | [vocabulary/state-street-vocabulary.yml](vocabulary/state-street-vocabulary.yml) |

## Resources

- [Developer Portal](https://developer.statestreet.com)
- [API Catalog](https://developer.statestreet.com/apis-list)
- [API Standards](https://developer.statestreet.com/api-platform-standards)
- [Getting Started](https://developer.statestreet.com/get-started-browser)
- [Alpha Platform](https://www.statestreet.com/alpha)
- [Support](mailto:api-support@statestreet.com)
- [LinkedIn](https://www.linkedin.com/company/state-street-corporation)
- [Privacy Policy](https://www.statestreet.com/us/en/individual-investor/tools-and-resources/privacy-notice)
