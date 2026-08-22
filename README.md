# State Street (state-street)

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
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

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
