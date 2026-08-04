# Flux (flux)

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

An open-source text-to-image AI model developed by Black Forest Labs that generates high-quality images from text prompts with improved prompt following and visual quality.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/flux/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/flux/refs/heads/main/apis.yml)

## Scope

- **Type:** Index

## Tags

- AI
- Image Generation
- Machine Learning
- Open Source
- Text to Image

## Timestamps

- **Created:** 2025-01-01
- **Modified:** 2026-05-19

## APIs

### Flux Image Generation API

REST API for generating images from text prompts using Black Forest Labs' FLUX models, including FLUX.1 [pro], FLUX.1 [dev], FLUX.1 [schnell], and FLUX.2 variants. The API follows an asynchronous pattern where requests return a polling URL to retrieve the completed image result.

- **Human URL:** [https://docs.bfl.ai/](https://docs.bfl.ai/)
- **Base URL:** `https://api.bfl.ai/v1`

#### Tags

- AI
- Image Generation
- Machine Learning
- Text to Image

#### Properties

- [Documentation](https://docs.bfl.ai/)
- [Getting Started](https://docs.bfl.ml/quick_start/generating_images)
- [Authentication](https://docs.bfl.ai/)
- [OpenAPI](openapi/flux-image-generation-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/flux-image-generation.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/flux-image-generation.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/flux-generation-request-schema.json) — [JSON Schema](https://json-schema.org/specification)

### Flux Image Editing API

REST API for editing and transforming existing images using the FLUX.1 Kontext models. Accepts an input image and a text prompt describing desired edits, and returns a modified image. Supports context-aware in-painting, style transfer, and image-to-image transformations.

- **Human URL:** [https://docs.bfl.ml/kontext/kontext_image_editing](https://docs.bfl.ml/kontext/kontext_image_editing)
- **Base URL:** `https://api.bfl.ai/v1`

#### Tags

- AI
- Image Editing
- Image to Image
- Kontext

#### Properties

- [Documentation](https://docs.bfl.ml/kontext/kontext_image_editing)
- [OpenAPI](openapi/flux-image-editing-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/flux-image-editing.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/flux-image-editing.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [JSON-LD](json-ld/flux-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [JSON Schema](json-schema/flux-generation-request-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [Website](https://bfl.ai/)
- [Documentation](https://docs.bfl.ai/)
- [Getting Started](https://docs.bfl.ml/quick_start/generating_images)
- [GitHub Organization](https://github.com/black-forest-labs)
- [GitHub Repository](https://github.com/black-forest-labs/flux)
- [Blog](https://bfl.ai/blog)
- [Changelog](https://docs.bfl.ai/release-notes)
- [Terms of Service](https://bfl.ai/legal/flux-api-service-terms)
- [Privacy Policy](https://bfl.ai/legal/privacy-policy)
- [Sign Up](https://auth.bfl.ai/register)
- [M C P Server](https://github.com/black-forest-labs/flux-mcp)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
