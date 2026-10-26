# Veritas NetBackup (veritas-netbackup)

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

Enterprise-grade data protection and backup solution with comprehensive REST APIs for backup, recovery, and data management operations.

**APIs.json:** [https://www.veritas.com/products/backup-and-recovery/netbackup](https://www.veritas.com/products/backup-and-recovery/netbackup)

## Tags

- Backup
- Data Protection
- Disaster Recovery
- Enterprise
- Recovery
- Storage

## Timestamps

- **Created:** 2024
- **Modified:** 2026-05-19

## APIs

### Veritas NetBackup REST API

Primary REST API for NetBackup operations including backup policies, jobs, catalogs, and asset management.

- **Human URL:** [https://www.veritas.com/support/en_US/article.100040135](https://www.veritas.com/support/en_US/article.100040135)
- **Base URL:** `https://netbackup-primary-server:1556/netbackup`

#### Tags

- Backup
- Catalog
- Jobs
- Policies
- Restore

#### Properties

- [Documentation](https://sort.veritas.com/documents/netbackup/10.1/productguides)
- [API Reference](https://sort.veritas.com/public/documents/nbu/10.1/windowsandunix/productguides/html/api/nbu_10.1_webapi.html)
- [Console](https://netbackup-primary-server:1556/api-docs)
- [Getting Started](https://sort.veritas.com/public/documents/nbu/10.3/windowsandunix/productguides/html/getting-started/)
- [Authentication](https://sort.veritas.com/public/documents/nbu/10.0/windowsandunix/productguides/html/getting-started/)
- [SDK](https://github.com/VeritasOS/netbackup-api-code-samples)
- [Changelog](https://www.veritas.com/protection/netbackup/whats-new)
- [Release Notes](https://www.veritas.com/support/en_US/doc/103228346-168289021-0/v168307940-168289021)
- [Documentation](https://www.veritas.com/support/en_US/article.100043102)
- [OpenAPI](openapi/veritas-netbackup-rest-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/veritas-netbackup-rest-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/veritas-netbackup-rest-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/veritas-netbackup-job-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON-LD](json-ld/veritas-netbackup-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)

### NetBackup Administration API

API for managing NetBackup jobs including getting job details, listing jobs by filter, restarting, resuming, suspending, canceling, and deleting jobs, and retrieving job file lists and logs.

- **Human URL:** [https://www.veritas.com/support/en_US/article.100040135](https://www.veritas.com/support/en_US/article.100040135)
- **Base URL:** `https://netbackup-primary-server:1556/netbackup/admin`

#### Tags

- Administration
- Jobs
- Management
- Monitoring

#### Properties

- [Documentation](https://sort.veritas.com/public/documents/nbu/10.3/windowsandunix/productguides/html/getting-started/)
- [Getting Started](https://sort.veritas.com/public/documents/nbu/10.3/windowsandunix/productguides/html/getting-started/)
- [Postman Collection](collections/veritas-netbackup-rest-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/veritas-netbackup-rest-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### NetBackup Asset Management API

API for managing NetBackup assets including servers, clients, and storage devices.

- **Human URL:** [https://www.veritas.com/support/en_US/doc/nbu_assets](https://www.veritas.com/support/en_US/doc/nbu_assets)
- **Base URL:** `https://netbackup-primary-server:1556/netbackup/assets`

#### Tags

- Assets
- Clients
- Inventory
- Servers

#### Properties

- [Documentation](https://sort.veritas.com/documents)
- [Getting Started](https://sort.veritas.com/public/documents/nbu/10.3/windowsandunix/productguides/html/getting-started/)
- [Postman Collection](collections/veritas-netbackup-rest-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/veritas-netbackup-rest-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### NetBackup Security API

API endpoints for managing authentication, authorization, certificates, credentials, tokens, and security audit logging configurations.

- **Human URL:** [https://www.veritas.com/support/en_US/article.100040135](https://www.veritas.com/support/en_US/article.100040135)
- **Base URL:** `https://netbackup-primary-server:1556/netbackup/security`

#### Tags

- Audit
- Authentication
- Authorization
- Certificates
- Credentials
- Security

#### Properties

- [Documentation](https://sort.veritas.com/documents)
- [Getting Started](https://sort.veritas.com/public/documents/nbu/10.3/windowsandunix/productguides/html/getting-started/)
- [Postman Collection](collections/veritas-netbackup-rest-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/veritas-netbackup-rest-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### NetBackup Image Management API

API for managing backup images, catalogs, and media retention.

- **Human URL:** [https://www.veritas.com/support/en_US/article.100040135](https://www.veritas.com/support/en_US/article.100040135)
- **Base URL:** `https://netbackup-primary-server:1556/netbackup/catalog`

#### Tags

- Catalog
- Images
- Media
- Retention

#### Properties

- [Documentation](https://sort.veritas.com/documents)
- [Getting Started](https://sort.veritas.com/public/documents/nbu/10.3/windowsandunix/productguides/html/getting-started/)
- [Postman Collection](collections/veritas-netbackup-rest-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/veritas-netbackup-rest-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### NetBackup Configuration API

API for configuring NetBackup hosts, policies, servers, VM server credentials, and storage settings.

- **Human URL:** [https://www.veritas.com/support/en_US/article.100040135](https://www.veritas.com/support/en_US/article.100040135)
- **Base URL:** `https://netbackup-primary-server:1556/netbackup/config`

#### Tags

- Configuration
- Hosts
- Policies
- Servers
- Storage

#### Properties

- [Documentation](https://sort.veritas.com/public/documents/nbu/10.3/windowsandunix/productguides/html/getting-started/)
- [Getting Started](https://sort.veritas.com/public/documents/nbu/10.3/windowsandunix/productguides/html/getting-started/)
- [Postman Collection](collections/veritas-netbackup-rest-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/veritas-netbackup-rest-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### NetBackup Storage API

API for managing storage consumption, capacity reporting, and backup storage on NetBackup primary servers.

- **Human URL:** [https://www.veritas.com/support/en_US/article.100040135](https://www.veritas.com/support/en_US/article.100040135)
- **Base URL:** `https://netbackup-primary-server:1556/netbackup/storage`

#### Tags

- Capacity
- Consumption
- Reporting
- Storage

#### Properties

- [Documentation](https://sort.veritas.com/public/documents/nbu/10.3/windowsandunix/productguides/html/getting-started/)
- [Getting Started](https://sort.veritas.com/public/documents/nbu/10.3/windowsandunix/productguides/html/getting-started/)
- [Postman Collection](collections/veritas-netbackup-rest-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/veritas-netbackup-rest-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### NetBackup Recovery API

API for VMware and cloud workload recovery operations including restore and instant access.

- **Human URL:** [https://www.veritas.com/support/en_US/article.100040135](https://www.veritas.com/support/en_US/article.100040135)
- **Base URL:** `https://netbackup-primary-server:1556/netbackup/recovery`

#### Tags

- Cloud
- Instant-Access
- Recovery
- Restore
- Vmware

#### Properties

- [Documentation](https://sort.veritas.com/public/documents/nbu/10.3/windowsandunix/productguides/html/getting-started/)
- [Getting Started](https://sort.veritas.com/public/documents/nbu/10.3/windowsandunix/productguides/html/getting-started/)
- [Postman Collection](collections/veritas-netbackup-rest-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/veritas-netbackup-rest-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### NetBackup RBAC Administration API

API for managing role-based access control, permissions, access rules, and access control lists.

- **Human URL:** [https://www.veritas.com/support/en_US/article.100040135](https://www.veritas.com/support/en_US/article.100040135)
- **Base URL:** `https://netbackup-primary-server:1556/netbackup/rbac`

#### Tags

- Access-Control
- Permissions
- Rbac
- Roles

#### Properties

- [Documentation](https://sort.veritas.com/public/documents/nbu/10.3/windowsandunix/productguides/html/getting-started/)
- [Getting Started](https://sort.veritas.com/public/documents/nbu/10.3/windowsandunix/productguides/html/getting-started/)
- [Postman Collection](collections/veritas-netbackup-rest-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/veritas-netbackup-rest-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### NetBackup Licensing API

API for managing entitlements and tracking Front-end Terabytes (FETBs) consumption for NetBackup licensing.

- **Human URL:** [https://www.veritas.com/support/en_US/article.100040135](https://www.veritas.com/support/en_US/article.100040135)
- **Base URL:** `https://netbackup-primary-server:1556/netbackup/licensing`

#### Tags

- Consumption
- Entitlements
- Licensing

#### Properties

- [Documentation](https://sort.veritas.com/public/documents/nbu/10.3/windowsandunix/productguides/html/getting-started/)
- [Getting Started](https://sort.veritas.com/public/documents/nbu/10.3/windowsandunix/productguides/html/getting-started/)
- [Postman Collection](collections/veritas-netbackup-rest-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/veritas-netbackup-rest-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### NetBackup Service Catalog API

API for managing service-level objectives (SLOs), protection plans, and subscription handling for backup operations.

- **Human URL:** [https://www.veritas.com/support/en_US/article.100040135](https://www.veritas.com/support/en_US/article.100040135)
- **Base URL:** `https://netbackup-primary-server:1556/netbackup/servicecatalog`

#### Tags

- Protection-Plans
- Service-Catalog
- Slo
- Subscriptions

#### Properties

- [Documentation](https://sort.veritas.com/public/documents/nbu/10.3/windowsandunix/productguides/html/getting-started/)
- [Getting Started](https://sort.veritas.com/public/documents/nbu/10.3/windowsandunix/productguides/html/getting-started/)
- [Postman Collection](collections/veritas-netbackup-rest-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/veritas-netbackup-rest-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### NetBackup Manage API

API for managing alerts and notification operations in NetBackup environments.

- **Human URL:** [https://www.veritas.com/support/en_US/article.100040135](https://www.veritas.com/support/en_US/article.100040135)
- **Base URL:** `https://netbackup-primary-server:1556/netbackup/manage`

#### Tags

- Alerts
- Management
- Notifications

#### Properties

- [Documentation](https://sort.veritas.com/public/documents/nbu/10.3/windowsandunix/productguides/html/getting-started/)
- [Getting Started](https://sort.veritas.com/public/documents/nbu/10.3/windowsandunix/productguides/html/getting-started/)
- [Postman Collection](collections/veritas-netbackup-rest-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/veritas-netbackup-rest-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### NetBackup Troubleshooting API

API for status code resolution and error reference to assist with troubleshooting NetBackup issues.

- **Human URL:** [https://www.veritas.com/support/en_US/article.100040135](https://www.veritas.com/support/en_US/article.100040135)
- **Base URL:** `https://netbackup-primary-server:1556/netbackup/troubleshooting`

#### Tags

- Diagnostics
- Errors
- Status-Codes
- Troubleshooting

#### Properties

- [Documentation](https://sort.veritas.com/public/documents/nbu/10.3/windowsandunix/productguides/html/getting-started/)
- [Getting Started](https://sort.veritas.com/public/documents/nbu/10.3/windowsandunix/productguides/html/getting-started/)
- [Postman Collection](collections/veritas-netbackup-rest-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/veritas-netbackup-rest-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### NetBackup IT Analytics REST API

REST API for accessing NetBackup IT Analytics report data, exporting reports in JSON, XML, HTML, PDF, and CSV formats, and exporting custom dashboards.

- **Human URL:** [https://www.veritas.com/support/en_US/doc/140670999-168357535-0/v149890439-168357535](https://www.veritas.com/support/en_US/doc/140670999-168357535-0/v149890439-168357535)
- **Base URL:** `https://portal-server/api/v1`

#### Tags

- Analytics
- Dashboards
- Monitoring
- Reporting

#### Properties

- [Documentation](https://www.veritas.com/support/en_US/doc/140670999-168357535-0/v149890439-168357535)
- [Authentication](https://www.veritas.com/support/en_US/doc/140670999-149890373-0/v149894265-149890373)
- [Getting Started](https://www.veritas.com/support/en_US/doc/140670999-166019911-0/v140669480-166019911)
- [Postman Collection](collections/veritas-netbackup-rest-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/veritas-netbackup-rest-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### NetBackup Self Service REST API

REST API for the NetBackup Self Service portal providing backup utilization data, protection status, tenant management, and self-service backup and restore operations.

- **Human URL:** [https://www.veritas.com/protection/netbackup/self-service](https://www.veritas.com/protection/netbackup/self-service)
- **Base URL:** `https://self-service-server/NetbackupAdapterPanels/Api`

#### Tags

- Portal
- Self-Service
- Tenants
- Utilization

#### Properties

- [Documentation](https://www.veritas.com/support/en_US/doc/109536476-156847273-0/v119207347-156847273)
- [Documentation](https://www.veritas.com/support/en_US/doc/109536476-167202398-1)
- [Postman Collection](collections/veritas-netbackup-rest-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/veritas-netbackup-rest-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### NetBackup Flex Scale REST API

REST API for controlling all aspects of NetBackup Flex Scale configuration including infrastructure monitoring, user management, node management, patch upgrades, and storage licensing.

- **Human URL:** [https://www.veritas.com/support/en_US/doc/139332629-144656221-0/v143532640-144656221](https://www.veritas.com/support/en_US/doc/139332629-144656221-0/v143532640-144656221)
- **Base URL:** `https://management-server:14161/swagger/infra/v1.0`

#### Tags

- Appliance
- Cluster
- Flex-Scale
- Infrastructure
- Node-Management

#### Properties

- [Documentation](https://www.veritas.com/support/en_US/doc/139332629-144656221-0/v143532640-144656221)
- [SDK](https://github.com/VeritasOS/NetBackup-Flex-Scale-REST-API-nuggets)
- [Getting Started](https://www.veritas.com/support/en_US/doc/139332629-144656221-0/v143532640-144656221)
- [Postman Collection](collections/veritas-netbackup-rest-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/veritas-netbackup-rest-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Support](https://www.veritas.com/support)
- [Documentation](https://www.veritas.com/support/en_US/article.100040135)
- [API Reference](https://www.veritas.com/support/en_US/doc/139300789-139300792-0/index)
- [Getting Started](https://sort.veritas.com/public/documents/nbu/10.3/windowsandunix/productguides/html/getting-started/)
- [Pricing](https://www.veritas.com/products/backup-and-recovery/netbackup/pricing)
- [Support](https://www.veritas.com/support/en_US/netbackup)
- [Contact](https://www.veritas.com/company/contact)
- [Knowledge Center](https://www.veritas.com/support/en_US/netbackup.PRODUCT_HOME)
- [Documentation](https://www.veritas.com/support/en_US/netbackup.download)
- [Documentation](https://vox.veritas.com/category/cohesity-discussions/discussions/netbackup)
- [Authentication](https://sort.veritas.com/public/documents/nbu/10.0/windowsandunix/productguides/html/getting-started/)
- [Rate Limits](https://sort.veritas.com/documents/netbackup/10.1/productguides)
- [Blog](https://www.veritas.com/blogs)
- [GitHub Organization](https://github.com/VeritasOS)
- [SDK](https://github.com/VeritasOS/netbackup-api-code-samples)
- [Code Examples](https://veritasos.github.io/netbackup-api-code-samples/)
- [Changelog](https://www.veritas.com/protection/netbackup/whats-new)
- [Release Notes](https://www.veritas.com/support/en_US/doc/103228346-168289021-0/v168307842-168289021)
- [Documentation](https://www.veritas.com/support/en_US/article.100032801)
- [X (Twitter)](https://twitter.com/veritastechllc)
- [LinkedIn](https://www.linkedin.com/company/veritas-technologies-llc)
- [Terms of Service](https://www.veritas.com/company/legal/legal-terms-of-use)
- [Privacy Policy](https://www.veritas.com/company/privacy)
- [Documentation](https://www.veritas.com/company)
- [Documentation](https://www.veritas.com/protection/netbackup/self-service)
- [Documentation](https://www.veritas.com/support/en_US/article.100043102)
- [Documentation](https://www.veritas.com/support/en_US/article.100052421)
- [Features](undefined)
- [Use Cases](undefined)
- [Integrations](undefined)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
**URL:** https://apievangelist.com
