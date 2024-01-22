# Azure Serverless Resume API

Create an [API](https://learn.microsoft.com/training/modules/build-api-azure-functions/3-overview-api) with Azure Function that displays your resume information in json. 

## Architecture 

![diagram](diagram.png)

## Learning DevOps Skills with this Project

Embarking on this project provides me with a hands-on opportunity to enhance my DevOps skills, incorporating various tools and practices commonly used in modern cloud development. Here's why this project is valuable for me as someone looking to learn new DevOps skills

- Real-world Scenario
- Toolchain Integration
- Infrastructure as Code (IaC)
- Continuous Integration and Continuous Deployment (CI/CD)
- Cloud Services
- Collaboration and Version Control
- Troubleshooting and Debugging


## Prerequisites
- Azure account
- GitHub account
- Visual Studio Code
- Docker
- Visual Studio Code Dev Container Extension

## Setup
**Fork Repository** 
- Fork the repository to have your own copy.

**Codespaces (Optional)**
- Create Codespaces on the main branch (GitHub Codespaces).

**Local Development**
- Clone the code and open it with VS Code.
- Launch the dev container using the VS Code Dev Container Extension.

**Azure Authentication**
- Log into your Azure account using az login --use-device-code.
- Set your desired Azure subscription with az account set --name "name-of-subscription".

**Azure Resources**
- Deploy resources to Azure using Bicep templates in the infra folder.

**Upload Resume to Blob Container**
- Use Azure CLI to upload myresume.json to the newly created blob container.

**Configure Local Settings**
- Update local.settings.json with the Storage Account Connection String.

**Run and Debug**
- Run and debug your function in your environment or using func start host in the terminal.

**CI/CD Setup**
- Update GitHub Actions configuration in .github/build.yml.
- Create a secret AZURE_FUNCTIONAPP_PUBLISH_PROFILE in GitHub with your Function's Publish Profile.

**Run CI/CD Workflow**
- Manually trigger the GitHub Actions workflow.

**View API**
- Access your resume API using tools like curl, a browser, or ThunderClient in VS Code.


