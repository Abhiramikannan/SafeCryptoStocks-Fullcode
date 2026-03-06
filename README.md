## SafeCryptoStock – Cloud-Native Stock Market Application

SafeCryptoStock is a cloud-native stock market application deployed on **Microsoft Azure** using a **microservices architecture**.

### Key Features

- Infrastructure provisioned using **Terraform (Infrastructure as Code)**
- Backend services **containerized using Docker**
- Applications deployed on **Azure Kubernetes Service (AKS)**
- **CI/CD pipelines implemented using Azure DevOps** for automated build and deployment
- **Azure Key Vault** used for secure secret management
- Kubernetes **SecretProviderClass** used to inject secrets into pods
- **MongoDB** used as the backend database
- **API Gateway** used for communication between frontend and backend microservices

### Architecture Overview

Frontend → API Gateway → Microservices → MongoDB  
Secrets → Azure Key Vault → AKS Pods  
Infrastructure → Terraform  
Deployment → Azure DevOps Pipelines

### Tech Stack

- Cloud: Microsoft Azure
- Containerization: Docker
- Orchestration: Azure Kubernetes Service (AKS)
- Infrastructure as Code: Terraform
- CI/CD: Azure DevOps
- Database: MongoDB
- Secret Management: Azure Key Vault
