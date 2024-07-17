# Cloud-Computing
Module 1 to 2 on cloud computing

Module 1:
Chapter 1:
Cloud computing ecosystems: What is the cloud?

In simple terms the cloud refers to server and storage systems which are assessible through the internet used to allow user the store data, run applications and perform computing tasks without needing to maintain physical hardware on their premises. 

3 services of cloud computing:

Infrastructure as a Service (IaaS):
Provides virtualized computing resources over the internet. Examples include Amazon Web Services (AWS), Microsoft Azure, and Google Cloud Platform (GCP).

Platform as a Service (PaaS): 
Provides a platform allowing customers to develop, run, and manage applications without dealing with the underlying infrastructure. Examples include Google App Engine and Microsoft Azure PaaS.

Software as a Service (SaaS): 
Delivers software applications over the internet, typically on a subscription basis. Examples include Google Workspace, Microsoft Office 365, and Salesforce.

Cloud benefits:
Scalability: Easily scale resources up or down based on demand.
Cost-Effectiveness: Pay only for the resources and services you use.
Accessibility: Access services and data from anywhere with an internet connection.
Reliability: Enhanced redundancy and disaster recovery capabilities.

# Ecosystem of the cloud

There are those who are the consumers of the cloud who buy and use cloud products such as Microsoft Onedrive.
There are the provider of cloud services, these cloud providers offer a variety of functions ranging from infrastructure services to applications and tools.
Designer of services are those companies who build applications and tools. Often services are intended to work within a specific cloud ecosystem or can augment a packaged cloud application.

Cloud Components and Clients
There are three main components in a cloud services solution. The first component is the client platform from which the cloud services are being accessed. The second is the data center where the cloud services are being hosted. The final component is the network connection between those two points.

![image](https://github.com/Darkinsator/Cloud-Computing/assets/112648301/814a4c04-dabc-401e-b784-34b8416c48b0)

![image](https://github.com/Darkinsator/Cloud-Computing/assets/112648301/c02c66cd-f573-4fb5-bca4-e61510a32fdb)

![image](https://github.com/Darkinsator/Cloud-Computing/assets/112648301/592ee917-ff99-4f4f-af58-b0c060d4b050)

Chapter 2:  Embracing the Business Imperative:

With the rise of commercial cloud computing vendors and services, the role of IT is changing dramatically. While the IT organization in the past had total control of computing resources, now IT is tasked with providing oversight, management, and vetting of options. IT must be able to provide the business with ways to integrate processes and data across silos. The security organization is also responsible for ensuring security and compliance. 

IT now has to provide oversight and management of both cloud and on-premises computing services. This means that IT needs to provide a transition plan for applications that no longer have the modularity to support business requirements. IT operations have to ensure that performance in a hybrid and multicloud world is consistent and predictable.

![image](https://github.com/Darkinsator/Cloud-Computing/assets/112648301/77818be8-1d13-4b67-b853-59035542fccd)
 Creating a cycle of innovation

Modern Development and Deployment Strategies
How does an established business move to an innovative cloud strategy? How do applications get developed so that they’re innovative and ready to support a multicloud environment? DevOps — a combination of modern application development and deployment techniques — is the requirement for building cloud-based innovation. With DevOps, developers employ an agile development approach that assumes an iterative development process. 

The focus of DevOps and agile development is to focus on customer needs and metrics that can predict success. How do customers use the new software? Is it intuitive? Does it encourage customers to stay on the site and purchase additional merchandise? Is the application modular and flexible enough to adopt as customers react to the environment? Is it easy to partner with businesses that offer complementary offerings? What is the performance like once the software is deployed across different cloud platforms and within an on-premises environment?

# 3.Cloud Architecture Considerations

![image](https://github.com/Darkinsator/Cloud-Computing/assets/112648301/4f317a5a-7365-4b39-bdb5-7f40f3d5458c)

Cloud consumers:  The individuals and groups within your business unit that use different types of cloud services to get a task accomplished. A cloud consumer could be a developer using computing services from a public cloud.
Direct customers:  Users who often take advantage of services that your business has created within a cloud environment. End users of your service have no idea that you are using a public or private cloud. As far as the users are concerned, they are interacting directly with your services and value.
Cloud service provider:  Commercial vendors or companies that create their own capabilities. Commercial vendors sell their services to cloud consumers. In contrast, a company might decide to become an internal cloud service provider to its own employees, partners, and customers — either as an internal service or as a profit center. These providers also create applications or services for these environments.


# Setting the Right Policies and Business Rules
Companies generally think about policy and business rules from an overall governance perspective. On the contrary, making policies and rules operational in a hybrid cloud environment means that these dictates must be integrated from an architectural perspective.

Building a policy or rule into the actual application may be straightforward in an on-premises environment. In a hybrid environment, however, you must make sure those policy requirements can be applied across components. 

For example, if a policy requires that personal data about French customers is stored in a physical server in France, this policy must be designed as a middleware service that controls the movement of data based on rules and conditions. it is not practical to try to implement each rule and policy inside each component of the hybrid environment.

The life cycle of cloud computing is different in many ways from the life cycle of a traditional computing environment. The architecture of the cloud environment is predicated on the ability to abstract the details away from users based on a services-oriented architecture. As a result of the cloud, you must think about the term life cycle in a new way. 

4. Managing a Hybrid and Multicloud Environment

Understanding the Role of Internal SLAs

When a company is a private or hybrid cloud provider to its internal consumers, the company should define SLAs for the resources and services provided. Doing so will formalize the operational requirements for those services and increase the chances that consumers will be pleased with the internal services. SLAs provide objective targets for performance and other operational characteristics, such as mean time between failures, and therefore are important for determining whether performance problems with applications are due to problems with the application or problems with the resources and services that the application uses.

In the public cloud, management of resources and services is the responsibility of the public cloud vendor or the third party who provides the software. A responsible organization should continually monitor the software operation to ensure that SLAs are being met. In the private cloud environment, it is usually the responsibility of IT operations to monitor the software for deviations from SLA commitments.

While public cloud providers have the responsibility to watch SLAs, they have many customers and may not always respond immediately. On the other hand, a company running its own private cloud has one customer (itself) and is equally responsible for ensuring that all applications, services, and resources are always working effectively. In some organizations, executives will be watching whether SLAs are being met because problems can affect the company’s bottom line.


# Managing External Services
In a hybrid cloud environment, organizations manage a variety of services, from basic data storage to custom applications in the public cloud. Successful management requires visibility and control over both external and internal resources.

DevOps and Deployment to Public Clouds
Modern cloud software development follows DevOps practices, integrating Development and Operations to enable continuous development and deployment. DevOps streamlines application management, making software more robust by involving developers in operational issues. After deployment, DevOps engineers monitor and address operational problems, quickly updating and redeploying applications as needed.

External System Monitoring
Monitoring external applications and services is crucial, as feedback from external users is less accessible compared to internal users. Providing external customers with product and operational status updates is essential due to their limited awareness and loyalty.

Application and Service Life Cycles
Public cloud applications must meet high availability standards. Continuous development and deployment aim to release new features without downtime, maintaining user access. Designing failover capabilities is critical to minimize disruptions and prevent data loss during failures, ensuring reliability and robustness.

# The Future of Multicloud Management
The hybrid cloud landscape is evolving with diverse services and deployment models, making integrated management of internal and external cloud and data center services crucial for efficient operations. Organizations often utilize multiple public cloud services alongside private and third-party services, increasing complexity as they scale.

Key questions to consider for multicloud management include:

What services are currently used and what additional ones are anticipated?
Why is each service used, and does it meet business requirements?
Do services meet the required security and governance standards?
Is data stored in the appropriate geographic location?
Is the environment's latency acceptable to all users?
A successful multicloud management strategy requires an infrastructure that seamlessly integrates all services, ensuring consistency and predictability across the entire environment, rather than treating services as isolated components.

Standards in the cloud world:

SDOS vs SSOS
Clearly setting standards can be complex and involves a number of organizations and bodies. Standards Developing Organizations (SDOs) and Standards Setting Organizations (SSOs) can be differentiated by how they create a standard. As the name implies, an SDO comes together to create and develop a standard. SSOs only set a standard. An SSO relies on an external body to develop the technical specifications and then subsequently adopts those specifications as a standard. Although SSOs may sound less influential, they can be quite successful at setting standards. The World Wide Web Consortium (W3C), for example, has had a long history of developing important standards for the web. These include HTML, CSS, and XML, which have received broad worldwide adoption. For a standard to truly succeed, it needs to be:

Broadly recognized and adopted by vendors,
Broadly adopted and demanded by consumers,
Open source.
If these criteria are not met, a “standard” is far from standard and is instead just a document. Regardless, establishing cloud standards is important because standards help improve choice, reduce cost, and improve quality. While standards are being developed in many specific areas, areas, where standards are being broadly developed, include the following:

Interoperability
Portability
Security

Interoperability is the ability for independent systems to work together and/or share information. One of the most important aspects of interoperability is the ability to enable applications to exchange data in a multicloud or on-premises data centre. It also includes independent cloud deployments working together, such as public clouds from different vendors or interoperability between a private cloud and an external public cloud. 

Portability
Portability enables you to take applications, data, or instances running on one vendor’s system and deploy it on another vendor’s implementation. For example, you may want to move your data or application from one cloud environment to another.

The Impact of Standards on the Multicloud
   
Standards let you do the following:


1. Move your infrastructure or applications from one cloud provider to another. With cloud standards across clouds, you do not have to rewrite code. In a multicloud world, where you may have part of the resources associated with an application on your own premises and part with a cloud provider, this capability is important because it enables your organization to be more flexible about where your resources may be located.

2. Prevent vendor lock-in. Lock-in occurs when you are so entrenched with a particular provider and its interfaces that moving to another provider is too costly. Removing barriers to lock-in increases your choices.

3. Integrate applications more easily between your on-premises data center and private and public cloud environments. Face it; integrating your assets across multiple environments can be time-consuming and costly if every cloud provider has a proprietary model. Standards help to make integration easier and eliminate many common barriers.


# Module 2: What is azure?

![image](https://github.com/Darkinsator/Cloud-Computing/assets/112648301/ba405ef4-9244-4fca-9b99-5ae3fdcd00d3)

# Features of azure
![image](https://github.com/Darkinsator/Cloud-Computing/assets/112648301/3b6bdc3d-d94d-4b3b-8dd5-ff94ba4a2fbd)

# Azure Services

![image](https://github.com/Darkinsator/Cloud-Computing/assets/112648301/e02f279f-b949-4e59-b15c-176e5f06e5e7)

# Core Architecture and Resource Management Concepts:

![image](https://github.com/Darkinsator/Cloud-Computing/assets/112648301/ed72d448-0247-4bdf-bebb-6b340d866603)

# Azure Role-Based Access Control (Azure RBAC)

It is important for any organization to be able to manage the user access for cloud resources and resource groups in Microsoft Azure. The Azure Role-based Access Control (RBAC) helps in user access management of resources in Azure. RBAC helps in controlling what users can do.

Azure RBAC is a system for authorization and access management of resources within the Azure platform. You can filter what a certain group of users can do and cannot do depending on the type of role they have in the organization.

Describe Azure Architecture and Services:

Describe the core architectural components of Azure
Describe Azure compute and networking services
Describe Azure Storage services
Describe Azure identity, access, and security

Azure Organization:

Geographies & Regions: Organized by geographic areas, each with multiple regions. Regions have pairs for high availability.
Sovereign Regions: Cater to specific government and country requirements.
Availability Zones: Ensure high availability within a region, with each enabled region having at least three zones.
Data Centers: Physical buildings with their own power, water, cooling, and network systems.
Resource Management:

Resource Groups: Logical entities for organizing Azure resources.
Azure Subscriptions: Provide access to create and manage resources.
Management Groups: Logical entities for managing multiple subscriptions.
Compute Services:

Azure Container Instances (ACI): Serverless option for running containerized workloads.
Azure Functions: Hosting microservices in the cloud.
Virtual Machines (VMs): Easily create VMs with various operating systems.
Availability Sets & VM Scale Sets: Ensure high availability and scalability of VMs.
Azure Virtual Desktop (AVD): Desktop virtualization service.
App Hosting:

Azure App Service: PaaS for hosting web apps.
Azure Kubernetes Service (AKS): PaaS for Kubernetes clusters.
Azure Spring Cloud: Hosting Spring apps.
Networking:

Virtual Networks (VNets): Create network environments in the cloud.
VNet Peering: Connect VNets, including global peering.
Azure DNS: Manage DNS records.
Azure VPN Gateway & ExpressRoute: Securely connect VNets to other networks.
Storage Services:

Azure Blob Storage: Store binary files in Blobs.
Azure Disks: Storage for VM disks.
Azure Files: Cloud-based SMB file shares.
Storage Tiers & Redundancy: Hot, Cool, and Archive tiers; LRS, ZRS, GRS, GZRS for redundancy.
Data Migration:

Azure Migrate: Discover, assess, and migrate workloads.
Azure Data Box: Offline data migration.
Identity & Security:

Azure Active Directory (AD): Cloud-based identity service.
Azure AD Domain Services: Connect on-premises domains to Azure AD.
Single Sign-On (SSO) & Multifactor Authentication (MFA): Enhance security and ease of access.
Passwordless Authentication & Guest Users: Alternative authentication methods and collaboration.
Conditional Access & Role-Based Access Control (RBAC): Define access policies and roles.
Defense in Depth & Zero-Trust: Multiple security layers and end-to-end security frameworks.
Microsoft Defender for Cloud: Manage security and compliance across resources.



   
  






































