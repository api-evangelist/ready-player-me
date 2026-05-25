# Ready Player Me

Ready Player Me is a cross-platform avatar API for games and applications. A single Ready Player Me avatar can be created once and then loaded across Unity, Unreal, web, iOS, and Android via binary glTF (`.glb`) and 2D PNG renders, with consistent rigging, ARKit / Oculus morph targets, mesh LODs, and texture atlas options. Founded in 2014 in Tallinn, Estonia (originally as Wolf3D / Wolfprint 3D), the platform reaches developers through the Avatar Creator iframe, Studio dashboard, official SDKs, and the `api.readyplayer.me` REST surface profiled here.

This profile is a Tier-1 catalog entry: the OpenAPI specifications, JSON Schemas, JSON-LD context, Naftiko capabilities, vocabulary, and Spectral ruleset are all generated against the real Ready Player Me API surface as observed in the official Unity, Unreal, Visage, React Avatar Creator, and example SDKs hosted at <https://github.com/readyplayerme>.

## APIs

- **Ready Player Me Avatars API** — Create, retrieve, update, and delete avatars; equip assets; manage drafts; mint GLB and PNG renders. ([OpenAPI](openapi/ready-player-me-avatars-api-openapi.yml))
- **Ready Player Me Assets API** — Discover and retrieve avatar wearables — hair, outfits, headwear, glasses, footwear, beards, costumes, and custom assets. ([OpenAPI](openapi/ready-player-me-assets-api-openapi.yml))
- **Ready Player Me Auth API** — Anonymous user creation, email-code login, token refresh, and avatar access tokens via the per-application Studio subdomain. ([OpenAPI](openapi/ready-player-me-auth-api-openapi.yml))

## Artifacts

| Artifact | Path |
|---|---|
| OpenAPI specs | [`openapi/`](openapi/) |
| JSON Schemas | [`json-schema/`](json-schema/) |
| JSON Structure | [`json-structure/`](json-structure/) |
| JSON-LD context | [`json-ld/ready-player-me-context.jsonld`](json-ld/ready-player-me-context.jsonld) |
| Examples | [`examples/`](examples/) |
| Naftiko capabilities | [`capabilities/`](capabilities/) |
| Vocabulary | [`vocabulary/ready-player-me-vocabulary.yml`](vocabulary/ready-player-me-vocabulary.yml) |
| Spectral ruleset | [`rules/ready-player-me-rules.yml`](rules/ready-player-me-rules.yml) |
| Plans & pricing | [`plans/ready-player-me-plans-pricing.yml`](plans/ready-player-me-plans-pricing.yml) |
| Rate limits | [`rate-limits/ready-player-me-rate-limits.yml`](rate-limits/ready-player-me-rate-limits.yml) |
| FinOps alignment | [`finops/ready-player-me-finops.yml`](finops/ready-player-me-finops.yml) |

## Authentication

All Ready Player Me Avatars and Assets endpoints are scoped per application via the `X-APP-ID` header. The Auth API runs on a per-application Studio subdomain (`https://<subdomain>.readyplayer.me/api/...`) and issues `token` / `refreshToken` pairs that downstream renders and avatar mutations use to act on behalf of an end user.

## SDKs

Ready Player Me ships first-party SDKs for Unity, Unreal, web (Visage / `three.js`), React, iOS, and Android, plus a `content-validation-schemas` repo containing JSON Schemas that validate 3D asset compatibility before they enter the avatar pipeline. The full SDK catalog is enumerated in [`apis.yml`](apis.yml).

## License & access

Catalog content is published under the [API Commons](https://github.com/apievangelist/apis-commons) framework. Ready Player Me APIs themselves are operated by Ready Player Me under the company's developer terms; see <https://docs.readyplayer.me/> for current availability.
