# WorkMotion (workmotion)

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

WorkMotion is a global employment and Employer of Record (EOR) platform that lets companies compliantly hire, onboard, and pay international employees and contractors across 160+ countries. Its partner/Open API surfaces employee and contract data, onboarding workflows, absences and time-off, documents, employment cost calculations, and webhooks so HRIS and payroll systems can integrate with WorkMotion's managed employment infrastructure.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/workmotion/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/workmotion/refs/heads/main/apis.yml)

> Note: WorkMotion's partner API is access-gated and its reference is not fully published to the open web. The OpenAPI file and collections in this repo faithfully model the documented product surfaces; endpoints and the base URL are flagged as modeled (not confirmed) in `review.yml`.

## Tags

- Employer of Record
- EOR
- Global Employment
- HR
- Payroll
- Onboarding
- Contractors
- Compliance

## Timestamps

- **Created:** 2026-07-01
- **Modified:** 2026-07-01

## APIs

### WorkMotion Employees API

Read and manage employees (talents) employed through WorkMotion, including personal details, employment status, country of employment, and lifecycle state from onboarding through offboarding.

- **Human URL:** [https://workmotion.com/integrations/](https://workmotion.com/integrations/)
- **Base URL:** `https://api.workmotion.com/v1`

#### Tags

- Employees
- Workforce
- HR

#### Properties

- [Documentation](https://workmotion.com/integrations/)
- [OpenAPI](openapi/workmotion-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/workmotion.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/workmotion.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### WorkMotion Contracts API

Generate, retrieve, and amend legally compliant employment contracts for talents, including compensation terms, benefits, paid time off, and country specific contract changes.

- **Human URL:** [https://workmotion.com/contracts-changes/](https://workmotion.com/contracts-changes/)
- **Base URL:** `https://api.workmotion.com/v1`

#### Tags

- Contracts
- Employment
- Compliance

#### Properties

- [Documentation](https://workmotion.com/contracts-changes/)
- [OpenAPI](openapi/workmotion-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/workmotion.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/workmotion.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### WorkMotion Onboarding API

Initiate and track accelerated global onboarding, moving a new hire through country selection, talent details, contract generation, e-signature, and completion.

- **Human URL:** [https://workmotion.com/accelerated-onboarding/](https://workmotion.com/accelerated-onboarding/)
- **Base URL:** `https://api.workmotion.com/v1`

#### Tags

- Onboarding
- Hiring
- Workflow

#### Properties

- [Documentation](https://workmotion.com/accelerated-onboarding/)
- [OpenAPI](openapi/workmotion-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/workmotion.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/workmotion.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### WorkMotion Absences API

Submit, approve, and query employee absences and time-off requests (paid time off, sick leave, and other leave types) and read remaining leave balances.

- **Human URL:** [https://workmotion.com/integrations/](https://workmotion.com/integrations/)
- **Base URL:** `https://api.workmotion.com/v1`

#### Tags

- Absences
- Time Off
- PTO

#### Properties

- [Documentation](https://workmotion.com/integrations/)
- [OpenAPI](openapi/workmotion-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/workmotion.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/workmotion.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### WorkMotion Documents API

Upload, list, and download employment documents (contracts, payslips, compliance paperwork, and signed agreements) attached to a talent.

- **Human URL:** [https://workmotion.com/integrations/](https://workmotion.com/integrations/)
- **Base URL:** `https://api.workmotion.com/v1`

#### Tags

- Documents
- Files
- E-Signature

#### Properties

- [Documentation](https://workmotion.com/integrations/)
- [OpenAPI](openapi/workmotion-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/workmotion.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/workmotion.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### WorkMotion Cost Calculator API

Calculate the fully-loaded cost of employment for a given gross salary in a specific country, returning employer taxes, contributions, and benefits so employers can price an offer before hiring.

- **Human URL:** [https://workmotion.com/tools/employment-cost-calculator/](https://workmotion.com/tools/employment-cost-calculator/)
- **Base URL:** `https://api.workmotion.com/v1`

#### Tags

- Cost Calculator
- Employment Cost
- Compensation

#### Properties

- [Documentation](https://workmotion.com/tools/employment-cost-calculator/)
- [OpenAPI](openapi/workmotion-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/workmotion.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/workmotion.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### WorkMotion Webhooks API

Register and manage webhook subscriptions to receive event notifications for employee, contract, onboarding, and absence changes, keeping external HRIS and payroll systems in sync.

- **Human URL:** [https://workmotion.com/integrations/](https://workmotion.com/integrations/)
- **Base URL:** `https://api.workmotion.com/v1`

#### Tags

- Webhooks
- Events
- Notifications

#### Properties

- [Documentation](https://workmotion.com/integrations/)
- [OpenAPI](openapi/workmotion-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/workmotion.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/workmotion.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/workmotion)
- [Website](https://www.workmotion.com)
- [Documentation](https://workmotion.com/integrations/)
- [Plans](plans/workmotion-plans-pricing.yml)
- [Rate Limits](rate-limits/workmotion-rate-limits.yml)
- [Fin Ops](finops/workmotion-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
