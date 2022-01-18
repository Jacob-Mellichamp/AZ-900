### Microsoft Trust Center
- Public web  Knowledge base to learn about various microsoft services. 

#### Azure Security Compliance Programs
- HIPAA, PIPEDA, FIPS-140-2 Compliant, NIST 800-53, GDPR
- boy there are alot of compiliance programs


### [[Azure Authentication]]

#### [[Active Directory]]
#### [[MFA]]

#### [[Azure Security Center]]
unified infrastructure security management system.
![[Pasted image 20220104151145.png]]
Tells you how compliant you are with security policies. 


#### [[Key Vault]]
- Helps you safeguard cryptographic keys and other secrets 
- Secrets Management
- Key Management
- Certificiate Managment
- Hardware Security Module
	- is a literal piece of hardware designed to store encryption keys. It's not written to disk, only in memory. 


#### [[Azure Sentinel]]


#### Azure DDoS Protection
![[Pasted image 20220104151621.png]]
![[Pasted image 20220104151711.png]]

#### Azure Firewall
- Mangaged cloud based network security service. Protects Virtual Network. 
- Point of entry for all traffic into the VNet
- Log application policies across subscriptions and virtual networks. 
- Uses a static public IP adddress 
- span multiple AZs for increased availability
	- no additional cost for firewall deployed in AZ

### Azure Information Protection (AIP)
- Protects sensitive Informantion. 
- 'Protect Button' that will encrypt important things in a document. 

### Azure Applicaiton Gateway
- OSI level 7 
- re-reuote traffic based on a set of rules. 
- WAF can be attached for addition protection on OSI layer 7
- ![[Pasted image 20220104152125.png]]

### Advanaced Threat Protection (ATP)  
![[Pasted image 20220104152341.png]]

- Intrustion Detection System
	- View 
- Intrustion Protection System
	- Takes action. 

cloud based security solution that leverages on-premises Active Direcotry. Signals to identify and detect malicious insider actions. 


#### Microsoft Security Development Lifecycle (SDL)
- A mondatory policy since 2004. SDL has played a critical role in embedding security and privacy in microsoft software. 
![[Pasted image 20220104152458.png]]

### [[Azure Polices]]
- A service that Azure uses to enable policies and control resources.
- Stay compliant with corporate standards.
- Initiatives:
	- Groups of related individual policies
- Azure Policy can automatically remediate noncompliant resources and configurations. 
###### Creating Policies
1. create a policy definition
2. Assign the definition to resources
3. Review the evaluation results.
![[Pasted image 20220104152551.png]]

#### Azure RBAC (Role Based Access Control)
- A concept of how access is given. 
- " Manages who has access to Azure resources"
	- **Role Assignments**
		- Security Principal: represents the identities requesting access to resource
			- User
			- Group
			- Service Principal (A security identity used by applications)
			- Managed Principal
		- Scope: Set of Resources that access for the Role Assignment applies to. 
		- Role Definition: is a collection of permissions, is a collection of permissions

![[Pasted image 20220105083423.png]]
Image of Role Definitions

Use Azure RBAC when you need to:

-   Allow one user to manage VMs in a subscription and another user to manage virtual networks.
-   Allow a database administrator group to manage SQL databases in a subscription.
-   Allow a user to manage all resources in a resource group, such as virtual machines, websites, and subnets.
-   Allow an application to access all resources in a resource group.

#### Lock resources
- as an admin, you may need to lock a subscription, resource group, or resrouce. Azure Portal can set the following lock levels:
	- CanNotDelete (Delete)
		- authorized users can still read/ modify but they can't delete the resource
	- ReadOnly(Read-only)
		- authorized users can read a resource, but they can't delete or update the resource. 

##### Management Groups
- managing accounts into a hierarchal structure.
- subscriptions = accounts. 
- 'Root Management group'

![[Pasted image 20220105083656.png]]
- inherit conditions from upper levels. 

#### Azure Monitor
- comprehensive solution for collecting, analyzing, and acting on telemetry from the cloud and on-premises environments. 
- ![[Pasted image 20220105083842.png]]
- Create visual dashboards
- smart alerts 
- log monitoring


### Service Health
- Information about current and upcoming issues such as:
	- impacting events
	- planned maintenance
	- other changes that may affect your availability. 

- Azure Status infroms you of service outages in Azure
- Azure service health, a personalized view of the health of the Azure services and regions you're using. 
- Azure resource health information about the health of individal cloud resrouces

- ![[Pasted image 20220105084156.png]]
- can be found in azure montior


### Azure advisor
- personalized cloud consultant that helps you follow best practices to optimize your azure deployments.
- Subscriptions for the following 5 categories.
	- high availability
	- security
	- performance cost
	- operational excellence 


#### SLAs
- Service Level agreement (SLA) describes Azure's commitments for uptime and connectivity. 
- Uptime and connectibity is described as performance targets. 

- Performance Target is represented as a percentage. 
- the higher the better. 



