`2021-05-10`

# `Module 1 - General Knowledge`

- Use sandbox and follow tutorials on aws.amazon.com
- Cloud computing is the on-demand delivery of compute power, database, storage, applications, and other IT resources via the internet with pay-as-you-go pricing.

- Cloud computing enables you to stop thinking of your infrastructure as hardware, and instead think of (and use) it as software.

- On Prem = On Premises

---

## Hardware Solutions:

- Require space, staff, physical security, planning, capital expenditure
- Have a long hardware procurement cycle
- Require you to provision capacity by guessing theoretical maximum peaks

- It can take 6 months to a year to get a new server up and running

---

## Software Solution:

- Are flexible
- Can change more quickly, easily, and cost-effectively than hardware solution
- Eliminate the undifferentiated heavy-lifting tasks

- IaaS (infrastructure as a service) MORE CONTROL / USED BY AWS
- PaaS (platform as a service) MEDIUM CONTROL
- SaaS (software as a service) running a service from the cloud, don't need to download an app. Think getting email from GMAIL. LESS CONTROL

---

## Cloud Deployment Models

- Cloud / all on the cloud
- Hybrid / little bit of both
- on-premises / run own personal cloud on premisis
- less expensive to use SaaS but you have no control over anything

---

## Advantages of Cloud Computing

- Data center investment based on forecast
- Pay only for the amount you consume
- Pay for what you use at the end of each month
- Don't have to guess what capacitys you need server wise when you use AWS
- If you overestimate you waste money and if you underestimate you are spending more than you need to
- Can spin up a new server on AWS if website is getting too much traffic and overloading

---

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

---

## Pricing:

- Pay for what you use
- Pay less when you reserve
- Pay less when you use more
- Pay even less as AWS grows

### Reserve:

Instances, you can save up to 75 percent over equivalent on-demand capacity. Reserved Instances are available in three options:

1. **AURI:** All Upfront Reserved Instance
2. **PURI:** Partial Upfront Reserved Instance
3. **NURI:** Upfront Payments Reserved Instance

### Custom Pricing:

- Custom pricing is available for high-volume projects with unique requirements.

### Total Cost of OwnerShip (TCO):

- the financial estimate to help identify direct and indirect costs of a system.

---

## Services With No Charge:

- **Amazon Virtual Private Cloud (Amazon VPC):** _Enables you to provision a logically isolated section of the AWS Cloud where you can launch AWS in a virtual network that you define._

- **AWS Identity and Access Management (IAM):** _Controls your users’ access to AWS services and resources._

- **AWS Pricing Calculator:** _Use to see how much money you can save._

- **Consolidated Billing:** _Is a billing feature in AWS Organizations to consolidate payment for multiple AWS accounts or multiple Amazon Internet Services Private Limited (AISPL) accounts. Consolidated billing provides:•One bill for multiple accounts.•The ability to easily track each account’s charges.•The opportunity to decrease charges as a result of volume pricing discounts from combined usage.•And you can consolidate all of your accounts using Consolidated Billing and get tiered benefits._

- **AWS Elastic Beanstalk:** _An even easier way for you to quickly deploy and manage applications in the AWS Cloud._

- **AWS CloudFormation:** _Gives developers and systems administrators an easy way to create a collection of related AWS resources and provision them in an orderly and predictable fashion._

- **Automatic Scaling:** _Automatically adds or removes resources according to conditions you define. The resources you are using increase seamlessly during demand spikes to maintain performance and decrease automatically during demand lulls to minimize costs._

- **AWS OpsWorks:** _An application management service that makes it easy to deploy and operate applications of all shapes and sizes._

---

## Key Notes:

- Pay for what you use
- Start and stop anytime
- No long-term contracts are required
- Some services are free, but the other AWS services that they provision might not be free

## No charge for:

1. Inbound data transfer
2. Data transfer between services within the same AWS Region

---

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

---

## Additional Benefits:

### Hard benefits:

- Reduced spending on compute, storage, networking, security
- Reductions in hardware and software purchases (capex)
- Reductions in operational costs, backup, & disaster recovery

### Soft benefits:

- Reuse of service and applications that enable you to define (and redefine solutions) by using the same cloud service
- Increased developer productivity
- Improved customer satisfaction
- Agile business processes that can quickly respond to new and emerging opportunities
- Increase in global reach

---

## Technical Support:

- Available 24/7

### AWS Support:

- Provided for:
- Experimenting with AWS
- Production use of AWS
- Business-critical use of AWS

### Proactive guidance:

- Technical Account Manager (TAM)

## `Module 3`

- An AWS Region is a geographical area.

  - Data replication: across Regions is controlled by you.
  - Communication between Regions uses AWS backbone network infrastructure.

- Each Region provides full redundancy and connectivity to the network.

- A Region typically consists of two or more Availability Zones.

---

## Availability Zones:

- Each Region has multiple availability zones.
- Each availability zone is a fully isolated partition of the AWS infrastructure.
- There are currently 69 availability zones worldwide.
- Availability zones consist of discrete data centers.
- They are designed for fault isolation.
- They are interconnected with other availability zones by using high-speed private networking.
- You choose you availability zones.
- AWS recommends replicating data and resources across Availability zones for resiliency.

---

## Data Centers:

- Each data center has redundant power, networking, and connectivity, and is housed in a separate facility.
- Typically has 50,000 to 80,000 physical servers.

---

## AWS infrastructure features:

- Elasticity and scalability:
  - Elastic infrastructure; dynamic adaption of capacity(can shrink and grow)
  - Scalable infrastructure; adapts to accommodate growth(only grows)
- Fault tolerance:
  - Continues operating properly in the presence of a failure
  - Built-in redundancy of components
- High availability:
  - High level of operational performance
  - Minimized downtime
  - No human intervention

---

# Section 2:

## Foundational Services:

- Domains are global
- Billing is global

---

# Module 4

## Security:

- AWS is responsible for the software and hardware on the cloud.
- The customer is responsible for platform, apps, identity & access management.
- Once you create an instance it is your responsibility.
- If something is wrong with the instance itself, it is AWS responsibility.
- AWS and the customer share security responsibilities
  – AWS is responsible for security of the cloud
  - Customer is responsible for security in the cloud

## Customer Responsibility:

- Amazon Elastic Compute Cloud (Amazon EC2) instance operating system (including patching, maintenance)
- Applications:
  - Passwords, role-based access, etc.
- Security group configuration:
  - OS or host-based firewalls
- including intrusion detection or prevention systems
- Account management

---

## Service Characteristics:

- Infrastructure as a service (IaaS):

  - Customer has more flexibility over configuring networking and storage settings.
  - Customer is responsible for managing more aspects of the security.
  - Customer configures the access controls.

- Platform as a service (PaaS):

  - Customer does not need to manage the underlying infrastructure.
  - AWS handles the operating system, database patching, firewall configuration, and disaster recovery.

- Software as a service (SaaS):
  - Software is centrally hosted.
  - Licensed on a subscription model or pay-as-you-go basis.
  - Services are typically accessed viw web browser, mobile app, or application programming interface (API).
  - Customers do not need to manage the infrastructure that supports the service.

---

# `Section 2`

## **IAM**:

- Identity and access management

- Use IAM to manage access to AWS resources:

- A resource is an entity in an AWS account that you can work with.

- Example resource; An Amazon EC2 instance or an Amazon s3 bucket.

- Use to manage access to AWS resources such as s3 bucket.

- Example

  - Control who can terminate Amazon EC2 instances.

- Can be used to handle authentication, and to specify and enforce authorization policies so that you can specify which users can access which services.

- A tool that centrally manages access to launching, configuring, managing, and terminating resources in your AWS account.

- Manage who has access to what resources.

---
