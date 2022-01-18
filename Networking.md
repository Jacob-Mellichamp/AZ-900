### Azure Network Services

### Virtual Network (vNet) and Subnets
a vNet is a logically isolated section of the Azure Network where you launch your Azure Resources. You choose a range of IPs using CIDR Range. 

![[Pasted image 20220104121002.png]]
**Public Subnets**
- is one that can reach the internet

**Private Subnet**:
- Can't be accessed by the internet. 


### [[Azure DNS]]
- Provides ultra-fast DNS responses and ultra high domain availability
- [[Azure Traffic Manager]]

### Azure Load Balancer
- OSI Level 4 
- Load Balancer
	- ROute traffic based on:
		- IP Address, port, and Desintation IP. 

- used for evenly distributing incoming traffic.
	- Public Load Balancer
		- incoming traffic from the internet to Public IPs. 
	- Internal Load Balancer
		- Incoming internal network traffic 


![[Pasted image 20220104122418.png]]
- [[Scale Sets]]

### Azure Application Gateway
- OSI Level 7
- HTTP Load Balancer
- Can apply a Firewall
- Optimizes app server farm delivery. 
- Enables you to manage traffic to your web aplications. 
	- Can make routing decisions based on additional attributes of an HTTP request. 

![[Pasted image 20220108161430.png]]
### Network security Groups
- virtual firewall at the subnet level. 


### Azure VPN Gateway
- Accesses Azure Virtual Networks through VPN Gateways



### Azure Traffic Manager
- Distributes network traffic across Azure regions worldwide

### Azure ExpressRoute
- Connects to Azure over high-bandwidth dedicated secure connections

##### 

### [[Enterprise Networking Services]]

