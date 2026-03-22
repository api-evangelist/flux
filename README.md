# Flux (flux)
An open-source text-to-image AI model developed by Black Forest Labs that generates high-quality images from text prompts with improved prompt following and visual quality.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/flux/refs/heads/main/apis.yml)

## Scope

- **Type:** Index 
- **Position:** Consuming 
- **Access:** 3rd-Party 

## Tags:

 - AI, Image Generation, Machine Learning, Text To Image, Open Source

## Timestamps

- **Created:** 2025-01-01 
- **Modified:** 2026-03-18 

## APIs

### Flux Image Generation API
REST API for generating images from text prompts using Black Forest Labs' FLUX models, including FLUX.1 [pro], FLUX.1 [dev], FLUX.1 [schnell], and FLUX.2 variants. The API follows an asynchronous pattern where requests return a polling URL to retrieve the completed image result.

**Human URL:** [https://docs.bfl.ai/](https://docs.bfl.ai/)


#### Tags:

 - Image Generation, Text To Image, AI, Machine Learning

#### Properties

- [Documentation](https://docs.bfl.ai/)
- [Getting Started](https://docs.bfl.ml/quick_start/generating_images)
- [Authentication](https://docs.bfl.ai/)
- [OpenAPI](openapi/flux-image-generation-openapi.yml)
- [JSONSchema](json-schema/flux-generation-request-schema.json)

### Flux Image Editing API
REST API for editing and transforming existing images using the FLUX.1 Kontext models. Accepts an input image and a text prompt describing desired edits, and returns a modified image. Supports context-aware in-painting, style transfer, and image-to-image transformations.

**Human URL:** [https://docs.bfl.ml/kontext/kontext_image_editing](https://docs.bfl.ml/kontext/kontext_image_editing)


#### Tags:

 - Image Editing, Image To Image, AI, Kontext

#### Properties

- [Documentation](https://docs.bfl.ml/kontext/kontext_image_editing)
- [OpenAPI](openapi/flux-image-editing-openapi.yml)

## Common Properties

- [JSON-LD](json-ld/flux-context.jsonld)
- [JSONSchema](json-schema/flux-generation-request-schema.json)
- [Website](https://bfl.ai/)
- [Documentation](https://docs.bfl.ai/)
- [Getting Started](https://docs.bfl.ml/quick_start/generating_images)
- [GitHub Organization](https://github.com/black-forest-labs)
- [GitHubRepository](https://github.com/black-forest-labs/flux)
- [Blog](https://bfl.ai/blog)
- [Change Log](https://docs.bfl.ai/release-notes)
- [Terms of Service](https://bfl.ai/legal/flux-api-service-terms)
- [Privacy Policy](https://bfl.ai/legal/privacy-policy)
- [Sign Up](https://auth.bfl.ai/register)

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
