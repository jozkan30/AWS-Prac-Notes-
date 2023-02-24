### Summary:

What is cloud computing: On-demand delivery of IT resources over the internet with pay as you go pricing.

What is EC2: A way to dynamically spin up and down virtual servers

### EC2 Instances:

- General Purpose: Compute, memory, and netwroking. as well as repos and web server
- Compute Optimized: Ideal for high-performance web servers, compute-intensive applications servers, and dedicated gaming servers.
- Memory Optimized: Designed to deliver fast performance for workloads that process large datasets in memory. For example, a wor load that requires a large amount of data to be preloaded before running the application
- Accelerated Computing: Loating-point number calculations, graphics processing, and data pattern matching.
- Storage: Designed for workloads that require high, sequential read and write access to large datasets on local storage. Examples of workloads suitable for storage optimized instances include distributed file systems, data warehousing applications, and high-frequency online transaction processing (OLTP) systems.

### EC2 Pricing Plans:

Types of billing plans:

- On Demand: Ideal for short term iregular workloads.
- Savings Plan: Enable you to reduce your compute costs by committing to a consistent amount of compute usage for a 1-year or 3-year term.
- Reserved Instances/ savings(contract): A billing discount applied to the use of On-Demand Instances in your account.
- Spot Instances:Ideal for workloads with flexible start and end times, or that can withstand interruptions.
- Dedicated Host:Are physical servers with Amazon EC2 instance capacity that is fully dedicated to your use.(1-3 years)

### Scalability:

To what degree will you use the EC2 instance

- Only using the resources you need at any given time. I.e a pay as you go model. W/O this scalibility, one will have ideal resoucres when not busy.

- There are two approaches to auto-scaling:

- 1.) Dynamic scaling responds to changing demand.

- 2.) Predictive scaling automatically schedules the right number of Amazon EC2 instances based on predicted demand.

### Elastic Load Balancing:

- AWS service that automatically distributes incoming application traffic across multiple resources, such as Amazon EC2 instances.
- Example: Evenly distributing customers in the coffee shop to a register. The employee telling cutomers which resgister to go to canbe thought of as the elastic load balancer.

#### Messaging and Queuing:

- Tightly coupled architecture: If one component fails; the others fail.

- To avoid this we use a microservices approach. Or a loose coupling.
