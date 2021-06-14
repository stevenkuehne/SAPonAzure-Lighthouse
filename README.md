# Delegate a subscription for management purposes to msg services ag
When clicking the following button, Azure Lighthouse will be deployed through an Azure Resource Manager Template. Having completed the onboarding-process, msg services ag is eligible to access onboarded subscriptions for management purposes.

### Requierements:
  - user who performs the deployment/onboarding has appropriate permissions

### Permissions granted
All required roles are defined below.  
Azure built-in roles are also defined [here](https://docs.microsoft.com/en-us/azure/role-based-access-control/built-in-roles)

Role Name | Roledefinition ID
----------|------------------
Contributors | b24988ac-6180-42a0-ab88-20f7382dd24c
Managed Services Registration assignment Delete Role | 91c1777a-f3dc-4fae-b103-61d183457e46
Log Analytics Reader | 73c42c96-874c-492b-b04d-ab87d138a893
Reader | acdd72a7-3385-48ef-bd42-f606fba81ae7
Virtual Machine Contributor | 9980e02c-c2be-4d73-94e8-173b1dc7cf3c
Storage Account Contributor | 17d1049b-9a84-46fb-8f53-869881c3d3ab
Reader and Data Access | c12c1c16-33a1-487b-954d-41c89c60f349
Monitoring Contributor | 749f88d5-cbae-40b8-bcfc-e573ddc772fa
Monitoring Reader | 43d0d8ad-25c7-4714-9337-8ba259a9fe05
Azure Sentinel Contributor | ab8e14d6-4a74-4a29-9ba8-549422addade

### Instructions:
  - click the button "Deploy to Azure"
    --> you will be redirected to the Azure Portal
  - select the correct subscription which needs to be delegated
  - continue with "Review and Create" --> "Create"

<a href="https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Fstevenkuehne%2FSAPonAzure-Lighthouse%2Fmain%2FAzureLighthouse-Onboarding.json">
  <img src="https://aka.ms/deploytoazurebutton"/>
</a>
