---
title: Anthropic

permalink: platform/instructions/en/latest/Actions/anthropic

---

<base target="_blank">
<container>

**Overview**
 
Claude by Anthropic is an advanced language model designed to assist developers in generating high-quality text. Developed by AI researchers, Claude provides a strong foundation for natural language understanding and generation, enabling innovative applications and advancements in AI language technology
 
The Kore.ai XO Platform allows you to easily connect your Anthropic models that can be used across Generative AI features in the platform.

</container>

<container>

**Authorization**
 
To connect to Anthropic, Kore.ai uses basic authentication. The end-user can use pre-authorized credentials provided by the developer during the configuration process. API requests require that an API key be passed in an X-API-Key header. New API keys can be generated via the console. Both of Anthropic's SDKs accept an API key when you instantiate the client object.

**Pre-authorize the Integration**
 
 To make the integration process smoother for customers, you can pre-authorize it by providing the necessary authorization credentials to obtain the access token.

**Basic**
 
1. There are a few pre-requisites before you can setup the integration.
 
   a. An Azure subscription
 
   b. Access granted to Azure OpenAI in the desired Azure subscription
 
   c. An Azure OpenAI resource with a model deployed.
 
2. Following details are required to enable the integration.
 
   a. ENDPOINT : This value can be found in the Keys & Endpoint section when examining your resource from the Azure portal. Alternatively, you can find the value in       Azure OpenAI Studio > Playground > Code View. An example endpoint is: docs-test-001.openai.azure.com
  
   b. API-KEY : This value can be found in the Keys & Endpoint section when examining your resource from the Azure portal. You can use either KEY1 or KEY2.
 
   c. DEPLOYMENT-NAME : This value will correspond to the custom name you chose for your deployment when you deployed a model. This value can be found under Resource       Management > Deployments in the Azure portal or alternatively under Management > Deployments in Azure OpenAI Studio. 
 
   Note: You can also refer to the Azure documentation for [more details](https://learn.microsoft.com/en-us/azure/cognitive-services/openai/quickstart?pivots=rest-api).
 
**Allow Users to Authorize the Integration**
 
This method requires the end user to provide credentials during the conversation for authorization.
 
**Basic**
 
1. Select All Users to Authorize the Integration.
 
2. Click Select Authorization.
 
3. Select Create New.
 
4. Select the type of authorization mechanism. 
 
   i.  Select API Key
 
   ii.  Provide a name for the authorization profile.
 
   iii.  Save Authorization Profile.
 
 5.  Click Enable.
 
 </container>
 
 <container>

**What can be achieved by integrating Azure with the Kore.ai XO Platform?**
 
 The Kore.ai XO Platform supports all common actions on Azure with pre-built dialog templates that are ready to use.
 
**Templates Supported**

| Action           | Description            |
|------------------|------------------------|
|General Query     |Use OpenAI to answer generic user queries|

</container>

