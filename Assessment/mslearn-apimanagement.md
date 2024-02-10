<a id="top" />

<br/>


[**Back to assessment**](./assessment.md) |   [**Back to main**](../README.md) 

# Learning Path 8: AZ-204: Implement API Management

## Multiple-choice questions	




1. Which of the following components of the API Management service would a developer use if they need to create an account and subscribe to get API keys?

    - [ ]  A. API gateway
    - [ ]  B. Azure portal 
    - [ ]  C. Developer portal

    <br>

    <details>
    <summary>Show answer</summary>
    Developer portal
    </details>

    <br>

2. Which of the following API Management policies would one use if one wants to apply a policy based on a condition?

    - [ ]  A. forward-request 
    - [ ]  B. choose
    - [ ]  C. return-response

    <br>

    <details>
    <summary>Show answer</summary>
    choose
    </details>

    <br>


## Open ended questions

1. What is an API Gateway and what problems does it help address?

    <br>

    <details>
    <summary>Show answer</summary>
    An API gateway sits between clients and services. It acts as a reverse proxy, routing requests from clients to services. It may also perform various cross-cutting tasks such as authentication, SSL termination, and rate limiting. If you don't deploy a gateway, clients must send requests directly to front-end services. However, there are some potential problems with exposing services directly to clients such as needed more complex code on the client and increasing the potential attack surface of the solution.
    </details>

    <br>




2. Describe how you can secure APIs.

    <br>

    <details>
    <summary>Show answer</summary>
    Certificates can be used to provide Transport Layer Security (TLS) mutual authentication between the client and the API gateway. You can configure the API Management gateway to allow only requests with certificates containing a specific thumbprint. The authorization at the gateway level is handled through inbound policies.
    </details>

    <br>




3. Policies can be used to change the behavior of an API. Describe how policies are configured and what each section of the configuration does.

    <br>

    <details>
    <summary>Show answer</summary>
    In Azure API Management, policies allow the publisher to change the behavior of the API through configuration. Policies are a collection of Statements that are executed sequentially on the request or response of an API. The configuration is divided into inbound, backend, outbound, and on-error. The series of specified policy statements is executed in order for a request and a response
    </details>

    <br>





<br/>

------

[**Back to top**](#top) | [**Back to assessment**](./assessment.md) | [**Back to main**](../README.md) 