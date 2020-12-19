# Azure Fundamentals

This contains notes taken based on the skills definition for the azure fundamentals exam. Although not thoroughly comprehensive it's intended to define/state some concepts that may not be clearly defined. This is only 
intended for study purposes:

### Describe Cloud Concepts


##### **Identify the benefits and considerations of using cloud services**

* **Identify the benefits of cloud computing, such as High Availability, Scalability, Elasticity,
  Agility, and Disaster Recovery.**

  *High Availability*: _Depending on the service-level agreement (SLA) that you choose, your cloud-based apps can provide a continuous user experience with no apparent downtime, even when things go wrong._
  
  *Scalability*:
    - *Vertically*: *Computing capacity can be increased by adding RAM or CPUs to a virtual machine.*
    - *Horizontally*: *Computing capacity can be increased by adding instances of a resource, such as adding more      virtual machines to your configuration.*
  
  *Elasticity*: *You can configure cloud-based apps to take advantage of autoscaling, so your apps always have the resources they need.*

  *Agility*: *Deploy and configure cloud-based resources quickly as your app requirements change.*

* **Difference between Capital Expenditure(CapEx) and Operation Expenditure(OpEx).**

  *CapEx is the upfront money spent on infrastructural development while OpEx is money spent on resources used now and being billed immediately.*

  *CapEx requires ongoing and support expenditures while OpEx is only responsible for computing resources it uses.*

* **Describe consumption based model.**

  *End users only pay for resources they use. No upfront cost is required and users also have the ability to add more computing resources as they go along.*

##### **Describe the differences between categories of cloud services**

* **Describe the shared responsibility model.**
   
   *A shared responsibility model is a cloud security framework that dictates the security and availability obligations of a cloud computing provider and its users to ensure accountability.*

* **Examples of cloud service models.**

  *Virtual Machine's ---> IaaS, Azure App Services ---> PaaS, Office 365 --> SaaS*


### Describe Core Azure Services

  **_Regions:_** *A region is a geographical area on the planet that contains at least one but potentially multiple datacenters that are nearby and networked together with a low-latency network.*

  **_Region pairs:_** *Each Azure region is always paired with another region within the same geography (such as US, Europe, or Asia) at least 300 miles away. This helps for replication and failover.*

  **_Availability Zones:_** *Availability zones are physically separate datacenters within an Azure region. Each availability zone is made up of one or more datacenters equipped with independent power, cooling, and networking.*

  **_Resource groups:_** *These are logical containers in Azure that house various related resources.*

  **_Resources:_** *A single unit of a manageable item found in unit, e.g VM's, virtual networks, webApps etc.*

  **_Subscriptions:_** *A subscription provides you with authenticated and authorized access to Azure products and services. It also allows you to provision resources. An Azure subscription is a logical unit of Azure services that links to an Azure account, which is an identity in Azure Active Directory (Azure AD) or in a directory that Azure AD trusts.*

  **_Management Groups:_** *This a scope level above subscriptions they help in managing policies, compliance etc across various subscriptions. They can support up to 6 level of depth.*

  **_Azure Resource Manager:_** *Azure Resource Manager is the deployment and management service for Azure. It provides a management layer that enables you to create, update, and delete resources in your Azure account.*

  **_Tenant:_** *A tenant represents an organization in Azure Active Directory. It's a dedicated Azure AD service instance that an organization receives and owns when it signs up for a Microsoft cloud service such as Azure, Microsoft Intune, or Microsoft 365. Each Azure AD tenant is distinct and separate from other Azure AD tenants.*
