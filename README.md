# Azure Pipelines (microsoft-azure-pipelines)

Azure Pipelines is a cloud service that you can use to automatically build and test your code project and make it available to other users. It works with just about any language or project type.

## Tags

- Automation
- Build
- CI/CD
- Deployment
- DevOps
- Pipelines

## Timestamps

- **Created:** 2024
- **Modified:** 2026-05-19

## APIs

### Azure Pipelines REST API

REST API for managing and interacting with Azure Pipelines including creating, listing, and getting pipelines, triggering and monitoring pipeline runs, and retrieving pipeline run logs. Provides programmatic access to the core CI/CD pipeline orchestration capabilities in Azure DevOps.

- **Human URL:** [https://learn.microsoft.com/en-us/rest/api/azure/devops/pipelines/](https://learn.microsoft.com/en-us/rest/api/azure/devops/pipelines/)
- **Base URL:** `https://dev.azure.com/{organization}/{project}/_apis`

#### Tags

- CI/CD
- Pipelines
- REST

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/rest/api/azure/devops/pipelines/)
- [OpenAPI](https://dev.azure.com/{organization}/_apis/public/api) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Authentication](https://learn.microsoft.com/en-us/azure/devops/integrate/get-started/authentication/authentication-guidance)
- [Quickstart](https://learn.microsoft.com/en-us/azure/devops/pipelines/create-first-pipeline)
- [Client  Libraries](https://learn.microsoft.com/en-us/azure/devops/integrate/concepts/dotnet-client-libraries)
- [Changelog](https://learn.microsoft.com/en-us/azure/devops/release-notes/features-timeline-released)
- [Y A M L  Schema](https://learn.microsoft.com/en-us/azure/devops/pipelines/yaml-schema/)
- [Postman Collection](collections/azure-pipelines-build-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/azure-pipelines-build-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/azure-pipelines-rest-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/azure-pipelines-rest-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Azure Pipelines Build REST API

REST API for managing build definitions, queuing builds, and retrieving build results, artifacts, tags, and logs. Supports the full lifecycle of continuous integration builds in Azure DevOps, including creating and updating build definitions from templates, listing and tagging builds, and downloading build artifacts.

- **Human URL:** [https://learn.microsoft.com/en-us/rest/api/azure/devops/build/](https://learn.microsoft.com/en-us/rest/api/azure/devops/build/)
- **Base URL:** `https://dev.azure.com/{organization}/{project}/_apis/build`

#### Tags

- Artifacts
- Build
- Continuous Integration
- Definitions

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/rest/api/azure/devops/build/)
- [Authentication](https://learn.microsoft.com/en-us/azure/devops/integrate/get-started/authentication/authentication-guidance)
- [Postman Collection](collections/azure-pipelines-build-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/azure-pipelines-build-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/azure-pipelines-rest-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/azure-pipelines-rest-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Azure Pipelines Release REST API

REST API for managing release definitions, creating and tracking releases, and configuring deployment approvals. Enables programmatic control of the continuous delivery process including defining release pipelines with multiple environments, triggering deployments, and managing approval workflows.

- **Human URL:** [https://learn.microsoft.com/en-us/rest/api/azure/devops/release/](https://learn.microsoft.com/en-us/rest/api/azure/devops/release/)
- **Base URL:** `https://vsrm.dev.azure.com/{organization}/{project}/_apis/release`

#### Tags

- Approvals
- Continuous Delivery
- Deployment
- Release

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/rest/api/azure/devops/release/)
- [Authentication](https://learn.microsoft.com/en-us/azure/devops/integrate/get-started/authentication/authentication-guidance)
- [Postman Collection](collections/azure-pipelines-build-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/azure-pipelines-build-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/azure-pipelines-rest-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/azure-pipelines-rest-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Azure Pipelines Approvals and Checks REST API

REST API for managing pipeline approvals and checks on resources such as environments, service connections, agent pools, variable groups, and secure files. Provides the ability to create and modify check configurations, manage approval workflows, query check evaluation details, and control pipeline permissions for protected resources.

- **Human URL:** [https://learn.microsoft.com/en-us/rest/api/azure/devops/approvalsandchecks/](https://learn.microsoft.com/en-us/rest/api/azure/devops/approvalsandchecks/)
- **Base URL:** `https://dev.azure.com/{organization}/{project}/_apis/pipelines`

#### Tags

- Approvals
- Checks
- Governance
- Security

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/rest/api/azure/devops/approvalsandchecks/)
- [Authentication](https://learn.microsoft.com/en-us/azure/devops/integrate/get-started/authentication/authentication-guidance)
- [Postman Collection](collections/azure-pipelines-build-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/azure-pipelines-build-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/azure-pipelines-rest-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/azure-pipelines-rest-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Getting Started](https://learn.microsoft.com/en-us/azure/devops/pipelines/get-started/what-is-azure-pipelines)
- [Portal](https://dev.azure.com/)
- [Pricing](https://azure.microsoft.com/en-us/pricing/details/devops/azure-devops-services/)
- [Status Page](https://status.dev.azure.com/)
- [Blog](https://devblogs.microsoft.com/devops/)
- [Terms of Service](https://azure.microsoft.com/en-us/support/legal/)
- [Privacy Policy](https://privacy.microsoft.com/en-us/privacystatement)
- [Documentation](https://learn.microsoft.com/en-us/azure/devops/pipelines/)
- [Website](https://azure.microsoft.com/en-us/products/devops)
- [Sign Up](https://azure.microsoft.com/en-us/products/devops)
- [Login](https://dev.azure.com/)
- [Support](https://azure.microsoft.com/en-us/support/devops/)
- [Changelog](https://learn.microsoft.com/en-us/azure/devops/release-notes/features-timeline-released)
- [Client  Libraries](https://learn.microsoft.com/en-us/azure/devops/integrate/concepts/dotnet-client-libraries)
- [Community](https://developercommunity.visualstudio.com/AzureDevOps)
- [GitHub Organization](https://github.com/MicrosoftDocs)
- [GitHub Repository](https://github.com/MicrosoftDocs/azure-devops-docs)
- [Stack Overflow](https://stackoverflow.com/questions/tagged/azure-devops)
- [Marketplace](https://marketplace.visualstudio.com/azuredevops)
- [C L I](https://github.com/Azure/azure-devops-cli-extension)
- [Task  Reference](https://learn.microsoft.com/en-us/azure/devops/pipelines/tasks/reference/)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
