#### There is a requirement to host a set of servers in the Cloud for a short period of 3 months. Which of the following launch types for AWS EC2 instances should be chosen to be the most cost-effective?
- Spot Instances : Incorrect. Spot instances are cheap, but they are only for Applications that have flexible start and end times, Applications that are only feasible at very low compute prices, or Users with urgent computing needs for large amounts of additional capacity.

- Partial Upfront costs Reserved : Incorrect. AWS requires a minimum 1-year term on their contracts for reserved instances.

- ##### On-Demand : Since the requirement is just for 3 months, then the most cost-effective option is to use On-Demand Instances.

- No Upfront costs Reserved : Incorrect. AWS requires a minimum 1-year term, and a successful billing history is needed before you can purchase No Upfront Reserved Instances.


#### In order to predict the cost of moving resources from on-premise to the cloud, which of the following can be used?

- AWS WAF

- AWS Pricing Calculator

- AWS Inspector

- AWS Trusted Advisor

The AWS TCO calculator makes it easy to estimate your savings when comparing the cloud to an on-premises or colocation environment. Use the TCO calculator to get detailed reports and insights into the cost components that make AWS a viable alternative to lower your costs.

#### Which of the following storage mechanisms can be used to store messages effectively which can be used across distributed systems.

- Amazon EBS Snapshots

- Amazon SQS

- Amazon Glacier

- Amazon EBS Volumes

Amazon Simple Queue Service (Amazon SQS) offers a reliable, highly-scalable hosted queue for storing messages as they travel between applications or microservices. It moves data between distributed application components and helps you decouple these components.

#### Which of the following security features is associated with a Subnet in a VPC to protect against Incoming traffic requests.

- NACL

- Subnet Groups

- AWS Inspector

- Security Groups


EXPLANATION
A-network access control list (ACL)-is an optional layer of security for your VPC that acts as a firewall for controlling traffic in and out of one or more subnets. You might set up network ACLs with rules similar to your security groups in order to add an additional layer of security to your VPC.

#### What service from AWS can help manage the costs for all resources in AWS?

- AWS Consolidated Billing is for managing the billing from multiple AWS accounts.

- Payment history just allows you to view your previous payments made to AWS.

- A Cost Allocation tag is a label that you or AWS assigns to an AWS resource to help track AWS costs.

- Cost Explorer is a free tool that you can use to view your costs. You can view your costs as either a cash-based view (costs are recorded when cash is received or paid) with unblended costs or as an accrual-based view (costs are recorded when income is earned or costs are incurred). You can view data for up to the last 12 months, forecast how much you are likely to spend for the next three months, and get recommendations for what Reserved Instances to purchase.

#### Which of the following options of AWS RDS allows for AWS to failover to a secondary database in case the primary one fails?

- AWS Failover

- AWS Standby

- AWS Secondary

- AWS Multi-AZ.

Amazon RDS Multi-AZ deployments provide enhanced availability and durability for Database (DB) Instances, making them a natural fit for production database workloads. When you provision a Multi-AZ DB Instance, Amazon RDS automatically creates a primary DB Instance and synchronously replicates the data to a standby instance in a different Availability Zone (AZ). Each AZ runs on its own physically distinct, independent infrastructure, and is engineered to be highly reliable. In case of an infrastructure failure, Amazon RDS performs an automatic failover to the standby (or to a read replica in the case of Amazon Aurora), so that you can resume database operations as soon as the failover is complete.

#### What AWS service has built-in DDoS mitigation?

- CloudTrail

- EC2

- CloudFront

- CloudWatch


EXPLANATION
CloudFront also integrates with-AWS WAF, a web application firewall that helps protect web applications from common web exploits, and-AWS Shield, a managed DDoS protection service that safeguards web applications running on AWS.