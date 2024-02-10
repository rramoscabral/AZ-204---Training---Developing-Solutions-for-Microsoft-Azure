<a id="top" />

<br/>


[**Back to assessment**](./assessment.md) |   [**Back to main**](../README.md) 

# Learning Path 9: AZ-204: Develop event-based solutions

## Multiple-choice questions		

1. Which of the following event schema properties requires a value?

    - [ ]  A. Topic 
    - [ ]  B. Data
    - [ ]  C. Subject

    <br>

    <details>
    <summary>Show answer</summary>
    Subject
    </details>

    <br>

    
2. Which of the following Event Grid built-in roles is appropriate for managing Event Grid resources?


    - [ ]  A. Event Grid Contributor
    - [ ]  B. Event Grid Subscription Contributor 
    - [ ]  C. Event Grid Data Sender 

    <br>

    <details>
    <summary>Show answer</summary>
    Event Grid Contributor
    </details>

    <br>

3. Which of the following Event Hubs concepts represents an ordered sequence of events that is held in an Event Hubs?

    - [ ]  A. Consumer group 
    - [ ]  B. Partition
    - [ ]  C. Event Hubs producer

    <br>

    <details>
    <summary>Show answer</summary>
    Partition
    </details>

    <br>


4. Which of the following options represents when an event processor marks or commits the position of the last successfully processed event within a partition?

    - [ ]  A. Checkpointing
    - [ ]  B. Scale 
    - [ ]  C. Load balance 


    <br>

    <details>
    <summary>Show answer</summary>
    Checkpointing
    </details>

    <br>

## Open ended questions

1. Describe what Azure Event Grid does, and what is the endpoint where publishers send events called?

    <br>

    <details>
    <summary>Show answer</summary>
    Azure Event Grid is an eventing backplane that enables event-driven, reactive programming. It uses the publish-subscribe model and connects sources of events to event handlers. Topics is the endpoint where publishers send events.
    </details>

    <br>





2. Event Grid can be configured to batch events in high-throughput scenarios. There are two settings that control batched delivery. Describe both settings.

    <br>

    <details>
    <summary>Show answer</summary>
    1. Max events per batch - Maximum number of events Event Grid will deliver per batch. Event Grid doesn't delay events to create a batch if fewer events are available. 
    2. Preferred batch size in kilobytes - target ceiling for batch size in kilobytes. Similar to max events, the batch size may be smaller if more events aren't available at the time of publish.
    </details>

    <br>

    





3. There are four built-in roles that control the level of access to perform management operations. List at least two of the roles and describe their scope.

    <br>

    <details>
    <summary>Show answer</summary>
    1. Event Grid Subscription Reader – lets you read Event Grid subscriptions. 
    2. Event Grid Subscription Contributor – lets you manage Event Grid event subscription operations. 
    3. Event Grid Contributor – lets you create and manage Event Grid resources. 
    4. Event Grid Data Sender – lets you send events to Event Grid topics.
    </details>

    <br>




<br/>

------

[**Back to top**](#top) | [**Back to assessment**](./assessment.md) | [**Back to main**](../README.md) 