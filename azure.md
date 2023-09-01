## HHA504 Assignment 1 : Intro to Azure

### **Storage**
- Azure Backup: A backup service that allows users to backup files, folders, and databases that is cost-effective, simple, and secure to use. Users can backup Windows/Linux VMs, Azure managed disks, Azure file shares, SQL server and SAP HANA databases running on Azure VMs, and Azure PostgreSQL databaases. Advantages of the service includes on-premises backup to the cloud, independent and isolated backups to guard against accidental destruction of data, scalability, unlimited data transfer, centralized monitoring and management, and various storage option. This service can possibly interact with Python through the use of the Azure Python SDK and appropriate scripts. 

- Azure Files: Allows for fully managed file shares that can be mounted on either the cloud or on-premises. It is compatible across Windows, Linus, and macOS environments and offers several advantages, such as simplified cloud development, shared access, resiliency, simple to use, diagnostic share, and scripting and tooling. Azure Files can interact with Python using the Azure Storage SDK for Python. This can be done by pip installing azure-storage-file-share via PyPI. 
---

### **Compute**
- Azure Functions: A serverless compute service that allows users to code without having to worry about maintaining infrastructure and deployment. This service provides user with the tools and resources to keep their applications running. Compatible languages includes C#, Java, JavaScript, PowerShell, and Python. Azure Functions can integrate with development tools such as Visual Studio Code and Maven for depolyments and debugging and provides various hosting options. Functions is compatible with Python and can be used through Visual Studio Code with the Azure Functions extension or the command line.  
- App Service: App service is HTTP-based for hosting web applications, REST APIs, and mobile back end. It is compatible with multiple languages and frameworks, such as ASP.NET, ASP.NET Core, Java, Ruby, Node.js, PHP, and Python. Key features includes a managed production environment, DevOps optimization, scalability, security, authentication, integration with Visual Studio and Visual Studio Code, and Java integration tools. This service can interact with Python by deploying a Python web application, such as Flask or Django. 
  
---

### **Databases**
- Azure Cosmos DB: A NoSQL database for app development that is fully managed, fast, and instantly scalable. Features include fast speeds with global read and write latencies, simplified application development, and a cost-effective fully managed database service. Azure Cosmos DB can be used with Python through Python SDK. 
- Azure SQL Database: A fully managed SQL database engine that can upgrade, patch, backup, and monitor without user involvement. It includes various service (general purpose, business critical, or hyperscale) and compute (provisioned compute or serverless compute) tiers and purchasing (vCore-based purchasing or  DTU-based purchasing) and deployment (single database or elastic pool) models. This service also include advanced monitoring and alerting features, advanced security and threat protection, query procesing, and data encryption. For python interaction, the pyodbc driver can be installed in Visual Studio Code to connect to the Azure SQL database. 
