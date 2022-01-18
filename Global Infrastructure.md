### Global Infrastructure
![[Pasted image 20220103143454.png]]
#### Paired Regions
- Each region is paired with another region 300 miles away. 
- Only one region is updated at a time. 
- Some Azure Services rely on Paired Regoins for Disaster Recovery
- Azure Geo-redundant Storage (GRS) replicates data to a secondary region automatically. 


### Availability Zones (AZ)
is physical location made up of one or more datacenters. 

Region will generally contain 3 availability zones
- AZs are isolated from each other, but they will be close enough to provide low-latency

- its common practice to run workloads in at least 3 AZs.

- A combination of a Fault domain and an Update Domain 

**Fault Domain**
A logical grouping of hardware to avoid a single point of failure within an AZ

**Update Domain**
Azure may need to apply updates to the underlying hardware and software

![[Pasted image 20220103150131.png]]

### Region Types and Service Availability 
- Not all Azure cloud services are availabile in every region.
**- Recommended vs Alternate (other)**
	- Recommended
		- most services
	- Other
		- not many....


### Service Groups
**Foundational**: Immediately or in 12 months in Recommeneded

**Mainstream**: when GA immediately or in 12 months in Reommended Regions. May become avilable in Alternate Regions based on customer demand.

**Specialized**: specialized regions to meet compliance or legal reasons
- Us DoD Central
- US Gov Virginia
- US Gov Iowa
- China East
- China North
	- Microsoft does not directly maintain the datacenters. 



