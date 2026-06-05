# Flux (flux)

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
