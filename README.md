# Citrix (citrix)

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

Citrix is a global software company providing virtualization, networking, workspace, and digital experience products that allow organizations to deliver applications and desktops securely from data centers and clouds to any device. Citrix exposes its programmable surface through the Citrix Cloud platform and developer.citrix.com / developer-docs.citrix.com, with REST APIs spanning Virtual Apps and Desktops, DaaS, Workspace, Citrix Cloud, ADC (NetScaler) NITRO, Endpoint Management, Secure Private Access, and Analytics. Authentication uses OAuth 2.0 bearer tokens issued through Citrix Cloud customer-id-scoped credentials.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/citrix/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/citrix/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags

- Application Delivery
- Desktop-As-A-Service
- Networking
- Virtualization
- Workspace

## Timestamps

- **Created:** 2024-01-01
- **Modified:** 2026-05-19

## APIs

### Citrix Virtual Apps and Desktops REST API

Manage and monitor Citrix Virtual Apps and Desktops deployments.

- **Human URL:** [https://developer.citrix.com/citrix-virtual-apps-and-desktops](https://developer.citrix.com/citrix-virtual-apps-and-desktops)
- **Base URL:** `https://{customer-id}.xendesktop.net`

#### Tags

- Remote Access
- VDI
- Virtual Desktop

#### Properties

- [Documentation](https://developer.citrix.com/citrix-virtual-apps-and-desktops/citrix-cvad-rest-apis)
- [OpenAPI](https://developer.citrix.com/citrix-virtual-apps-and-desktops/citrix-cvad-rest-apis/docs/openapi) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Authentication](https://developer.citrix.com/citrix-virtual-apps-and-desktops/citrix-cvad-rest-apis/docs/how-to-get-started)
- [OpenAPI](openapi/citrix-daas-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/citrix-daas.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/citrix-daas.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Citrix Workspace API

Integrate and customize Citrix Workspace for end users.

- **Human URL:** [https://developer.citrix.com/citrix-workspace](https://developer.citrix.com/citrix-workspace)
- **Base URL:** `https://api.cloud.com`

#### Tags

- SSO
- User Experience
- Workspace

#### Properties

- [Documentation](https://developer.citrix.com/citrix-workspace/citrix-workspace-platform)
- [API Reference](https://developer.citrix.com/citrix-workspace/citrix-workspace-platform/build/api-reference)
- [Postman Collection](collections/citrix-adc-nitro.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/citrix-adc-nitro.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/citrix-cloud.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/citrix-cloud.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/citrix-daas.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/citrix-daas.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/citrix-endpoint-management.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/citrix-endpoint-management.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/citrix-secure-private-access.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/citrix-secure-private-access.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/citrix-storefront-web.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/citrix-storefront-web.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Citrix ADC (NetScaler) NITRO API

Configure and monitor Citrix ADC application delivery controllers.

- **Human URL:** [https://developer.citrix.com/citrix-adc](https://developer.citrix.com/citrix-adc)
- **Base URL:** `https://{netscaler-ip}/nitro/v1`

#### Tags

- ADC
- Application Delivery
- Load Balancing
- Networking

#### Properties

- [Documentation](https://developer-docs.citrix.com/projects/netscaler-nitro-api/en/latest/)
- [API Reference](https://developer-docs.citrix.com/projects/netscaler-nitro-api/en/latest/api-reference/)
- [SDK](https://developer-docs.citrix.com/projects/netscaler-nitro-api/en/latest/getting-started/)
- [OpenAPI](openapi/citrix-adc-nitro-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/citrix-adc-nitro.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/citrix-adc-nitro.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Citrix DaaS REST API

Manage Citrix Desktop as a Service (DaaS) cloud deployments.

- **Human URL:** [https://developer.citrix.com/citrix-daas](https://developer.citrix.com/citrix-daas)
- **Base URL:** `https://api.cloud.com/cvad`

#### Tags

- Cloud
- DaaS
- Desktop as a Service

#### Properties

- [Documentation](https://developer.citrix.com/citrix-daas/citrix-daas-rest-apis)
- [OpenAPI](https://developer.citrix.com/citrix-daas/citrix-daas-rest-apis/docs/openapi) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Getting Started](https://developer.citrix.com/citrix-daas/citrix-daas-rest-apis/docs/getting-started)
- [OpenAPI](openapi/citrix-daas-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/citrix-daas.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/citrix-daas.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Citrix Analytics API

Access analytics data for security and performance insights.

- **Human URL:** [https://developer.citrix.com/citrix-analytics](https://developer.citrix.com/citrix-analytics)
- **Base URL:** `https://api.analytics.cloud.com`

#### Tags

- Analytics
- Insights
- Monitoring
- Security

#### Properties

- [Documentation](https://developer.citrix.com/citrix-analytics/api-overview)
- [API Reference](https://developer.citrix.com/citrix-analytics/api-reference)
- [Postman Collection](collections/citrix-adc-nitro.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/citrix-adc-nitro.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/citrix-cloud.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/citrix-cloud.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/citrix-daas.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/citrix-daas.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/citrix-endpoint-management.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/citrix-endpoint-management.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/citrix-secure-private-access.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/citrix-secure-private-access.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/citrix-storefront-web.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/citrix-storefront-web.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Citrix Cloud API

Platform-level API for managing Citrix Cloud services, including authentication, service principals, resource locations, and notifications across the Citrix Cloud platform.

- **Human URL:** [https://developer-docs.citrix.com/en-us/citrix-cloud/citrix-cloud-api-overview/get-started-with-citrix-cloud-apis.html](https://developer-docs.citrix.com/en-us/citrix-cloud/citrix-cloud-api-overview/get-started-with-citrix-cloud-apis.html)
- **Base URL:** `https://api.cloud.com`

#### Tags

- Cloud
- Identity
- Management
- Platform

#### Properties

- [Documentation](https://developer-docs.citrix.com/en-us/citrix-cloud/citrix-cloud-api-overview/get-started-with-citrix-cloud-apis.html)
- [Getting Started](https://developer-docs.citrix.com/en-us/citrix-cloud/citrix-cloud-api-overview/citrix-cloud-api-walkthrough.html)
- [Authentication](https://developer-docs.citrix.com/en-us/citrix-cloud/citrix-cloud-api-overview/get-started-with-citrix-cloud-apis.html)
- [OpenAPI](openapi/citrix-cloud-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/citrix-cloud.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/citrix-cloud.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Citrix Monitor Service OData API

OData-based API for querying monitoring data from Citrix Virtual Apps and Desktops deployments, including session, connection, machine, and application usage data for reporting and analytics.

- **Human URL:** [https://developer-docs.citrix.com/en-us/monitor-service-odata-api/overview.html](https://developer-docs.citrix.com/en-us/monitor-service-odata-api/overview.html)
- **Base URL:** `https://{delivery-controller}/Citrix/Monitor/OData/v4/Data`

#### Tags

- Analytics
- Monitoring
- OData
- Reporting

#### Properties

- [Documentation](https://developer-docs.citrix.com/en-us/monitor-service-odata-api/overview.html)
- [Reference](https://developer-docs.citrix.com/en-us/monitor-service-odata-api/monitor-service-resources.html)
- [Getting Started](https://developer-docs.citrix.com/en-us/monitor-service-odata-api/access-methods.html)
- [Postman Collection](collections/citrix-adc-nitro.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/citrix-adc-nitro.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/citrix-cloud.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/citrix-cloud.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/citrix-daas.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/citrix-daas.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/citrix-endpoint-management.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/citrix-endpoint-management.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/citrix-secure-private-access.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/citrix-secure-private-access.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/citrix-storefront-web.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/citrix-storefront-web.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Citrix StoreFront Web API

HTTP API for building custom client applications that authenticate users, enumerate available applications and desktops, manage HDX sessions, and launch resources from Citrix StoreFront.

- **Human URL:** [https://developer-docs.citrix.com/en-us/storefront/storefront-web-api/overview.html](https://developer-docs.citrix.com/en-us/storefront/storefront-web-api/overview.html)
- **Base URL:** `https://{storefront-server}/Citrix/Store`

#### Tags

- Client
- Resources
- Sessions
- StoreFront

#### Properties

- [Documentation](https://developer-docs.citrix.com/en-us/storefront/storefront-web-api/overview.html)
- [Getting Started](https://developer-docs.citrix.com/en-us/storefront/storefront-web-api/getting-started.html)
- [Reference](https://developer-docs.citrix.com/en-us/storefront/storefront-web-api/apis/)
- [OpenAPI](openapi/citrix-storefront-web-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/citrix-storefront-web.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/citrix-storefront-web.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Citrix StoreFront Store Services API

Server-side API for customizing and extending the Citrix StoreFront store services, including endpoint management, authentication, and resource enumeration behaviors.

- **Human URL:** [https://developer-docs.citrix.com/en-us/storefront/storefront-store-services-api/overview.html](https://developer-docs.citrix.com/en-us/storefront/storefront-store-services-api/overview.html)
- **Base URL:** `https://{storefront-server}/Citrix/Store`

#### Tags

- Customization
- Server
- StoreFront

#### Properties

- [Documentation](https://developer-docs.citrix.com/en-us/storefront/storefront-store-services-api/overview.html)
- [Reference](https://developer-docs.citrix.com/en-us/storefront/storefront-store-services-api/endpoints-service/)
- [Postman Collection](collections/citrix-adc-nitro.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/citrix-adc-nitro.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/citrix-cloud.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/citrix-cloud.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/citrix-daas.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/citrix-daas.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/citrix-endpoint-management.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/citrix-endpoint-management.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/citrix-secure-private-access.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/citrix-secure-private-access.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/citrix-storefront-web.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/citrix-storefront-web.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Citrix StoreFront Authentication SDK

SDK for building custom authentication methods for Citrix StoreFront, allowing integration with third-party identity providers and custom authentication workflows.

- **Human URL:** [https://developer-docs.citrix.com/en-us/storefront/citrix-storefront-authentication-sdk/overview.html](https://developer-docs.citrix.com/en-us/storefront/citrix-storefront-authentication-sdk/overview.html)
- **Base URL:** `https://{storefront-server}`

#### Tags

- Authentication
- Identity
- StoreFront

#### Properties

- [Documentation](https://developer-docs.citrix.com/en-us/storefront/citrix-storefront-authentication-sdk/overview.html)
- [Postman Collection](collections/citrix-adc-nitro.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/citrix-adc-nitro.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/citrix-cloud.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/citrix-cloud.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/citrix-daas.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/citrix-daas.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/citrix-endpoint-management.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/citrix-endpoint-management.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/citrix-secure-private-access.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/citrix-secure-private-access.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/citrix-storefront-web.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/citrix-storefront-web.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Citrix Endpoint Management REST API

REST API for managing mobile devices, applications, and policies in Citrix Endpoint Management, enabling integration with external systems for device lifecycle management and compliance.

- **Human URL:** [https://docs.citrix.com/en-us/citrix-endpoint-management/rest-apis.html](https://docs.citrix.com/en-us/citrix-endpoint-management/rest-apis.html)
- **Base URL:** `https://{xms-server}:4443/xenmobile/api/v1`

#### Tags

- Endpoint Management
- MDM
- Mobile
- UEM

#### Properties

- [Documentation](https://docs.citrix.com/en-us/citrix-endpoint-management/rest-apis.html)
- [OpenAPI](openapi/citrix-endpoint-management-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/citrix-endpoint-management.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/citrix-endpoint-management.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Citrix Secure Private Access API

REST API for managing zero trust network access policies, applications, application domains, and certificates in Citrix Secure Private Access, providing secure access to internal web and SaaS applications.

- **Human URL:** [https://developer-docs.citrix.com/en-us/secure-private-access/access-security/overview.html](https://developer-docs.citrix.com/en-us/secure-private-access/access-security/overview.html)
- **Base URL:** `https://api.cloud.com/accessSecurity`

#### Tags

- Access Control
- Security
- Zero Trust
- ZTNA

#### Properties

- [Documentation](https://developer-docs.citrix.com/en-us/secure-private-access/access-security/overview.html)
- [Getting Started](https://developer-docs.citrix.com/en-us/secure-private-access/access-security/getting-started.html)
- [OpenAPI](openapi/citrix-secure-private-access-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/citrix-secure-private-access.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/citrix-secure-private-access.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/citrix)
- [Portal](https://developer-docs.citrix.com/)
- [Getting Started](https://developer-docs.citrix.com/en-us/citrix-cloud/citrix-cloud-api-overview/get-started-with-citrix-cloud-apis.html)
- [Authentication](https://developer-docs.citrix.com/en-us/citrix-cloud/citrix-cloud-api-overview/get-started-with-citrix-cloud-apis.html)
- [Blog](https://www.citrix.com/blogs/)
- [Status Page](https://status.cloud.com/)
- [Support](https://support.citrix.com/)
- [Terms of Service](https://developer.cloud.com/citrix-developer-terms-of-use)
- [Privacy Policy](https://www.citrix.com/about/legal/privacy/plain.html)
- [GitHub Organization](https://github.com/citrix)
- [Community](https://discussions.citrix.com/)
- [S D Ks](https://docs.citrix.com/en-us/citrix-cloud/sdk-api.html)
- [Website](https://www.citrix.com)
- [Login](https://accounts.cloud.com/)
- [JSON-LD](json-ld/citrix-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [JSON Schema](json-schema/citrix-machine-catalog-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/citrix-session-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [Spectral Rules](rules/citrix-rules.yml) — [Spectral](https://docs.stoplight.io/docs/spectral)
- [Integrations](https://www.citrix.com/partners/)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
