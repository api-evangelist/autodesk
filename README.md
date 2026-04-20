# Autodesk (autodesk)

Autodesk is a global leader in design, engineering, and entertainment software, providing cloud-connected platform APIs through Autodesk Platform Services (APS). APS APIs enable developers to build applications that access design data, automate workflows, visualize 3D models, manage construction projects, create digital twins, and integrate sustainability data across Autodesk's product ecosystem including AutoCAD, Revit, Inventor, Maya, BIM 360, and Autodesk Construction Cloud.

**URL:** [https://raw.githubusercontent.com/api-evangelist/autodesk/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/autodesk/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - 3D Modeling, Architecture, BIM, CAD, Construction, Design, Digital Twins, Engineering, Manufacturing, Media and Entertainment, Sustainability

## Timestamps

- **Created:** 2024-11-13
- **Modified:** 2026-04-19

## APIs

### Autodesk Build Photos API

Provides a single, unified place to view and manage photos and videos in Autodesk Build. This is useful for documenting progress photos on construction projects.

**Human URL:** [https://aps.autodesk.com/blog/autodesk-build-photos-api](https://aps.autodesk.com/blog/autodesk-build-photos-api)

#### Tags:

 - Construction, Photos, Documentation

#### Properties

- [Documentation](https://aps.autodesk.com/blog/autodesk-build-photos-api)

### Autodesk Authentication API

The Authentication API provides OAuth 2.0 based authentication and authorization for Autodesk Platform Services, enabling applications to securely access user data across different services without directly handling user passwords.

**Human URL:** [https://aps.autodesk.com/developer/overview/authentication-api](https://aps.autodesk.com/developer/overview/authentication-api)

#### Tags:

 - Authentication, OAuth

#### Properties

- [Documentation](https://aps.autodesk.com/developer/overview/authentication-api)
- [APIReference](https://aps.autodesk.com/en/docs/oauth/v2/reference/http)
- [GettingStarted](https://aps.autodesk.com/en/docs/oauth/v2/tutorials)
- [OpenAPI](openapi/autodesk-authentication-openapi.yml)

### Autodesk Data Management API

The Data Management API enables management of data across Autodesk Docs, BIM 360 Docs, Fusion Team, and the Object Storage Service. It provides project navigation, folder management, and version control for items stored across Autodesk cloud services.

**Human URL:** [https://aps.autodesk.com/developer/overview/data-management-api](https://aps.autodesk.com/developer/overview/data-management-api)

#### Tags:

 - BIM 360, Data Management, Storage

#### Properties

- [Documentation](https://aps.autodesk.com/developer/overview/data-management-api)
- [GettingStarted](https://aps.autodesk.com/en/docs/data/v2/tutorials/)
- [OpenAPI](openapi/autodesk-data-management-openapi.yml)

### Autodesk Model Derivative API

The Model Derivative API translates designs into formats like SVF and SVF2 for rendering in the Viewer, supports over 60 file input formats, converts designs to STL and OBJ, and extracts object hierarchy trees, properties, and geometries for analysis.

**Human URL:** [https://aps.autodesk.com/developer/overview/model-derivative-api](https://aps.autodesk.com/developer/overview/model-derivative-api)

#### Tags:

 - 3D Models, File Conversion, Metadata

#### Properties

- [Documentation](https://aps.autodesk.com/developer/overview/model-derivative-api)
- [APIReference](https://aps.autodesk.com/en/docs/model-derivative/v2/reference/)
- [GettingStarted](https://aps.autodesk.com/en/docs/model-derivative/v2/tutorials/)
- [OpenAPI](openapi/autodesk-model-derivative-openapi.yml)

### Autodesk Design Automation API

The Automation API enables batch processing of design files, parameter adjustments, drawing generation, and data extraction at enterprise scale using AutoCAD, Revit, Inventor, 3ds Max, and Fusion cloud engines.

**Human URL:** [https://aps.autodesk.com/developer/overview/automation-api](https://aps.autodesk.com/developer/overview/automation-api)

#### Tags:

 - 3ds Max, AutoCAD, Automation, Fusion, Inventor, Revit

#### Properties

- [Documentation](https://aps.autodesk.com/developer/overview/automation-api)
- [OpenAPI](openapi/autodesk-design-automation-openapi.yml)

### Autodesk Viewer SDK

The Viewer SDK is a JavaScript library for building interactive web applications that display 2D and 3D design models. It supports various file formats, offers customizable toolbars, and provides a flexible extension framework for creating immersive design experiences.

**Human URL:** [https://aps.autodesk.com/developer/overview/viewer-sdk](https://aps.autodesk.com/developer/overview/viewer-sdk)

#### Tags:

 - 2D Visualization, 3D Visualization, Viewer

#### Properties

- [Documentation](https://aps.autodesk.com/developer/overview/viewer-sdk)
- [GettingStarted](https://aps.autodesk.com/en/docs/viewer/v7/developers_guide/)

### Autodesk Webhooks API

The Webhooks API enables applications to receive event notifications via POST requests to a callback URL, eliminating the need for continuous polling. It works with Data Management and Model Derivative APIs to monitor events like file modifications within projects.

**Human URL:** [https://aps.autodesk.com/webhooks-api](https://aps.autodesk.com/webhooks-api)

#### Tags:

 - Events, Notifications, Webhooks

#### Properties

- [Documentation](https://aps.autodesk.com/webhooks-api)
- [APIReference](https://aps.autodesk.com/en/docs/webhooks/v1/reference/)
- [GettingStarted](https://aps.autodesk.com/en/docs/webhooks/v1/tutorials/)
- [OpenAPI](openapi/autodesk-webhooks-openapi.yml)
- [AsyncAPI](asyncapi/autodesk-webhooks-asyncapi.yml)

### Autodesk Reality Capture API

The Reality Capture API uses photogrammetry techniques to generate high-resolution 3D models, point clouds, and orthophotos from photographs. It leverages cloud computing for structure-from-motion and multi-view-geometry algorithms.

**Human URL:** [https://aps.autodesk.com/developer/overview/reality-capture-api](https://aps.autodesk.com/developer/overview/reality-capture-api)

#### Tags:

 - 3D Models, Photogrammetry, Point Clouds, Reality Capture

#### Properties

- [Documentation](https://aps.autodesk.com/developer/overview/reality-capture-api)
- [GettingStarted](https://aps.autodesk.com/en/docs/reality-capture/v1/tutorials/create-3d-mesh-from-photos/)
- [OpenAPI](openapi/autodesk-reality-capture-openapi.yml)

### Autodesk AEC Data Model API

The AEC Data Model API provides direct cloud access to granular design data via GraphQL, enabling navigation through data structures from hubs and projects to individual elements and parameters.

**Human URL:** [https://aps.autodesk.com/developer/overview/aec-data-model-api](https://aps.autodesk.com/developer/overview/aec-data-model-api)

#### Tags:

 - AEC, BIM, Design Data, GraphQL

#### Properties

- [Documentation](https://aps.autodesk.com/developer/overview/aec-data-model-api)

### Autodesk Data Exchange API

The Data Exchange API enables seamless sharing of complete or selective 3D model data across BIM, CAD, and other business applications through Autodesk Docs.

**Human URL:** [https://aps.autodesk.com/developer/overview/data-exchange](https://aps.autodesk.com/developer/overview/data-exchange)

#### Tags:

 - BIM, CAD, Data Exchange, Interoperability

#### Properties

- [Documentation](https://aps.autodesk.com/developer/overview/data-exchange)
- [APIReference](https://aps.autodesk.com/en/docs/fdxgraph/v1/reference/graphql_endpoint/)
- [GettingStarted](https://aps.autodesk.com/en/docs/fdxgraph/v1/tutorials/getting_started/task1/)

### Autodesk Sustainability Data API

The Sustainability Data API provides access to regional environmental data through a standardized interface, enabling accurate carbon calculations and integration of trusted third-party sustainability datasets.

**Human URL:** [https://aps.autodesk.com/developer/overview/sustainability-data-api](https://aps.autodesk.com/developer/overview/sustainability-data-api)

#### Tags:

 - Carbon Calculations, Environmental Data, Sustainability

#### Properties

- [Documentation](https://aps.autodesk.com/developer/overview/sustainability-data-api)
- [APIReference](https://aps.autodesk.com/en/docs/sustainability/v3/reference/http/)
- [GettingStarted](https://aps.autodesk.com/en/docs/sustainability/v3/tutorials/tutorial_01/)
- [OpenAPI](openapi/autodesk-sustainability-data-openapi.yml)

### Autodesk Parameters API

The Parameters API manages parameter definitions and related metadata in the Autodesk platform cloud, including parameters, groups, collections, labels, and classifications.

**Human URL:** [https://aps.autodesk.com/developer/overview/parameters-api](https://aps.autodesk.com/developer/overview/parameters-api)

#### Tags:

 - BIM, Parameters, Revit

#### Properties

- [Documentation](https://aps.autodesk.com/developer/overview/parameters-api)
- [GettingStarted](https://aps.autodesk.com/en/docs/parameters/v1/tutorials/getting-started/)
- [OpenAPI](openapi/autodesk-parameters-openapi.yml)

### Autodesk Tandem Data API

The Tandem Data API enables reading BIM model data and reading/writing custom schema properties for facility management, facilitating digital twin integration.

**Human URL:** [https://aps.autodesk.com/developer/overview/tandem-data-api](https://aps.autodesk.com/developer/overview/tandem-data-api)

#### Tags:

 - Digital Twins, Facility Management, IoT

#### Properties

- [Documentation](https://aps.autodesk.com/developer/overview/tandem-data-api)
- [OpenAPI](openapi/autodesk-tandem-data-openapi.yml)

### Autodesk Flow Graph Engine API

The Flow Graph Engine API enables evaluation of Bifrost graphs in the cloud for media and entertainment workflows, allowing developers to offload heavy processing tasks to concurrent cloud operations.

**Human URL:** [https://aps.autodesk.com/developer/overview/flow-graph-engine-api](https://aps.autodesk.com/developer/overview/flow-graph-engine-api)

#### Tags:

 - Bifrost, Cloud Computing, Media and Entertainment

#### Properties

- [Documentation](https://aps.autodesk.com/developer/overview/flow-graph-engine-api)
- [APIReference](https://aps.autodesk.com/en/docs/flow_graph_engine/v1/reference/quick_reference/)
- [OpenAPI](openapi/autodesk-flow-graph-engine-openapi.yml)

### Autodesk ACC Account Admin API

The ACC Account Admin API automates the creation and management of projects, users, and company directories within Autodesk Construction Cloud.

**Human URL:** [https://aps.autodesk.com/en/docs/acc/v1/tutorials/admin](https://aps.autodesk.com/en/docs/acc/v1/tutorials/admin)

#### Tags:

 - Account Administration, Construction, Project Management

#### Properties

- [Documentation](https://aps.autodesk.com/developer/overview/autodesk-construction-cloud)
- [GettingStarted](https://aps.autodesk.com/en/docs/acc/v1/tutorials/admin)
- [APIReference](https://aps.autodesk.com/en/docs/acc/v1/reference)
- [OpenAPI](openapi/autodesk-acc-account-admin-openapi.yml)

### Autodesk BIM 360 API

The BIM 360 API enables integration with the BIM 360 cloud-based construction management platform, providing access to project data, documents, issues, and workflows.

**Human URL:** [https://aps.autodesk.com/developer/overview/bim-360-api](https://aps.autodesk.com/developer/overview/bim-360-api)

#### Tags:

 - BIM, Construction, Project Management

#### Properties

- [Documentation](https://aps.autodesk.com/developer/overview/bim-360-api)
- [APIReference](https://aps.autodesk.com/en/docs/bim360/v1/reference/)
- [OpenAPI](openapi/autodesk-bim360-openapi.yml)

## Common Properties

- [Portal](https://aps.autodesk.com/)
- [Blog](https://aps.autodesk.com/blog)
- [Support](https://aps.autodesk.com/en/support/get-help)
- [GettingStarted](https://aps.autodesk.com/en/docs/oauth/v2/tutorials/get-started-with-aps/)
- [TermsOfService](https://www.autodesk.com/company/legal-notices-trademarks/terms-of-service-autodesk360-web-services/autodesk-web-services-api-terms-of-service)
- [PrivacyPolicy](https://www.autodesk.com/company/legal-notices-trademarks/privacy-statement)
- [GitHubOrganization](https://github.com/autodesk-platform-services)
- [Documentation](https://aps.autodesk.com/developer/documentation)
- [Pricing](https://aps.autodesk.com/pricing)
- [Tutorials](https://tutorials.autodesk.io/)
- [Quickstart](https://get-started.aps.autodesk.com/)
- [StatusPage](https://health.autodesk.com/)
- [ChangeLog](https://aps.autodesk.com/developer/overview/changelog)
- [Console](https://aps.autodesk.com/myapps/)
- [YouTube](https://www.youtube.com/@autodesk)
- [StackOverflow](https://stackoverflow.com/questions/tagged/autodesk-forge+or+autodesk-aps)
- [Website](https://www.autodesk.com)

## Features

| Name | Description |
|------|-------------|
| OAuth 2.0 Authentication | Industry-standard OAuth 2.0 authentication enabling secure access to Autodesk platform services and user data across all APS APIs. |
| Design File Translation | Model Derivative API translates over 60 CAD file formats to web-viewable SVF and SVF2 formats, enabling browser-based 3D visualization. |
| Cloud Design Automation | Design Automation API enables batch processing of CAD operations at scale using cloud engines for AutoCAD, Revit, Inventor, and Fusion. |
| Digital Twins | Tandem Data API enables building digital twin applications by connecting BIM model data with IoT sensors, asset management, and facility systems. |
| Construction Cloud Integration | ACC APIs provide programmatic access to construction project management, issues, RFIs, submittals, cost, and coordination data. |
| Sustainability Data | Access to regional environmental and carbon emissions data for integrating sustainability calculations into design workflows. |
| Reality Capture | Photogrammetry-based 3D model generation from photographs using cloud-scale structure-from-motion algorithms. |

## Use Cases

| Name | Description |
|------|-------------|
| Custom Viewer Applications | Building web applications that display BIM and CAD models using the Viewer SDK with custom extensions, toolbars, and interactive features. |
| Construction Project Automation | Automating construction project workflows through ACC APIs for issues, RFIs, submittals, and cost management with ERP and MES integrations. |
| Digital Twin Development | Building facility digital twin applications connecting BIM data with live IoT sensor streams, maintenance systems, and energy monitoring. |
| Design Batch Processing | Automating batch generation of drawings, BOMs, and reports from design models using Design Automation API cloud engines at enterprise scale. |
| AEC Data Analytics | Extracting and analyzing design element data, model properties, and project metrics using AEC Data Model GraphQL API for reporting. |

## Integrations

| Name | Description |
|------|-------------|
| Revit | Deep integration with Autodesk Revit for BIM data access, parameter management, and design automation via APS APIs. |
| AutoCAD | Integration with AutoCAD for cloud-based drawing generation and data extraction via the Design Automation API. |
| Salesforce | CRM and project management integration connecting Autodesk construction data with Salesforce customer and project records. |
| SAP | ERP integration connecting ACC cost management and project data with SAP for enterprise financial reporting and project accounting. |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [Autodesk Authentication OpenAPI](openapi/autodesk-authentication-openapi.yml)
- [Autodesk Data Management OpenAPI](openapi/autodesk-data-management-openapi.yml)
- [Autodesk Model Derivative OpenAPI](openapi/autodesk-model-derivative-openapi.yml)
- [Autodesk Design Automation OpenAPI](openapi/autodesk-design-automation-openapi.yml)
- [Autodesk Webhooks OpenAPI](openapi/autodesk-webhooks-openapi.yml)
- [Autodesk Reality Capture OpenAPI](openapi/autodesk-reality-capture-openapi.yml)
- [Autodesk Sustainability Data OpenAPI](openapi/autodesk-sustainability-data-openapi.yml)
- [Autodesk Parameters OpenAPI](openapi/autodesk-parameters-openapi.yml)
- [Autodesk Tandem Data OpenAPI](openapi/autodesk-tandem-data-openapi.yml)
- [Autodesk Flow Graph Engine OpenAPI](openapi/autodesk-flow-graph-engine-openapi.yml)
- [Autodesk ACC Account Admin OpenAPI](openapi/autodesk-acc-account-admin-openapi.yml)
- [Autodesk BIM 360 OpenAPI](openapi/autodesk-bim360-openapi.yml)

### AsyncAPI

- [Autodesk Webhooks AsyncAPI](asyncapi/autodesk-webhooks-asyncapi.yml)

### JSON Schema

- [Autodesk Hub Schema](json-schema/autodesk-hub.json)
- [Autodesk Project Schema](json-schema/autodesk-project.json)
- [Autodesk Item Schema](json-schema/autodesk-item.json)
- [Autodesk Version Schema](json-schema/autodesk-version.json)
- [Autodesk Webhook Event Schema](json-schema/autodesk-webhook-event.json)
- [Autodesk Issue Schema](json-schema/autodesk-issue.json)

### JSON-LD

- [Autodesk Context](json-ld/autodesk-context.jsonld)

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
