# Veritas NetBackup (veritas-netbackup)

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
