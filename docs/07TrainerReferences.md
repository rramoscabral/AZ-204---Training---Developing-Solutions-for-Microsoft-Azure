---
layout: default
title: 'Trainer References'
nav_order: 7
has_children: false
---

# Trainer References
{: .no_toc }


## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

<br/>

---

<br/>

## Learning Path 1: Implement Azure App Service web apps

| Lessons | Notes |
| --- | --- |
| Explore Azure App Service | - [Choose an Azure compute service](https://learn.microsoft.com/en-us/azure/architecture/guide/technology-choices/compute-decision-tree) <br> - [Azure App Service plan overview](https://learn.microsoft.com/en-us/azure/app-service/overview-hosting-plans) <br>  - [App Service limits](https://learn.microsoft.com/en-us/azure/azure-resource-manager/management/azure-subscription-service-limits#app-service-limits) <br> - [App Service Environment v3 and App Service public multitenant comparison](https://learn.microsoft.com/en-us/azure/app-service/environment/ase-multi-tenant-comparison) |
| Extra | - [Tutorial: Isolate back-end communication in Azure App Service with Virtual Network integration](https://learn.microsoft.com/en-us/azure/app-service/tutorial-networking-isolate-vnet) | 


<br/>

## Learning Path 2: Implement task processing logic by using Azure Functions


| Lessons | Notes |
| --- | --- |
| Explore Azure Functions | - [Azure Functions pricing](https://azure.microsoft.com/en-us/pricing/details/functions/) |
| Develop Azure Functions | - [Develop Azure Functions locally using Core Tools](https://learn.microsoft.com/en-us/azure/azure-functions/functions-run-local) <br>  - [Code and test Azure Functions locally](https://learn.microsoft.com/en-us/azure/azure-functions/functions-develop-local)  <br> -  [Develop Azure Functions by using Visual Studio Code](https://learn.microsoft.com/en-us/azure/azure-functions/functions-develop-vs-code) <br> - [Command line tools for Azure Functions (GitHub)](https://github.com/Azure/azure-functions-core-tools) |  


<br/>

## Learning Path 3: Develop solutions that use Blob storage


| Lessons | Notes |
| --- | --- |
| Explore Azure Blob storage | - [Understanding block blobs, append blobs, and page blobs](https://learn.microsoft.com/en-us/rest/api/storageservices/understanding-block-blobs--append-blobs--and-page-blobs) <br> - [Access tiers for blob data](https://learn.microsoft.com/en-gb/azure/storage/blobs/access-tiers-overview) |
| Work with Azure Blob storage | - [BlobClient Class](https://learn.microsoft.com/en-us/dotnet/api/azure.storage.blobs.blobclient) <br> - [BlobClientOptions Class](https://learn.microsoft.com/en-us/dotnet/api/azure.storage.blobs.blobclientoptions) <br> - [BlobContainerClient Class](https://learn.microsoft.com/en-us/dotnet/api/azure.storage.blobs.blobcontainerclient)  <br> - [BlobServiceClien Class](https://learn.microsoft.com/en-us/dotnet/api/azure.storage.blobs.blobserviceclient) <br> - [BlobUriBuilder Class](https://learn.microsoft.com/en-us/dotnet/api/azure.storage.blobs.bloburibuilder) <br> - [Azure Storage REST API Reference](https://learn.microsoft.com/en-us/rest/api/storageservices/) |

<br/>


## Learning Path 4: Develop solutions that use Azure Cosmos DB


| Lessons | | Notes |
| --- | --- | --- | 
| Explore Azure Cosmos DB | - Explore Azure Cosmos DB for developers | -  [Azure Cosmos DB developer](https://developer.azurecosmosdb.com)| 
| | - Resource Units | - [How to choose between provisioned throughput and serverless](https://learn.microsoft.com/en-gb/azure/cosmos-db/throughput-serverless) <br> - [How to choose between standard (manual) and autoscale provisioned throughput](https://learn.microsoft.com/en-gb/azure/cosmos-db/how-to-choose-offer) <br> - [Azure Cosmos DB capacity calculator](https://cosmos.azure.com/capacitycalculator/) <br> - [Azure Cosmos DB pricing](https://azure.microsoft.com/en-us/pricing/details/cosmos-db/standard-provisioned/) |
| | - Partitioning | - [Partitioning and horizontal scaling in Azure Cosmos DB](https://learn.microsoft.com/en-us/azure/cosmos-db/partitioning-overview) <br> - [Choose a partition key](https://learn.microsoft.com/en-us/azure/cosmos-db/partitioning-overview#choose-a-partition-key) | 
| | - Item         | - [Azure Cosmos DB properties of an item](https://learn.microsoft.com/en-us/azure/cosmos-db/resource-model#properties-of-an-item) |
| | - Consistency levels | - [Consistency levels in Azure Cosmos DB](https://learn.microsoft.com/en-us/azure/cosmos-db/consistency-levels) |
| | - Queries | - [Cosmos DB Documents](https://learn.microsoft.com/en-us/rest/api/cosmos-db/documents)
| Work with Azure Cosmos DB |  - .NET SDK | - [Azure Cosmos DB Developer](https://developer.azurecosmosdb.com) <br> - [Azure Cosmos DB SDKs](https://developer.azurecosmosdb.com/community/sdk) <br> - [CosmosClient Class](https://learn.microsoft.com/en-us/dotnet/api/microsoft.azure.cosmos.cosmosclient) |
| Extra | - Migrate data  | - [Migrate data to Azure Cosmos DB using the desktop data migration tool](https://learn.microsoft.com/en-us/azure/cosmos-db/how-to-migrate-desktop-tool) <br> - [Migrate hundreds of terabytes of data into Azure Cosmos DB](https://learn.microsoft.com/en-us/azure/cosmos-db/migrate) |





<br/>

## Learning Path 5: Implement containerized solutions

| Lessons | Notes |
| --- | --- |
| Manage Container Images in Azure Container Registry | - [Writing a Dockerfile](https://docs.docker.com/get-started/docker-concepts/building-images/writing-a-dockerfile/) <br> - [Dockerfile reference (Docker Docs)](https://docs.docker.com/engine/reference/builder/) <br> - [Dockerfile on Windows](https://learn.microsoft.com/en-us/virtualization/windowscontainers/manage-docker/manage-windows-dockerfile) <br> - [Publishing and exposing ports (Docker Docs)](https://docs.docker.com/get-started/docker-concepts/running-containers/publishing-ports/) <br> - [ACR Service tier features and limits](https://learn.microsoft.com/en-us/azure/container-registry/container-registry-skus#service-tier-features-and-limits) |
| Run container images in Azure Container Instances  | - [Choose an Azure compute service](https://learn.microsoft.com/en-us/azure/architecture/guide/technology-choices/compute-decision-tree) <br> - [Choose an Azure compute option for microservices](https://learn.microsoft.com/en-us/azure/architecture/microservices/design/compute-options) <br> - [Microsoft Artifact Registry](https://mcr.microsoft.com/) <br> - [Use storage mounts in Azure Container Apps](https://learn.microsoft.com/en-us/azure/container-apps/storage-mounts) <br> - [Docker Volumes (Docker Docs)](https://docs.docker.com/engine/storage/volumes/) |
| Implement Azure Container Apps  | - [Azure Container Apps overview](https://learn.microsoft.com/en-us/azure/container-apps/overview) <br> - [Azure Container Apps (Darp Docs)](https://docs.dapr.io/operations/hosting/serverless/azure-container-apps/) <br> - [Tutorial: Deploy a Dapr application to Azure Container Apps using the Azure CLI](https://learn.microsoft.com/en-us/azure/container-apps/microservices-dapr) |




<br/>

## Learning Path 6: Implement user authentication and authorization


| Lessons |Notes |
| --- | --- |
| Explore the Microsoft identity platform |  - [What is the Microsoft identity platform?](https://learn.microsoft.com/en-us/entra/identity-platform/v2-overview) <br> - [What is Azure role-based access control (Azure RBAC)?](https://learn.microsoft.com/en-us/azure/role-based-access-control/overview) <br> - [What is Azure attribute-based access control (Azure ABAC)?](https://learn.microsoft.com/en-us/azure/role-based-access-control/conditions-overview) |
| Implement authentication by using the Microsoft Authentication Library | - [Overview of the Microsoft Authentication Library (MSAL)](https://learn.microsoft.com/en-us/entra/identity-platform/msal-overview) <br> - [Choosing a version of MSAL.NET](https://learn.microsoft.com/en-us/entra/msal/dotnet/getting-started/choosing-msal-dotnet) |
| Implement shared access signatures | - [Grant limited access to Azure Storage resources using shared access signatures (SAS)](https://learn.microsoft.com/en-us/azure/storage/common/storage-sas-overview) <br> - [Create a service SAS for a container or blob with .NET](https://learn.microsoft.com/en-us/azure/storage/blobs/sas-service-create-dotnet)<br> - [Service SAS examples](https://learn.microsoft.com/en-us/rest/api/storageservices/service-sas-examples) |
| Explore Microsoft Graph | - [Microsoft Graph quick start](https://developer.microsoft.com/en-us/graph/quick-start) <br> - [Graph Explorer](https://developer.microsoft.com/en-us/graph/graph-explorer) | 


<br/>

## Learning Path 7: Implement secure cloud solutions

| Lessons | Notes |
| --- | --- |
| Implement Azure Key Vault | - [Azure Key Vault developer's guide]( https://learn.microsoft.com/en-us/azure/key-vault/general/developers-guide) <br> - [Azure Key Vault availability and redundancy](https://learn.microsoft.com/en-us/azure/key-vault/general/disaster-recovery-guidance) <br> - [Azure Key Vault REST API reference](https://learn.microsoft.com/en-us/rest/api/keyvault/) <br> - [Use Key Vault references as app settings in Azure App Service and Azure Functions](https://learn.microsoft.com/en-us/azure/app-service/app-service-key-vault-references)  <br> - [New Thales Luna HSM Bring Your Own Key (BYOK) for Microsoft Azure Key Vault](https://data-protection-updates.gemalto.com/2020/08/07/new-thales-luna-hsm-bring-your-own-key-byok-for-microsoft-azure-key-vault/) |
| Implement managed identities | - [Application and service principal objects in Microsoft Entra ID](https://learn.microsoft.com/en-us/entra/identity-platform/app-objects-and-service-principals) <br> - [What is Azure role-based access control (Azure RBAC)?](https://learn.microsoft.com/en-us/azure/role-based-access-control/overview) <br> - [What is Azure attribute-based access control (Azure ABAC)?](https://learn.microsoft.com/en-us/azure/role-based-access-control/conditions-overview) | <br> - [Azure built-in roles](https://learn.microsoft.com/en-us/azure/role-based-access-control/built-in-roles) <br> - [Steps to assign an Azure role](https://learn.microsoft.com/en-us/azure/role-based-access-control/role-assignments-steps) |
| Implement Azure App Configuration | - [What is Azure App Configuration](https://learn.microsoft.com/en-us/azure/azure-app-configuration/overview) <br> [Azure App Configuration best practices](https://learn.microsoft.com/en-us/azure/azure-app-configuration/howto-best-practices) | 
| Extra | - [What is a private endpoint?](https://learn.microsoft.com/en-us/azure/private-link/private-endpoint-overview) <br> - [What is Azure Private Endpoint and Azure Private Link Service?](https://learn.microsoft.com/en-us/azure/private-link/private-link-faq#what-is-azure-private-endpoint-and-azure-private-link-service-) |

<br/>

## Learning Path 8: Implement API Management

| Lessons | Notes |
| --- | --- |
| - Explore API Management | - [Azure API Management v2 tiers Supported regions](https://learn.microsoft.com/en-us/azure/api-management/v2-service-tiers-overview#supported-regions) <br> - [API Management policy reference](https://learn.microsoft.com/en-us/azure/api-management/api-management-policies) <br> - [Azure APIM - Add an API manually](https://learn.microsoft.com/en-us/azure/api-management/add-api-manually) <br> - [API Management policy reference](https://learn.microsoft.com/en-us/azure/api-management/api-management-policies) <br> - [Tutorial: Import and publish your first API](https://learn.microsoft.com/en-us/azure/api-management/import-and-publish) |

<br/>

## Learning Path 9: Develop event-based solutions


| Lessons | Notes |
| --- | --- |
| Explore Azure Event Grid | [Publisher-Subscriber pattern](https://learn.microsoft.com/en-us/azure/architecture/patterns/publisher-subscriber) <br> - [Azure Event Grid event schema](https://docs.microsoft.com/en-us/azure/event-grid/event-schema) |
| Explorer Azure Event Hubs | - [Schema Registry in Azure Event Hubs](https://learn.microsoft.com/en-us/azure/event-hubs/schema-registry-concepts) <br> - [Client-side schema enforcement](https://learn.microsoft.com/en-us/azure/event-hubs/schema-registry-client-side-enforcement) <br> - [Stream processing with Azure Stream Analytics (Architecture)](https://learn.microsoft.com/en-us/azure/architecture/reference-architectures/data/stream-processing-stream-analytics) |
| Explore Azure Event Hubs | - [Scaling with Event Hubs](https://learn.microsoft.com/en-us/azure/event-hubs/event-hubs-scalability#throughput-units) <br> - [Choose between Azure messaging services - Event Grid, Event Hubs, and Service Bus](https://learn.microsoft.com/en-us/azure/service-bus-messaging/compare-messaging-services) |
| Hands-on Labs            | - [Azure-Samples/azure-event-grid-viewer](https://github.com/Azure-Samples/azure-event-grid-viewer) |



<br/>

## Learning Path 10: Develop message-based solutions


| Lessons | Notes |
| --- | --- |
| Service Bus | - [Use a message broker and events to integrate enterprise systems (Architecture)](https://learn.microsoft.com/en-us/azure/architecture/example-scenario/integration/queues-events) <br> - [Storage queues and Service Bus queues - compared and contrasted](https://learn.microsoft.com/en-us/azure/service-bus-messaging/service-bus-azure-and-service-bus-queues-compared-contrasted) <br> - [Choose between Azure messaging services - Event Grid, Event Hubs, and Service Bus](https://learn.microsoft.com/en-us/azure/service-bus-messaging/compare-messaging-services) |



<br/>

## Learning Path 11: Troubleshoot solutions by using Application Insights


| Lessons | Notes |
| --- | --- |
| Azure Monitor Insights | - [Azure Monitor overview](https://learn.microsoft.com/en-us/azure/azure-monitor/fundamentals/overview) <br> - [Azure Monitor Insights overview](https://learn.microsoft.com/en-us/azure/azure-monitor/insights/insights-overview) |
| Application Insights   | - [Azure Monitor Application Insights overview](https://learn.microsoft.com/en-us/azure/azure-monitor/app/app-insights-overview) |



<br/>

## Learning Path 12: Implement caching for solutions


| Lessons | Notes |
| --- | ---
| Develop for Azure Cache for Redis | - [Redis Open Source (Redis.io)](https://Redis.io) <br> - [Redis Cloud Essentials plans (Redis.io)](https://Redis.io/docs/latest/operate/rc/subscriptions/view-essentials-subscription/essentials-plan-details/) <br> - [Redis enterprise](https://redis.com) <br> - [Redis CLI (Redis.io) ](https://Redis.io/docs/manual/cli/) |
| Develop for storage on CDNs | - [Content Delivery Network limits](https://learn.microsoft.com/en-us/azure/azure-resource-manager/management/azure-subscription-service-limits#content-delivery-network-limits) |

<br/>

