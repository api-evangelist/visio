# Microsoft Visio API (visio)

Microsoft Visio provides APIs for creating, editing, and managing Visio diagrams and drawings. The Visio JavaScript API enables developers to build Office Add-ins that interact with Visio diagrams embedded in SharePoint Online pages, accessing document elements such as pages, shapes, hyperlinks, comments, and shape data. Visio APIs support programmatic diagram manipulation, visual overlay creation, mouse event handling, and data visualization workflows.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/visio/refs/heads/main/apis.yml)

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
- **Modified:** 2026-05-03

## APIs

### Visio JavaScript API

The Visio JavaScript API enables building Office Add-ins that interact with Visio diagrams embedded in classic SharePoint Online pages. The API provides access to document elements including pages, shapes, hyperlinks, comments, shape data items, and shape views.

**Human URL:** [https://learn.microsoft.com/en-us/office/dev/add-ins/visio/visio-overview](https://learn.microsoft.com/en-us/office/dev/add-ins/visio/visio-overview)
**Base URL:** https://appsforoffice.microsoft.com/embedded/1.0

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
- [API Reference](https://learn.microsoft.com/en-us/javascript/api/visio)
- [Getting Started](https://learn.microsoft.com/en-us/office/dev/add-ins/quickstarts/visio-quickstart)
- [Samples](https://github.com/OfficeDev/Office-Add-in-samples)
- [OpenAPI](openapi/visio-javascript-openapi.yml)

### Microsoft Graph Visio API

Access and manipulate Visio files stored in OneDrive and SharePoint through Microsoft Graph.

**Human URL:** [https://learn.microsoft.com/en-us/graph/api/resources/visio](https://learn.microsoft.com/en-us/graph/api/resources/visio)
**Base URL:** https://graph.microsoft.com/v1.0

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
- [SDKs](https://learn.microsoft.com/en-us/graph/sdks/sdks-overview)

## Common Properties

- [Terms of Service](https://www.microsoft.com/en-us/legal/terms-of-use)
- [Privacy Policy](https://privacy.microsoft.com/en-us/privacystatement)
- [Developer Portal](https://developer.microsoft.com/en-us/microsoft-365)
- [Status Page](https://status.office.com)
- [Pricing](https://www.microsoft.com/en-us/microsoft-365/visio/microsoft-visio-plans-and-pricing-compare-visio-options)
- [Blog](https://devblogs.microsoft.com/microsoft365dev/)
- [Change Log](https://learn.microsoft.com/en-us/javascript/api/overview/visio/release-notes)

## Artifacts

| Type | File |
|------|------|
| OpenAPI | [openapi/visio-javascript-openapi.yml](openapi/visio-javascript-openapi.yml) |
| JSON Schema | [json-schema/visio-shape-schema.json](json-schema/visio-shape-schema.json) |
| JSON Schema | [json-schema/visio-page-schema.json](json-schema/visio-page-schema.json) |
| JSON Structure | [json-structure/visio-shape-structure.json](json-structure/visio-shape-structure.json) |
| JSON-LD | [json-ld/visio-context.jsonld](json-ld/visio-context.jsonld) |
| Spectral Rules | [rules/visio-rules.yml](rules/visio-rules.yml) |
| Vocabulary | [vocabulary/visio-vocabulary.yml](vocabulary/visio-vocabulary.yml) |

## Capabilities

### Shared Definitions

| API | File |
|-----|------|
| Visio JavaScript API | [capabilities/shared/visio-javascript.yaml](capabilities/shared/visio-javascript.yaml) |

### Workflow Capabilities

| Workflow | File | Description |
|----------|------|-------------|
| Diagram Automation | [capabilities/diagram-automation.yaml](capabilities/diagram-automation.yaml) | AI-assisted diagram inspection, shape data extraction, and visual presentation |

## Examples

- [List Pages](examples/visio-javascript-listPages-example.json)
- [List Shapes](examples/visio-javascript-listShapes-example.json)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
