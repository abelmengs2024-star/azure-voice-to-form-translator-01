      Azure Voice-to-Form Translator

A cloud-based patient intake solution built using Microsoft Azure.

The application allows a user to speak patient information, converts the
speech to text, translates it into English, processes the information,
and stores the resulting documents securely in Azure.

Technologies Used

- Microsoft Azure
- Azure App Service
- Azure Functions
- Azure Blob Storage
- Azure Speech Service
- Azure Translator
- Azure API Management
- Azure Application Gateway
- Web Application Firewall
- Azure Traffic Manager
- Microsoft Entra ID
- Azure Key Vault
- Azure Monitor / Application Insights

 Architecture

voicetoform-Architecture.png 

The project uses a multi-region Azure architecture with Canada Central
as the primary region and Canada East as the secondary region.

Traffic Manager provides failover between the two regions.

 What I Learned

This project gave me hands-on experience with:

- Deploying cloud applications
- Configuring Azure networking
- Using serverless Azure Functions
- Securing applications with WAF and Key Vault
- Implementing API Management
- Configuring high availability
- Monitoring Azure resources
- Troubleshooting cloud services
