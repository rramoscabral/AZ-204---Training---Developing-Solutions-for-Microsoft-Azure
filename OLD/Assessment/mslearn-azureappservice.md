<a id="top" />

<br/>


[**Back to assessment**](./assessment.md) |   [**Back to main**](../README.md) 

# Learning Path 1: AZ-204: Implement Azure App Service web apps
	
## Multiple-choice questions	

1. Which of the following App Service plan categories provides the maximum scale out capabilities?
    - [ ] A.  Dedicated compute
    - [ ] B.  Isolated
    - [ ] C.  Shared compute

    <br>

    <details>
    <summary>Show answer</summary>
     Isolated
    </details>

    <br>

2. Which of the following networking features of App Service can be used to control outbound network traffic?

    - [ ] A.  App-assigned address
    - [ ] B.  Hybrid Connections
    - [ ] C.  Service endpoints

    <br>

    <details>
    <summary>Show answer</summary>
    Hybrid Connections
    </details>

    <br>

3. In which of the following app configuration settings categories would you set the language and SDK version?

    - [ ] A.  Application settings
    - [ ] B.  Path mappings
    - [ ] C.  General settings

    <br>

    <details>
    <summary>Show answer</summary>
     General settings
    </details>

    <br>

4. Which of the following types of application logging is supported on the Linux platform?

    - [ ] A.  Web server logging 
    - [ ] B.  Failed request tracing 
    - [ ] C.  Deployment logging

    <br>

    <details>
    <summary>Show answer</summary>
    Deployment logging
    </details>

    <br>

5. Which of these statements best describes autoscaling?

    - [ ] A.  Autoscaling requires an administrator to actively monitor the workload on a system. 
    - [ ] B.  Autoscaling is a scale out/scale in solution.
    - [ ] C.  Scaling up/scale down provides better availability than autoscaling. 

    <br>

    <details>
    <summary>Show answer</summary>
    Autoscaling is a scale out/scale in solution.
    </details>

    <br>

6. Which of these scenarios is a suitable candidate for autoscaling?


    - [ ] A.  The number of users requiring access to an application varies according to a regular schedule. For example, more users use the system on a Friday than other days of the week.
    - [ ] B.  The system is subject to a sudden influx of requests that grinds your system to a halt.
    - [ ] C.  Your organization is running a promotion and expects to see increased traffic to their web site for the next couple of weeks.

    <br>

    <details>
    <summary>Show answer</summary>
    The number of users requiring access to an application varies according to a regular schedule. For example, more users use the system on a Friday than other days of the week.
    </details>

    <br>

7. By default, all client requests to the app's production URL (http://<app_name>.azurewebsites.net) are routed to the production slot. One can automatically route a portion of the traffic to another slot. What is the default routing rule applied to new deployment slots?

    - [ ] A.  0% 
    - [ ] B.  10% 
    - [ ] C.  20% 

    <br>

    <details>
    <summary>Show answer</summary>
    0% 
    </details>

    <br>

8. Some configuration elements follow the content across a swap (not slot specific), whereas other configuration elements stay in the same slot after a swap (slot specific). Which of the following settings are swapped?

    - [ ] A.  Publishing endpoints 
    - [ ] B.  WebJobs content
    - [ ] C.  WebJobs schedulers Open ended questions

    <br>

    <details>
    <summary>Show answer</summary>
    WebJobs content
    </details>

    <br>


## Open ended questions

1. Describe how App Service plans impact the scalability of an app. 


    <details>
    <summary>Show answer</summary>
    Scaling up in App Service means the virtual machine the app is running on will have more processing power and higher performance. Apps in App Service can be scaled up, or scaled down (less processing power), by adjusting the pricing tier of the plan.
    </details>

    <br>


2. What are some of the advantages of using the built-in authentication in Azure App Service?



    <details>
    <summary>Show answer</summary>
    The built-in authentication doesn’t require any particular programming language, security expertise, or any code to utilize. App Service uses federated identity with many identity providers like Facebook, Google, and Twitter available by default. You can also use any OpenID Connect provider. 
    </details>

    <br>



3. You can set up rules (called conditions) in App Service to automate scaling an app out and in. Describe how App Service evaluates those rules. What types of metrics can be included in the rules?


    <details>
    <summary>Show answer</summary>
     When evaluating rules App Service evaluates the chosen metrics across all instances of the app. For example, if CPU utilization is one of the metrics used to determine if a change in scaling is needed, App Service will aggregate the CPU utilization for all instances of the app across a period of time known as the time grain. App service will perform the autoscale operation if the aggregated number meets the conditions in the rule.
    </details>

    <br>




4. What are web app deployment slots and how can they be used?

    <details>
    <summary>Show answer</summary>
    Deployment slots allow your app to run different instances. For example, a staging instance and a production instance. Deployment slots are live apps with their own hostnames. Deployment slots help you validate changes before making the app live. Slots also avoid a cold start which eliminates downtime. Lastly, slots let you fall back to a known good site.
    </details>

    <br>


<br/>

------

[**Back to top**](#top) | [**Back to assessment**](./assessment.md) | [**Back to main**](../README.md) 