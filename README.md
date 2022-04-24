# Learning Azure

This is a collection of resources to learn Azure and prepare for certifications. 

:pushpin: *By default, all the resources are free unless it's specified.*

## Azure general resources and tools:
* [Azure Architecture browser](https://docs.microsoft.com/en-us/azure/architecture/browse/): Microsoft architecture diagrams and descriptions for common workloads.
* [Azure Architecture Center](https://docs.microsoft.com/azure/architecture/): Guidance for architecting solutions on Azure using established patterns and practices.
* [Microsoft 30 days to learn it](https://developer.microsoft.com/offers/30-days-to-learn-it): Free courses with sandboxed test environments
* [Microsoft Cloud Adoption Framework for Azure](https://docs.microsoft.com/azure/cloud-adoption-framework/): Guidance and best practices to adopt cloud.
* [Microsoft Azure Well-Architected Framework](https://docs.microsoft.com/azure/architecture/framework/): Set of guiding tenets that can be used to improve the quality of a workload
* [Microsoft Learning Github](https://github.com/MicrosoftLearning): Set of labs for the Azure certifications.
* [Microsoft virtual training days](https://www.microsoft.com/es-es/training-days) (Spain): Free virtual training events in Spain.

## Microsoft AZ-104 certification
### Certification overview
* [Microsoft official site](https://docs.microsoft.com/en-us/learn/certifications/exams/az-104)


| Study areas | Weight |
|---|---|
| Manage Azure identities and governance | 15-20% |
| Implement and manage storage | 15-20% |
| Deploy and manage Azure compute resources | 20-25% |
| Configure and manage virtual networking | 25-30% |
| Monitor and back up Azure resources | 10-15% |

*Full detail of the skills measured [here](https://query.prod.cms.rt.microsoft.com/cms/api/am/binary/RE4pCWy).*


Study resources:

* [AZ-104 Microsoft Azure Administrator Labs](https://microsoftlearning.github.io/AZ-104-MicrosoftAzureAdministrator/)
* John Savill YouTube videos:
  * [AZ-104 Azure Administrator Study List](https://www.youtube.com/playlist?list=PLlVtbbG169nGlGPWs9xaLKT1KfwqREHbs)
  * [AZ-104 Azure Administrator Study Cram](https://www.youtube.com/watch?v=VOod_VNgdJk&list=PLlVtbbG169nGlGPWs9xaLKT1KfwqREHbs&index=2&t=995s)
* [Microsoft AZ104 sample questions](https://query.prod.cms.rt.microsoft.com/cms/api/am/binary/RWSOFn)
* [Examtopics AZ-104 practice exam](https://www.examtopics.com/exams/microsoft/az-104/)

### Prerequisites for Azure administrators

* [Prerequisites for Azure administrators](https://docs.microsoft.com/en-us/learn/paths/az-104-administrator-prerequisites/) (Microsoft Learn)
* John Savill videos:
  * [What IS Microsoft Azure?](https://www.youtube.com/watch?v=_x1V2ny8FWM&list=PLlVtbbG169nGlGPWs9xaLKT1KfwqREHbs&index=4)
  * [Microsoft Azure Master Class Part 1 - Cloud Foundation](https://www.youtube.com/watch?v=aHJe0qBqwmk&list=PLlVtbbG169nGlGPWs9xaLKT1KfwqREHbs&index=6)
  * [Master the Azure Pricing Calculator](https://www.youtube.com/watch?v=rMKmbZ1SYQg&list=PLlVtbbG169nGlGPWs9xaLKT1KfwqREHbs&index=7)
  * [Understanding Microsoft Azure Availability Zones!](https://www.youtube.com/watch?v=4nDRvZR2EjU&list=PLlVtbbG169nGlGPWs9xaLKT1KfwqREHbs&index=16&t=55s)
* Microsoft Learning Labs:
  * [Manage Azure resources by Using the Azure Portal](https://microsoftlearning.github.io/AZ-104-MicrosoftAzureAdministrator/Instructions/Labs/LAB_03a-Manage_Azure_Resources_by_Using_the_Azure_Portal.html)
  * [Manage Azure resources by Using ARM Templates](https://microsoftlearning.github.io/AZ-104-MicrosoftAzureAdministrator/Instructions/Labs/LAB_03b-Manage_Azure_Resources_by_Using_ARM_Templates.html)
  * [Manage Azure resources by Using Azure PowerShell](https://microsoftlearning.github.io/AZ-104-MicrosoftAzureAdministrator/Instructions/Labs/LAB_03c-Manage_Azure_Resources_by_Using_Azure_PowerShell.html)
  * [Manage Azure resources by Using Azure CLI](https://microsoftlearning.github.io/AZ-104-MicrosoftAzureAdministrator/Instructions/Labs/LAB_03d-Manage_Azure_Resources_by_Using_Azure_CLI.html)


### Manage Azure identities and governance

Topics to study:
* Manage Azure Active Directory (Azure AD) objects
* Manage role-based access control (RBAC)
* Manage subscriptions and governance

Study resources:
* [Manage identities and governance in Azure](https://docs.microsoft.com/en-us/learn/paths/az-104-manage-identities-governance/) (Microsoft Learn)
* John Savill videos:
  * [Microsoft Azure Master Class Part 2 - Identity](https://www.youtube.com/watch?v=Jd3IzN9x2as&list=PLlVtbbG169nGlGPWs9xaLKT1KfwqREHbs&index=8)
  * [The Line Between AD and Azure AD](https://www.youtube.com/watch?v=uts0oy8NlUs&list=PLlVtbbG169nGlGPWs9xaLKT1KfwqREHbs&index=9)
  * [What are Azure AD External Identities?](https://www.youtube.com/watch?v=9P10hgPDRZg&list=PLlVtbbG169nGlGPWs9xaLKT1KfwqREHbs&index=10)
  * [Azure AD Administrative Units Overview](https://www.youtube.com/watch?v=1-x86jJuK7c&list=PLlVtbbG169nGlGPWs9xaLKT1KfwqREHbs&index=11)
  * [Microsoft Azure Managed Identity Deep Dive](https://www.youtube.com/watch?v=rC1TV0_sIrM&list=PLlVtbbG169nGlGPWs9xaLKT1KfwqREHbs&index=13)
  * [Microsoft Azure Master Class Part 3 - Governance](https://www.youtube.com/watch?v=cIh_Nfl67T0&list=PLlVtbbG169nGlGPWs9xaLKT1KfwqREHbs&index=14)
  * [Azure Role-Based Access Control Deep Dive](https://www.youtube.com/watch?v=qFoHDTxkQII&list=PLlVtbbG169nGlGPWs9xaLKT1KfwqREHbs&index=15)
* Microsoft Learning Labs:
  * [Manage Azure Active Directory Identities](https://microsoftlearning.github.io/AZ-104-MicrosoftAzureAdministrator/Instructions/Labs/LAB_01-Manage_Azure_AD_Identities.html)
  * [Manage Subscriptions and RBAC](https://microsoftlearning.github.io/AZ-104-MicrosoftAzureAdministrator/Instructions/Labs/LAB_02a_Manage_Subscriptions_and_RBAC.html)
  * [Manage Governance via Azure Policy](https://microsoftlearning.github.io/AZ-104-MicrosoftAzureAdministrator/Instructions/Labs/LAB_02b-Manage_Governance_via_Azure_Policy.html)

### Implement and manage storage

Topics to study:
* Secure storage
* Manage storage
* Configure Azure files and Azure Blob Storage

Study resources:
* [Implement and manage storage in Azure](https://docs.microsoft.com/en-us/learn/paths/az-104-manage-storage/) (Microsoft Learn)
* [Microsoft Azure Master Class Part 5 - Storage](https://www.youtube.com/watch?v=ZNuzmUKt6IE&list=PLlVtbbG169nGlGPWs9xaLKT1KfwqREHbs&index=18&t=1s) (John Savill)
* Microsoft Learning Labs:
  * [Manage Azure Storage](https://microsoftlearning.github.io/AZ-104-MicrosoftAzureAdministrator/Instructions/Labs/LAB_07-Manage_Azure_Storage.html)

### Deploy and manage Azure compute resources

Topics to study:
* Automate deployment of virtual machines (VMs) by using Azure Resource Manager templates
* Configure VMs
* Create and configure containers
* Create and configure Azure App Service

Study resources:
* [Deploy and manage Azure compute resources](https://docs.microsoft.com/en-us/learn/paths/az-104-manage-compute-resources/) (Microsoft Learn) 
* John Savill videos:
  * [Microsoft Azure Master Class Part 7 - VMs and VMSS](https://www.youtube.com/watch?v=LLhzCgIJMdo&list=PLlVtbbG169nGlGPWs9xaLKT1KfwqREHbs&index=21)
  * [Creating your first VM in Azure](https://www.youtube.com/watch?v=K-FQXgVZyl0&list=PLlVtbbG169nGlGPWs9xaLKT1KfwqREHbs&index=22)
  * [Microsoft Azure Master Class Part 8 - Application Services](https://www.youtube.com/watch?v=_E73_SQN8ZU&list=PLlVtbbG169nGlGPWs9xaLKT1KfwqREHbs&index=23)
  * [DevOps Master Class - Part 7 - Containers & Friends](https://www.youtube.com/watch?v=r6YIlPEC4y4&list=PLlVtbbG169nGlGPWs9xaLKT1KfwqREHbs&index=24)
* Microsoft Learning Labs:
  * [Manage Virtual Machines](https://microsoftlearning.github.io/AZ-104-MicrosoftAzureAdministrator/Instructions/Labs/LAB_08-Manage_Virtual_Machines.html)
  * [Implement Web Apps](https://microsoftlearning.github.io/AZ-104-MicrosoftAzureAdministrator/Instructions/Labs/LAB_09a-Implement_Web_Apps.html)
  * [Implement Azure Container Instances](https://microsoftlearning.github.io/AZ-104-MicrosoftAzureAdministrator/Instructions/Labs/LAB_09b-Implement_Azure_Container_Instances.html)
  * [Implement Azure Kubernetes Service](https://microsoftlearning.github.io/AZ-104-MicrosoftAzureAdministrator/Instructions/Labs/LAB_09c-Implement_Azure_Kubernetes_Service.html)

### Configure and manage virtual networking

Topics to study:
* Implement and manage virtual networking
* Secure access to virtual networks
* Configure load balancing
* Monitor and troubleshoot virtual networking
* Integrate an on-premises network with an Azure virtual network

Study resources:
* [Configure and manage virtual networks for Azure administrators](https://docs.microsoft.com/en-us/learn/paths/az-104-manage-virtual-networks/) (Microsoft Learn)
* John Savill videos:
  * [Microsoft Azure Master Class Part 6 - Networking](https://www.youtube.com/watch?v=K8ePZdLfU7M&list=PLlVtbbG169nGlGPWs9xaLKT1KfwqREHbs&index=19)
  * [AZ-700 Designing and Implement Azure Networking Study SUPER Guide](https://www.youtube.com/watch?v=nVZYDhB_M64&list=PLlVtbbG169nGlGPWs9xaLKT1KfwqREHbs&index=20&t=1s)
* Microsoft Learning Labs:
  * [Implement Virtual Networking](https://microsoftlearning.github.io/AZ-104-MicrosoftAzureAdministrator/Instructions/Labs/LAB_04-Implement_Virtual_Networking.html)
  * [Implement Intersite Connectivity](https://microsoftlearning.github.io/AZ-104-MicrosoftAzureAdministrator/Instructions/Labs/LAB_05-Implement_Intersite_Connectivity.html)
  * [Implement Traffic Management](https://microsoftlearning.github.io/AZ-104-MicrosoftAzureAdministrator/Instructions/Labs/LAB_06-Implement_Network_Traffic_Management.html)


### Monitor and back up Azure resources

Topics to study:
* Monitor resources by using Azure Monitor
* Implement backup and recovery

Study resources:
* [Monitor and back up Azure resources](https://docs.microsoft.com/en-us/learn/paths/az-104-monitor-backup-resources/) (Microsoft Learn)
* John Savill videos:
  * [Microsoft Azure Master Class Part 9 - Monitoring and Security](https://www.youtube.com/watch?v=hTS8jXEX_88&list=PLlVtbbG169nGlGPWs9xaLKT1KfwqREHbs&index=25)
  * [Azure Security Center and Azure Sentinel Overview (AZ-500)](https://www.youtube.com/watch?v=rE-qgIgDCq8&list=PLlVtbbG169nGlGPWs9xaLKT1KfwqREHbs&index=26)
  * [Microsoft Azure Master Class Part 4 - Resiliency](https://www.youtube.com/watch?v=zLMXu4rtlEk)
* Microsoft Learning Labs: 
  * [Backup virtual machines](https://microsoftlearning.github.io/AZ-104-MicrosoftAzureAdministrator/Instructions/Labs/LAB_10-Implement_Data_Protection.html)
  * [Microsoft Azure Master Class Part 4 - Resiliency](https://www.youtube.com/watch?v=zLMXu4rtlEk&list=PLlVtbbG169nGlGPWs9xaLKT1KfwqREHbs&index=15&t=86s)
  * [Disaster Recovery in Microsoft Azure](https://www.youtube.com/watch?v=8fvO3WArG-Y&list=PLlVtbbG169nGlGPWs9xaLKT1KfwqREHbs&index=17&t=711s)
  * [Implement Monitoring](https://microsoftlearning.github.io/AZ-104-MicrosoftAzureAdministrator/Instructions/Labs/LAB_11-Implement_Monitoring.html)

