# Aflac

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

Aflac is America's leading provider of supplemental insurance, paying benefits when a policyholder has an accident, illness, or injury. Aflac runs its own integration-API platform, Aflac Enterprise Connect (AEC), on AWS API Gateway in front of Java and .NET services, and publishes the platform's design rules openly at docs.enterprise-connect.aflac.com: a layered service taxonomy (experience, process, core, system, aspect), a strict resource-path grammar, a mandated general-response envelope, a mandatory health endpoint on every API, and a complete enterprise canonical data model (EDS v2020, roughly 90 canonicals across 20 libraries). The portal is written for Aflac application teams, not outside partners: the service catalog, Swagger console and spec builder sit behind a PingIdentity login, OAuth 2.0 client-credentials is the only supported authentication, and credentials are issued by internal request. The design documentation is public; the contracts and endpoints are not.

**Areas:** Fortune 500 · Insurance · Supplemental Insurance · Employee Benefits · Claims · Enrollment · Policy Administration · Enterprise Integration

## Aflac on APIs.io

Everything profiled for Aflac is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/aflac/](https://apis.io/providers/aflac/)** — or go straight to one of the APIs or properties below.

### APIs (6)

- [Aflac Claims API](https://apis.io/apis/aflac/claims-api/) — The Aflac Claims API provides programmatic access to supplemental insurance claim submission, status retrieval, and benefit payment tracking. It enables…
- [aflac Claims API](https://apis.io/apis/aflac/aflac-claims-api/) — Claims submission and status retrieval operations.
- [aflac Eligibility API](https://apis.io/apis/aflac/aflac-eligibility-api/) — Employee eligibility verification operations.
- [aflac Enrollment API](https://apis.io/apis/aflac/aflac-enrollment-api/) — Benefits enrollment operations for supplemental insurance products.
- [aflac Groups API](https://apis.io/apis/aflac/aflac-groups-api/) — Employer group management operations.
- [aflac Policies API](https://apis.io/apis/aflac/aflac-policies-api/) — Policy management and retrieval operations.

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Aflac Agentic Access](https://apis.io/agentic-access/aflac/aflac-agentic-access/)

#### JSON Schema (13)

The data models the API reads and writes.

- [Claim](https://apis.io/schemas/aflac/enterprise-connect-claim/)
- [ClaimList](https://apis.io/schemas/aflac/enterprise-connect-claim-list/)
- [ClaimRequest](https://apis.io/schemas/aflac/enterprise-connect-claim-request/)
- [Dependent](https://apis.io/schemas/aflac/enterprise-connect-dependent/)
- [EligibilityRequest](https://apis.io/schemas/aflac/enterprise-connect-eligibility-request/)
- [EligibilityResponse](https://apis.io/schemas/aflac/enterprise-connect-eligibility-response/)
- [Enrollment](https://apis.io/schemas/aflac/enterprise-connect-enrollment/)
- [EnrollmentList](https://apis.io/schemas/aflac/enterprise-connect-enrollment-list/)
- [EnrollmentRequest](https://apis.io/schemas/aflac/enterprise-connect-enrollment-request/)
- [Group](https://apis.io/schemas/aflac/enterprise-connect-group/)
- [GroupList](https://apis.io/schemas/aflac/enterprise-connect-group-list/)
- [Policy](https://apis.io/schemas/aflac/enterprise-connect-policy/)
- [PolicyList](https://apis.io/schemas/aflac/enterprise-connect-policy-list/)

#### JSON Structure (13)

Data models expressed in JSON Structure.

- [Enterprise Connect Claim List Structure](https://apis.io/json-structure/aflac/enterprise-connect-claim-list-structure/)
- [Enterprise Connect Claim Request Structure](https://apis.io/json-structure/aflac/enterprise-connect-claim-request-structure/)
- [Enterprise Connect Claim Structure](https://apis.io/json-structure/aflac/enterprise-connect-claim-structure/)
- [Enterprise Connect Dependent Structure](https://apis.io/json-structure/aflac/enterprise-connect-dependent-structure/)
- [Enterprise Connect Eligibility Request Structure](https://apis.io/json-structure/aflac/enterprise-connect-eligibility-request-structure/)
- [Enterprise Connect Eligibility Response Structure](https://apis.io/json-structure/aflac/enterprise-connect-eligibility-response-structure/)
- [Enterprise Connect Enrollment List Structure](https://apis.io/json-structure/aflac/enterprise-connect-enrollment-list-structure/)
- [Enterprise Connect Enrollment Request Structure](https://apis.io/json-structure/aflac/enterprise-connect-enrollment-request-structure/)
- [Enterprise Connect Enrollment Structure](https://apis.io/json-structure/aflac/enterprise-connect-enrollment-structure/)
- [Enterprise Connect Group List Structure](https://apis.io/json-structure/aflac/enterprise-connect-group-list-structure/)
- [Enterprise Connect Group Structure](https://apis.io/json-structure/aflac/enterprise-connect-group-structure/)
- [Enterprise Connect Policy List Structure](https://apis.io/json-structure/aflac/enterprise-connect-policy-list-structure/)
- [Enterprise Connect Policy Structure](https://apis.io/json-structure/aflac/enterprise-connect-policy-structure/)

#### JSON-LD (1)

Linked-data contexts for the provider's vocabulary.

- [Aflac Enterprise Context](https://apis.io/jsonld/aflac/aflac-enterprise-context/)

#### Vocabulary (1)

The provider's domain terms, defined.

- [Aflac Vocabulary](https://apis.io/vocabularies/aflac/aflac-vocabulary/)

#### Examples (13)

Example requests and responses.

- [Enterprise Connect Claim Example](https://apis.io/examples/aflac/enterprise-connect-claim-example/)
- [Enterprise Connect Claim List Example](https://apis.io/examples/aflac/enterprise-connect-claim-list-example/)
- [Enterprise Connect Claim Request Example](https://apis.io/examples/aflac/enterprise-connect-claim-request-example/)
- [Enterprise Connect Dependent Example](https://apis.io/examples/aflac/enterprise-connect-dependent-example/)
- [Enterprise Connect Eligibility Request Example](https://apis.io/examples/aflac/enterprise-connect-eligibility-request-example/)
- [Enterprise Connect Eligibility Response Example](https://apis.io/examples/aflac/enterprise-connect-eligibility-response-example/)
- [Enterprise Connect Enrollment Example](https://apis.io/examples/aflac/enterprise-connect-enrollment-example/)
- [Enterprise Connect Enrollment List Example](https://apis.io/examples/aflac/enterprise-connect-enrollment-list-example/)
- [Enterprise Connect Enrollment Request Example](https://apis.io/examples/aflac/enterprise-connect-enrollment-request-example/)
- [Enterprise Connect Group Example](https://apis.io/examples/aflac/enterprise-connect-group-example/)
- [Enterprise Connect Group List Example](https://apis.io/examples/aflac/enterprise-connect-group-list-example/)
- [Enterprise Connect Policy Example](https://apis.io/examples/aflac/enterprise-connect-policy-example/)
- [Enterprise Connect Policy List Example](https://apis.io/examples/aflac/enterprise-connect-policy-list-example/)

#### Collections (6)

Postman and Open Collection request collections.

- [Aflac Enterprise Connect Claims API](https://apis.io/collections/aflac/open-aflac-claims-api/)
- [Aflac Enterprise Connect Claims Eligibility API](https://apis.io/collections/aflac/open-aflac-eligibility-api/)
- [Aflac Enterprise Connect Claims Enrollment API](https://apis.io/collections/aflac/open-aflac-enrollment-api/)
- [Aflac Enterprise Connect API](https://apis.io/collections/aflac/open-aflac-enterprise-connect/)
- [Aflac Enterprise Connect Claims Groups API](https://apis.io/collections/aflac/open-aflac-groups-api/)
- [Aflac Enterprise Connect Claims Policies API](https://apis.io/collections/aflac/open-aflac-policies-api/)

#### Governance rules (2)

Spectral rulesets for the provider's contracts.

- [Aflac — jsonschema rules](https://apis.io/rules/aflac/aflac-jsonschema-spectral-rules/)
- [Aflac API Rules](https://apis.io/rules/aflac/aflac-spectral-rules/)

#### Security (2)

Authentication, trust centre, and vulnerability disclosure.

- [Aflac Authentication](https://apis.io/security/aflac/aflac-authentication/)
- [Aflac Domain Security](https://apis.io/security/aflac/aflac-domain-security/)

#### OAuth scopes (1)

The permissions the API asks for.

- [Aflac Scopes](https://apis.io/scopes/aflac/aflac-scopes/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Aflac Plans Pricing](https://apis.io/plans/aflac/aflac-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Aflac Rate Limits](https://apis.io/rate-limits/aflac/aflac-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [Aflac Finops](https://apis.io/finops/aflac/aflac-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://www.aflac.com)
- [Documentation](https://docs.enterprise-connect.aflac.com/docs/index)
- [Getting started](https://docs.enterprise-connect.aflac.com/docs/onboarding)
- [API reference](https://docs.enterprise-connect.aflac.com/docs/developer-guide/app-team-controls/openapi-specification)
- [Support](https://www.aflac.com/contact-aflac/default.aspx)
- [Blog](https://newsroom.aflac.com/)
- [Terms of service](https://www.aflac.com/about-aflac/legal/terms-and-conditions.aspx)
- [Privacy policy](https://www.aflac.com/about-aflac/legal/privacy-policy.aspx)
- [GitHub](https://github.com/Aflac-SCM)

## API Evangelist rating

**Kin Score 36.8** — thin · rubric 0.24.0 · scored 2026-10-17

| Facet | Score |
|---|---|
| Discoverability | 78.6 |
| Contract quality | 27.8 |
| Contract governance | 45.5 |
| Operational transparency | 34.2 |
| Developer ergonomics | 35.7 |
| Access clarity | 18.4 |

**Agent readiness 36.3** — agent-ready

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
| Reversibility Documented | — |
| MCP Server | — |
| Auth Clarity | negotiable (partial credit) |
| Idempotency | — |
| Error Semantics | verified |
| OpenAPI Examples | verified |
| Rate Limit Signal | documented (partial credit) |
| Event Surface Described | — |
| Agent Skills | — |
| Well Known Catalog | yes |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |

**Regulatory alignment 29.8** — Insurance

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/aflac/](https://apis.io/providers/aflac/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Aflac: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/aflac/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
