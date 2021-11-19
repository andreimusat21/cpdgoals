# CPD goals
(a 2-a sapt din sprint)
## **Testing** 

<details> 
1. The art of unit testing (Second edition)
</details>

## **Project tehnology** 
<details> 
  
1. DDD
2. CQRS
3. MediatR
  
</details>

## **Microservice Design Patterns and Principles** 

<details> 

1. Database per Microservice
2. Event Sourcing
3. CQRS
4. Saga
5. BFF
6. API Gateway
7. Strangler
8. Circuit Breaker
9. Externalized Configuration
10. Consumer-Driven Contract Tracing

</details>

## **Books & Tutorials C# - November**
<details> 

* [DDD patters and architecture](https://)

* [Unit testing books and video tutorial](https://)
* [SOLID](https://)

</details>

## **Kubernetes**
<details> 
  <summary>Expand</summary>

* [Kubernetes patterns - CPD](https://www.wallarm.com/what/top-kubernetes-design-patterns)
* [Complete Kubernetes - CPD](https://cognizant.udemy.com/course/learn-devops-the-complete-kubernetes-course/)
  
</details>
  
  
## **Azure certifications**
<details> 
  
* [AZ-900: Microsoft Azure Fundamentals CPD](https://docs.microsoft.com/en-us/learn/certifications/exams/az-900)
* [AZ-204: Developing Solutions for Microsoft Azure CPD](https://docs.microsoft.com/en-us/learn/certifications/exams/az-204)

</details>


## *CLOUD DESIGN PATTERNS*

<details> 
  <summary>Expand</summary>

* [Availability](https://docs.microsoft.com/en-us/azure/architecture/patterns/category/availability)
  * [Deployment stamps](https://docs.microsoft.com/en-us/azure/architecture/patterns/deployment-stamp)
    * *Deploy multiple independent copies of application components, including data stores*
  * [Geodes](https://docs.microsoft.com/en-us/azure/architecture/patterns/geodes)
    * *Deploy backend services into a set of geographical nodes, each of which can service any client request in any region*
  * [Health endpoint monitoring](https://docs.microsoft.com/en-us/azure/architecture/patterns/health-endpoint-monitoring)
    * *Implement functional checks in an application that external tools can access through exposed endpoints at regular intervals*
  * [Queue-based load leveling](https://docs.microsoft.com/en-us/azure/architecture/patterns/queue-based-load-leveling)
    * *Use a queue that acts as a buffer between a task and a service that it invokes, to smooth intermittent heavy loads*
  * [Throttling](https://docs.microsoft.com/en-us/azure/architecture/patterns/throttling)
    * *Control the consumption of resources by an instance of an application, an individual tenant, or an entire service*
* [Data management](https://docs.microsoft.com/en-us/azure/architecture/patterns/category/data-management)
  * [Cache-aside](https://docs.microsoft.com/en-us/azure/architecture/patterns/cache-aside)
    * *Load data on demand into a cache from a data store*
  * [Command and Query responsibility segregation (CQRS)](https://docs.microsoft.com/en-us/azure/architecture/patterns/cqrs)
    * *Segregate operations that read data from operations that update data by using separate interfaces*
  * [Event sourcing](https://docs.microsoft.com/en-us/azure/architecture/patterns/event-sourcing)
    * *Use an append-only store to record the full series of events that describe actions taken on data in a domain*
  * [Index table](https://docs.microsoft.com/en-us/azure/architecture/patterns/index-table)
    * *Create indexes over the fields in data stores that are frequently referenced by queries*
  * [Materialized view](https://docs.microsoft.com/en-us/azure/architecture/patterns/materialized-view)
    * *Generate prepopulated views over the data in one or more data stores when the data isn't ideally formatted for required query operations*
  * [Sharding](https://docs.microsoft.com/en-us/azure/architecture/patterns/sharding)
    * *Divide a data store into a set of horizontal partitions or shards*
  * [Static content hosting](https://docs.microsoft.com/en-us/azure/architecture/patterns/static-content-hosting)
    * *Deploy static content to a cloud-based storage service that can deliver them directly to the client*
  * [Valet key](https://docs.microsoft.com/en-us/azure/architecture/patterns/valet-key)
    * *Use a token or key that provides clients with restricted direct access to a specific resource or service*
* [Design and Implementation](https://docs.microsoft.com/en-us/azure/architecture/patterns/category/design-implementation)
  * [Ambassador](https://docs.microsoft.com/en-us/azure/architecture/patterns/ambassador)
    * *Create helper services that send network requests on behalf of a consumer service or application*
  * [Anti-corruption layer](https://docs.microsoft.com/en-us/azure/architecture/patterns/anti-corruption-layer)
    * *Implement a façade or adapter layer between a modern application and a legacy system*
  * [Backends for Frontends](https://docs.microsoft.com/en-us/azure/architecture/patterns/backends-for-frontends)
    * *Create separate backend services to be consumed by specific frontend applications or interfaces*
  * [Command and Query responsibility segregation (CQRS)](https://docs.microsoft.com/en-us/azure/architecture/patterns/cqrs)
    * *Segregate operations that read data from operations that update data by using separate interfaces*
  * [Compute resource consolidation](https://docs.microsoft.com/en-us/azure/architecture/patterns/compute-resource-consolidation)
    * *Consolidate multiple tasks or operations into a single computational unit*
  * [External configuration store](https://docs.microsoft.com/en-us/azure/architecture/patterns/external-configuration-store)
    * *Move configuration information out of the application deployment package to a centralized location*
  * [Gateway aggregation](https://docs.microsoft.com/en-us/azure/architecture/patterns/gateway-aggregation)
    * *Use a gateway to aggregate multiple individual requests into a single request*
  * [Gateway offloading](https://docs.microsoft.com/en-us/azure/architecture/patterns/gateway-offloading)
    * *Offload shared or specialized service functionality to a gateway proxy*
  * [Gateway routing](https://docs.microsoft.com/en-us/azure/architecture/patterns/gateway-routing)
    * *Route requests to multiple services using a single endpoint*
  * [Leader election](https://docs.microsoft.com/en-us/azure/architecture/patterns/leader-election)
    * *Coordinate the actions performed by a collection of collaborating task instances in a distributed application by electing one instance as the leader that assumes responsibility for managing the other instances*
  * [Pipes and filters](https://docs.microsoft.com/en-us/azure/architecture/patterns/pipes-and-filters)
    * *Break down a task that performs complex processing into a series of separate elements that can be reused*
  * [Sidecar](https://docs.microsoft.com/en-us/azure/architecture/patterns/sidecar)
    * *Deploy components of an application into a separate process or container to provide isolation and encapsulation*
  * [Static content hosting](https://docs.microsoft.com/en-us/azure/architecture/patterns/static-content-hosting)
    * *Deploy static content to a cloud-based storage service that can deliver them directly to the client*
  * [Strangler fig](https://docs.microsoft.com/en-us/azure/architecture/patterns/strangler-fig)
    * *Incrementally migrate a legacy system by gradually replacing specific pieces of functionality with new applications and services*
* [Management and Monitoring](https://docs.microsoft.com/en-us/azure/architecture/patterns/category/management-monitoring)
  * [Ambassador](https://docs.microsoft.com/en-us/azure/architecture/patterns/ambassador)
    * *Create helper services that send network requests on behalf of a consumer service or application*
  * [Anti-corruption layer](https://docs.microsoft.com/en-us/azure/architecture/patterns/anti-corruption-layer)
    * *Implement a façade or adapter layer between a modern application and a legacy system*
  * [External configuration store](https://docs.microsoft.com/en-us/azure/architecture/patterns/external-configuration-store)
    * *Move configuration information out of the application deployment package to a centralized location*
  * [Gateway aggregation](https://docs.microsoft.com/en-us/azure/architecture/patterns/gateway-aggregation)
    * *Use a gateway to aggregate multiple individual requests into a single request*
  * [Gateway offloading](https://docs.microsoft.com/en-us/azure/architecture/patterns/gateway-offloading)
    * *Offload shared or specialized service functionality to a gateway proxy*
  * [Gateway routing](https://docs.microsoft.com/en-us/azure/architecture/patterns/gateway-routing)
    * *Route requests to multiple services using a single endpoint*
  * [Health endpoint monitoring](https://docs.microsoft.com/en-us/azure/architecture/patterns/health-endpoint-monitoring)
    * *Implement functional checks in an application that external tools can access through exposed endpoints at regular intervals*
  * [Sidecar](https://docs.microsoft.com/en-us/azure/architecture/patterns/sidecar)
    * *Deploy components of an application into a separate process or container to provide isolation and encapsulation*
  * [Strangler fig](https://docs.microsoft.com/en-us/azure/architecture/patterns/strangler-fig)
    * *Incrementally migrate a legacy system by gradually replacing specific pieces of functionality with new applications and services*
* [Messaging](https://docs.microsoft.com/en-us/azure/architecture/patterns/category/messaging)
  * [Asynchronous request-reply](https://docs.microsoft.com/en-us/azure/architecture/patterns/async-request-reply)
    * *Decouple backend processing from a frontend host, where backend processing needs to be asynchronous, but the frontend still needs a clear response*
  * [Claim-check](https://docs.microsoft.com/en-us/azure/architecture/patterns/claim-check)
    * *Split a large message into a claim check and a payload to avoid overwhelming a message bus*
  * [Choreography](https://docs.microsoft.com/en-us/azure/architecture/patterns/choreography)
    * *Have each component of the system participate in the decision-making process about the workflow of a business transaction, instead of relying on a central point of control*
  * [Competing consumers](https://docs.microsoft.com/en-us/azure/architecture/patterns/competing-consumers)
    * *Enable multiple concurrent consumers to process messages received on the same messaging channel*
  * [Pipes and filters](https://docs.microsoft.com/en-us/azure/architecture/patterns/pipes-and-filters)
    * *Break down a task that performs complex processing into a series of separate elements that can be reused*
  * [Priority queue](https://docs.microsoft.com/en-us/azure/architecture/patterns/priority-queue)
    * *Prioritize requests sent to services so that requests with a higher priority are received and processed more quickly than those with a lower priority*
  * [Publish-subscriber](https://docs.microsoft.com/en-us/azure/architecture/patterns/publisher-subscriber)
    * *Enable an application to announce events to multiple interested consumers asynchronously, without coupling the senders to the receivers*
  * [Queue-based load leveling](https://docs.microsoft.com/en-us/azure/architecture/patterns/queue-based-load-leveling)
    * *Use a queue that acts as a buffer between a task and a service that it invokes in order to smooth intermittent heavy loads*
  * [Scheduler agent supervisor](https://docs.microsoft.com/en-us/azure/architecture/patterns/scheduler-agent-supervisor)
    * *Coordinate a set of actions across a distributed set of services and other remote resources*
  * [Sequential convoy](https://docs.microsoft.com/en-us/azure/architecture/patterns/sequential-convoy)
    * *Process a set of related messages in a defined order, without blocking processing of other groups of messages*
* [Performance and Scalability](https://docs.microsoft.com/en-us/azure/architecture/patterns/category/performance-scalability)
  * [Cache-aside](https://docs.microsoft.com/en-us/azure/architecture/patterns/cache-aside)
    * *Load data on demand into a cache from a data store*
  * [Choreography](https://docs.microsoft.com/en-us/azure/architecture/patterns/choreography)
    * *Have each component of the system participate in the decision-making process about the workflow of a business transaction, instead of relying on a central point of control*
  * [Command and Query responsibility segregation (CQRS)](https://docs.microsoft.com/en-us/azure/architecture/patterns/cqrs)
    * *Segregate operations that read data from operations that update data by using separate interfaces*
  * [Event sourcing](https://docs.microsoft.com/en-us/azure/architecture/patterns/event-sourcing)
    * *Use an append-only store to record the full series of events that describe actions taken on data in a domain*
  * [Deployment stamps](https://docs.microsoft.com/en-us/azure/architecture/patterns/deployment-stamp)
    * *Deploy multiple independent copies of application components, including data stores*
  * [Geodes](https://docs.microsoft.com/en-us/azure/architecture/patterns/geodes)
    * *Deploy backend services into a set of geographical nodes, each of which can service any client request in any region*
  * [Index table](https://docs.microsoft.com/en-us/azure/architecture/patterns/index-table)
    * *Create indexes over the fields in data stores that are frequently referenced by queries*
  * [Materialized view](https://docs.microsoft.com/en-us/azure/architecture/patterns/materialized-view)
    * *Generate prepopulated views over the data in one or more data stores when the data isn't ideally formatted for required query operations*
  * [Priority queue](https://docs.microsoft.com/en-us/azure/architecture/patterns/priority-queue)
    * *Prioritize requests sent to services so that requests with a higher priority are received and processed more quickly than those with a lower priority*
  * [Queue-based load leveling](https://docs.microsoft.com/en-us/azure/architecture/patterns/queue-based-load-leveling)
    * *Use a queue that acts as a buffer between a task and a service that it invokes in order to smooth intermittent heavy loads*
  * [Sharding](https://docs.microsoft.com/en-us/azure/architecture/patterns/sharding)
    * *Divide a data store into a set of horizontal partitions or shards*
  * [Static content hosting](https://docs.microsoft.com/en-us/azure/architecture/patterns/static-content-hosting)
    * *Deploy static content to a cloud-based storage service that can deliver them directly to the client*
  * [Throttling](https://docs.microsoft.com/en-us/azure/architecture/patterns/throttling)
    * *Control the consumption of resources by an instance of an application, an individual tenant, or an entire service*
* [Resiliency](https://docs.microsoft.com/en-us/azure/architecture/patterns/category/resiliency)
  * [Bulkhead](https://docs.microsoft.com/en-us/azure/architecture/patterns/bulkhead)
    * *Isolate elements of an application into pools so that if one fails, the others will continue to function*
  * [Circuit breaker](https://docs.microsoft.com/en-us/azure/architecture/patterns/circuit-breaker)
    * *Handle faults that might take a variable amount of time to fix when connecting to a remote service or resource*
  * [Compensating transatcion](https://docs.microsoft.com/en-us/azure/architecture/patterns/compensating-transaction)
    * *Undo the work performed by a series of steps, which together define an eventually consistent operation*
  * [Health endpoint monitoring](https://docs.microsoft.com/en-us/azure/architecture/patterns/health-endpoint-monitoring)
    * *Implement functional checks in an application that external tools can access through exposed endpoints at regular intervals*
  * [Leader election](https://docs.microsoft.com/en-us/azure/architecture/patterns/leader-election)
    * *Coordinate the actions performed by a collection of collaborating task instances in a distributed application by electing one instance as the leader that assumes responsibility for managing the other instances*
  * [Queue-based load leveling](https://docs.microsoft.com/en-us/azure/architecture/patterns/queue-based-load-leveling)
    * *Use a queue that acts as a buffer between a task and a service that it invokes in order to smooth intermittent heavy loads*
  * [Retry](https://docs.microsoft.com/en-us/azure/architecture/patterns/retry)
    * *Enable an application to handle anticipated, temporary failures when it tries to connect to a service or network resource by transparently retrying an operation that's previously failed*
  * [Scheduler agent supervisor](https://docs.microsoft.com/en-us/azure/architecture/patterns/scheduler-agent-supervisor)
    * *Coordinate a set of actions across a distributed set of services and other remote resources*
* [Security](https://docs.microsoft.com/en-us/azure/architecture/patterns/category/security)
  * [Federated identity](https://docs.microsoft.com/en-us/azure/architecture/patterns/federated-identity)
    * *Delegate authentication to an external identity provider.*
  * [Gatekeeper](https://docs.microsoft.com/en-us/azure/architecture/patterns/gatekeeper)
    * *Protect applications and services by using a dedicated host instance that acts as a broker between clients and the application or service, validates and sanitizes requests, and passes requests and data between them*
  * [Valet key](https://docs.microsoft.com/en-us/azure/architecture/patterns/valet-key)
    * *Use a token or key that provides clients with restricted direct access to a specific resource or service*

</details>

