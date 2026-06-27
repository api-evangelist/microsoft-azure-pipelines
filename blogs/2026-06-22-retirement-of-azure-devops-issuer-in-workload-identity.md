---
title: "Retirement of Azure DevOps issuer in Workload identity federation service connections"
url: "https://devblogs.microsoft.com/devops/retirement-of-azure-devops-issuer-in-workload-identity-federation-service-connections/"
date: "2026-06-22"
author: "Eric van Wijk"
feed_url: "https://devblogs.microsoft.com/devops/feed/"
---
Microsoft is deprecating the Azure DevOps issuer in workload identity federation service connections, which uses the https://vstoken.dev.azure.com prefix in federated credentials, with retirement planned for July 1, 2027. The deprecation applies only to service connections in Azure public cloud using single-tenant Microsoft Entra applications or managed identities. Service connections can be converted to the Microsoft Entra issuer through an update process, with no immediate impact to existing pipelines.
