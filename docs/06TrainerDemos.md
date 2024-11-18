---
layout: default
title: 'Trainer demonstrations'
nav_order: 6
has_children: false
---

# Trainer demonstrations
{: .no_toc }


## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

<br/>

---

<br/>

## Learning Path 1: Explore Azure App Service

<!-- Demonstrations -->

- **Deploy Web App using Git repository**

    ```bash
    az login
    
    gitrepo="https://github.com/Azure-Samples/php-docs-hello-world"
    
    $gitrepo
    
    az group create --location eastus --name <resource-group-name>
    
    az appservice plan create --name <web-app-service-plan-name> --resource-group <resource-group-name> --sku FREE
    
    az webapp create --name <web-app-service-name>  --resource-group <resource-group-name> --plan <web-app-service-plan-name> 
    
    az webapp deployment source config --name <web-app-service-name> --resource-group <resource-group-name> --repo-url $gitrepo --branch master --manual-integration
    ```

<br/>

---

<br/>


## Learning Path 02: Implement task processing logic by using Azure Functions

<!-- Demonstrations -->


<br/>

---

<br/>


## Learning Path 03: Develop solutions that use Blob storage

<!-- Demonstrations -->


<br/>

---

<br/>

## Learning Path 04: Develop solutions that use Azure Cosmos DB


<!-- Demonstrations -->


<br/>

---

<br/>

## Learning Path 05: Implement containerized solutions

<!-- Demonstrations -->

<br/>

---

<br/>


## Learning Path 06: Implement user authentication and authorization


<!-- Demonstrations -->


<br/>

---

<br/>


## Learning Path 07: Implement secure cloud solutions

<!-- Demonstrations -->



<br/>

---

<br/>

## Learning Path 08: Implement API Management


<!-- Demonstrations -->


<br/>

---

<br/>



## Learning Path 09: Develop event-based solutions

<!-- Demonstrations -->


<br/>

---

<br/>



## Learning Path 10: Develop message-based solutions


<!-- Demonstrations -->


<br/>

---

<br/>



## Learning Path 11: Troubleshoot solutions by using Application Insights


<!-- Demonstrations -->


<br/>

---

<br/>


## Learning Path 12: Implement caching for solutions


<!-- Demonstrations -->


<br/>

---

<br/>
