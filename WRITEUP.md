# Write-up Template

### Analyze, choose, and justify the appropriate resource option for deploying the app.

*For **both** a VM or App Service solution for the CMS app:*
- *Analyze costs, scalability, availability, and workflow*
- *Choose the appropriate solution (VM or App Service) for deploying the app*
- *Justify your choice*
In my opinion, I will choose the App Service, these some point that I choose it:
-Costs: It very clearly that App service will provide services with cost is cheaper than VM.
-App service is lightweight, easily deploy, build and scale
-Support multiple languages: .net, python, java, node, ...
-The VM need to manage software, update, security, ...

### Assess app changes that would change your decision.

*Detail how the app and any other needs would have to change for you to change your decision in the last section.* 
If my app need to scale in the future, i will consider choose VM. 
VM have many approach for the compute, network(traffic).
And if I have a plan develop other service with a non-support language in app service  I need to use VM to setup my programming language to deploy.