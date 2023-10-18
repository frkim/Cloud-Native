# Microsoft Azure OpenAI

Azure OpenAI Service provides REST API access to OpenAI's powerful language models including the GPT-4, GPT-35-Turbo, and Embeddings model series.

These models can be easily adapted to your specific task including but not limited to:

- content generation
- summarization
- semantic search

- natural language to code translation

Users can access the service through REST APIs, Python SDK, or our web-based interface in the Azure OpenAI Studio.

[General Documentation on Microsoft Learn](https://learn.microsoft.com/en-us/azure/ai-services/openai/)

![AOAI Enterprise Deployment](https://techcommunity.microsoft.com/t5/image/serverpage/image-id/495112i80DA3D88097DEC9D/image-size/large?v=v2&px=999)

## Overview

### Grounding LLM

Grounding is the process of using large language models (LLMs) with information that is use-case specific, relevant, and not available as part of the LLM's trained knowledge. It is crucial for ensuring the quality, accuracy, and relevance of the generated output. While LLMs come with a vast amount of knowledge already, this knowledge is limited and not tailored to specific use-cases. To obtain accurate and relevant output, we must provide LLMs with the necessary information. In other words, we need to "ground" the models in the context of our specific use-case.

[Read more here](https://techcommunity.microsoft.com/t5/fasttrack-for-azure/grounding-llms/ba-p/3843857)

## Private ChatGPT

First, I strongly recommand to start with this introduction post: [How to create a private ChatGPT with your own data](https://medium.com/@imicknl/how-to-create-a-private-chatgpt-with-your-own-data-15754e6378a1)

[Chat Copilot Sample Application](https://github.com/microsoft/semantic-kernel) - This sample allows you to build your own integrated large language model (LLM) chat copilot. The sample is built on [Microsoft Semantic Kernel](https://learn.microsoft.com/en-us/semantic-kernel/overview/).

![AKS 101](https://camo.githubusercontent.com/db6af42498ba3e603ce6ac38f5ab124708ac1c25b48114108889c979baae7f67/68747470733a2f2f6c6561726e2e6d6963726f736f66742e636f6d2f656e2d75732f73656d616e7469632d6b65726e656c2f6d656469612f636861742d636f70696c6f742d696e2d616374696f6e2e676966)

## Architecture

### High Level Architecture

[Building a Private ChatGPT Interface With Azure OpenAI](https://techcommunity.microsoft.com/t5/azure-architecture-blog/building-a-private-chatgpt-interface-with-azure-openai/ba-p/3869522)
![PrivateGPT with Azure](https://techcommunity.microsoft.com/t5/image/serverpage/image-id/487496iA87525AA8B2197EE/image-size/large?v=v2&px=999)

### Enterprise Implementation

[Azure OpenAI Landing Zone reference architecture](https://techcommunity.microsoft.com/t5/azure-architecture-blog/azure-openai-landing-zone-reference-architecture/ba-p/3882102)

[GitHub Repository with implementation](https://github.com/FreddyAyala/AzureAIServicesLandingZone/tree/main)

![Reference Architecture](https://techcommunity.microsoft.com/t5/image/serverpage/image-id/495142i616B2737C1324F0D/image-size/large?v=v2&px=999)

[Implement logging and monitoring for Azure OpenAI models](https://learn.microsoft.com/en-us/azure/architecture/ai-ml/openai/architecture/log-monitor-azure-openai)
![Implement logging and monitoring for Azure OpenAI models](https://learn.microsoft.com/en-us/azure/architecture/ai-ml/openai/architecture/_images/openai-monitor-log.png)

### Enterprise Deployment with Azure API Management

- [Azure API Management with Azure OpenAI](https://github.com/pascalvanderheiden/ais-apim-openai)
- [Manage Azure Open AI using APIM](https://github.com/microsoft/AzureOpenAI-with-APIM#azure-commercial-api-management-to-azure-open-ai-with-private-endpoints)

## Tutorial, Walkthrough

- [Introduction to Azure OpenAI Service - 1hr3min](https://learn.microsoft.com/en-us/training/modules/explore-azure-openai/?ns-enrollment-type=Collection&ns-enrollment-id=4oefo3dozy48y)
- [Develop Generative AI solutions with Azure OpenAI Service - 5hr34min](https://learn.microsoft.com/en-us/training/paths/develop-ai-solutions-azure-openai/)
- [Azure Open AI Blueprint – Navigating from MVP to Enterprise Environments](https://www.floriankitterer.com/post/your-azure-openai-blueprint-navigating-from-mvp-to-enterprise-environments)
- [Intelligent App Workshop for Microsoft Copilot Stack](https://copilotwksp.com/)

## Demos

- [Azure-OpenAI-demos by Serge Retkowsky](https://github.com/retkowsky/Azure-OpenAI-demos)

## Aditional Resources

- Azure Open Ai Models: [Azure OpenAI Service models](https://learn.microsoft.com/en-us/azure/ai-services/openai/concepts/models#model-summary-table-and-region-availability)
- Azure AI News: [Azure AI Techcommunity Blog](https://techcommunity.microsoft.com/t5/azure-ai-services-blog/bg-p/Azure-AI-Services-blog)
- Azure Open AI: [Azure OpenAI Service - Pricing](https://azure.microsoft.com/en-us/pricing/details/cognitive-services/openai-service/)
- Quota & Limits: [Azure OpenAI Service quotas and limits](https://learn.microsoft.com/en-us/azure/ai-services/openai/quotas-limits)
