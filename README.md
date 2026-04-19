# Aflac (aflac)
Aflac is America's leading provider of supplemental insurance, offering products that pay benefits when a policyholder experiences an accident, illness, or injury. Aflac provides REST APIs through its Enterprise Connect (AEC) platform enabling benefits technology companies, HR platforms, and benefits administrators to integrate supplemental insurance enrollment, policy management, and claims capabilities into their workflows.

**URL:** [https://docs.enterprise-connect.aflac.com](https://docs.enterprise-connect.aflac.com)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Benefits, Claims, Enrollment, Insurance, Payments, Supplemental Insurance, Workforce

## Timestamps

- **Created:** 2026-03-21
- **Modified:** 2026-04-19

## APIs

### Aflac Enterprise Connect API
The Aflac Enterprise Connect (AEC) API enables benefits administrators, HR platforms, and third-party enrollment systems to integrate with Aflac's supplemental insurance platform programmatically. It provides REST API access to benefits enrollment, policy management, claims status, and eligibility verification for group and individual supplemental insurance products. The API supports electronic benefits enrollment workflows replacing traditional EDI 834 file exchanges, enabling real-time enrollment confirmation and policy administration for employers and their benefits technology partners.

**Human URL:** [https://docs.enterprise-connect.aflac.com](https://docs.enterprise-connect.aflac.com)

#### Tags:

 - Benefits, Enrollment, Insurance, Supplemental Insurance, Workforce

#### Properties

- [Documentation](https://docs.enterprise-connect.aflac.com)
- [GettingStarted](https://docs.enterprise-connect.aflac.com/docs/getting-started)
- [OpenAPI](openapi/aflac-enterprise-connect-openapi.yml)

### Aflac Claims API
The Aflac Claims API provides programmatic access to supplemental insurance claim submission, status retrieval, and benefit payment tracking. It enables policyholders and administrators to submit claims digitally, track claim processing status, and receive benefit payment notifications. The API supports claims for Aflac's portfolio of supplemental products including accident, critical illness, cancer, hospital indemnity, and short-term disability insurance.

**Human URL:** [https://docs.enterprise-connect.aflac.com](https://docs.enterprise-connect.aflac.com)

#### Tags:

 - Claims, Insurance, Payments, Supplemental Insurance

#### Properties

- [Documentation](https://docs.enterprise-connect.aflac.com)

## Common Properties

- [Portal](https://docs.enterprise-connect.aflac.com)
- [Website](https://www.aflac.com)
- [SignUp](https://www.aflac.com/business/default.aspx)
- [TermsOfService](https://www.aflac.com/about-aflac/legal/terms-and-conditions.aspx)
- [PrivacyPolicy](https://www.aflac.com/about-aflac/legal/privacy-policy.aspx)
- [Support](https://www.aflac.com/contact-aflac/default.aspx)

## Features

| Name | Description |
|------|-------------|
| Electronic Benefits Enrollment | Replace EDI 834 file-based enrollment with real-time API-driven enrollment workflows for supplemental insurance products. |
| Policy Administration | Manage group and individual supplemental insurance policies including enrollments, terminations, and coverage changes. |
| Claims Submission | Enable digital claim filing for supplemental insurance products including accident, critical illness, cancer, and disability coverage. |
| Eligibility Verification | Verify employee eligibility for Aflac supplemental insurance products in real time during enrollment. |
| Benefits Administration Integration | Connect benefits administration platforms with Aflac's enrollment and policy systems via standardized REST APIs. |
| Real-Time Enrollment Confirmation | Receive immediate enrollment confirmation and policy numbers upon successful enrollment submission. |

## Use Cases

| Name | Description |
|------|-------------|
| HR Platform Integration | HR and benefits administration platforms integrate with Aflac's API to offer supplemental insurance enrollment within their existing benefits workflows. |
| Employer Self-Service Enrollment | Employers manage supplemental insurance enrollments for employees during open enrollment periods via connected benefits platforms. |
| Claims Tracking | Employees and HR teams track the status of Aflac supplemental insurance claims submitted after a qualifying health event. |
| Benefits Broker Workflow | Benefits brokers manage group policy setup, employee enrollment, and plan changes for employer clients through integrated tools. |

## Integrations

| Name | Description |
|------|-------------|
| Employee Navigator | Aflac connects with Employee Navigator benefits administration platform for automated enrollment data exchange. |
| Benefitfocus | Integration with Benefitfocus benefits marketplace for supplemental insurance enrollment. |
| ADP | Payroll and HR integration with ADP for Aflac premium deduction and enrollment synchronization. |
| Workday | Enterprise HR platform integration for benefits enrollment and Aflac policy administration. |
| bswift | Benefits administration platform integration for Aflac group enrollment. |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [aflac-enterprise-connect-openapi](openapi/aflac-enterprise-connect-openapi.yml)

### JSON Schema

- [enterprise-connect-claim-list-schema](json-schema/enterprise-connect-claim-list-schema.json)
- [enterprise-connect-claim-request-schema](json-schema/enterprise-connect-claim-request-schema.json)
- [enterprise-connect-claim-schema](json-schema/enterprise-connect-claim-schema.json)
- [enterprise-connect-dependent-schema](json-schema/enterprise-connect-dependent-schema.json)
- [enterprise-connect-eligibility-request-schema](json-schema/enterprise-connect-eligibility-request-schema.json)
- [enterprise-connect-eligibility-response-schema](json-schema/enterprise-connect-eligibility-response-schema.json)
- [enterprise-connect-enrollment-list-schema](json-schema/enterprise-connect-enrollment-list-schema.json)
- [enterprise-connect-enrollment-request-schema](json-schema/enterprise-connect-enrollment-request-schema.json)
- [enterprise-connect-enrollment-schema](json-schema/enterprise-connect-enrollment-schema.json)
- [enterprise-connect-group-list-schema](json-schema/enterprise-connect-group-list-schema.json)
- [enterprise-connect-group-schema](json-schema/enterprise-connect-group-schema.json)
- [enterprise-connect-policy-list-schema](json-schema/enterprise-connect-policy-list-schema.json)
- [enterprise-connect-policy-schema](json-schema/enterprise-connect-policy-schema.json)

### JSON Structure

- [enterprise-connect-claim-list-structure](json-structure/enterprise-connect-claim-list-structure.json)
- [enterprise-connect-claim-request-structure](json-structure/enterprise-connect-claim-request-structure.json)
- [enterprise-connect-claim-structure](json-structure/enterprise-connect-claim-structure.json)
- [enterprise-connect-dependent-structure](json-structure/enterprise-connect-dependent-structure.json)
- [enterprise-connect-eligibility-request-structure](json-structure/enterprise-connect-eligibility-request-structure.json)
- [enterprise-connect-eligibility-response-structure](json-structure/enterprise-connect-eligibility-response-structure.json)
- [enterprise-connect-enrollment-list-structure](json-structure/enterprise-connect-enrollment-list-structure.json)
- [enterprise-connect-enrollment-request-structure](json-structure/enterprise-connect-enrollment-request-structure.json)
- [enterprise-connect-enrollment-structure](json-structure/enterprise-connect-enrollment-structure.json)
- [enterprise-connect-group-list-structure](json-structure/enterprise-connect-group-list-structure.json)
- [enterprise-connect-group-structure](json-structure/enterprise-connect-group-structure.json)
- [enterprise-connect-policy-list-structure](json-structure/enterprise-connect-policy-list-structure.json)
- [enterprise-connect-policy-structure](json-structure/enterprise-connect-policy-structure.json)

### JSON-LD

- [aflac-enterprise-context](json-ld/aflac-enterprise-context.jsonld)

### Examples

- [enterprise-connect-claim-example](examples/enterprise-connect-claim-example.json)
- [enterprise-connect-claim-list-example](examples/enterprise-connect-claim-list-example.json)
- [enterprise-connect-claim-request-example](examples/enterprise-connect-claim-request-example.json)
- [enterprise-connect-dependent-example](examples/enterprise-connect-dependent-example.json)
- [enterprise-connect-eligibility-request-example](examples/enterprise-connect-eligibility-request-example.json)
- [enterprise-connect-eligibility-response-example](examples/enterprise-connect-eligibility-response-example.json)
- [enterprise-connect-enrollment-example](examples/enterprise-connect-enrollment-example.json)
- [enterprise-connect-enrollment-list-example](examples/enterprise-connect-enrollment-list-example.json)
- [enterprise-connect-enrollment-request-example](examples/enterprise-connect-enrollment-request-example.json)
- [enterprise-connect-group-example](examples/enterprise-connect-group-example.json)
- [enterprise-connect-group-list-example](examples/enterprise-connect-group-list-example.json)
- [enterprise-connect-policy-example](examples/enterprise-connect-policy-example.json)
- [enterprise-connect-policy-list-example](examples/enterprise-connect-policy-list-example.json)

## Capabilities

Naftiko capabilities organized as shared per-API definitions composed into customer-facing workflows.

### Shared Per-API Definitions

- [enterprise-connect](capabilities/shared/enterprise-connect.yaml)

### Workflow Capabilities

| Workflow | APIs Combined | Tools | Persona |
|----------|--------------|-------|---------|
| [Aflac Benefits Administration](capabilities/benefits-administration.yaml) | aflac-enterprise-connect | 6 | HR Platform Engineer |

## Vocabulary

- [Aflac Vocabulary](vocabulary/aflac-vocabulary.yaml) — Unified taxonomy mapping resources, actions, workflows, and personas

## Rules

- [aflac-spectral-rules](rules/aflac-spectral-rules.yml) — 24 rules enforcing Aflac API conventions

## Maintainers

**FN:** Kin Lane

**Email:** info@apievangelist.com
