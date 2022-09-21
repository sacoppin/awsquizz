

**Amazon LightSail** : Créer rapidement des applications et des sites web grâce à des ressources cloud préconfigurées et peu coûteuses

**Cost Allocation Tags**: You can tag resources. You can use AWS Cloud Explorer to view the cost of those tags.

A tag is a label that you or AWS assigns to an AWS resource. Each tag consists of a key and a value. For each resource, each tag key must be unique, and each tag key can have only one value. You can use tags to organize your resources, and cost allocation tags to track your AWS costs on a detailed level. After you activate cost allocation tags, AWS uses the cost allocation tags to organize your resource costs on your cost allocation report, to make it easier for you to categorize and track your AWS costs. AWS provides two types of cost allocation tags, an AWS generated tags and user-defined tags. AWS, or AWS Marketplace ISV defines, creates, and applies the AWS generated tags for you, and you define, create, and apply user-defined tags. You must activate both types of tags separately before they can appear in Cost Explorer or on a cost allocation report.

Dedicated EC2 Server integrated with AWS License Manager

Bring existing licenses to Dedicated Hosts

Amazon EC2 offers Dedicated Hosts, which allow you to access hardware that's fully dedicated for your use. You can use your own licensed software on dedicated infrastructure, even without Software Assurance. For more information on bringing licenses without Software Assurance or License Mobility benefits, please visit this section of the FAQ.

Amazon EC2 Dedicated Host is also integrated with AWS License Manager, a service which helps you manage your software licenses, including Windows Server and SQL Server licenses. In License Manager, you can specify your licensing terms for governing license usage, and easily track licenses for compliance and auditing. You can also specify Dedicated Host management preferences for host allocation and host capacity utilization. Once setup, AWS takes care of these administrative tasks on your behalf, so that you can seamlessly launch virtual machines (instances) on Dedicated Hosts just like you would launch an EC2 instance with AWS-provided licenses.

Eligible Products

Microsoft software covered by the Microsoft Product Terms can be deployed on AWS using Amazon EC2 Dedicated Hosts. Examples include:

Microsoft Windows Server
Microsoft SQL Server
Microsoft Remote Desktop Services (user CALs)
Microsoft Exchange Server
Microsoft SharePoint Server
Microsoft System Center
Microsoft Dynamics products

  #### CloudWatch Alarms to monitor Billing information, what two things must you do?

  Create a Billing Alarm and Enable Billing Alerts

**Amazon Quicksight** : Amazon Quicksight is a Business Intelligence (BI) tool.

Amazon Quicksight can inject data sources from various AWS storage and databases services such as S3.

Amazon QuickSight is a cloud-scale business intelligence (BI) service that you can use to deliver easy-to-understand insights to the people who you work with, wherever they are. Amazon QuickSight connects to your data in the cloud and combines data from many different sources. In a single data dashboard, QuickSight can include AWS data, third-party data, big data, spreadsheet data, SaaS data, B2B data, and more. As a fully managed cloud-based service, Amazon QuickSight provides enterprise-grade security, global availability, and built-in redundancy. It also provides the user-management tools that you need to scale from 10 users to 10,000, all with no infrastructure to deploy or manage.

QuickSight gives decision-makers the opportunity to explore and interpret information in an interactive visual environment. They have secure access to dashboards from any device on your network and from mobile devices.

**AWS Snowcone**: 	Snowcone is for 8TB or less of data.
- 8TB - AWS Snowcone.
80TB - AWS Snowball Edge Storage Optimized 42TB - AWS Snowball Edge Compute Optimized.
100PB - AWS Snowmobile.

#### Which of the following Compliance certifications attests to the security of the AWS platform regarding credit card transactions?

**PCI DSS Level 1** 


The Payment Card Industry Data Security Standard (PCI DSS) is a proprietary information security standard administered by the PCI Security Standards Council, which was founded by American Express, Discover Financial Services, JCB International, MasterCard Worldwide and Visa Inc.

**AWS WAF**: AWS Web Application Firewall monitor requests forwarded from CloudFront or ALB allowing you control access to said requests AWS WAF.

**Amazon Macie**: 	
Macie automatically and continually evaluates all of your S3 buckets and alerts you to any unencrypted buckets, publicly accessible buckets, or buckets shared with AWS accounts outside those you have defined in the AWS Organizations.

**AWS Service Catalog** : AWS Service Catalog allows organizations to create and manage catalogs of IT services that are approved for use on AWS. These IT services can include everything from virtual machine images, servers, software, and databases to complete multi-tier application architectures. AWS Service Catalog allows you to centrally manage deployed IT services and your applications, resources, and metadata.

**An Availability Zone (AZ)**	
 is not a single point of failure.

An AZ can be composed of multiple data centers at a single location (separate building per data center) Within a data center, hardware is physically isolated from each other in the case of a disaster. So, for example, if one room catches fire, the other rooms will not be affected.

**secu**
The exam guide outline lists the following benifits of AWS Cloud - Security
- Reliability
- High Availability
- Elasticity
- Agility
- Pay-as-you go pricing
- Scalability
- Global Reach
- Economy of scale

**AWS Security Hub**
	
AWS Security Hub consumes, aggregates, and analyzes security findings from various supported AWS and third-party products.

Security Hub provides controls for the following standards.

- CIS AWS Foundations
- Payment Card Industry Data Security Standard (PCI DSS)
- AWS Foundational Security Best Practices
These are basically managed AWS Config Conformance packs since the controls are just AWS Config Rules.

**Sessions Manager**
	
Sessions Manager allows you to access an EC2 instance to a Linux virtual without the need of SSH key pairs.

AWS has many ways to connect to an EC2 instance but this is the recommended method.

**Contact abuse@amazonaws.com** 
	
If you suspect that AWS resources are used for abusive purposes, contact the AWS Trust & Safety team using the Report Amazon AWS abuse form, or by contacting abuse@amazonaws.com. Provide all the necessary information, including logs in plaintext, email headers, and so on, when you submit your request.

**PowerUserAccess** 	
Provides full access to AWS services and resources, but does not allow management of Users and groups.

**AWS Direct Connect**
AWS Direct Connect is a cloud service solution that makes it easy to establish a dedicated network connection from your premises to AWS. Using AWS Direct Connect, you create a private connection between AWS and your data center, office, or colocation environment. This can increase bandwidth throughput and provide a more consistent network experience than internet-based connections.

**AWS Cost Explorer**	
AWS Cost Explorer can forecast cost and usage with granular detail. AWS Cost Explorer is useful for speculative reporting.

**CloudTrail** 	
CloudTrail logs who made what calls to services via console or through the API. CloudTrail will tell us which user account terminated the EC2 instance.

**AWS Outposts** AWS Outposts is a fully managed service that offers the same AWS infrastructure, AWS services, APIs, and tools to virtually any datacenter, co-location space, or on-premises facility for a truly consistent hybrid experience.

AWS Outposts can guarantee Data sovereignty because the data will be running physical servers within your own on-premise environment.

Another way to apply Data sovereignty is through IAM policies, AWS Organization Service Control Policies, and Permission Boundaries. But there is always a chance of misconfiguration.