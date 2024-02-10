<a id="top" />

<br/>


[**Back to assessment**](./assessment.md) |   [**Back to main**](../README.md) 

# Learning Path 12: AZ-204: Implement caching for solutions

## Multiple-choice questions		


1. What is the lowest service tier of Azure Cache for Redis recommended for use in production scenarios?

    - [ ]  A. Basic 
    - [ ]  B. Standard
    - [ ]  C. Premium 

    <br>

    <details>
    <summary>Show answer</summary>
    Standard
    </details>

    <br>


2. Which of the following represents the expire time resolution when applying a time to live (TTL) to a key in Redis?

    - [ ]  A. 1-millisecond
    - [ ]  B. 10-milliseconds 
    - [ ]  C. seconds or milliseconds 


    <br>

    <details>
    <summary>Show answer</summary>
    1-millisecond
    </details>

    <br>



3. Each Azure subscription has default limits on resources needed for an Azure Content Delivery Network. Which of the following resources has subscription limitations that may impact your solution?

    - [ ]  A. Resource group
    - [ ]  B. CDN profiles
    - [ ]  C. Storage account 


    <br>

    <details>
    <summary>Show answer</summary>
    CDN profiles
    </details>

    <br>


4. When publishing a website through Azure CDN, the files on that site are cached until their time-to-live (TTL) expires. What is the default TTL for large file optimizations?

    - [ ]  A. One day
    - [ ]  B. One week 
    - [ ]  C. One year


    <br>

    <details>
    <summary>Show answer</summary>
    One day
    </details>

    <br>



## Open ended questions

1. How does Azure Cache for Redis improve app performance?


    <br>

    <details>
    <summary>Show answer</summary>
    Azure Cache for Redis provides an in-memory data store based on the Redis software. Redis improves the performance and scalability of an application that uses backend data stores heavily. It's able to process large volumes of application requests by keeping frequently accessed data in the server memory.
    </details>

    <br>




2. How does Azure Content Delivery Network improve app performance?

    <br>

    <details>
    <summary>Show answer</summary>
    Azure Content Delivery Network (CDN) delivers high-bandwidth content to users by caching their content at strategically placed physical nodes across the world. Azure CDN can also accelerate dynamic content, which cannot be cached, by 
leveraging various network optimizations using CDN POPs.
    </details>

    <br>




3. Describe how content can be updated in Azure CDN.

    <br>

    <details>
    <summary>Show answer</summary>
    In normal operation, an Azure CDN edge node will serve an asset until its TTL expires. The node will fetch another copy of the asset, resetting the TTL in the process. Alternatively, you can purge cached content from the edge nodes, which refreshes the content on the next client request.
    </details>

    <br>





<br/>

------

[**Back to top**](#top) | [**Back to assessment**](./assessment.md) | [**Back to main**](../README.md) 