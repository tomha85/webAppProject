# Selection App Service Vs Virtual Machine

# App Service

Azure App Service is an HTTP-based service for hosting web applications, REST APIs, and mobile back ends. It is a Platform as a Service (PaaS) that allows a developer to focus on the application while Azure takes care of the infrastructure.

# Benefits of using an App Service are:

Support of multiple languages, such as .NET, .NET Core, Java, Ruby, Node.js, PHP, or Python
High availability, auto-scaling, and support of both Linux and Windows environments.
Continuous deployment model using GitHub, Azure DevOps, or any Git repo.
Vertical or Horizontal scaling. Vertical scaling increases or decreases resources allocated to our App Service, such as the amount of vCPUs or RAM, by changing the App Service pricing tier. Horizontal scaling increases or decreases the number of Virtual Machine instances our App Service is running.
You can set the amount of hardware allocated to host your application, and the cost varies based on the plan you choose. There are three different tiers - Dev/Test, Production, and Isolated. 

# Some limitations:

Limited access to the host server, so you are unable to control the underlying OS or install software on the server.
Paying for the service plan, even if your services or application isn’t running.
There are hardware limitations, such as a maximum of 14GB of memory and 4 vCPU cores per instance

# Azure Virtual Machines (VMs) provide infrastructure as a service (IaaS) by allowing you to create and use virtual machines in the cloud.

VMs allow you full access and control of the VM.
Lower up-front cost compared to purchasing and maintaining hardware.
Support of both Linux and Windows VMs.
Multiple types to choose from, such as compute or memory-optimized VMs, along with varying amounts of CPU, RAM, and storage.
VMs allow for the installation of custom images and are an excellent choice for migrating from an on-premises server to the cloud.
Multiple VMs can be grouped to provide high availability, scalability, and redundancy. There are two options when it comes to scaling—Virtual Machine Scale Sets and Load Balancers. These will be covered in a different course.

# Limitations of VMs are:

They are more expensive
They can be more time consuming for the developer than other compute options
App Service

# Conclusion 
It depends on situations and applications Here is small application. So, App service is good choice

Deploying a series of lightweight APIs

Less concern about scaling up processing power

Cost-consciousness

I choose App service for deployment

# Result
Link http://tomwebbapp.azurewebsites.net/login

![image](https://user-images.githubusercontent.com/31414852/164993584-98eeafa6-f649-41ad-ab2b-115eb32deb90.png)

![image](https://user-images.githubusercontent.com/31414852/164993671-60b51f0f-2f72-4b23-8108-49905ee914d4.png)

![image](https://user-images.githubusercontent.com/31414852/164993733-0dfc5da1-5804-4c3a-9204-8d576c624fd1.png)

![image](https://user-images.githubusercontent.com/31414852/164993752-9662dadb-34a6-41c2-80d3-93f492695b2f.png)



