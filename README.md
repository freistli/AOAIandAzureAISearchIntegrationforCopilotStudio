# Azure OpenAI and Azure AI Search Integration for Copilot Studio


## Overview

This POC project provides a low code method to integrate Azure OpenAI with your own data in Copilot Studio. 

![image](https://github.com/user-attachments/assets/4f8df4b5-3f6b-4dba-8e2e-7b1c87027ed2)

It has one customized power workflow to send sepcific [Azure OpenAI On Your Data REST API](https://learn.microsoft.com/en-us/azure/ai-services/openai/references/on-your-data?tabs=rest) to Azure OpenAI,and parse JSON result, return to Copilot Studio with proper format:

### Power Autoflow AOAI Integration
<image src="https://github.com/user-attachments/assets/724523e4-cfcf-4390-9b7c-c610a867c797" width=500px></image>

### Copilot Studio Call AOAI Integration
<image src="https://github.com/user-attachments/assets/00140285-06d2-4c80-a53f-45ba21870ced" width=400px></image>


## Preparation

LLM Model deployment in Azure OpenAI service

Azure AI Search service

Sample Data Files

## Build Index with your own data in Azure AI Search


  1.  Access Azure OpenAI Studio: https://openai.studio-ppe.azure.com/
     
  2.  Select your AOAI resource, click **Deployments**, and then choose your Model. For demo purpose, it is gpt-4o here.
   
  <image src="https://github.com/user-attachments/assets/a4af8c65-4365-4fe9-8a26-040c60581a97" width=500px></image>     
     
  3. Click gpt-4o, and then click Open Playground

  <image src="https://github.com/user-attachments/assets/a0905ef7-7ee0-485f-bc72-f5f3bbdf58f7" width=300px></image>
   
  4. Click **Add your data** -> **Add a data source**, if you haven't created Azure AI Search index with this wizard before, can choose data soruce such as **Azure Block Storage** or **Upload files**, the wizard will give you some fields to input Azure AI Search settings. Below are snapshots for each wizard step, can be skipped you are familar with create the index with your data in the playground.

  <image src="https://github.com/user-attachments/assets/4bdd688e-d65a-4578-84e5-50e1ab14153a" width=500px></image>


  <image src="https://github.com/user-attachments/assets/8aff9e26-2730-4b0a-a684-501575c8647e" width=500px></image>


  <image src="https://github.com/user-attachments/assets/53e7ea94-b4b8-45f0-96bb-25e567c2ed06" width=500px></image>


  <image src="https://github.com/user-attachments/assets/410731fb-0485-49f3-8e14-8b7136fda561" width=500px></image>

  
  <image src="https://github.com/user-attachments/assets/357c80cf-af73-4f09-ad3f-a8bcf848998a" width=500px></image>
  

  For more information about adding data source, can check: [Chat with Azure OpenAI models using your own data](https://learn.microsoft.com/en-us/azure/ai-services/openai/use-your-data-quickstart?tabs=typescript%2Ccommand-line%2Cpython-new&pivots=programming-language-studio)
  
  5. 

     

