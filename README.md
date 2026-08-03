# aflac (aflac)

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

Aflac is America's leading provider of supplemental insurance, offering products that pay benefits when a policyholder experiences an accident, illness, or injury. Aflac provides REST APIs through its Enterprise Connect (AEC) platform enabling benefits technology companies, HR platforms, and benefits administrators to integrate supplemental insurance enrollment, policy management, and claims capabilities into their workflows.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/aflac/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/aflac/refs/heads/main/apis.yml)

## Timestamps

- **Modified:** 2026-04-19

## APIs

### Aflac Enterprise Connect API

The Aflac Enterprise Connect (AEC) API enables benefits administrators, HR platforms, and third-party enrollment systems to integrate with Aflac's supplemental insurance platform programmatically. It provides REST API access to benefits enrollment, policy management, claims status, and eligibility verification for group and individual supplemental insurance products. The API supports electronic benefits enrollment workflows replacing traditional EDI 834 file exchanges, enabling real-time enrollment confirmation and policy administration for employers and their benefits technology partners.

- **Human URL:** [https://docs.enterprise-connect.aflac.com](https://docs.enterprise-connect.aflac.com)
- **Base URL:** `https://api.enterprise-connect.aflac.com`

#### Tags

- Benefits
- Enrollment
- Insurance
- Supplemental Insurance
- Workforce

#### Properties

- [Documentation](https://docs.enterprise-connect.aflac.com)
- [Getting Started](https://docs.enterprise-connect.aflac.com/docs/getting-started)
- [OpenAPI](openapi/aflac-enterprise-connect-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/aflac-enterprise-connect.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/aflac-enterprise-connect.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Aflac Claims API

The Aflac Claims API provides programmatic access to supplemental insurance claim submission, status retrieval, and benefit payment tracking. It enables policyholders and administrators to submit claims digitally, track claim processing status, and receive benefit payment notifications. The API supports claims for Aflac's portfolio of supplemental products including accident, critical illness, cancer, hospital indemnity, and short-term disability insurance.

- **Human URL:** [https://docs.enterprise-connect.aflac.com](https://docs.enterprise-connect.aflac.com)
- **Base URL:** `https://api.enterprise-connect.aflac.com`

#### Tags

- Claims
- Insurance
- Payments
- Supplemental Insurance

#### Properties

- [Documentation](https://docs.enterprise-connect.aflac.com)
- [Postman Collection](collections/aflac-enterprise-connect.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/aflac-enterprise-connect.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [GitHub Organization](https://github.com/Aflac-SCM)
- [LinkedIn](https://www.linkedin.com/company/aflac)
- [Portal](https://docs.enterprise-connect.aflac.com)
- [Website](https://www.aflac.com)
- [Sign Up](https://www.aflac.com/business/default.aspx)
- [Terms of Service](https://www.aflac.com/about-aflac/legal/terms-and-conditions.aspx)
- [Privacy Policy](https://www.aflac.com/about-aflac/legal/privacy-policy.aspx)
- [Support](https://www.aflac.com/contact-aflac/default.aspx)
- [Features](undefined)
- [Use Cases](undefined)
- [Integrations](undefined)
- [OpenAPI](openapi/aflac-enterprise-connect-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [JSON Schema](json-schema/enterprise-connect-claim-list-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/enterprise-connect-claim-request-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/enterprise-connect-claim-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/enterprise-connect-dependent-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/enterprise-connect-eligibility-request-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/enterprise-connect-eligibility-response-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/enterprise-connect-enrollment-list-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/enterprise-connect-enrollment-request-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/enterprise-connect-enrollment-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/enterprise-connect-group-list-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/enterprise-connect-group-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/enterprise-connect-policy-list-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/enterprise-connect-policy-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](json-structure/enterprise-connect-claim-list-structure.json)
- [JSON Structure](json-structure/enterprise-connect-claim-request-structure.json)
- [JSON Structure](json-structure/enterprise-connect-claim-structure.json)
- [JSON Structure](json-structure/enterprise-connect-dependent-structure.json)
- [JSON Structure](json-structure/enterprise-connect-eligibility-request-structure.json)
- [JSON Structure](json-structure/enterprise-connect-eligibility-response-structure.json)
- [JSON Structure](json-structure/enterprise-connect-enrollment-list-structure.json)
- [JSON Structure](json-structure/enterprise-connect-enrollment-request-structure.json)
- [JSON Structure](json-structure/enterprise-connect-enrollment-structure.json)
- [JSON Structure](json-structure/enterprise-connect-group-list-structure.json)
- [JSON Structure](json-structure/enterprise-connect-group-structure.json)
- [JSON Structure](json-structure/enterprise-connect-policy-list-structure.json)
- [JSON Structure](json-structure/enterprise-connect-policy-structure.json)
- [JSON-LD](json-ld/aflac-enterprise-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [Example](examples/enterprise-connect-claim-example.json)
- [Example](examples/enterprise-connect-claim-list-example.json)
- [Example](examples/enterprise-connect-claim-request-example.json)
- [Example](examples/enterprise-connect-dependent-example.json)
- [Example](examples/enterprise-connect-eligibility-request-example.json)
- [Example](examples/enterprise-connect-eligibility-response-example.json)
- [Example](examples/enterprise-connect-enrollment-example.json)
- [Example](examples/enterprise-connect-enrollment-list-example.json)
- [Example](examples/enterprise-connect-enrollment-request-example.json)
- [Example](examples/enterprise-connect-group-example.json)
- [Example](examples/enterprise-connect-group-list-example.json)
- [Example](examples/enterprise-connect-policy-example.json)
- [Example](examples/enterprise-connect-policy-list-example.json)
- [Spectral Rules](rules/aflac-spectral-rules.yml)
- [Vocabulary](vocabulary/aflac-vocabulary.yaml)
- [L L Ms Txt](https://docs.enterprise-connect.aflac.com/llms.txt)

## Maintainers

**FN:** Kin Lane
**Email:** info@apievangelist.com
