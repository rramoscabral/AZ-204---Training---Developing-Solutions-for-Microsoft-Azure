<a id="top" />

<br/>


[**Back to assessment**](./assessment.md) |   [**Back to main**](../README.md) 

# Learning Path 5: AZ-204: Implement containerized solutions

## Multiple-choice questions		


1. Which of the following Azure Container Registry options support geo-replication to manage a single registry across multiple regions?

    - [ ]  A. Basic 
    - [ ]  B. Standard 
    - [ ]  C. Premium

    <br>

    <details>
    <summary>Show answer</summary>
    Premium
    </details>

    <br>


2. Which Azure container registry tiers benefit from encryption-at-rest?

    - [ ]  A. Basic, Standard, and Premium
    - [ ]  B. Basic and Standard only 
    - [ ]  C. Premium only 

    <br>

    <details>
    <summary>Show answer</summary>
    Basic, Standard, and Premium
    </details>

    <br>

3. Which of the following methods is recommended when deploying a multi-container group that includes only containers?

    - [ ]  A. Azure Resource Management template
    - [ ]  B. YAML file
    - [ ]  C. az container creates command 

    <br>

    <details>
    <summary>Show answer</summary>
    YAML file
    </details>

    <br>


4. What is the purpose of a restart policy in Azure Container Instances?

    - [ ]  A. To charge customers more for compute resources used while the container is running. 
    - [ ]  B. To ensure that containers are never restarted, even if the process fails. 
    - [ ]  C. To specify when and how containers should be restarted, based on the desired behavior.

    <br>

    <details>
    <summary>Show answer</summary>
    To specify when and how containers should be restarted, based on the desired behavior.
    </details>

    <br>

5. Which of the following options is true about the built-in authentication feature in Azure Container Apps?

    - [ ]  A. It can only be configured to restrict access to authenticated users. 
    - [ ]  B. It allows for out-of-the-box authentication with federated identity providers.
    - [ ]  C. It requires the use of a specific language or SDK.


    <br>

    <details>
    <summary>Show answer</summary>
    It allows for out-of-the-box authentication with federated identity providers.
    </details>

    <br>

6. What is a revision in Azure Container Apps?
    - [ ]  A. A dynamic snapshot of a container app version. 
    - [ ]  B. A version of a container app that is actively being used. 
    - [ ]  C. An immutable snapshot of a container app version.


    <br>

    <details>
    <summary>Show answer</summary>
    An immutable snapshot of a container app version.
    </details>

    <br>


## Open ended questions

1. What is the process for managing versions in Azure Container Apps?


    <br>

    <details>
    <summary>Show answer</summary>
    Managing versions in Azure Container Apps involves creating new versions of your app, deploying them to the appropriate environment, and monitoring and updating them as needed. When creating a new version, you can use the Azure CLI or portal to specify the container image and any necessary configuration changes.
    </details>

    <br>




2. What are the three restart policy settings in Azure Container Instances and how do they behave?. 

    <br>

    <details>
    <summary>Show answer</summary>
    The Always setting restarts a container if they are stopped. Containers are never restarted if the Never setting is used. If the OnFailure setting is used containers are only restarted if they are stopped because the process executed in the container fails.
    </details>

    <br>


3. Describe the three service tiers in Azure Container Registry.

    <br>

    <details>
    <summary>Show answer</summary>
    1. The Basic tier is a cost-optimized entry point for developers learning about Azure Container Registry. Basic registries have the same programmatic capabilities as Standard and Premium tiers.
    2. The Standard tier offers the same capabilities as Basic, with increased included storage and image throughput. Standard registries should satisfy the needs of most production scenarios.
    3. The Premium tier provides the highest amount of included storage and concurrent operations, enabling high-volume scenarios. In addition to higher image throughput, Premium adds features such as geo-replication.
    </details>

    <br>







<br/>

------

[**Back to top**](#top) | [**Back to assessment**](./assessment.md) | [**Back to main**](../README.md) 