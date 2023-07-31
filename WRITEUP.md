# Write-up Template

### Analyze, choose, and justify the appropriate resource option for deploying the app.

*For **both** a VM or App Service solution for the CMS app:*
- *Analyze costs, scalability, availability, and workflow*
- *Choose the appropriate solution (VM or App Service) for deploying the app*
- *Justify your choice*

**My selection** With this project, I will choose Azure APP Service.
There are several reasons for this choice, but from the previous practical exercises, I found using Azure APP Service to be very straightforward. 
After linking with GitHub, I can quickly build and deploy the app without worrying about installing Python, Flask, or other libraries. 
When using Azure Virtual Machines (VMs), all those installation tasks have to be done manually, which makes it feel a bit cumbersome.

### Assess app changes that would change your decision.

*Detail how the app and any other needs would have to change for you to change your decision in the last section.* 
As I mentioned above, if Azure Virtual Machines (VMs) could provide some support to reduce the tasks related to installing libraries or environments for building and deploying applications, it would be great. However, fundamentally, Azure Virtual Machines (VMs) are infrastructure as a Service (IaaS), so that might not be entirely feasible.

Therefore, I will probably still prioritize choosing Azure APP Service. Unless the project has very stringent hardware requirements, then I might consider using Azure Virtual Machines (VMs).