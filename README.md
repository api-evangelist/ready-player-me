# Ready Player Me (ready-player-me)

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

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/ready-player-me/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/ready-player-me/refs/heads/main/apis.yml)

## Scope

- **Access:** 3rd-Party

## Tags

- Avatars
- 3D
- Gaming
- VR
- AR
- Metaverse
- glTF
- Cross-Platform
- Unity
- Unreal
- Web
- Mobile

## APIs

### Ready Player Me Avatars API

Create, retrieve, update, and delete Ready Player Me cross-platform avatars. Includes template-based creation, asset equipping, draft management, color palette discovery, and binary glTF (.glb) plus 2D PNG renders used in Unity, Unreal, web, iOS, and Android. Supports A/T-pose, mesh LODs, texture atlases, ARKit / Oculus morph targets, Draco and Meshopt compression.

- **Human URL:** [https://docs.readyplayer.me/ready-player-me/api-reference](https://docs.readyplayer.me/ready-player-me/api-reference)
- **Base URL:** `https://api.readyplayer.me/`

#### Tags

- Avatars
- 3D
- GLB
- Gaming

#### Properties

- [Documentation](https://docs.readyplayer.me/ready-player-me/api-reference)
- [OpenAPI](openapi/ready-player-me-avatars-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/ready-player-me-avatars-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/ready-player-me-avatars-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Ready Player Me Assets API

Discover and retrieve avatar wearable assets — hair, outfits, headwear, glasses, facewear, footwear, beards, costumes, and custom assets — scoped to an application and optionally filtered to those viewable or usable by a specific user. Powers the wardrobe surface of the Ready Player Me Avatar Creator.

- **Human URL:** [https://docs.readyplayer.me/ready-player-me/api-reference/rest-api/assets](https://docs.readyplayer.me/ready-player-me/api-reference/rest-api/assets)
- **Base URL:** `https://api.readyplayer.me/`

#### Tags

- Assets
- Wearables
- 3D
- Gaming

#### Properties

- [Documentation](https://docs.readyplayer.me/ready-player-me/api-reference/rest-api/assets)
- [OpenAPI](openapi/ready-player-me-assets-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/ready-player-me-assets-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/ready-player-me-assets-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Ready Player Me Auth API

Anonymous user creation, email-code login, token refresh, and avatar access tokens used by the Ready Player Me Avatar Creator and SDKs. Authentication runs through each application's per-studio subdomain.

- **Human URL:** [https://docs.readyplayer.me/ready-player-me/api-reference/rest-api/users](https://docs.readyplayer.me/ready-player-me/api-reference/rest-api/users)
- **Base URL:** `https://api.readyplayer.me/`

#### Tags

- Authentication
- Identity
- Users

#### Properties

- [Documentation](https://docs.readyplayer.me/ready-player-me/api-reference/rest-api/users)
- [OpenAPI](openapi/ready-player-me-auth-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/ready-player-me-auth-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/ready-player-me-auth-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Portal](https://readyplayer.me/)
- [Documentation](https://docs.readyplayer.me/)
- [Documentation](https://docs.readyplayer.me/ready-player-me/api-reference)
- [Documentation](https://docs.readyplayer.me/ready-player-me/integration-guides)
- [Portal](https://studio.readyplayer.me/)
- [Portal](https://readyplayer.me/developers)
- [Portal](https://readyplayer.me/hub)
- [Blog](https://readyplayer.me/blog)
- [Github](https://github.com/readyplayerme)
- [LinkedIn](https://www.linkedin.com/company/ready-player-me/)
- [Twitter](https://twitter.com/readyplayerme)
- [YouTube](https://www.youtube.com/@readyplayerme)
- [Discord](https://discord.com/invite/readyplayerme)
- [Support](mailto:support@readyplayer.me)
- [SDK](https://github.com/readyplayerme/rpm-unity-sdk-core)
- [SDK](https://github.com/readyplayerme/rpm-unreal-sdk)
- [SDK](https://github.com/readyplayerme/visage)
- [SDK](https://github.com/readyplayerme/rpm-react-avatar-creator)
- [SDK](https://github.com/readyplayerme/Example-iOS-Swift)
- [SDK](https://github.com/readyplayerme/Example-Android-Kotlin)
- [SDK](https://github.com/readyplayerme/Example-React-Native)
- [JSON Schema](https://github.com/readyplayerme/content-validation-schemas) — [JSON Schema](https://json-schema.org/specification)
- [Tools](https://github.com/readyplayerme/animation-library)
- [Plans](plans/ready-player-me-plans-pricing.yml)
- [Rate Limits](rate-limits/ready-player-me-rate-limits.yml)
- [Fin Ops](finops/ready-player-me-finops.yml)
- [Vocabulary](vocabulary/ready-player-me-vocabulary.yml)
- [JSON-LD](json-ld/ready-player-me-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)

## Maintainers

**FN:** Kin Lane
**Email:** info@apievangelist.com
**URL:** http://apievangelist.com
