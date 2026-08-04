# Microsoft Visio API (visio)

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

Microsoft Visio provides APIs for creating, editing, and managing Visio diagrams and drawings. The Visio JavaScript API enables developers to build Office Add-ins that interact with Visio diagrams embedded in SharePoint Online pages, accessing document elements such as pages, shapes, hyperlinks, comments, and shape data. Visio APIs support programmatic diagram manipulation, visual overlay creation, mouse event handling, and data visualization workflows.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/visio/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/visio/refs/heads/main/apis.yml)

## Scope

- **Type:** Index

## Tags

- Business Process
- Collaboration
- Diagrams
- Enterprise
- Flowcharts
- Microsoft 365
- Visualization

## Timestamps

- **Created:** 2024
- **Modified:** 2026-05-19

## APIs

### Visio JavaScript API

The Visio JavaScript API enables building Office Add-ins that interact with Visio diagrams embedded in classic SharePoint Online pages. The API provides access to document elements including pages, shapes, hyperlinks, comments, shape data items, and shape views. Developers can create visual markup overlays, register mouse event handlers, read shape text and shape data, and control application toolbar visibility. The API uses a request context and proxy object pattern with batch execution via Visio.run() and context.sync().

- **Human URL:** [https://learn.microsoft.com/en-us/office/dev/add-ins/visio/visio-overview](https://learn.microsoft.com/en-us/office/dev/add-ins/visio/visio-overview)
- **Base URL:** `https://appsforoffice.microsoft.com/embedded/1.0`

#### Tags

- Add-Ins
- Client-Side
- Diagrams
- JavaScript
- Office
- SharePoint
- Web

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/office/dev/add-ins/visio/visio-overview)
- [Reference](https://learn.microsoft.com/en-us/javascript/api/visio)
- [Getting Started](https://learn.microsoft.com/en-us/office/dev/add-ins/quickstarts/visio-quickstart)
- [Samples](https://github.com/OfficeDev/Office-Add-in-samples)
- [OpenAPI](openapi/visio-javascript-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/visio-javascript.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/visio-javascript.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Microsoft Graph Visio API

Access and manipulate Visio files stored in OneDrive and SharePoint through Microsoft Graph. While direct Visio-specific REST endpoints are limited, Microsoft Graph provides file management capabilities for Visio documents through the DriveItem resource, enabling upload, download, and metadata operations on .vsdx and .vsd files stored in SharePoint and OneDrive.

- **Human URL:** [https://learn.microsoft.com/en-us/graph/api/resources/visio](https://learn.microsoft.com/en-us/graph/api/resources/visio)
- **Base URL:** `https://graph.microsoft.com/v1.0`

#### Tags

- Cloud
- Collaboration
- Diagrams
- Enterprise
- Microsoft Graph
- OneDrive
- SharePoint

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/graph/api/resources/visio)
- [Authentication](https://learn.microsoft.com/en-us/graph/auth/)
- [S D Ks](https://learn.microsoft.com/en-us/graph/sdks/sdks-overview)
- [Postman Collection](collections/visio-javascript.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/visio-javascript.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Terms of Service](https://www.microsoft.com/en-us/legal/terms-of-use)
- [Privacy Policy](https://privacy.microsoft.com/en-us/privacystatement)
- [Developer  Portal](https://developer.microsoft.com/en-us/microsoft-365)
- [Status Page](https://status.office.com)
- [Pricing](https://www.microsoft.com/en-us/microsoft-365/visio/microsoft-visio-plans-and-pricing-compare-visio-options)
- [Blog](https://devblogs.microsoft.com/microsoft365dev/)
- [Changelog](https://learn.microsoft.com/en-us/javascript/api/overview/visio/release-notes)
- [OpenAPI](openapi/visio-javascript-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [JSON Schema](json-schema/visio-shape-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/visio-page-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](json-structure/visio-shape-structure.json)
- [JSON-LD](json-ld/visio-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [Vocabulary](vocabulary/visio-vocabulary.yml)
- [Spectral Rules](rules/visio-rules.yml)
- [Integrations](https://www.microsoft.com/en-us/marketplace)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
