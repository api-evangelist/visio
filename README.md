# Microsoft Visio API (visio)

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
