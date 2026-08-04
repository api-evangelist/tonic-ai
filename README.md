# Tonic.ai (tonic-ai)

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

Tonic.ai builds developer-data products for de-identifying, subsetting, and synthesizing data for AI and software teams. The portfolio includes Tonic Structural (structured/semi-structured data), Tonic Textual (unstructured free-text and files), Tonic Validate (RAG evaluation), and Tonic Fabricate (relational synthetic data and mock APIs). Each product ships its own REST API and SDKs.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/tonic-ai/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/tonic-ai/refs/heads/main/apis.yml)

## Tags

- Synthetic Data
- De-Identification
- Privacy
- Unstructured Data
- RAG Evaluation
- REST
- SDK
- Developer Tools

## Timestamps

- **Created:** 2026-05-23
- **Modified:** 2026-05-23

## APIs

### Tonic Structural REST API

REST API for Tonic Structural - de-identify, subset, and synthesize structured and semi-structured data. Authentication via API token in the Authorization header (Authorization Apikey <token>). API tokens are created from User Settings and do not expire. All requests are versioned.

- **Human URL:** [https://docs.tonic.ai/app/api/api-documentation](https://docs.tonic.ai/app/api/api-documentation)
- **Base URL:** `https://app.tonic.ai`

#### Tags

- REST
- Structural
- Synthetic Data
- De-Identification

#### Properties

- [Documentation](https://docs.tonic.ai/app/api/api-documentation)
- [API Reference](https://app.tonic.ai/apidocs/index.html)
- [Get Token](https://docs.tonic.ai/app/api/tonic-api-get-token)
- [Examples](https://docs.tonic.ai/app/api/api-examples)
- [Postman Collection](collections/tonic-ai.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/tonic-ai.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Tonic Textual REST API

REST API for Tonic Textual - de-identify, redact, and synthesize unstructured data, free-text, and files. Authentication via API key in the Authorization header. Backed by a Python SDK (tonic-textual).

- **Human URL:** [https://docs.tonic.ai/textual](https://docs.tonic.ai/textual)
- **Base URL:** `https://textual.tonic.ai/api`

#### Tags

- REST
- Textual
- Unstructured
- Redaction

#### Properties

- [Documentation](https://docs.tonic.ai/textual/textual-rest-api/rest-api-authentication)
- [SDK](https://tonic-textual-sdk.readthedocs-hosted.com/en/latest/index.html)
- [Postman Collection](collections/tonic-ai.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/tonic-ai.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Tonic Validate

Tonic Validate is an open-source RAG evaluation framework and metrics platform for measuring retrieval-augmented generation quality. Used via a Python SDK that reports runs to the Tonic Validate web UI.

- **Human URL:** [https://www.tonic.ai/products/validate](https://www.tonic.ai/products/validate)
- **Base URL:** `https://validate.tonic.ai`

#### Tags

- RAG
- Evaluation
- Metrics
- SDK
- Python

#### Properties

- [Product Page](https://www.tonic.ai/products/validate)
- [Source Code](https://github.com/TonicAI/tonic_validate)
- [Postman Collection](collections/tonic-ai.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/tonic-ai.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Tonic Fabricate

Tonic Fabricate generates synthetic relational data, free-text, and mockable APIs from a schema definition. Used through the Fabricate web app and project APIs.

- **Human URL:** [https://www.tonic.ai/products/fabricate](https://www.tonic.ai/products/fabricate)
- **Base URL:** `https://fabricate.tonic.ai`

#### Tags

- Synthetic Data
- Relational
- Mock API

#### Properties

- [Product Page](https://www.tonic.ai/products/fabricate)
- [Documentation](https://docs.tonic.ai/fabricate)
- [Postman Collection](collections/tonic-ai.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/tonic-ai.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Website](https://www.tonic.ai/)
- [Documentation](https://docs.tonic.ai/)
- [Git Hub](https://github.com/TonicAI)
- [LinkedIn](https://www.linkedin.com/company/tonicfakedata)
- [Plans](plans/tonic-ai-plans-pricing.yml)
- [Rate Limits](rate-limits/tonic-ai-rate-limits.yml)
- [Fin Ops](finops/tonic-ai-finops.yml)
- [L L Ms Txt](https://docs.tonic.ai/llms.txt)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
