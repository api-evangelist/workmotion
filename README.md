# WorkMotion (workmotion)

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
