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
| Explore Azure Cosmos DB | - Explore Azure Cosmos DB for developers | -  [Azure Cosmos DB developer](https://developer.azurecosmosdb.com) <br> - Resource Units | - [How to choose between provisioned throughput and serverless](https://learn.microsoft.com/en-gb/azure/cosmos-db/throughput-serverless) <br> - [How to choose between standard (manual) and autoscale provisioned throughput](https://learn.microsoft.com/en-gb/azure/cosmos-db/how-to-choose-offer) <br> - [Azure Cosmos DB capacity calculator](https://cosmos.azure.com/capacitycalculator/) <br> - [Azure Cosmos DB pricing](https://azure.microsoft.com/en-us/pricing/details/cosmos-db/standard-provisioned/) |
| | - Partitioning | - [Partitioning and horizontal scaling in Azure Cosmos DB](https://learn.microsoft.com/en-us/azure/cosmos-db/partitioning-overview) | 
| | - Item         | - [Azure Cosmos DB properties of an item](https://learn.microsoft.com/en-us/azure/cosmos-db/resource-model#properties-of-an-item) |
| | - Consistency levels | - [Consistency levels in Azure Cosmos DB](https://learn.microsoft.com/en-us/azure/cosmos-db/consistency-levels) |
| | - Queries | - [Cosmos DB Documents](https://learn.microsoft.com/en-us/rest/api/cosmos-db/documents)
| Work with Azure Cosmos DB |  - .NET SDK | -[Azure Cosmos DB Developer](https://developer.azurecosmosdb.com) <br> - [Azure Cosmos DB SDKs](https://developer.azurecosmosdb.com/community/sdk) <br> - [CosmosClient Class](https://learn.microsoft.com/en-us/dotnet/api/microsoft.azure.cosmos.cosmosclient) |
| Extra | Migrate data  | - [Migrate data to Azure Cosmos DB using the desktop data migration tool](https://learn.microsoft.com/en-us/azure/cosmos-db/how-to-migrate-desktop-tool) <br> - [Migrate hundreds of terabytes of data into Azure Cosmos DB](https://learn.microsoft.com/en-us/azure/cosmos-db/migrate) |





<br/>

## Learning Path 5: Implement containerized solutions

| Lessons | Notes |
| --- | --- |
| Manage Container Images in Azure Container Registry | - [Dockerfile reference (Docker Docs)](https://docs.docker.com/engine/reference/builder/) <br> - [Dockerfile on Windows](https://learn.microsoft.com/en-us/virtualization/windowscontainers/manage-docker/manage-windows-dockerfile) <br> - [Publishing and exposing ports (Docker Docs)](https://docs.docker.com/get-started/docker-concepts/running-containers/publishing-ports/) <br> - [ACR Service tier features and limits](https://learn.microsoft.com/en-us/azure/container-registry/container-registry-skus#service-tier-features-and-limits) |
| Run container images in Azure Container Instances  | - [Choose an Azure compute service](https://learn.microsoft.com/en-us/azure/architecture/guide/technology-choices/compute-decision-tree) <br> - [Choose an Azure compute option for microservices](https://learn.microsoft.com/en-us/azure/architecture/microservices/design/compute-options) <br> - [Microsoft Artifact Registry](https://mcr.microsoft.com/) <br> - [Use storage mounts in Azure Container Apps](https://learn.microsoft.com/en-us/azure/container-apps/storage-mounts) <br> - [Docker Volumes (Docker Docs)](https://docs.docker.com/engine/storage/volumes/) |
| Implement Azure Container Apps  | - [Azure Container Apps overview](https://learn.microsoft.com/en-us/azure/container-apps/overview) <br> - [Azure Container Apps (Darp Docs)](https://docs.dapr.io/operations/hosting/serverless/azure-container-apps/) <br> - [Tutorial: Deploy a Dapr application to Azure Container Apps using the Azure CLI](https://learn.microsoft.com/en-us/azure/container-apps/microservices-dapr) |




<br/>

## Learning Path 6: Implement user authentication and authorization


| Lessons |Notes |
| --- | --- |
| Explore the Microsoft identity platform |  - [What is the Microsoft identity platform?](https://learn.microsoft.com/en-us/entra/identity-platform/v2-overview) |
| Implement authentication by using the Microsoft Authentication Library | - [Overview of the Microsoft Authentication Library (MSAL)](https://learn.microsoft.com/en-us/entra/identity-platform/msal-overview) <br> - [Choosing a version of MSAL.NET](https://learn.microsoft.com/en-us/entra/msal/dotnet/getting-started/choosing-msal-dotnet) |
| Explore Microsoft Graph | - [Microsoft Graph quick start](https://developer.microsoft.com/en-us/graph/quick-start) <br> - [Graph Explorer](https://developer.microsoft.com/en-us/graph/graph-explorer) | 


<br/>

## Learning Path 7: Implement secure cloud solutions

| Lessons | Notes |
| --- | --- |
| Implement Azure Key Vault | - [Azure Key Vault developer's guide]( https://learn.microsoft.com/en-us/azure/key-vault/general/developers-guide) <br> - [Azure Key Vault availability and redundancy](https://learn.microsoft.com/en-us/azure/key-vault/general/disaster-recovery-guidance) <br> - [Azure Key Vault REST API reference](https://learn.microsoft.com/en-us/rest/api/keyvault/) |
| Implement managed identities | - [Application and service principal objects in Microsoft Entra ID](https://learn.microsoft.com/en-us/entra/identity-platform/app-objects-and-service-principals) <br> - [What is Azure role-based access control (Azure RBAC)?](https://learn.microsoft.com/en-us/azure/role-based-access-control/overview) <br> - [Azure built-in roles](https://learn.microsoft.com/en-us/azure/role-based-access-control/built-in-roles) <br> - [Steps to assign an Azure role](https://learn.microsoft.com/en-us/azure/role-based-access-control/role-assignments-steps) |

<br/>

## Learning Path 8: Implement API Management

| Lessons | Notes |
| --- | --- |
| - Explore API Management | - [Azure API Management v2 tiers Supported regions](https://learn.microsoft.com/en-us/azure/api-management/v2-service-tiers-overview#supported-regions) <br> - [API Management policy reference](https://learn.microsoft.com/en-us/azure/api-management/api-management-policies) <br> - [Tutorial: Import and publish your first API](https://learn.microsoft.com/en-us/azure/api-management/import-and-publish) |


<br/>

## Learning Path 9: Develop event-based solutions


| Lessons | Notes |
| --- | --- |
| Explore Azure Event Grid | - [Azure Event Grid event schema](https://docs.microsoft.com/en-us/azure/event-grid/event-schema) |
| Explorer Azure Event Hubs | - [Schema Registry in Azure Event Hubs](https://learn.microsoft.com/en-us/azure/event-hubs/schema-registry-concepts) - <br> - [Client-side schema enforcement](https://learn.microsoft.com/en-us/azure/event-hubs/schema-registry-client-side-enforcement) <br> - [Stream processing with Azure Stream Analytics (Architecture)](https://learn.microsoft.com/en-us/azure/architecture/reference-architectures/data/stream-processing-stream-analytics) |
| Hands-on Labs            | - [Azure-Samples/azure-event-grid-viewer](https://github.com/Azure-Samples/azure-event-grid-viewer) |



<br/>

## Learning Path 10: Develop message-based solutions


| Lessons | Notes |
| --- | --- |
| Service Bus | - [Use a message broker and events to integrate enterprise systems (Architecture)](https://learn.microsoft.com/en-us/azure/architecture/example-scenario/integration/queues-events) |



<br/>

## Learning Path 11: Troubleshoot solutions by using Application Insights


| Lessons | Notes |
| --- | ---
| Application Insights | - [Application Insights overview](https://learn.microsoft.com/en-us/azure/azure-monitor/app/app-insights-overview) |



<br/>

## Learning Path 12: Implement caching for solutions


| Lessons | Notes |
| --- | ---
| Develop for Azure Cache for Redis | - [Redis Open Source](https://redis.io) <br> - [Redis enterprise](https://redis.com) <br> - [Redis CLI](https://redis.io/docs/manual/cli/) |
| Develop for storage on CDNs | - [Content Delivery Network limits](https://learn.microsoft.com/en-us/azure/azure-resource-manager/management/azure-subscription-service-limits#content-delivery-network-limits) |


<br/>

