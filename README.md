# SentinelAzureOpenAIQueryCheck
This repository provides summarization Schedule Analytics Rules in Sentinel Incident
![image](https://github.com/hisashin0728/SentinelAzureOpenAIQueryCheck/assets/55295601/bd462bab-37ed-4c1e-8cf3-ae141a2706b7)

# Deploy
> Push to the deploy Azure!
[![Deploy to Azure](https://aka.ms/deploytoazurebutton)](https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Fhisashin0728%2FSentinelAzureOpenAIQueryCheck%2Fmain%2FSentinelKQLAnalysisAOAI.json)

# Image
> Here is a image about flow of Logic Apps
<img width="293" alt="image" src="https://github.com/hisashin0728/SentinelAzureOpenAIQueryCheck/assets/55295601/ddc6b831-3fc0-44fe-84f1-ae4f9c321b8d">

# Requirement
- Apply the following role for Managed Identity of logic apps
  - Microsoft Sentinel Responder Role
  - Azure OpenAI User Role
- Update RESTAPI URI of POST to Azure OpenAI
  - Azure OpenAI endopont
  - Azure OpenAI DeployModule
