<a id="top" />

<br/>


[**Back to assessment**](./assessment.md) |   [**Back to main**](../README.md) 

# Learning Path 7: AZ-204: Implement secure Azure solutions

## Multiple-choice questions		




1. Which of the below methods of authenticating to Azure Key Vault is recommended for most scenarios?

    - [ ]  A. Service principal and certificate
    - [ ]  B. Service principal and secret
    - [ ]  C. Managed identities

    <br>

    <details>
    <summary>Show answer</summary>
    Managed identities
    </details>

    <br>

2. Azure Key Vault protects data when it's traveling between Azure Key Vault and clients. What protocol does it use for encryption?

    - [ ]  A. Secure Sockets Layer 
    - [ ]  B. Transport Layer Security
    - [ ]  C. Presentation Layer 

    <br>

    <details>
    <summary>Show answer</summary>
    Transport Layer Security
    </details>

    <br>

3. Which of the following managed identity characteristics is indicative of user assigned identities?

    - [ ]  A. Shared lifecycle with an Azure resource
    - [ ]  B. Independent life-cycle
    - [ ]  C. Can only be associated with a single Azure esource


    <br>

    <details>
    <summary>Show answer</summary>
    Independent life-cycle
    </details>

    <br>


4. A client app requests managed identities for an access token for a given resource. Which of the below is the basis for the token?

    - [ ]  A. Oauth 2.0 
    - [ ]  B. Service principal
    - [ ]  C. Virtual machine

    <br>

    <details>
    <summary>Show answer</summary>
    Service principal
    </details>

    <br>

5. Which type of encryption does Azure App Configuration use to encrypt data at rest?

    - [ ]  A. 64-bit AES 
    - [ ]  B. 128-bit AES 
    - [ ]  C. 256-bit AES


    <br>

    <details>
    <summary>Show answer</summary>
    256-bit AES
    </details>

    <br>


6. Which of the following options evaluates the state of a feature flag?

    - [ ]  A. Feature flag 
    - [ ]  B. Feature manager 
    - [ ]  C. Filter

    <br>

    <details>
    <summary>Show answer</summary>
    Filter
    </details>

    <br>

## Open ended questions

1. Describe at least one of the three main security problems Azure Key Vault helps to solve.


    <br>

    <details>
    <summary>Show answer</summary>
    1. Secrets management: Azure Key Vault can be used to Securely store and tightly control access to tokens, passwords, certificates, API keys, and other secrets. 
    2. Key management: Azure Key Vault can also be used as a Key Management solution. Azure Key Vault makes it easy to create and control the encryption keys used to encrypt your data.
    3. Certificate management: Azure Key Vault is also a service that lets you easily provision, manage, and deploy public and private Secure Sockets Layer/Transport Layer Security (SSL/TLS) certificates for use with Azure and your internal connected resources.
    </details>

    <br>







2. To do any operation with Azure Key Vault, you first need to authenticate to it. There are three ways to manage authenticating to Key Vault, which method is considered a best practice?

    <br>

    <details>
    <summary>Show answer</summary>
    Using managed identities for authentication is onsidered a best practice. When you deploy an app on a virtual machine in Azure, you can assign an identity to your virtual machine that has access to Key Vault. You can also assign identities to other Azure resources. The benefit of this approach is that the app or service isn't managing the rotation of the first secret. Azure automatically rotates the service principal client secret associated with the identity.
    </details>

    <br>




3. Describe how Azure App Configuration enhances running apps in the cloud.


    <br>

    <details>
    <summary>Show answer</summary>
    Modern programs, especially programs running in a cloud, generally have many components that are distributed in nature. Spreading configuration settings across these components can lead to hard-to-troubleshoot errors during an application deployment. Use App Configuration to store all the settings for your application and secure their access in one place.
    </details>

    <br>





<br/>

------

[**Back to top**](#top) | [**Back to assessment**](./assessment.md) | [**Back to main**](../README.md) 