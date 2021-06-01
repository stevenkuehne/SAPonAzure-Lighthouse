# Delegate a subscription for management purposes to msg services ag
When clicking the following button, Azure Lighthouse will be deployed through an Azure Resource Manager Template. Having completed the onboarding-process, msg services ag is eligible to access onboarded subscriptions for management purposes.

### Requierements:
  - user who performs the deployment/onboarding has appropriate permissions
  - a specific objectID for an Azure AD group has been given to you

### Instructions:
  - Click the Button "Deploy to Azure"
    --> you will be redirected to the Azure Portal
  - make sure to select the correct subscription which needs to be delegated
  - in the textfield "objectID" enter the objectID
  - Continue with "Review and Create" --> "Create"

<a href="https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Fstevenkuehne%2FSAPonAzure-Lighthouse%2Fmain%2FAzureLighthouse-Onboarding.json">
  <img src="https://aka.ms/deploytoazurebutton"/>
</a>
