# .NET-Web-Application
Description: This repository contains the VamsiWebApplication, a .NET web application that includes sample code, unit tests, CI/CD pipeline configuration using Azure DevOps, ARM templates for provisioning, and instructions for integrating monitoring and logging.

Details Step by Step Implementation of CI/CD is as follows:

1. Continuous Integration (CI): - Azure DevOps pipeline that automatically builds the application upon code commits. 

2. Continuous Deployment (CD): - Configure the pipeline to deploy the application to an Azure App Service. 

3. Infrastructure as Code (IaC): - Use Azure Resource Manager (ARM) templates or Terraform to define and provision the 

4. Monitoring and Logging: - Integrate application monitoring using Azure Application Insights. 

5. Security and Compliance: - Implement security best practices.
 
 Prerequisites:

 * .net sdk INSTALLED ON YOUR LOCAL MACHINE
 * Azure CLI installed
 * Azure DevOps account

 Set Up:

 git clone https://vamsikrishnayadavloya@dev.azure.com/vamsikrishnayadavloya/Vamsi/_git/Vamsi
 cd VamsiWebApplication

 Restrore .NET dependencies:
 dotnet restore
 dotnet build (To build the application)
 dotnet run --project VamsiWebApplication (Run the application in local)

 *Azure DevOps Pipeline Configuration*
 This repository includes a YAML file for configuring an Azure DevOps pipeline to build, test, and deploy the application. "azure-pipelines.yml"

 *Infrastructure as Code (IaC)*
 This repository includes ARM templates for provisioning the necessary Azure resources.

 *Integrating Monitoring and Logging*
Application Insights:

* Navigate to the Azure portal.
* Create an Application Insights resource.
* Add the Application Insights SDK to your application.

dotnet add package Microsoft.ApplicationInsights.AspNetCore
* Update "Program.cs" to include Application Insights.



