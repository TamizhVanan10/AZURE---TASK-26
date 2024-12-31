# AZURE---TASK-26

 ## Kubernetes Services

## 1. Sign in to Azure Portal
Go to Azure Portal and sign in with your Azure credentials.
## 2. Create AKS Cluster
Click on "Create a resource" in the portal.
Search for "Kubernetes Service" and select it.
Click "Create".
## 3. Configure AKS Cluster
Subscription: Choose your subscription.
Resource Group: Select or create a new resource group.
Cluster Name: Enter a name for your AKS cluster.
Region: Choose the desired region.
Node Pool: Configure node pool settings (VM size, count, OS).
Authentication: Choose between Azure Active Directory or SSH for authentication.
Click "Next" and proceed to other optional settings (e.g., networking, monitoring).
## 4. Review and Create
Review your configuration and click "Create".
## 5. Connect to AKS Cluster
Install Azure CLI and kubectl.
Use az aks get-credentials to fetch cluster credentials.
Verify with kubectl get nodes.
## 6. Deploy Applications
Create a Deployment YAML file for your application.
Apply the deployment using kubectl apply -f deployment.yaml.
## 7. Expose Application
Create a Service YAML file (e.g., LoadBalancer) to expose your app.
Apply the service using kubectl apply -f service.yaml.
## 8. Monitor and Manage Cluster
Use Azure Monitor and Azure CLI to manage and scale the cluster as needed.
