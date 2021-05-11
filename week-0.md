`2021-05-10`

# `Module 1 - General Knowledge`

- Use sandbox and follow tutorials on aws.amazon.com
- Cloud computing is the on-demand delivery of compute power, database, storage, applications, and other IT resources via the internet with pay-as-you-go pricing.

- Cloud computing enables you to stop thinking of your infrastructure as hardware, and instead think of (and use) it as software.

- On Prem = On Premises

## Hardware Solutions:

- Require space, staff, physical security, planning, capital expenditure
- Have a long hardware procurement cycle
- Require you to provision capacity by guessing theoretical maximum peaks

- It can take 6 months to a year to get a new server up and running

## Infrastructure as software

## Software Solution:

- Are flexible
- Can change more quickly, easily, and cost-effectively than hardware solution
- Eliminate the undifferentiated heavy-lifting tasks

- IaaS (infrastructure as a service) MORE CONTROL / USED BY AWS
- PaaS (platform as a service) MEDIUM CONTROL
- SaaS (software as a service) running a service from the cloud, don't need to download an app. Think getting email from GMAIL. LESS CONTROL

## Cloud Deployment Models

- Cloud / all on the cloud
- Hybrid / little bit of both
- on-premises / run own personal cloud on premisis
- less expensive to use SaaS but you have no control over anything

## Advantages of Cloud Computing

- Data center investment based on forecast
- Pay only for the amount you consume
- Pay for what you use at the end of each month
- Don't have to guess what capacitys you need server wise when you use AWS
- If you overestimate you waste money and if you underestimate you are spending more than you need to
- Can spin up a new server on AWS if website is getting too much traffic and overloading

## Intro to AWS

- A web service is any piece of software that makes itself available over the internet and uses a standardized format -such as Extensible Markup Language (XML) or JavaScript Object Notation (JSON) for the request and the response of an application programming interface (API) interaction.

- AWS is a secure cloud platform that offers a broad set of global cloud-based products
- AWS provides you with on-demand access to compute, storage, network, database, and other IT resources and management tools
- You pay only for the individual services you need
- Going to be using networking, compute, database, & storage
- ECC: Error Correction Control
- IAM: Identity Access Management

## Three ways to interact with AWS

- AWS Management Console
- Command Line Interface(AWS CLI)
- Software Development Kits (SDK)

## AWS Cloud Adoption Framework (AWS CAF)

- Provides guidance and best practices to help organizations build a comprehensive approach to cloud computing across the organization and throughout the IT lifecycle to accelerate successful cloud adoption

# `Module 2 - Pricing`

## AWS Pricing Model:

- Three fundamental drivers of cost with AWS

### Compute:

- Charged per hour/second
- Varies by instance type
- Linux only

### Storage:

- Charged typically per GB

### Data transfer:

- Outbound is aggregated and charged
- Inbound has no charge (with some exceptions)
- Charged typically per GB

### Pricing:

- Pay for what you use
- Pay less when you reserve
- Pay less when you use more
- Pay even less as AWS grows

## Reserve:

Instances, you can save up to 75 percent over equivalent on-demand capacity. Reserved Instances are available in three options:

1. **AURI:** All Upfront Reserved Instance
2. **PURI:** Partial Upfront Reserved Instance
3. **URI:** Upfront Payments Reserved Instance

## Custom Pricing:

- Custom pricing is available for high-volume projects with unique requirements.

## Services With No Charge:

- **Amazon Virtual Private Cloud (Amazon VPC):** _Enables you to provision a logically isolated section of the AWS Cloud where you can launch AWS in a virtual network that you define_

- **AWS Identity and Access Management (IAM):** _Controls your users’ access to AWS services and resources_

- **Consolidated Billing:** _Is a billing feature in AWS Organizations to consolidate payment for multiple AWS accounts or multiple Amazon Internet Services Private Limited (AISPL) accounts. Consolidated billing provides:•One bill for multiple accounts.•The ability to easily track each account’s charges.•The opportunity to decrease charges as a result of volume pricing discounts from combined usage.•And you can consolidate all of your accounts using Consolidated Billing and get tiered benefits._

- **AWS Elastic Beanstalk:** _An even easier way for you to quickly deploy and manage applications in the AWS Cloud._

- **AWS CloudFormation:** _Gives developers and systems administrators an easy way to create a collection of related AWS resources and provision them in an orderly and predictable fashion._

- **Automatic Scaling:** _Automatically adds or removes resources according to conditions you define. The resources you are using increase seamlessly during demand spikes to maintain performance and decrease automatically during demand lulls to minimize costs._

- **AWS OpsWorks:** _An application management service that makes it easy to deploy and operate applications of all shapes and sizes._

## Key Notes:

- Pay for what you use
- Start and stop anytime
- No long-term contracts are required
- Some services are free, but the other AWS services that they provision might not be free

## No charge for:

1. Inbound data transfer
2. Data transfer between services within the same AWS Region

## On-Premises:

- On-premises infrastructure is installed locally on a company's own computers and servers
- Fixed-Costs are known as Capital Expenses
- Scaling down on-premises does not reduce any costs
- Involves a discussion that is based on capital expenditure, long planning cycles, and multiple components to buy, build, manage, and refresh resources over time

## Cloud:

- A cloud infrastructure is purchased from a service provider who builds and maintains the facilities, hardware, and maintenance staff
- Customer pays for what is used
- Scaling up or down is simple
- AWS Cloud involves a discussion about flexibility, agility, and consumption-based costs
-
