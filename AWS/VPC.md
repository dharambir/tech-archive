---

## VPC (Virtual Private Cloud)
A logically isolated private network in AWS where resources are launched and networking/security is controlled.

**Interview one-liner:**  
“VPC is a private isolated network in AWS where we deploy resources and control networking, security, and communication.”

## Subnet
A smaller network inside a VPC used to organize and isolate resources.

- Public subnet → internet accessible
- Private subnet → no direct internet access

**Interview one-liner:**  
“A subnet is a segmented network inside a VPC used to isolate resources.”

## Route Table
Contains rules that decide where network traffic should go.

**Interview one-liner:**  
“A route table defines routing rules that determine how traffic moves between subnets, the internet, and AWS services.”

## Internet Gateway (IGW)
Allows resources in a public subnet to communicate with the internet.

**Interview one-liner:**  
“Internet Gateway enables inbound and outbound internet access for resources inside a public subnet.”

## NAT Gateway
Allows private subnet resources to access the internet outbound only.

**Interview one-liner:**  
“NAT Gateway provides secure outbound internet access for private subnet resources without exposing them to incoming internet traffic.”

## VPC Endpoint
Enables private communication between VPC and AWS services without public internet.

**Interview one-liner:**  
“VPC Endpoint enables private access to AWS services from a VPC without using the internet.”

---
