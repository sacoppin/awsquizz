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
CloudFront also integrates with-AWS WAF, a web application firewall that helps protect web applications from common web exploits, and-AWS Shield, a managed DDoS protection service that safeguards web applications running on AW



#### A company wants to run a development environment for their web application which is backed by the relational database Postgres.
#### Which AWS service would best meet their requirements?

- Amazon Aurora

You can use Amazon Aurora but it's expensive and intended for production workloads.

- AWS Postgres
There is no such service name AWS Postgres


- DynamoDB is a NoSQL database

- Amazon Relational Database Service (RDS) supports Postgres engines and is suited for both development and production workloads.

It works well for development workloads since you can choose a free-tier instance type and choose to opt-out of costly features like Multi-AZ

#### An AWS Availability Zone (AZ) is a single point of failure. To avoid a single point of failure, a company needs to deploy its workload across multiple AZs in the same AWS Region.

TRUE

FALSE

An Availability Zone (AZ) is not a single point of failure.

An AZ can be composed of multiple data centers at a single location (separate building per data center) Within a data center, hardware is physically isolated from each other in the case of a disaster. So, for example, if one room catches fire, the other rooms will not be affected.

#### In order to use CloudWatch Alarms to monitor Billing information, what two things must you do?

* *Create a Billing Alarm*

- Create an AWS Budget.
AWS Budget likely uses Billing Alarms underneath but they are managed by AWS. The question is about using a Billing Alarm directly.

- Enable Cost and Usage Reports.
Cost and Usage Reports does not relate to Billing Alarms

* *Enable Billing Alerts*.

(Before you can create an alarm for your estimated charges, you must enable billing alerts, so that you can monitor your estimated AWS charges and create an alarm using billing metric data. After you enable billing alerts, you can't disable data collection, but you can delete any billing alarms that you created.

After you enable billing alerts for the first time, it takes about 15 minutes before you can view billing data and set billing alarms.)

- Create an AWS Cost and Usage Report

(Cost and Usage Reports does not relate to Billing Alarms)

You can monitor your estimated AWS charges by using Amazon CloudWatch. When you enable the monitoring of estimated charges for your AWS account, the estimated charges are calculated and sent several times daily to CloudWatch as metric data.

Billing metric data is stored in the US East (N. Virginia) Region and represents worldwide charges. This data includes the estimated charges for every service in AWS that you use, in addition to the estimated overall total of your AWS charges.

The alarm triggers when your account billing exceeds the threshold you specify. It triggers only when actual billing exceeds the threshold. It doesn't use projections based on your usage so far in the month.

If you create a billing alarm at a time when your charges have already exceeded the threshold, the alarm goes to the ALARM state immediately.

#### An organization wants to download a compliance report to attest that AWS meets regulatory compliance before they decide to adopt AWS as their primary cloud service provider.
#### Which AWS service will meet this requirement?

- Amazon Regulatory Reporter

(There is no such service)

* *AWS Artifact*

(AWS Artifact is your go-to, central resource for compliance-related information that matters to you. It provides on-demand access to AWS’ security and compliance reports and select online agreements. Reports available in AWS Artifact include our Service Organization Control (SOC) reports, Payment Card Industry (PCI) reports, and certifications from accreditation bodies across geographies and compliance verticals that validate the implementation and operating effectiveness of AWS security controls. Agreements available in AWS Artifact include the Business Associate Addendum (BAA) and the Nondisclosure Agreement (NDA).)

https://aws.amazon.com/artifact/

- Amazon Inspector

(Amazon Inspector is an automated security assessment service that helps improve the security and compliance of applications deployed on AWS. Amazon Inspector automatically assesses applications for exposure, vulnerabilities, and deviations from best practices. After performing an assessment, Amazon Inspector produces a detailed list of security findings prioritized by level of severity. These findings can be reviewed directly or as part of detailed assessment reports which are available via the Amazon Inspector console or API.)

https://aws.amazon.com/inspector/

- AWS Customer Compliance Center

#### Which AWS Managed Job Function provides full access to AWS services and resources, but does not allow management of Users and groups?

- SystemAdministrator

(Grants full access permissions necessary for resources required for application and development operations.)

-  ViewOnlyAccess

(This policy grants permission to view resources and basic metadata across all AWS services)

- AdministratorAccess

(SELECTED
Provides full access to AWS services and resources.)

  *PowerUserAccess*

Provides full access to AWS services and resources, but does not allow management of Users and groups.


- AdministratorAccess - Provides full access to AWS services and resources.
- Billing - Grants permissions for billing and cost management. This includes viewing account usage and viewing and modifying budgets and payment methods.
- DatabaseAdministrator - Grants full access permissions to AWS services and actions required to set up and configure AWS database services.
- DataScientist - Grants permissions to AWS data analytics services
- NetworkAdministrator - Grants full access permissions to AWS services and actions required to set up and configure AWS network resources
- PowerUserAccess - Provides full access to AWS services and resources, but does not allow management of Users and groups.
- SecurityAudit - The security audit template grants access to read security configuration metadata. It is useful for software that audits the configuration of an AWS account.
- SupportUser - This policy grants permissions to troubleshoot and resolve issues in an AWS account. This policy also enables the user to contact AWS support to create and manage cases
- SystemAdministrator - Grants full access permissions necessary for resources required for application and development operations.
- ViewOnlyAccess - This policy grants permissions to view resources and basic metadata across all AWS services


#### Which AWS Service can be used to purchase and manage their domain name records?

- AWS DNS

(SELECTED
DNS stands from Domain Name Service. AWS does not have a service by this name.)

- You cannot purchase domain names on AWS. Use a third-party service like GoDaddy Let AWS manage the domain

(This is not true, AWS Route53 can be used to purchase domain names.)

  *Amazon Route53*

(Amazon Route 53 is a highly available and scalable Domain Name System (DNS) web service. You can use Route 53 to perform three main functions in any combination: domain registration, DNS routing, and health checking.)

https://docs.aws.amazon.com/Route53/latest/DeveloperGuide/Welcome.html

- Amazon CloudFront

(CloudFront is Content Distribution Network (CDN) Its not used for purchasing or managing domain names.) 

#### A small business wants to deploy a Wordpress website with a custom domain on AWS but they have minimal knowledge of AWS.
#### Which AWS service offering would be the easiest solution for this customer?

- AWS Elastic Beanstalk

SELECTED
(You can deploy a wordpress on Elastic Beanstalk but requires developer knowledge to do so.)

- AWS CodeStar

(You can launch WordPress from CodeStar. It's not as easy as LightSail and does not handle domain registry as well. This sill requires developer knowledge. AWS CodeStar generally launches AWS Elastic Beanstalk environments.)

  *Amazon LightSail*

(Lighsail an easy-to-use UI to launch common workloads that you might found on providers like Godaddy or HostGator. You can easily launch WordPress, Joomla, Magento and more... You can also register a custom domain through LightSail

LightSail is just using EC2, Route53 and other AWS services underneath. These service resources will be managed by AWS eg. You will not see the EC2 in your EC2 console, only in LightSail.

Lightsail is an easy-to-use virtual private server (VPS) provider that offers you everything needed to build an application or website for a cost-effective, monthly plan. Whether you’re new to the cloud or looking to get on the cloud quickly with AWS infrastructure you trust, we’ve got you covered.)

https://aws.amazon.com/lightsail/

- AWS Amplify

(AWS Amplify is an opinionated serverless framework and hosting platform for AWS. It requires developer knowledge and can't be used to deploy a WordPress which is incompatible.)

#### A company needs to run batch jobs a few times throughout the year.

#### These jobs can be interrupted and resumed with no impact on the business.

##### Which instance EC2 Pricing Model is the most cost-effective option?

- Dedicated Hosts

- Reserved

  *Spot*

(Spot Instances is Ec2 compute that you can bid to use at a discount. Spot instances can be interrupted at any time for priority customers.

If you can handle an interruption to your service, or can carry on computational workload from where you last left off or from the start than Spot is ideal.)

https://aws.amazon.com/ec2/spot/?cards.sort-by=item.additionalFields.startDateTime&cards.sort-order=asc https://aws.amazon.com/ec2/faqs/#Spot_instances

- On-Demand

#### An organization wants to ensure the files that it stores in S3 are secure at rest.

#### What functionality would provide this security?

*Server-Side Encryption*

(Server-side encryption protects data at rest. Amazon S3 encrypts each object with a unique key. As an additional safeguard, it encrypts the key itself with a key that it rotates regularly. Amazon S3 server-side encryption uses one of the strongest block ciphers available to encrypt your data, 256-bit Advanced Encryption Standard (AES-256).)

https://docs.aws.amazon.com/AmazonS3/latest/userguide/UsingServerSideEncryption.html

- Client-Side Encryption


(Client-Side Encryption is the action of encrypting data before sending it to S3. This is for encryption in transit.)

https://docs.aws.amazon.com/AmazonS3/latest/userguide/UsingClientSideEncryption.html

- Presigned URLs

(Presigned URLs allow you to generate temporary URLs to access private files.)

https://docs.aws.amazon.com/AmazonS3/latest/userguide/ShareObjectPreSignedURL.html

- Infrequent Access

(S3 Infrequent Access is an access tier that can reduce the cost of storage but is not applicable to security.)

https://aws.amazon.com/s3/storage-classes/


#### Which AWS security services allow you to apply a set of security controls?

AWS Security Hub.

#### Which AWS service is used to calculate the Total Cost of Ownership?

AWS Pricing Calculator

#### A developer wants to gain remote access to an EC2 Instance running Linux without the need of managing a key pair.
#### What EC2 feature will meet this requirement?
Sessions Manager

#### An AWS customer believes that one of their accounts has been comprised and it has resources running compute workloads performing illegal activities.

#### What action should the AWS customer take?
	
Contact abuse@amazonaws.com

#### Which AWS Managed Job Function provides full access to AWS services and resources, but does not allow management of Users and groups?

	
PowerUserAccess

#### A company needs a dedicated connection from their on-premise data center to their AWS Cloud VPC.

#### Which AWS service will meet this requirement?

AWS Direct Connect

#### Which AWS billing services are capable of forecasting cost and usage?
AWS Cost Explorer

#### A company has an EC2 instance running and suddenly the server was terminated. It's suspected that a junior developer may have terminated this instance by mistake.

#### Which AWS service will help determining who was responsible?
CloudTrail

#### What actions within an AWS Account can only be performed by an AWS Account root user?

Create an Account
Updating Billing Information

#### What are three key factors from the twelve-factor app pattern methodology that play a role in designing for failure?


Logs, Disposability, Dev/prod parity

#### Which of the following are examples of Capital Expenses (CAPEX)?

- Network Costs -


- Datacenter Costs -

- IT Personnel. 


#### A Canadian company needs to meet regulatory compliance where the data must reside within Canada. Their CIO has experience with maintaining and trusting on-premise infrastructure because it provides a guarantee of Data sovereignty. However, they would like to use an AWS service to take care of this for them.

#### Which AWS service provides a guarantee of Data sovereignty?

AWS Outposts



