<a id="top" />

<br/>


[**Back to assessment**](./assessment.md) |   [**Back to main**](../README.md) 

# Learning Path 6: AZ-204: Implement user authentication and authorization

## Multiple-choice questions		


1. Which of the types of permissions supported by the Microsoft identity platform is used by apps that have a signed-in user present?

    - [ ]  A. Delegated permissions
    - [ ]  B. App-only access permissions 
    - [ ]  C. Both delegated and app-only access permissions 

    <br>

    <details>
    <summary>Show answer</summary>
    Delegated permissions
    </details>

    <br>
    
2. Which of the following app scenarios require code to handle Conditional Access challenges?


    - [ ]  A. Apps performing the device-code flow
    - [ ]  B. Apps performing the on-behalf-of flow
    - [ ]  C. Apps performing the Integrated Windows uthentication flow 

    <br>

    <details>
    <summary>Show answer</summary>
    Apps performing the on-behalf-of flow
    </details>

    <br>


3. Which of the following MSAL libraries supports single-page web apps?

    - [ ]  A. MSAL Node 
    - [ ]  B. MSAL.js
    - [ ]  C. MSAL.NET

    <br>

    <details>
    <summary>Show answer</summary>
    MSAL.js
    </details>

    <br>

4. What is the purpose of using PublicClientApplicationBuilder class in MSAL.NET?


    - [ ]  A. It is used to create a new Azure account. 
    - [ ]  B. Enables the automation and validation of the creation and teardown of environments to help deliver secure and stable application hosting platforms
    - [ ]  C. It is used to add a new API permission to the registered app.

    <br>

    <details>
    <summary>Show answer</summary>
    Enables the automation and validation of the creation and teardown of environments to help deliver secure and stable application hosting platforms
    </details>

    <br>


5. Which HTTP method below is used to update a resource with new values?

    - [ ]  A. POST 
    - [ ]  B. PATCH
    - [ ]  C. PUT 

    <br>

    <details>
    <summary>Show answer</summary>
    PATCH
    </details>

    <br>

6. Which of the following types of shared access signatures (SAS) applies to Blob storage only?

    - [ ]  A. Account SAS 
    - [ ]  B. Service SAS 
    - [ ]  C. User delegation SAS

    <br>

    <details>
    <summary>Show answer</summary>
    User delegation SAS
    </details>

    <br>
7. Which of the following best practices provides the most flexible and secure way to use a service or account shared access signature (SAS)?


    - [ ]  A. Associate SAS tokens with a stored access policy.
    - [ ]  B. Always use HTTPS 
    - [ ]  C. Implement a user delegation SAS 

    <br>

    <details>
    <summary>Show answer</summary>
    Associate SAS tokens with a stored access policy.
    </details>

    <br>


8. Which of the components of the Microsoft 365 platform is used to deliver data external to Azure into Microsoft Graph services and applications?

    - [ ]  A. Microsoft Graph API 
    - [ ]  B. Microsoft Graph connectors
    - [ ]  C. Microsoft Graph Data Connect 

    <br>

    <details>
    <summary>Show answer</summary>
    Microsoft Graph connectors
    </details>

    <br>


## Open ended questions


1. How is a service principal object created and what does it define?

    <br>

    <details>
    <summary>Show answer</summary>
    When you register an application in the portal, an application object (the globally unique instance of the app) as well as a service principal object are automatically created in your home tenant. The security principal defines the access policy and permissions for the user/application in the Microsoft Entra tenant.
    </details>

    <br>



2. The Microsoft identity platform supports two types of permissions: delegated and user permissions. How are they different?

    <br>

    <details>
    <summary>Show answer</summary>
    Delegated permissions are used by apps that have a signed-in user present. For these apps, either the user or an administrator consents to the permissions that the app requests. The app is delegated with the permission to act as a signed-in user when it makes calls to the target resource. User permissions are used by apps that run without a signed-in user present, for example, apps that runas background services or daemons. Only an administrator can consent to application permissions.
    </details>

    <br>



3. When would Conditional Access impact an app?

    <br>

    <details>
    <summary>Show answer</summary>
    In most common cases, Conditional Access does not change an app's behavior or require any changes from the developer. Only in certain cases when an app indirectly or silently requests a token for a service does an app require code changes to handle Conditional Access challenges. It may be as simple as performing an interactive sign-in request.
    </details>

    <br>



<br/>

------

[**Back to top**](#top) | [**Back to assessment**](./assessment.md) | [**Back to main**](../README.md) 