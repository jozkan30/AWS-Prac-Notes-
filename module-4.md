### Summary and objectives:

- Describe the basic concepts of networking.
- Describe the difference between public and private networking resources. 
- Explain a virtual private gateway using a real life scenario. 
- Explain a virtual private network (VPN) using a real life scenario.
- Describe the benefit of AWS Direct Connect. 
- Describe the benefit of hybrid deployments. 
- Describe the layers of security used in an IT strategy.
- Describe the services customers use to interact with the AWS global network.



### What is Networking? 
- Interconnected computing devices that can exchange data and share resources with each other. These networked devices use a system of rules, called communications protocols, to transmit information over physical or wireless technologies.
- [OSI Model explanation ]('https://www.youtube.com/watch?v=dV8mjZd1OtU')

### Amazon VPC (Virtual Private Cloud)
- Enables you to provision an isolated section of the AWS Cloud. In this isolated section, you can launch resources in a virtual network that you define. 
-  Within this cloud you can orgainize your resources into *subnets*
- Subnet is a section of the VPC that can contain resourceses such as EC2 instances
- In order to allow prublic traffic to access the VPC you attach a gateway to the VPC.