<a id="top" />

<br/>


[**Back to assessment**](./assessment.md) |   [**Back to main**](../README.md) 

# Learning Path 2: AZ-204: Implement Azure Functions

## Multiple-choice questions		

1. Which of the following Azure Functions hosting plans is best hen predictive scaling and costs are required?

    - [ ]  A. Functions Premium Plan
    - [ ]  b. Dedicated plan
    - [ ]  c. Consumption plan

    <br>

    <details>
    <summary>Show answer</summary>
    Dedicated plan
    </details>

    <br>

2. An organization wants to implement a serverless workflow to solve a business problem. One of the requirements is the solution needs to use a designer-first (declarative) development model. Which of the choices below meets the requirements?

    - [ ]  A. Azure Functions 
    - [ ]  b. Azure Logic Apps
    - [ ]  c. WebJobs 

    <br>

    <details>
    <summary>Show answer</summary>
    Azure Logic Apps
    </details>

    <br>

3. Which of the following choices is required for a function to run?

    - [ ]  A. Binding
    - [ ]  b. Trigger
    - [ ]  c. Both triggers and bindings


    <br>

    <details>
    <summary>Show answer</summary>
    Trigger
    </details>

    <br>

4. Which of the following choices supports both the in and out direction settings?

    - [ ]  A. Bindings
    - [ ]  b. Trigger
    - [ ]  c. Connection value

    <br>

    <details>
    <summary>Show answer</summary>
    Bindings
    </details>

    <br>

## Open ended questions

1. Describe the role of triggers and bindings in an Azure Function app. Which, if any, are required?


    <br>

    <details>
    <summary>Show answer</summary>
    Triggers are what cause a function to run. A trigger defines how a function is invoked and a function must have exactly one trigger. Triggers have associated data, which is often provided as the payload of the function. Bindings, which are not required, connect functions to other resources in Azure and have an in or outdirection. 
    </details>

    <br>



2. Describe how Azure Functions are scaled in the Consumption and Premium plans.

    <br>

    <details>
    <summary>Show answer</summary>
    In the Consumption and Premium plans, Azure Functions scales CPU and memory resources by adding additional instances of the Functions host. The number of instances is determined on the number of events that trigger a function.
    </details>

    <br>


<br/>

------

[**Back to top**](#top) | [**Back to assessment**](./assessment.md) | [**Back to main**](../README.md) 