
# Microservices (Definition and benefits)

Before we get in the definition of microservice , our normal way of work is writing a large monolithic services that handles all of our business features and making this services exposed to the client

But this methodology has it disadvantages especially when our system become bigger

### What are the problems of monolithic service :

-   Using single service for features makes it impossible to implement theses features using different technologies
-   Using single service makes it hard to maintain as if failure happened in any part it will affect whole service parts
-   Scaling single service containing all features would be very hard as when we apply scale technique to specific feature it will be applied to all features in spite it may not adapt them
-   When applying small change in specific feature , whole service should be deployed and that takes time

### **What are microservices :**

Microservices are small, autonomous services that work together.

### Why Microservices:

-   Applying microservices allows services written in different technologies to communicate with each and this concepts is know as  **technology heterogeneity**
-   Using microservice makes your system more resilient as if one service failed , system will continue working and this failure can be isolated and handled separately
-   Using microservices make scaling your application easier , as now you are working with multiple services so each service can be scaled using different techniques and independently from other services
-   Using microservices make yours application easier to deploy as now you have separate decoupled independent services in which each service correspond to a specific feature and can be deployed independently of other services , so updating a specific feature will require deploying of its service only instead of deploying whole services
-   You can reuse your microservice in different places with different ways for different purposes
-   It is easier to delete or replace a microservice as it is small in size and concentrating on specific function with fewer lines of codes

So now that we know definition and benefits of microservices , in the next section we will discuss how to model our services from [here](modelservices.md)
