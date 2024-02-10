<a id="top" />

<br/>


[**Back to assessment**](./assessment.md) |   [**Back to main**](../README.md) 

# Learning Path 3: AZ-204: Develop solutions that use Blob storage

## Multiple-choice questions	


1. Which of the following types of blobs are used to store virtual hard drive files?

    - [ ]  A. Block blobs
    - [ ]  B. Append blobs
    - [ ]  C. Page blobs

    <br>

    <details>
    <summary>Show answer</summary>
    Page blobs
    </details>

    <br>

2. Which of the following types of storage accounts is recommended for most scenarios using Azure Storage?

    - [ ]  A. General-purpose v2
    - [ ]  B. General-purpose v1 
    - [ ]  C. FileStorage

    <br>

    <details>
    <summary>Show answer</summary>
    General-purpose v2
    </details>

    <br>

3. Which access tier is considered to be offline and can't be read or modified?

    - [ ]  A. Cool
    - [ ]  B. Archive
    - [ ]  C. Hot

    <br>

    <details>
    <summary>Show answer</summary>
    Archive
    </details>

    <br>

4. Which of the following storage account types supports lifecycle policies?

    - [ ]  A. General Purpose v1
    - [ ]  B. General Purpose v2
    - [ ]  C. FileStorage 

    <br>

    <details>
    <summary>Show answer</summary>
    General Purpose v2
    </details>

    <br>

5. Which of the following standard HTTP headers are supported for both containers and blobs when setting properties by using REST?

    - [ ]  A. Last-Modified
    - [ ]  B. Content-Length
    - [ ]  C. Origin

    <br>

    <details>
    <summary>Show answer</summary>
    Last-Modified
    </details>

    <br>

6. Which of the following classes of the Azure Storage client library for .NET allows you to manipulate both Azure Storage containers and their blobs?

    - [ ]  A. BlobClient
    - [ ]  B. BlobContainerClient
    - [ ]  C. BlobUriBuilde

    <br>

    <details>
    <summary>Show answer</summary>
    BlobContainerClient
    </details>

    <br>

## Open ended questions

1. What are Azure blobs and what four access tiers are provided?


    <br>

    <details>
    <summary>Show answer</summary>
    Azure blob storage stores unstructured data. Blob storage can store any type of text or binary data. For example, images and video. The hot tier is optimized for frequent access of objects in the storage account. The cool tier is optimized for storing large amounts of data that is infrequently accessed and stored for at least 30 days. The cold tier is optimized for storing data that is infrequently accessed and stored for a minimum of 90 days. The cold tier has lower storage costs and higher access costs compared to the cool tier. The archive tier is optimized for data that can tolerate several hours of retrieval latency and will remain in the Archive tier for at least 180 days.
    </details>

    <br>



2. Describe some of the security capabilities Azure Storage provides that enable developers to build secure applications.

    <br>

    <details>
    <summary>Show answer</summary>
    All data written to Azure Storage is automatically encrypted using Storage Service Encryption. You can use Microsoft Entra ID and Role-Based Access Control for both resource management and data operations. You can also use shared access signatures to delegate access to data object in Azure Storage.
    </details>

    <br>



3. Blob containers support system properties and user-defined metadata, in addition to the data they contain. What is user-defined metadata and how it is specified?

    <br>

    <details>
    <summary>Show answer</summary>
    User-defined metadata consists of one or more name-value pairs that you specify for a Blob storage resource. You can use metadata to store additional values with the resource. Metadata values are for your own purposes only, and do not affect how the resource behaves
    </details>

    <br>


<br/>

------

[**Back to top**](#top) | [**Back to assessment**](./assessment.md) | [**Back to main**](../README.md) 