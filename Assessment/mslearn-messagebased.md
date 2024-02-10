<a id="top" />

<br/>


[**Back to assessment**](./assessment.md) |   [**Back to main**](../README.md) 

# Learning Path 10: AZ-204: Develop message-based solutions

## Multiple-choice questions		

1. Which of the following advanced features of Azure Service Bus creates a first-in, first-out (FIFO) guarantee?

    - [ ]  A. Transactions 
    - [ ]  B. Scheduled delivery 
    - [ ]  C. Message sessions

    <br>

    <details>
    <summary>Show answer</summary>
    Message sessions
    </details>

    <br>

2. In Azure Service Bus messages are durably stored which enables a load-leveling benefit. Which of the following correctly describes the load-leveling benefit relative to a consuming application's performance?

    - [ ]  A. Performance needs to handle peak load 
    - [ ]  B. Performance needs to handle average load
    - [ ]  C. Performance needs to handle low loads 

    <br>

    <details>
    <summary>Show answer</summary>
    Performance needs to handle average load
    </details>

    <br>

## Open ended questions

1. What factors do you need to consider when choosing to integrate Storage queues or Service Bus queues?

    <br>

    <details>
    <summary>Show answer</summary>
    Azure Backup is the main tool to backup and restore workloads. On-premises workloads include files and folders, Hyper-V virtual machines, VMware virtual machines, Microsoft SQL Server, Microsoft SharePoint, Microsoft Exchange, System State, and Bare Metal Recovery. Azure workloads include virtual machines, Azure file shares, SQL Server in Azure VM, and SAP HANA in Azure VM. 
    </details>

    <br>


2. You need to configure on-premises file and folder backups. What are basic steps to configuring the backup?

    <br>

    <details>
    <summary>Show answer</summary>
    Consider choosing Storage queues when: Your solution needs to receive messages without having to poll the queue. Your solution needs to support automatic duplicate detection. You want your application to process messages as parallel long-running streamsConsider choosing Storage queues when: Your application must store over 80 gigabytes of messages in a queue. Your application wants to track progress for processing a message in the queue. You require server-side logs of all the transactions executed against your queues.
    </details>

    <br>



3. Describe the First In, First Out message delivery in Azure Service Bus. 

    <br>

    <details>
    <summary>Show answer</summary>
    Queues in Service Bus offer message delivery to one or more competing consumers. That is, receivers typically receive and process messages in the order in which they were added to the queue. Only one message consumer receives and processes each message. Because messages are stored durably in the queue producers (senders) and consumers (receivers) don't have to process messages concurrently
    </details>

    <br>




<br/>

------

[**Back to top**](#top) | [**Back to assessment**](./assessment.md) | [**Back to main**](../README.md) 