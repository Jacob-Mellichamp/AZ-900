#### Dedicated
- Physical server wholly utilized by a single customer
- You have to **guess your capacity, you'll overpay for an underutilized server**
- Multiple apps can result in conflicts in resource sharing. 

#### VMs
![[Pasted image 20220104142210.png]]
- Hypervisor is the software layer that lets you use a VM
- You are pay for a fraction of the server
- You are limited by the Guest Operating System
- **Multiple apps on a single virtual machine can result in conflicts in resource sharing. **

#### Containers
- Virtual Machine running multiple containers
- maximum the utilize the available capacity which is more cost-effective. 
- Your containers share the same underlying OS
- multiple apps can run side by side without being limited to the same OS requirement. 

#### Functions
- Apps broken into snippets of code.

- Managed VM running containers
- **This is Serverless**
- Only resonsible for code and data, nothing else.
- Very Cost-effective, only pay for the time code is running. RMs only run when there is code to be executed. Cold Starts, is a side-effect of this setup. 



#### [[Serverless Services]]