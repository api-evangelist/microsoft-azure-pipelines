# Azure Pipelines (microsoft-azure-pipelines)

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
