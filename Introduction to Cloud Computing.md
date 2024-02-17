---
title: Introduction to Cloud Computing
updated: 2024-02-16 10:44:06Z
created: 2024-02-04 08:08:50Z
latitude: 35.70902590
longitude: 139.73199250
altitude: 0.0000
---

# Module 2

In Module 2, you will learn about the different types of service and deployment models of cloud computing. The first lesson covers the three main service models available on the cloud—

- Infrastructure-as-a-Service (IaaS),
- Platform-as-a-Service (PaaS),...
- Software-as-a-Service (SaaS).

You will learn  
the differences between each model,  
the advantages of each,  
and the key components of cloud infrastructure.

The second lesson goes over the four main deployment models available on the cloud—

- public,
- private,
- hybrid,
- and community.

You will learn what deployment models are and the differences and advantages of each model. At the end of the module, you will create an account on IBM Cloud.😊

**Learning Objectives**  
Describe the essential characteristics, use cases, and benefits of the different types of cloud service and deployment models and their use cases

1.  List the three main service models available on the cloud
2.  Define IaaS and discuss its components and use cases
3.  Define PaaS and discuss its characteristics, use cases, and benefits
4.  Distinguish SaaS from IaaS and PaaS and describe its features and use cases
5.  List the four main deployment models available on the cloud
6.  Define the public cloud model and its components and use cases
7.  Define the private cloud model and its characteristics
8.  Define the hybrid cloud model and its similarities and differences from Public and Private
9.  Define the community cloud model and its components

![OIP (2).jpeg](../_resources/OIP%20%282%29.jpeg)

With IaaS, the cloud provider manages

- the physical resources,
    
- data centers,
    
- cooling,
    
- power,
    
- network
    
- and security,
    
- as well as computing resources that include
    
- - servers
- - and storage.

With PaaS the provider, in addition to the computing resources, also manages the platform infrastructure which includes

1.  the operating systems,
2.  development tools,
3.  databases,
4.  and business analytics.

In the SaaS model, in addition to the infrastructure and the platform resources, the provider also hosts and manages the applications and data. In the next video.

![iaas.png](../_resources/iaas.png)  
Cloud providers often provide customers the ability to track and monitor the performance and usage of their cloud services and manage disaster recovery.

## **key components of cloud infrastructure:**

**Physical data centers**: IaaS providers manage large data centers that contain the physical machines required to power the various layers of abstraction on top of them.  
*In most IaaS models, end users do not interact directly with the physical infrastructure but experience it as a service provided to them.*

**Compute**: IaaS providers manage the hypervisors and end-users programmatically provision virtual instances with desired amounts of compute, memory, and storage resources.  
*Cloud compute typically comes with supporting services like auto scaling and load balancing that provide scalability and high performance.*

**Network**: Users get access to networking resources on the cloud through virtualization or programmatically, through APIs.

**Storage**: There are three types of cloud data storage: object, file, and block storage.

*Object storage* is the most common mode of storage in the cloud, given that it is highly distributed and resilient.

## IaaS supports a wide array of use cases.

We’ll look at some typical use cases here

1.  Organizations today are using cloud infrastructure services to enable their teams to set up test and development environments faster, helping create new applications more quickly. By **abstracting the low-level components**, cloud infrastructure is helping developers focus more on business logic than infrastructure management.
2.  **Business continuity** and disaster recovery require a significant amount of technology and staff investments. IaaS is helping organizations reduce this cost and make applications and data accessible as usual during a disaster or outage.
3.  Organizations are using cloud infrastructure to **deploy their web applications faster** and also scale infrastructure up and down as demand fluctuates.
4.  Organizations are leveraging the high-performance computing capabilities of cloud infrastructure to **solve complex problems** involving millions of variables and calculations such as climate and weather predictions and financial modeling.
5.  **Mining massive data sets** to locate valuable patterns, trends, and associations requires a huge amount of processing power. Cloud infrastructure not only provides the required high-performance computing but also makes it economically viable.

While there are some concerns regarding the lack of transparency in the cloud infrastructure’s configuration and management and dependency on a third-party for workload availability and performance, Infrastructure-as-a-Service is the fastest growing cloud model today.

![paas7.png](../_resources/paas7.png)  
is a cloud computing model that provides customers a complete platform to

- develop,
- deploy,
- manage
- and run applications

<span style="color: red;">created by them or acquired from a third party</span>

The PaaS provider hosts everything:

- servers,
- networks,
- storage,
- operating system,
- application runtimes,
- APIs,
- middleware,
- databases
- and other tools at their data center.

The provider also takes responsibility for the

- installation,
- configuration,
- and operation of the application infrastructure,

leaving the user responsible for only the application code and its maintenance. Customers pay for this service on a usage basis and purchase resources on demand.

With IaaS, the cloud provider offers access to raw computing resources such as servers, storage, and networking, while the user is responsible for the platform and application software.

With P-a-a-S or PaaS, the cloud service provider delivers and manages the entire platform infrastructure, abstracting users from the lower level details of the environment.

![paas34.png](../_resources/paas34.png)

- PaaS clouds are distinguished by the high level of abstraction they provide to the users, eliminating the complexity of deploying applications, configuring infrastructure, and provisioning and configuring supporting technologies like load balancers and databases.
- PaaS clouds provide services and APIs that help simplify the job of developers in delivering elastically scalable and highly available cloud applications. These services typically include a variety of capabilities such as APIs for distributing, caching, queuing and messaging, file and data storage, workload management, user identity, and analytics, thus eliminating the need to integrate disparate components.
- The PaaS runtime environment executes end user code according to policies set by the application owner and cloud provider
- Many of the PaaS offerings provide developers with rapid deployment mechanisms or push and run mechanism for deploying and running applications
- PaaS offerings support a range of application infrastructure or middleware capabilities such as application servers, database management systems, business analytics servers, mobile backend services, integration services, business process management systems, rules engines, and complex event processing systems. Such an application infrastructure assists developers by reducing the amount of code that must be written while expanding the application's functional capabilities

<span style="color: red;">The most important use case for PaaS is strategic, build, test, deploy, enhance and scale applications rapidly and cost effectively.</span>

![paas526.png](../_resources/paas526.png)

1.  Organizations are using PaaS to develop, run, manage and secure APIs and microservices, which are loosely coupled, independently deployable components and services.
2.  Internet of Things, or IoT: PaaS clouds support a broad range of application environments, programming languages, and tools used for IoT deployments.
3.  Business analytics, or intelligence: PaaS tools allow organizations to analyze their data to find business insights that enable more informed business decisions and predictions.
4.  Organizations are using the PaaS cloud to access BPM platform delivered as a service.
5.  Master data management, or MDM: Organizations are leveraging the PaaS cloud to provide a single point of reference for critical business data, such as information about customer transactions and analytical data to support decision-making.

![paas739.png](../_resources/paas739.png)

![paas947.png](../_resources/paas947.png)

![saas2104.png](../_resources/saas2104.png)

But the benefits can far outweigh these risks. PaaS continues to experience strong growth and is predicted to become the prevailing platform delivery model moving forward.

## Software-as-a-Service

Software-as-a-Service, or “SaaS,” is a cloud offering that provides users with access to a service provider’s cloud-based software. SaaS providers maintain the servers, databases, and code that constitute an application. They also manage access to the application, including security, availability, and performance. Applications reside on a remote cloud network, and users use these applications without having to maintain and update the infrastructure.

![saas7.png](../_resources/saas7.png)

**SaaS characteristics are:**

- Multitenant architecture  
    *Infrastructure and code are maintained centrally and accessed by all users.*
- Manage privileges and Monitor date  
    *SaaS makes it easy for users to manage privileges, monitor data use, and ensure everyone sees the same information at the same time.*
- Security, compliance, and maintenance
- Customization of applications  
    *In SaaS, customizations are often limited, however some SaaS applications may allow certain types of customizations like branding;*
- Subscription model
- Scaling

![saas29.png](../_resources/saas29.png)

**SaaS advantages are:**

- Direct procurement of solutions
- Improved workforce productivity and efficiency
- Enable distribution of software costs  
    ![saas613.png](../_resources/saas613.png)

![saas714.png](../_resources/saas714.png)

## Deployment Models

Deployment models indicate where the infrastructure resides, who owns and manages it, and how cloud resources and services are made available to users. There are four main deployment models available on the cloud—public, private, hybrid, and community.

**In the public cloud model**, the service provider owns, manages, provisions, and maintains the physical infrastructure such as data centers, servers, networking equipment, and storage, with users accessing virtualized computing, networking and storage resources as services.

**In the private cloud model,** the provider provisions the cloud infrastructure for exclusive use by a single organization. The private cloud infrastructure can be internal to the organization and run or on-premises. Or it can be on a public cloud, as in the case of Virtual Private Clouds (VPC), and be owned, managed, and operated by the cloud provider.

- exclusive use by a single organization comprising multiple consumers,
- owned, managed, and operated by the organization, a third party or some combination of them,
- and it may exist on or off premises

![Screenshot 2024-02-08 232503.png](../_resources/Screenshot%202024-02-08%20232503.png)

**In the hybrid cloud model,** an organization’s on-premise private cloud and a third-party, public cloud are connected as a single, flexible infrastructure that leverages the features and benefits of both Public and Private clouds.

## hybrid cloud types:

**1\. Hybrid Monocloud**

- **One cloud provider:** You connect your private cloud environment to a single public cloud service (e.g., combining your on-premises infrastructure with AWS or Azure).
- **Focus on consistency:** The goal is easier management and seamless workload movement using shared technologies and tools from that one provider.
- **Limitation:** Potential for vendor lock-in, meaning it might be harder to shift to a different public cloud vendor later down the line.

**2\. Hybrid Multicloud**

- **Multiple cloud providers:** You combine your private cloud with two or more public clouds (e.g., connecting to both AWS and Google Cloud).
- **Increased flexibility:** This reduces dependence on a single vendor and lets you select the best services from each provider.
- **Complexity:** Managing across different platforms and tools can be more challenging.

**3\. Composite Multicloud**

- **Ultimate flexibility:** This is a variant of hybrid multicloud where you distribute not just whole workloads, but components of a single application across multiple clouds.
- **Example:** Running storage on AWS, database on Azure, and frontend web serving on Google Cloud – all components of the same app working together.
- **Advantage:** Lets you tap into the absolute best specialized service or price from each provider.
- **Downside:** Can be significantly complex to design and manage effectively.

**To Summarize:**

- **Hybrid Monocloud:** Simplest, good for consistency.
- **Hybrid Multicloud:** More choice, avoid vendor lock-in.
- **Composite Multicloud:** The most granular control but toughest to manage.

* * *

**In the community cloud model,** the provider provisions the cloud infrastructure for use by a community of organizations with shared concerns. One or more of the organizations in the community, a third-party provider, or both are responsible for the ownership, management, and operation of this infrastructure.

**What is a Community Cloud?**

- A cloud solution shared by organizations with similar needs (like security or regulations).
- It can be run by the organizations themselves, a third party, or a mix of both.
- Think of it like a shared workspace for groups with common goals.

**Why Use a Community Cloud?**

- **Shared Security:** Everyone follows the same security rules.
- **Data Control:** Easier to meet data location and ownership requirements.
- **Clear Boundaries:** A defined security border around the whole community.

**Google Cloud's Approach**

- **Software-Defined:** Uses smart software to create secure communities instead of relying on separate physical hardware. This makes it more flexible and easier to manage.
- **Project-Based Communities:** Each project in Google Cloud acts like a mini private cloud. You can set security rules and data location specifically for each project, so it fits that community's needs.

**Benefits of Google's Software-Defined Community Cloud:**

- **Top-Notch Security:** Meets tough security and compliance standards.
- **Faster Updates:** Communities can use the latest cloud tech sooner.
- **Efficiency:** Scale resources quickly, improving performance and reliability for everyone.  
    Absolutely! Here's the information transformed into a table format:

## Module 2 Glossary: Cloud Computing Models

| Term | Definition |
| --- | --- |
| **BPM** | **Business Process Management:** Methods and tools for designing, analyzing, and improving business workflows. |
| **Composite Multicloud** | A hybrid multicloud variant distributing application components across multiple clouds for maximum flexibility. |
| **CRM** | **Customer Relationship Management:** Software focused on managing interactions with customers and potential customers. |
| **HCM** | **Human Capital Management:** Tools for managing HR functions like payroll, employee data, and recruiting. |
| **Hybrid Cloud** | Connects an on-premises private cloud and third-party public cloud into a single system for running workloads. |
| **Hybrid Monocloud** | Hybrid cloud using a single public cloud provider. |
| **Hybrid Multicloud** | Hybrid cloud using multiple public cloud providers. |
| **IaaS** | **Infrastructure as a Service:** Pay-as-you-go access to compute, storage, and networking resources from a cloud provider. |
| **IoT** | **Internet of Things:** The network of connected devices with sensing and processing capabilities. |
| **MDM** | **Master Data Management:** Ensuring the consistency and accuracy of core business data across systems. |
| **PaaS** | **Platform as a Service:** A complete cloud-based platform for developing and deploying applications. |
| **Pay-as-you-go** | A cloud pricing model where resources are charged based on usage. |
| **Private Cloud** | Cloud infrastructure dedicated exclusively to a single organization. |
| **Public Cloud** | Cloud services accessible to many customers over the internet. |
| **SaaS** | **Software as a Service:** Applications delivered over the internet, usually via a subscription model. |
| **SIP** | **SaaS Interaction Platforms:** Tools and processes for connecting and integrating different SaaS applications. |
| **TCO** | **Total Cost for Ownership:** The full cost of acquiring and operating a technology asset over its lifespan. |
| **VM** | **Virtual Machine:** A software emulation of a physical computer system. |
| **VPC** | **Virtual Private Cloud:** A logically isolated section of a public cloud. |

![Module divider.png](../_resources/Module%20divider.png)

## Module 3 - Cloud Infrastructure.

* * *

- Cloud infrastructure is the foundation of the cloud.
- It consists of physical resources that are housed in Regions, Zones, and Data Centers.
- A cloud Region is a geographic area where a Cloud provider’s infrastructure is clustered.
- Each Cloud Region can have multiple Zones, which are typically distinct Data Centers.
- Cloud providers offer several compute options, including Virtual Servers, Bare Metal Servers, and “Serverless” computing resources.
- Storage: Information and data can be stored in many different types of storage options on the Cloud.
- Networking: Networking infrastructure in a cloud datacenter includes traditional networking hardware like routers and switches, but more importantly for users of the Cloud, the Cloud providers have Software Defined Networking (or SDN) options where certain networking resources are virtualized or made available programmatically, through APIs.

Computing Options

- Virtual Servers
- Bare metal Servers
- Serverless

* * *

**What is Virtualization?**

Virtualization lets you create software-based versions of things like computers, storage, and networks. Think of it as running multiple "virtual" computers on a single physical machine. This magic is made possible by a tool called a hypervisor.

**The Hypervisor: Your Virtualization Powerhouse**

The hypervisor sits between your physical server and your virtual machines (VMs). Its job is to slice up the server's resources (like processing power and memory) and hand them out to your VMs.

There are two main types of hypervisors:

- **Type 1:** The boss! Installed directly on the server, they are super-efficient and secure (examples: VMware ESXi, Microsoft Hyper-V).
- **Type 2:** Runs on top of an existing operating system, good for personal use (examples: Oracle VirtualBox, VMware Workstation).

**Virtual Machines: Software Computers**

VMs are like independent computers within your computer. Each has its own operating system (Windows, Linux, etc.) and apps. Why is this so cool?

- **Flexibility:** Run different operating systems side-by-side on one machine.
- **Portability:** Move VMs between servers for easy maintenance and disaster recovery.

**Benefits of Virtualization**

- **Save Money:** Run more on less hardware, cutting down on energy and maintenance costs.
- **Speed & Agility:** Spin up new VMs in minutes instead of waiting for a whole new server to be set up.
- **Reduce Downtime:** If a server fails, easily move your VMs to another machine to keep things running smoothly.

**Virtualization is the foundation of cloud computing. Stay tuned to learn more about different types of virtual machines!**

**Enhancements in this recap:**

- **Clearer focus:** Emphasizes the "why" behind virtualization and its practical benefits.
- **Simpler language:** Avoids overly technical jargon where possible.
- **Engaging style:** Uses analogies ("computers within a computer") for easier understanding.
- **Stronger ending:** Highlights how virtualization powers cloud computing, encouraging further viewing.

* * *

**Understanding Virtual Machines (VMs)**

- **VMs in the Cloud:** Think of VMs as virtual computers you can rent from cloud providers (like AWS, Google Cloud, or Azure). You customize them with the features you need and get billed based on usage.
- **Flexibility:** Choose the region, operating system (Windows, Linux, etc.), and whether you want to share the underlying hardware (shared VM) or have it all to yourself (dedicated VM).

**Types of VMs for Different Needs**

1.  **Shared VMs:**
    
    - The budget-friendly option. You share a physical server with other users.
    - Providers offer various sizes (think processing power and memory) for different workloads.
    - Pay-as-you-go, billed hourly or even by the second!
2.  **Transient/Spot VMs**
    
    - Super cheap VMs using spare cloud capacity.
    - Downside: Can be taken away if the provider needs the resources back.
    - Perfect for testing, non-critical tasks, and big data jobs where cost is key.
3.  **Reserved VMs**
    
    - **Guarantee** you'll always have the virtual machines you need for a set period (like 1 or 3 years).
    - **Get a discount** compared to on-demand VMs.
    - **Pricing**: You commit to a specific VM configuration and a term (generally 1 or 3 years). In exchange, you receive a significant discount compared to the on-demand price.
    - **Flexibility**: Less flexible than on-demand. You're locked into the reserved resources for the contract duration.
    - **Availability**: Guarantees you always have the VMs you reserved, regardless of fluctuating demand.
4.  **Dedicated Hosts**
    
    - You get a whole physical server to yourself - no sharing!
    - Ideal for strict security, licensing, or specific performance needs.

**Key Takeaway**

Virtual machines are the backbone of cloud computing! Cloud providers offer different types of VMs to fit various use cases and budgets, giving you incredible flexibility.

* * *

Absolutely! Here's a condensed and focused recap of bare metal servers, keeping the most essential points:

**What are Bare Metal Servers?**

- Dedicated physical servers rented from a cloud provider – it's like having your own powerful computer in their data center.
- You get full control: Choose the hardware (processors, RAM, storage), operating system, and even install your own virtualization software.
- No "noisy neighbors": Since you're not sharing the hardware with anyone else, you get consistent performance and top-level security.

**Ideal Use Cases for Bare Metal Servers:**

- High-performance computing: Great for data-heavy tasks, scientific analysis, AI/deep learning.
- Sensitive workloads: Perfect if you need maximum security and control (e.g., financial or healthcare apps).
- Legacy applications: Run the apps you used in your traditional data center, but in the cloud.
- Customization needs: For specialized scenarios where standard virtual machines won't cut it.

**Comparing Bare Metal vs. Virtual Machines (VMs)**

| Feature | Bare Metal Servers | Virtual Machines |
| --- | --- | --- |
| Performance | Maximum, no shared resources | Shared resources, potential performance fluctuations |
| Security | Highest | Good, but potential for impact from other VMs |
| Customization | Full control of hardware and software | Limited by provider's VM configurations |
| Cost | Higher | Lower, pay-as-you-go |
| Provisioning Time | Slower (minutes to hours) | Faster (seconds to minutes) |

**In a Nutshell**

Bare metal servers offer power, control, and security at a premium. Choose them if your applications demand top-tier performance, complete isolation, or if you have strict compliance requirements.

* * *

**Building a Secure Cloud Network: Key Concepts**

- **Cloud vs. On-Premises:** The fundamentals of networking still apply, but cloud networks use software-defined (logical) components instead of physical hardware.
- **Network Boundaries:** Start by defining your virtual private cloud (VPC) – your secure slice of the cloud. Divide it into subnets for different application tiers.
- **Security is Crucial:**
    - **Access Control Lists (ACLs):** Act as firewalls at the subnet level.
    - **Security Groups:** Provide protection for individual virtual machines (VMs).

**Setting Up a Typical Cloud Network**

1.  **Tiered Structure:** Use subnets for your web-facing VMs, application VMs, and database VMs. This mirrors traditional on-premises setups.
2.  **Security:** Place each tier in its own security group with appropriate rules.
3.  **Internet Access:** If needed, add a public gateway for web-facing VMs.
4.  **Hybrid Clouds:** Securely connect your cloud and on-premises resources with a Virtual Private Network (VPN). Consider dedicated, high-speed connections (like IBM Cloud Direct Link) for extra security and performance.

**Extra Considerations:**

- **Load Balancing:** Use load balancers to ensure application responsiveness and handle traffic spikes.
- **Beyond the Basics:** Explore additional cloud networking features as your needs grow (e.g., traffic monitoring, intrusion detection).

**Key Takeaway**

Cloud networking gives you the flexibility to design secure, high-performing networks that mirror your on-premises architecture while harnessing the power of the cloud.

* * *

**Containers vs. Virtual Machines**

- **VMs: The Old Way** Each virtual machine (VM) includes a full guest operating system, libraries, and your application. This makes them large, slow to spin up, and prone to "works on my machine" compatibility issues.
    
- **Containers: The Leaner Way** Containers package only your application and its necessary libraries. They share the host operating system, making them incredibly lightweight, fast to deploy, and consistent across environments.
    

**Why Containers are Better**

- **Efficiency:** No duplicated operating systems means more of your hardware resources go directly to running your applications.
- **Scaling Power:** Since containers are small, you can easily spin up more copies of your application as needed, handling traffic spikes effortlessly.
- **Mix and Match:** Easily run applications written in different languages (Node.js, Python, etc.) side-by-side on the same host, making them perfect for microservice architectures.
- **DevOps Dream:** Containers create a predictable, portable package. That means what runs flawlessly on your laptop will run the same way in production - no more surprises.

**In Short:** Containers let you do more with less hardware, streamline developer workflows, and make application scaling a breeze.

* * *

**Choosing the Right Cloud Tool**

- **Containers:** The default for many modern apps thanks to their speed, scalability, and portability. Perfect for microservices and cloud-native architectures.
- **Virtual Machines (VMs):** Offer the familiarity of a full operating system. Good for when you need greater isolation (security) or consistent, predictable performance.
- **Bare Metal Servers:** The raw power choice. Select these when you need absolute maximum performance, control over hardware, or must meet strict compliance regulations.
- **Serverless Functions:** Ideal for short, infrequent tasks where you want pay-per-use efficiency and zero maintenance.

**Decision Factors**

Consider these questions when choosing your cloud resource:

- **Performance Needs:** Does your application demand every ounce of processing power? (Bare Metal might be best)
- **Security & Isolation:** Is sharing hardware out of the question due to regulations or sensitivity? (Look at VMs or Bare Metal)
- **Flexibility & Portability:** Need to run your app in different cloud environments easily? (Containers shine here)
- **Cost & Efficiency:** Is paying only for what you use and maximizing scalability crucial? (Consider containers or serverless)

**The Trend:** Containers (especially with Kubernetes) are increasingly prevalent. Start there unless you have a specific reason to use other options.

* * *

* * *

## Cloud Storage and Content Delivery Networks

**Cloud Storage: The Basics**

Cloud storage is like having a vast, remote hard drive for your data. Instead of storing files on your own computer or a local server, you save them "in the cloud." This means your data is kept on secure servers managed by a cloud provider (like Google Cloud, Amazon Web Services, or Microsoft Azure).

**Why Use Cloud Storage?**

- **Scalability:** Need more space? Easily increase your storage without buying physical hardware. You pay only for what you use.
- **Accessibility:** Since your data is online, you can access it from anywhere with an internet connection.
- **Reliability and Security:** Cloud providers invest heavily in protecting and backing up your data, often more robustly than you could manage on your own.
- **Cost-effectiveness:** No need to invest in and maintain your own expensive storage infrastructure.

**Types of Cloud Storage**

Cloud storage comes in four main flavors, each best suited for different tasks:

- **Direct Attached Storage (DAS):** This is storage built into or very closely connected to a single server. Think of it like a computer's internal hard drive but accessible from the cloud.
    
    - **Pros:** Super fast. Often used for a server's operating system.
    - **Cons:** Not easily shareable, can be lost if the server fails, less resilient to data loss than other cloud options.
- **File Storage:** Simulates a familiar folder and file hierarchy (like what you see on your own computer). Data moves over standard internet connections.
    
    - **Pros:** Simple to use, can be shared by multiple servers at once.
    - **Cons:** Typically slower than DAS or block storage.
- **Block Storage:** Data is broken into "blocks" and spread across storage systems. A server sees it as an extra, super-fast hard drive.
    
    - **Pros:** Excellent for databases and applications that need lightning-fast storage.
    - **Cons:** Usually can't be shared by multiple servers at the same time.
- **Object Storage:** Perfect for massive amounts of unstructured data like images, videos, backups, and logs. Accessed through internet requests (APIs).
    
    - **Pros:** Incredibly scalable (practically unlimited), very cost-effective.
    - **Cons:** Slower than other types, not ideal for things that need constant, quick modification.

**Additional Key Concepts**

- **IOPS:** Stands for "Input/Output Operations Per Second." A measure of how fast you can read and write data to storage.
- **Persistence:** This means whether or not your file or block storage stays around even when the server it's connected to is shut down.
- **Snapshots:** Like a freeze-frame of your file or block storage. Used for quick backups or rolling back to previous versions.

* * *

**What is Object Storage?**

- **API-Driven, Not Server-Bound:** Unlike file or block storage attached to specific servers, object storage is its own service. You interact with it via an API (think of it like a command center), allowing direct access from any device that can send API requests. This provides flexibility.
- **Cost-Effective:** Priced per gigabyte used, object storage is often the cheapest cloud storage option. Great for situations where costs must be carefully managed.
- **Infinitely Scalable:** No upfront size decision! Your storage can continuously grow to accommodate what you need. This suits data where the total size may be unknown or rapidly expanding.

**When to Use Object Storage**

- **Unstructured Data:** Ideal for data not needing folders or rigid hierarchies (images, videos, sensor logs, etc.). Objects live in flat "buckets" you can name for basic organization, but nesting buckets isn't supported.
- **Metadata for Identification:** Each object in a bucket has "data about the data" attached for quick access and information (upload time, etc.).
- **No Size Worries:** Buckets auto-expand as you upload; just pay for what you use. Service provider handles capacity issues behind the scenes.
- **Resilience Tiers:** Providers usually offer choices in how well your data is protected.
    - Basic: Data in one data center – cheaper, but risks localized disruption
    - Multi-Region: Data copies exist across distant locations – costlier, but ensures accessibility even if a whole data center fails.

**What Object Storage Stores**

Almost anything *static*, where read/write speed isn't the top concern: text files, media, backups, virtual machine images... the list goes on!

**What Object Storage ISN'T Good For**

Running operating systems, databases, or anything with frequently changing data. Its strengths lie in long-term storage, not constant modification.

**Summary**

- **Storage for Static Objects:** Objects in buckets, not complex folders.
- **Types of Objects:** Huge variety: text, media, backups, etc.
- **No Need to Pre-plan Size:** Scales as you add data.
- **Cost & Resilience Options:** Choices to balance budget vs. how vital it is your data is always safe.

**Areas for Improvement in Original Text**

The original text is quite good! A few tweaks to enhance clarity:

- **API Emphasis:** Could stress more that APIs mean no need for an *additional* server just to access files, unlike other storage types.
- **Dynamic vs. Static:** The term "static" needs clearer definition: data content doesn't change often, as opposed to data *size* growing as you add things.

* * *

**Understanding Object Storage: Tiers, APIs, and Beyond**

Object storage provides different "tiers" or "classes" for your data. Think of them like storage plans affecting cost and how quickly you can access your files:

- **Standard Tier:** Your go-to for anything used often. Files load quickly, but this tier has the highest per-gigabyte storage cost.
- **Vault/Archive Tier:** Designed for those documents used maybe once or twice a month, sometimes less. Much cheaper storage, but slower retrieval.
- **Cold Vault Tier:** Imagine data needed once or twice a YEAR. Comes at the lowest price (often fractions of a cent per gigabyte), but files might take hours to access as this storage stays offline until requested.

**Smart Archiving:** Many providers offer automatic archiving with rules you set up. If a file goes unused for a set time, it moves to a cheaper tier! This uses the file's metadata (data *about* your data) to decide when to migrate down the cost ladder.

**Speed vs. Cost Considerations**

- **No IOPS with Object Storage:** Unlike file or block storage, there's no option to pay for extra "speed points" (IOPS). Object storage tends to be slower, with downloads potentially taking seconds or more.
- **Know Your Needs:** Object storage might not suit your application if files need lightning-fast access.

**The Cost Breakdown**

- **Pay-As-You-Go:** Your cost is based on how many gigabytes you store. Great for unpredictable or growing data needs.
- **Beyond Storage:** There are often small retrieval fees as well. These increase for data in Vault or Cold Vault, so choosing the right tier for how often you need your files is critical!

**APIs: The Key to Access**

You don't attach object storage to a server. Instead, you use an API - like a specialized instruction set for your applications.

- **The S3 Standard:** The most common API is called S3 (based on Amazon Web Services' approach). Many cloud providers make their API S3-compatible. This helps developers, as their code works across multiple object storage solutions.
- **APIs in Action:** These APIs use web standards (HTTP, REST) to manage everything: creating storage buckets, uploading/downloading objects... even complex actions!

**Practical Uses for Object Storage**

- **Beyond New Apps:** While great for modern tools, it also can revamp how existing applications use storage.
- **Backup Reimagined:** Object storage often replaces old-fashioned offsite tapes for backups and disaster recovery. It's faster to retrieve your data in a crisis! Many backup programs now let you save directly to cloud object storage.
- **Efficiency Over Tapes:** No more loading tapes into physical drives or shipping them across locations. Cloud object storage wins for speed and geographic safety.

**To Summarize**

- **Tiers for your Budget:** Different storage classes balance cost and accessibility.
- **Flexible Pricing:** Pay for gigabytes used, plus sometimes small retrieval fees.
- **Consider Speed:** Object storage is generally slower than file/block storage.
- **Auto-Archiving:** Rules can move older, less-used files to cheaper tiers.
- **APIs Are Essential:** The way programs interact with object storage .
- **S3 Compatibility:** Developers benefit from multiple providers supporting this standard.
- **Modern Backup Solution:** Object storage makes disaster recovery simpler.

* * *

**Choosing the Right Cloud Storage: What the Experts Say**

Cloud storage isn't one-size-fits-all! These tech professionals highlight the main factors to guide your decision-making:

**1\. Cost: The Ever-Present Question**

- **Price Tag:** How much does it cost per gigabyte of storage?
- **Beyond Storage:** Factor in retrieval fees. Accessing your data, especially from cheaper storage tiers, often incurs costs that build up over time.
- **Usage Is Key:** Understand *how* the storage will be used (frequent access, long-term archive, etc.). This aligns your budget with your needs.

**2\. Performance: Speed vs. Cost**

- **Latency:** How long does it take to retrieve or save data? Object storage is often slower, while block storage shines with low latency for performance-hungry apps like databases.
- **Trade-offs:** Generally, faster access = higher price. Balance application needs against budget.

**3\. Security & Encryption**

- **Data At Rest:** Is your data encrypted even when not in use? This is crucial for sensitive information.
- **Data In Motion:** Is encryption used during transfer to/from the storage? Look for 'encryption in flight' capabilities.
- **Control:** Some providers let you manage your own encryption keys for added security.

**4\. Operational Ease**

- **How Easy Is Management:** Consider how seamlessly the storage integrates with your workflow and tools. Avoid solutions that create administrative headaches.

**The Main Cloud Storage Types**

- **File Storage:** Familiar folders and files, supports multiple users at once. Good for collaboration and general purposes.
- **Block Storage:** Blazing-fast 'chunks' of storage often attached to single servers. Databases love this, but sharing between servers is limited.
- **Object Storage:** Massively scalable for huge files or lots of unstructured data (images, backups). Retrieval can be slower, and the file-within-bucket design takes getting used to.

**Additional Considerations & Specialized Uses**

- **Frequency of Access:** Hot storage (needs to be quickly available) costs more than cold / archive storage for infrequently used data.
- **Data Lifecycles:** Do you need automated backup rules, moving data between tiers, or deleting old content? Look for providers with strong automation features.
- **Content Delivery Networks (CDNs):** If speed across geographies matters for end-users (like loading website images), CDNs pair with cloud storage to push content closer to the people requesting it.

**The Big Takeaway**

There's NO one 'best' cloud storage! Answer these questions about your project to find the right fit:

- What am I storing? (Data type, size)
- How fast do I need to access it?
- How many people/systems need the data concurrently?
- What's my budget, factoring in potential usage costs?
- How important is robust encryption?

* * *

## Module 3 Glossary: Components of Cloud Computing

| Term | Definition |
| --- | --- |
| ACL | Access Control Lists |
| AZ  | Availability Zones are distinct Data Centers with their own power, cooling and networking resources. These Zones can have names like DAL-09 or us-east-1. |
| Bare-metal hypervisor | Installed directly on top of the physical server. They're more secure, have lower latency, and are usually the ones you see in the market the most |
| Block storage | Is presented to compute nodes using high-speed fiber connections, which means that read and write speeds are typically much faster and reliable than with file storage |
| CDNs | Content Delivery Networks is a distributed server network that delivers temporarily stored, or cached, copies of website content to users based on the user’s geographic location |
| Cloud Region | A geographic area or location where a Cloud provider’s infrastructure is clustered, and may have names like NA South or US East |
| Containers | Are an executable unit of software in which application code is packaged, along with its libraries and dependencies, in common ways so that it can be run anywhere, whether it be on desktop, traditional IT, or the cloud |
| Data center | A huge room or a warehouse containing cloud infrastructure |
| Dedicated hosts | Offer single-tenant isolation |
| Direct Attached storage | Or Local storage is storage which is presented directly to a cloud-based server and is effectively either within the host server chassis or within the same rack |
| File storage | Is typically presented to compute nodes as ‘NFS Storage’. NFS stands for Network File System and means that the storage is connected to compute nodes over a standard ethernet network |
| Hosted hypervisor | There's a layer of host OS between the physical server and the hypervisor. These hypervisors are less frequently used and mostly used for “end-user” virtualization |
| HPC | High-performance computing |
| Hypervisor | A piece of software that runs above the physical server or host |
| IOPS | Input/Output Operations Per Second and refers to the speed at which the disks can write and read data |
| NFS | Network File Storage |
| Object storage | Storage not attached to a compute node, rather it is accessed via an API |
| Reserved virtual server | Instances allow you to reserve capacity and guarantee resources for future deployments |
| SDN | Software Defined Networking |
| Shared or Public Cloud VMs | Are provider-managed, multi-tenant deployments that can be provisioned on-demand with predefined sizes |
| Transient or Spot VMs | Take advantage of unused capacity in a cloud data center |
| Virtualization | Process of creating a software-based or virtual version of something whether that be compute, storage, networking, servers, or applications |
| VLANs | Virtual Local Area Networks |
| VM  | Virtual machines are software-based computers, based on virtualization technologies |
| VPC | Virtual Private Cloud |
| VPN | Virtual Private Networks |

* * *

* * *

## Module 4 - Emergent Trends and Practices

<ins>**Hybrid Multi-Cloud, Microservices, and Serverless**</ins>

**Hybrid Cloud**

* **Definition:** A single infrastructure combining an organization's private cloud with a public cloud service.
* **Key Benefit:** Allows seamless operation of applications across both private and public environments.

**Multi-Cloud**

* **Definition:** Using multiple cloud services (public, private, managed) from different providers for various IT functions (email, applications, infrastructure).
* **Key Benefit:** Leverages the best features/services from each cloud provider.

**Hybrid Multi-Cloud**

* **Definition:**  Combines the concepts above – applications/workloads operate across multiple different clouds, including private on-premises infrastructure.  

**Use Cases for Hybrid/Multi-Cloud**

1. **Cloud Scaling**
   * **Problem:** On-premises infrastructure can't handle peak demand.
   * **Solution:** Hybrid/multi-cloud lets businesses "burst" into the cloud during high demand, then scale down when not needed, avoiding costly on-premises expansion.
   * **Example:** Flower delivery service catering to holidays.

2. **Composite Cloud**
   * **Problem** Some components of an app have region-specific performance requirements.
   * **Solution:**  Distribute application parts across multiple clouds/data centers geographically to keep everything fast for end users.
   * **Example:** Flower delivery service moves billing/UI to North America for better customer experience there.

3. **Modernization (Travel Industry Example)**
   * **Problem:** Legacy on-premises systems hold companies back.
   * **Solution:**  Build new features (like mobile apps) on the cloud that interact with older on-premises systems. Allows innovation without totally rebuilding core infrastructure.

4. **Data and AI (Travel Industry Example)**
   * **Problem:** Airlines have valuable data, but struggle to use it effectively.
   * **Solution:** Cloud resources let them apply machine learning to historical data (maintenance records) to predict issues and improve operations.

5. **Vendor Lock-in Prevention**
   * **Problem:** Relying on one cloud provider creates inflexibility.
   * **Solution:** Multi-cloud keeps you from being dependent on a single company; you can shift workloads if prices, features, etc., become unfavorable.
* * *
**What are Microservices?**

* Instead of building one giant application, microservices break down apps into smaller, independent parts called services. 
* Each service has its own code and runs separately (often in a container).
* Services talk to each other using APIs,  events, and message brokers.

**Why Use Microservices?**

* **Faster Development:** Smaller teams can work on individual services without affecting the whole application.
* **Flexibility:** Developers can choose the best technology stack for each service.
* **Scalability:** Only scale the specific parts of your application that are under heavy load, saving money.

**How Microservices are Changing Development**

* **Less Monolithic Code:** Instead of huge applications written from scratch, developers use pre-existing code and cloud platforms for the basic building blocks.
* **Small, Focused Teams:** Teams  specialize in individual microservices instead of everyone working on a single, massive codebase.
* **Easier Experimentation:**  Each microservice container is like a plug-and-play building block.  Swap them out  to try new features without breaking the whole app.

**Example: Improving a Streaming Service**

* **Problem:** User (Ron) wants a personalized way to find his favorite soccer team's games on a streaming service.
* **Microservice Solution:**
    * **Content Catalog:** Organizes videos with searchable metadata.
    * **Search:**  Lets users find specific games.
    * **Recommendations:** Learns user preferences to personalize what they see.
* **APIs:** Allow these services to communicate and share data. 
* **Service Discovery:** Helps these services find each other within the larger application. 
* **The Result:**  Ron easily finds the games he wants and the streaming service keeps him engaged through personalized content.

**Key Takeaway:** Microservices help businesses release new features quickly and adapt to changing customer interests. 

* * *
**What is Serverless Computing?**

* A way to run code without directly managing servers.
* Your cloud provider handles the infrastructure (servers, scaling, updates) while you focus on writing your application logic.
* It's *not* literally serverless – servers still exist, but they're hidden from you.

**Key Features**

* **Zero upfront setup:** No need to choose server sizes or install software. 
* **Run code on-demand:** Your code only runs when needed (triggered by events).
* **True pay-as-you-go:** You pay for actual usage, not idle time.
* **Functions over servers**:  Break your app into small, stateless functions (pieces of code with a single purpose).

**Example:**

1. User uploads a text file to your website.
2. Serverless function translates the text into multiple languages.
3. Serverless saves translated files to cloud storage.
4. Your website presents links to the user.

**Popular Serverless Providers:**

* IBM Cloud Functions
* AWS Lambda
* Microsoft Azure Functions

**Is Serverless Always the Best Choice?**

* **No.** Some apps are better suited to traditional server setups. Consider serverless for:
    * Apps with short-lived tasks (seconds or minutes).
    * Workloads that vary a lot (busy periods, quiet periods).
    * Event-driven processes (user clicks a button, file gets uploaded).
    * Microservices architecture (large apps composed of many small functions)

**Common Serverless Use Cases**

* **Data & Event Processing:** Handle incoming streams of data or files.
* **IoT:** Respond to data from connected devices.
* **Microservices:** Build scalable backend services.
* **Media Processing:** Resize images, transcode videos, etc.

**Potential Challenges**

* **Long-running tasks:** Traditional servers might be easier for slow, continuous processes.
* **Vendor Lock-in:** Using specific cloud provider features can make it harder to switch.
* **Cold Starts:** Some delay the first time a function runs after inactivity (this is improving over time). 
* * *
## Cloud Native Applications, DevOps, and Application Modernization

* Cloud native applications are designed to be built and deployed on the cloud, and they take advantage of the benefits of the cloud, such as scalability, elasticity, and agility.
* Cloud native applications are made up of microservices, which are small, independent services that can be developed, deployed, and scaled independently.
* Containers and container orchestration tools are used to package and manage microservices.
* DevOps is a cultural and process change that enables continuous delivery and deployment of cloud native applications.
* Cloud native applications leverage standardized components and best practices, such as Kubernetes, Jaeger, and Linkerd.
* * *
Here's your requested revised version of the notes! I focused on clarity, simplifying vocabulary, and improving readability for a general audience:

**What is DevOps?**

* DevOps combines Development (Dev) and Operations (Ops) teams to deliver better software faster.
* Teams work together throughout the entire process, from idea to release, continuously improving.
* This results in higher quality software, faster responses to customer needs, and smoother running systems.

**Key DevOps Practices**

* **Continuous Delivery:** Small, frequent software updates for fast improvements.
* **Continuous Integration:** Code changes are regularly merged and tested to catch problems early.
* **Continuous Deployment:** Automatic updates to production environments ensure features get to users without delays.
* **Continuous Monitoring:** Tracking system health for proactive problem solving.
* **Delivery Pipeline:** An automated process to take ideas from concept to working software.

**DevOps and the Cloud**

* DevOps shines in cloud environments because it is all about efficiency and quick changes.
* DevOps helps create reliable cloud applications by:
    * **Automated Setup:**  No more configuring every little thing!
    * **Easier Deployments:** Automatic tools make them fast and safe.
    * **Flexible Testing:** Quickly spin up realistic environments for testing.
    * **Disaster Recovery:** Rebuilding systems fast if issues occur. 

**In Plain English**

DevOps is like a team sport for software. Devs and Ops work together to create the best possible product. They constantly release small updates, catch problems early, and respond quickly to changes. This is especially helpful for cloud projects where adaptability is key. 
* * *
**Unlocking the Power of DevOps in the Cloud**

Modern businesses need to deliver software quickly, reliably, and at scale.  DevOps, the practice of uniting development and operations teams,  is the key to making this happen. In this article, we'll explore what DevOps is, how it supercharges cloud platforms, and see real-world examples using AWS, Azure, GCP, and IBM Cloud.

**Understanding DevOps**

DevOps is more than tools; it's a way of working that gets everyone on the same page. By sharing goals, automating tasks, and constantly getting feedback, DevOps teams release better software faster.

**The DevOps Cycle**

Here's how a typical DevOps process works:

* **Continuous Integration (CI):**  Devs frequently  check their code into a shared space. Version control software like Git helps catch problems early.
* **Continuous Delivery (CD):** This ensures your code is always ready to go live. Build, test, and deploy stages become  automated (Jenkins and Bamboo are popular tools for this).
* **Continuous Deployment (CDep):** Going even further, this method pushes tested code directly to users on its own.
* **Continuous Monitoring (CM):**  Get instant updates on app performance  (Prometheus and ELK Stack are commonly used). This means quick problem solving!

**DevOps + Cloud: A Perfect Match**

Here's why DevOps fits so well with cloud platforms:

* **Scale with Ease:** The cloud can grow or shrink based on what you need, matching your DevOps cycles.
* **Fast Setup and Launches:** Pre-built tools and templates mean less manual work and quicker product releases.
* **Pay for What You Use:** Avoid buying expensive equipment upfront - the cloud lets you pay as your needs change.
* **Collaboration is King:**  Cloud workspaces, shared code storage, and communication tools are built-in. This is essential for DevOps.
* **CI/CD Power-Up:** Popular DevOps tools work directly with cloud services, making complex work automatic.

**Real-World Examples**

Let's look at DevOps on top cloud platforms:

* **AWS:**  CodePipeline (CI/CD), Elastic Beanstalk (simplified deployment), Lambda (no servers to manage!) are perfect for DevOps.
* **Azure:** Azure DevOps (collaboration), Kubernetes Service (container management), Functions (serverless coding) offer incredible control.
* **GCP:**  Build (CI/CD), Kubernetes Engine (container HQ), Functions (serverless) streamline operations at  scale.
* **IBM Cloud:** Continuous Delivery (auto deployments), Kubernetes Service (container control), Functions (serverless) bring DevOps' focus to a reliable platform.

**The Winning Combo**

DevOps lets companies release software faster and adapt to customer needs easily. When built on the cloud, this gets even better, allowing teams to scale  work on-demand. From AWS to IBM Cloud,  DevOps and the cloud work together to keep businesses at the forefront of modern software development. 
* * *
**Making Old Apps New Again: Modernization Explained**

Companies often have older applications that are hard to update and expensive to keep running.  "Modernizing" means updating these apps to take advantage of newer technology for faster change and a better customer experience.  Cloud computing is a huge part of this process!

**The Big Three: How Everything Has Changed**

1. **Architecture (the way apps are built):** Old apps were like giant blocks (monoliths), running on individual servers. We planned their development in big stages, like a 1-year plan. That doesn't work well anymore.
2. **Infrastructure (where apps run):**  Most businesses now  have apps divided into smaller parts (services) which talk to each other. These often run on virtual machines for efficient space use.
3. **Way of Working:** "Agile Development"  became the norm—instead of rigid project plans, we move more flexibly as things change.

**Today's Goal: Even Smaller, Faster, Cloud-Based**

We're making our app services even tinier (microservices) to increase speed and independence. This plays perfectly with:

* **Cloud:** On-demand servers you rent as needed – public options (like Amazon's AWS) or private ones your company controls. Instant changes!
* **DevOps:** Development and Operations teams become one. This tightens the feedback loop so the right solutions arrive faster.

**Why These Changes Go Hand-in-Hand**

Think of it this way:

* **Microservices need the cloud:** If it takes months to get hardware for each new tiny service, the speed advantage is lost. The cloud lets you launch instantly. 
* **Cloud loves microservices:**  It makes more sense to rent small spaces if you have lots of little apps with changing needs, compared to giant old-school setups.
* **DevOps brings it together:** Devs want speed, Ops needs apps to survive crashes. They can program the cloud system together  to keep everything reliable even during fast changes.

**Example:** Your company updates its store software every 2 years with lots of planning. A modernized approach might let them add new features each month since there are small, focused microservices and a smooth cloud-based deployment.

**Modernization = Big Transformation** 

Many companies talk about  'going to the cloud',  'doing DevOps', and  'adopting microservices'.  What's important to realize is this isn't three separate problems – it's how software itself is changing as companies try to keep up with customer needs.
* * *
**Note: Emerging Trends in Cloud Computing**

In this video, cloud application professionals discuss several emerging trends and technologies shaping the landscape of cloud computing. Here are the key points highlighted by the experts:

1. **Hybrid Cloud Adoption**: Many companies are shifting from relying on a single cloud provider to embracing a hybrid cloud approach. This entails utilizing multiple cloud providers, whether public or private, to meet diverse business needs effectively.

2. **Rise of Edge Computing**: Edge computing is gaining prominence within cloud computing as an increasing number of devices connect to the internet. With an estimated 75 billion devices expected online by 2075, edge computing becomes crucial for facilitating communication between devices and servers, especially in scenarios requiring low latency.

3. **Integration of Machine Learning and Artificial Intelligence**: The utilization of machine learning and artificial intelligence is becoming integral to decision-making processes in cloud computing. These technologies enable enhanced automation and intelligence, contributing to more efficient operations within the cloud environment.

4. **Serverless Computing**: A significant trend is the adoption of serverless computing, where developers focus solely on writing application logic without managing underlying servers or infrastructure. Cloud providers handle operational aspects like high availability and scalability, allowing developers to concentrate on crafting unique application features.

5. **Cloud-Native Architecture**: The shift towards cloud-native architecture involves breaking down monolithic legacy applications into smaller, more manageable microservices. This approach, along with the adoption of containerization and orchestration technologies like Docker and Kubernetes, offers flexibility, scalability, and efficiency in application development and deployment.

6. **DevOps Integration**: DevOps practices promote closer collaboration between development and operations teams, fostering a seamless integration of code development, deployment, and maintenance. Through continuous integration and continuous deployment (CI/CD) pipelines, developers can oversee the entire lifecycle of their applications in production environments.

7. **Advancements in Data Science and Artificial Intelligence**: Cloud services are evolving to offer comprehensive solutions for building data pipelines and implementing artificial intelligence solutions. These services range from low-level AI tools for custom solution development to pre-trained models for applications such as image recognition and speech processing.

8. **Focus on Application Modernization**: With the availability of advanced cloud services, companies are reconsidering their application architectures to leverage cloud-native capabilities effectively. This involves offloading certain application functionalities to cloud providers' services, such as transcription and image recognition, to streamline operations and improve efficiency.

In summary, the evolving landscape of cloud computing is characterized by a shift towards hybrid and edge computing, integration of advanced technologies like machine learning and AI, adoption of serverless and cloud-native architectures, closer collaboration through DevOps practices, and a focus on leveraging cloud services for application modernization and enhanced data processing capabilities. These trends reflect the ongoing evolution and innovation within the cloud computing industry.
* * *
| Term | Definition |
|---|---|
| API | Application Programming Interface |
| Application modernization | Helps organizations accelerate their digital transformation, take advantage of new technologies and services, and become more responsive to changing market dynamics |
| Cloud native application | An application developed from the outset to work only in the cloud environment, or an existing app that has been refactored and reconfigured with cloud native principles |
| Continuous delivery | Delivering small, well-designed, high-quality increments of software to customers |
| Continuous deployment | Progressing each new packaged build through the deployment lifecycle as rapidly as possible |
| Continuous integration | Creating packaged builds of the code changes released as immutable images |
| Continuous monitoring | Monitoring with tools that help developers understand the performance and availability of their applications, even before they’re deployed to production |
| Delivery pipeline | An automated sequence of steps that involves the stages of Ideation, Coding, Building, Deploying, Managing, and Continuous Improvement |
| DevOps | Collaborative approach where business owners and the development, operations, and quality assurance teams collaborate to continuously deliver software |
| Hybrid multicloud | An open standards-based stack that can be deployed on any public cloud infrastructure |
| Microservices | Break down large applications into their core functions |
| Microservices architecture | Approach in which a single application is composed of many loosely coupled and independently deployable, smaller components or services |
| Monolithic architecture | Approach in which a single application is built out of one piece of software |
| Serverless | Approach to computing that offloads responsibility for common infrastructure management tasks |
| Service discovery | Creates a roadmap for microservices to communicate |

* * *
* * *
## Cloud Security and Monitoring

**What is Cloud Security?**

* Companies are increasingly using cloud computing, which means storing data and using tools online instead of on their own computers.
* This offers some benefits but also creates unique security risks. Businesses need strong cloud security to protect their data and operations.

**Challenges of Cloud Security**

* **Visibility:** It's harder to see who is accessing your data in a public cloud.
* **Multitenancy:** Many companies might share the same cloud server, creating risk if someone attacks a different company on that server.
* **Access & Shadow IT:**  It's harder to control who accesses your services from  where.
* **Misconfigurations:** Incorrect settings (like weak passwords) are a big security risk.

**Threats to the Cloud:**

* **Insider Threats:** People within your company could misuse their access.
* **DDoS Attacks:** Attackers overload your servers with fake traffic to take your business offline.
* **Data Breaches:** Hackers could steal sensitive data, damaging your reputation and finances.

**The Shared Responsibility Model**

* In cloud computing, both you AND the cloud provider are responsible for security. 
* **What you usually handle:** Protecting your operating system, data, and user access.
* **What the provider handles:** Security of their physical data centers and often some software security.

* * *
**Cloud Security in a Complex World**

As businesses move more operations to the cloud, especially setups that mix cloud and on-premises systems, their potential attack surface widens. This means new challenges in protecting data and staying compliant with regulations. That's why you need strong data-focused security, visibility into everything happening in your cloud, and strict monitoring to prevent data theft.

**How Do We Protect Data in the Cloud?**

* **People, Process, Technology:** All three matter! Figure out your most important data, control who has access, and use technology to protect it.
* **Data Loss Prevention:** Tools and policies proactively stop accidental data leaks before they happen.
* **Governance:** This means clearly defined processes, ways to measure security success, and constant checks to identify data you may have missed.
* **Database Security:** The heart of your cloud needs specific tools to be compliant and protected across cloud and on-premises setups.

**Access Control is Key**

* **Cloud IAM:**  Identity & Access Management in the cloud is a bit different. Look for ways to modernize that won't break what you already have.
* **Zero Trust:** This buzzword is worth it. Zero trust means NO ONE is automatically trusted – every user is constantly re-authenticated for added protection.
* **Scalability:** If your business suddenly gets huge, your cloud security has to handle that growth without major changes.

**More Cloud Security Essentials**

* **Cloud Network Security:** Your network has new risks in the cloud. Invest in security tools specifically designed for cloud environments to detect threats, reduce errors, and encrypt your data.
* **Best Practices:** Your journey should have these 3 phases:
    * **Identify:** Map data use, risks, and how everything is set up.
    * **Protect:** Encrypt data, strictly control access and sharing, protect against malware and bots.
    * **Respond:**  Know how to quickly adapt to attacks with extra authentication and policies.

**Extra Resources and Trends**

* **NIST Cybersecurity Framework:** Their "Identify, Protect, Detect, Respond, Recover" model is a great foundational guide.
* **CSPM:** Cloud Security Posture Management tools automate checking for misconfigurations (a huge risk!) and other common security tasks.
* **The Future:** Zero-trust models, protection for remote workers, and AI-powered tools will take center stage as cloud security becomes even more important.

* * *
**Cloud Security: It's All About Who Gets In (And What They Can Do)**

* **Policies: The Rulebook** Think of policies as the "dos and don'ts" of your cloud environment. They answer questions like "Who can access what?", "What are they allowed to do?", and "How do we make sure everyone's following the rules?"  Cloud providers have their own policies, but you need yours too, tailored to your business.

* **Least Privilege: Need-to-Know Basis**  Imagine only giving people the keys to rooms they *actually* need. That's the idea here. Giving users the absolute minimum access they need to do their jobs reduces the damage if an account gets hacked.

* **User Access: It Depends on the Job** Some users just need the dashboard to manage things. Developers need the code-level tools.  Understanding *who* needs *what* helps you give the right access, nothing more.

* **IAM: The Gatekeeper** Identity & Access Management is like your cloud's bouncer. It checks IDs, knows who's allowed in, and what they can do once inside. IAM  makes adding or removing users a breeze, which is key for security.

* **Passwords: Old But Important** A good password policy is the annoying friend everyone needs. Things like "must be a weird mix of symbols" and "change it every 90 days" might be a pain, but they help a LOT.

* **Identity Providers: Like a Digital Passport** SAML and OpenID are ways to make login easier *and* safer. Users basically get a special "cloud passport" they can use with lots of services, not just yours. This also lets you outsource some of the heavy security lifting to these identity providers.

**Key Takeaway:** Cloud access isn't about being restrictive, it's about being SMART.  Give people what they need to work, and protect the stuff they don't need to touch. 

* * *
**Data Security in the Cloud: Who Is Allowed Where?**

* **Worry #1: Data Leaks** The biggest fear in cloud security isn't fancy hackers, it's often employee mistakes or accounts getting compromised. This is why access control is critical.
* **IAM:  Like a Digital Door Policy** This system decides who gets into your cloud, what they can do once inside, and what areas are blocked off. You control access based on a person's role, project, etc. 

**Types of Users (And the Risks They Pose)**

* **Admins:**  These folks have the keys to the kingdom. If their accounts get hacked, it's BAD news – leaked data, ruined services, etc.
* **Developers:**  Need access to the code of your cloud apps. If compromised, code could be changed or sensitive info stolen.
* **App Users:**  Your everyday customers interacting with cloud-based services.

**IAM: The Building Blocks**

* **Authentication:** It's like checking IDs at the door.  The system confirms you are who you say you are (username, password, plus extra security like a code sent to your phone).
* **Cloud Directory:** Stores user profiles and passwords securely within the cloud, meaning apps you use don't have to manage their own user lists.
* **Reporting:** Think of this as the security camera footage. Shows who accessed what resources and when. Super important for spotting problems quickly.

**Audit and Compliance: The 'Must-Haves'**

* **Meeting the Rules:** Auditors check you're following laws (like data privacy), industry standards, and your own security promises. If you fail, there can be big fines or damage to your reputation.
* **Controlling User Access:**  IAM lets you easily add or remove users based on their jobs. Helps stay compliant - people only have access they *need*.

**Protecting Those Powerful Accounts**

Admins and developers require the tightest security:

* **Roles:** Grant access only to the stuff someone needs for their specific job. 
* **Strong Passwords:** The usual – complex, changed often.
* **Multi-Factor Authentication:** Extra hurdles (like an SMS code) in case a password gets stolen.
* **Quick Removal:** Disable access the INSTANT an employee leaves or changes roles.

**Cloud Providers and IAM**

Most cloud providers (like AWS, Google Cloud, etc.) offer IAM tools:

* **Access Groups:** Makes assigning permissions easier. Instead of setting rules for Bob, then Jane, then... you create a "Developer" group with the right access, and add them in one go. 
* **Policies:** These are those detailed rules: "A Developer can access Project X's code, but not the customer database". These make sure your system behaves the way you want, security-wise.

**The Main Point:**  The cloud offers tons of power and flexibility, but without great IAM, all your data is at risk. A well-designed IAM system strikes a balance between ease of use for your team and rock-solid protection of sensitive information. 
* * *
**Cloud Monitoring: Like a Health Checkup for Your Tech**

Imagine your business relies on a bunch of apps and services running in the cloud. Keeping an eye on everything to fix problems FAST is tough.  That's where cloud monitoring comes in.

**What is Cloud Monitoring?**

* It's like a set of sensors watching your cloud system, checking performance, security, and cost.
* It's not just fancy software, it's how you *use* that software to proactively improve your cloud stuff.
**Why Bother?**

* **Catch problems early:**  Know when things slow down BEFORE customers get annoyed.
* **Save money:** Is your cloud setup costing too much? Monitoring helps find waste.
* **Security checkup:** Spot hackers trying to get in or weird behavior inside your systems.
* **Kubernetes Fan?** If you use this (complex but powerful), monitoring is a MUST.

**Tools of the Trade**

* **Infrastructure Monitoring:** Think hardware – are your virtual servers healthy? Is the network okay?
* **Database Monitoring:** Your data is gold. These tools make sure it's safe and running smoothly.
* **Application Performance Monitoring (APM):** This analyzes how well your apps are working for *real users*. Slow loading? Errors? APM finds the cause.

**Best Practices (The Smart Way to Do It)**

* **User Experience is King:** Don't just monitor the tech, see how it feels for actual customers.
* **One Big Dashboard:** If your data is spread out, you'll miss problems. Centralize your monitoring!
* **Track Your Cloud Bill:**  Avoid expensive surprises! Monitoring helps optimize costs.
* **Automate as Much as Possible:** Less manual work = more time to improve stuff.
* **Practice Makes Perfect:**  Simulate outages! Make sure your monitoring actually catches issues.

**Bottom Line:** The cloud is great, but it can get complex. Cloud monitoring is like having an expert technician on-call 24/7, helping you keep things running smoothly and securely. 
* * *
**Cloud Monitoring: Your Cloud's Security Guard & Tech Doctor**

Think of your business as a building running on cloud services. Cloud monitoring is like installing security cameras and sensors, AND hiring a doctor to make sure everything's healthy.

**Why Cloud Monitoring Matters**

* **Avoid Surprises:** Catch problems (slow apps, overloaded systems) BEFORE they break everything.
* **Security Check:** Spot hackers poking around where they shouldn't be.
* **Cloud Bill Control:**  See if you're paying for resources you don't need.

**Key Monitoring Tools**

* **Alarms:**  Bleeps like a smoke alarm if something specific goes wrong (server down, etc.)
* **Logs:**  Basically text records of everything happening – used to troubleshoot weird issues.
* **Metrics:**  Numbers representing performance – think of graphs tracking temperature over time.
* **Events:** Specific things happening that trigger actions (like automatically adding more servers if traffic spikes).
* **Service Monitoring:** Keeps tabs on individual cloud services you use, like load balancing or content delivery.
* **IaC Monitoring:** If you use code to define your cloud setup, monitor that too to catch accidental changes.

**API Calls: The Secret Diary of Your Cloud**

* **Every Interaction Matters:** APIs are how programs talk to cloud services. Tracking every call tells you WHO is doing WHAT.
* **Security Watchdog:** Helps spot suspicious activity that could mean someone's snooping on your data.

**Threats To Look Out For**

* **DDoS Attacks:** Think of this as someone spamming your doorbell to prevent real guests from arriving.
* **Data Breaches:**  Bad guys trying to steal your stored info.
* **Misconfigurations:** Oops, you left the door ajar! It's easy to misconfigure cloud settings by accident.
* **Insider Threats:** Even staff you trust can make mistakes or misuse their access.

**Protecting Yourself**

* **Strong Logins:** Like having good locks on your doors.
* **Encryption:** Scrambles your data, making it useless to thieves.
* **Vulnerability Testing:**  Hire 'good hackers' to try and find weak spots.
* **Watching the Traffic:** Weird patterns can signal an attack is underway.

**The Takeaway:**  You wouldn't run a business without security measures – the same goes for the cloud. Monitoring might seem techy, but it's about having the right information to keep everything safe and running smoothly.
* * *
**Cloud Jobs Are HOT (And Here's Why)**

Companies are going ALL-IN on cloud computing. This means the market for cloud professionals is booming, but finding qualified people is tough. Why?

* **Growth:** The cloud market is growing like crazy, so companies need to hire faster than ever before.
* **Skills Gap:**  Cloud tech can be complex. Not enough people have the right skills for the number of jobs.

**6 In-Demand Cloud Jobs**

1. **Cloud Developer:** These folks build and maintain the actual apps that run in the cloud. Think coding, testing, and being super familiar with cloud providers (like AWS or Azure).

2. **Cloud Integration Specialist:**  Connects new cloud stuff to the company's existing systems.  It's about making everything play nicely together without breaking things.

3. **Cloud Data Engineer:** Manages and designs pipelines to make data usable  in the cloud. They get insights out of massive amounts of info.

4. **Cloud Security Engineer:** Cloud = data heaven for hackers. These experts build fortresses around cloud systems to keep data safe.

5. **Cloud DevOps Engineer:** The bridge between dev teams and operations. They make sure apps get released smoothly and that the cloud setup runs efficiently.

6. **Cloud Architect:** The big-picture designer. They turn vague business needs into a cloud system that actually works. 

**How Can I Get These Skills?**

* **Instructor-led Classes:** Traditional, more focused approach.
* **Online Courses:** Learn at your own pace, lots of choice out there.
* **Videos/Books:** Good for supplementing other learning methods.
* **Cloud Provider Resources:** AWS, Google, etc. often have their own free training portals with tons of info.

**The Takeaway:** If you're into tech and want a job that's in demand, the cloud is a good place to look. Lots of paths to choose from, and resources to help you learn! 
* * *
## Module 5 Glossary: Cloud Security, Monitoring, Case Studies, & Jobs

| Term | Definition |
|---|---|
| Access group | A collection of users and service IDs given the same access rights with one or more policies. |
| Administrative users | Manage instances of apps and services, needing insight into team activity. |
| API keys | Unique codes passed into an API to identify the caller (app or user). |
| Application Performance Monitoring (APM) | Tracks app health and performance, giving tools to fix problems. |
| Application users  | The everyday users of your cloud-based applications. |
| AppSec | Short for Application Security. |
| Audit and compliance | Processes used to check if security controls match policies and regulations. |
| Authentication | Like checking an ID – it allows apps to confirm a user's identity. |
| BYOK | Bring Your Own Keys – you, not the cloud provider, manage encryption keys. |
| Client-side encryption | Scrambling data locally, *before* it's sent to cloud storage.  |
| Cloud directory services | Securely store user profiles, passwords, and access rules in the cloud. |
| Cloud encryption | Protects data, provides access control, and manages encryption keys. |
| Cloud monitoring solutions | Tools to assess data, apps, and infrastructure for performance, risks, etc. |
| Cloud security | The policies, software, and practices used to protect your stuff in the cloud. |
| Database monitoring tools | Help ensure databases are accurate, reliable, and running smoothly. |
| Decryption key | Used to transform encrypted data back into its readable form. |
| Developer users | Have access to sensitive info and can create/update your cloud apps. |
| Encryption | The process of scrambling data to make it unreadable without a key. |
| Encryption algorithm | The rules used to transform data, making it illegible. |
| Encryption at rest | Protects stored data ("at rest" on a hard drive, for example). |
| Encryption in transit | Protects data while it's being sent across networks. |
| Encryption in use | Protects data even when it's being actively used in memory.  |
| Identity and access management (IAM) | Controls who can access which resources within your cloud setup. |
| Infrastructure monitoring tools |  Detect hardware problems and security gaps, alerting for fixes. |
| Key management services | Help organize and control access to encryption keys. |
| KYOK | Keep Your Own Keys – similar to BYOK, you control encryption keys. |
| Multifactor authentication | Requires more than a password (e.g. a code sent to your phone). |
| Reporting | Shows user access patterns - key for spotting unauthorized activity. |
| Server-side encryption | Data is scrambled *after* reaching the cloud server, but before storage. |
| SSL/TLS | Protocols that  secure data on the move while browsing the web, etc. | 
| User and service access management | Lets you automate adding/removing users/services as needed. |

