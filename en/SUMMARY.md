# Table of contents

## Getting Started

* [Welcome to Dify](README.md)
  * [Features and Specifications](getting-started/readme/features-and-specifications.md)
  * [List of Model Providers](getting-started/readme/model-providers.md)
* [Dify Community](getting-started/install-self-hosted/README.md)
  * [Deploy with Docker Compose](getting-started/install-self-hosted/docker-compose.md)
  * [Start with Local Source Code](getting-started/install-self-hosted/local-source-code.md)
  * [Start Frontend Docker Container Separately](getting-started/install-self-hosted/start-the-frontend-docker-container.md)
  * [Environment Variables Explanation](getting-started/install-self-hosted/environments.md)
  * [FAQs](getting-started/install-self-hosted/faqs.md)
* [Dify Cloud](getting-started/cloud.md)
* [Dify Premium on AWS](getting-started/dify-premium-on-aws.md)

## Guides

* [Model](guides/model-configuration/README.md)
  * [Add New Provider](guides/model-configuration/new-provider.md)
  * [Predefined Model Integration](guides/model-configuration/predefined-model.md)
  * [Custom Model Integration](guides/model-configuration/customizable-model.md)
  * [Interfaces](guides/model-configuration/interfaces.md)
  * [Schema](guides/model-configuration/schema.md)
  * [Integrate Open Source Models from Hugging Face](guides/model-configuration/hugging-face.md)
  * [Integrate Open Source Models from Replicate](guides/model-configuration/replicate.md)
  * [Integrate Local Models Deployed by Xinference](guides/model-configuration/xinference.md)
  * [Integrate Local Models Deployed by OpenLLM](guides/model-configuration/openllm.md)
  * [Integrate Local Models Deployed by LocalAI](guides/model-configuration/localai.md)
  * [Integrate Local Models Deployed by Ollama](guides/model-configuration/ollama.md)
  * [Load Balancing](guides/model-configuration/load-balancing.md)
* [Application Orchestration](guides/application-orchestrate/README.md)
  * [Create Application](guides/application-orchestrate/creating-an-application.md)
  * [Conversation Assistant](guides/application-orchestrate/conversation-application.md)
  * [Agent](guides/application-orchestrate/agent.md)
  * [Application Toolkits](guides/application-orchestrate/app-toolkits/README.md)
    * [Moderation Tool](guides/application-orchestrate/app-toolkits/moderation-tool.md)
* [Workflow](guides/workflow/README.md)
  * [Key Concepts](guides/workflow/key_concepts.md)
  * [Node Description](guides/workflow/node/README.md)
    * [Start](guides/workflow/node/start.md)
    * [End](guides/workflow/node/end.md)
    * [Direct Reply](guides/workflow/node/answer.md)
    * [LLM](guides/workflow/node/llm.md)
    * [Knowledge Retrieval](guides/workflow/node/knowledge-retrieval.md)
    * [Question Classifier](guides/workflow/node/question-classifier.md)
    * [Conditional Branch IF/ELSE](guides/workflow/node/ifelse.md)
    * [Code Execution](guides/workflow/node/code.md)
    * [Template](guides/workflow/node/template.md)
    * [Variable Aggregator](guides/workflow/node/variable-assigner.md)
    * [Iteration](guides/workflow/node/iteration.md)
    * [Parameter Extraction](guides/workflow/node/parameter-extractor.md)
    * [HTTP Request](guides/workflow/node/http-request.md)
    * [Tools](guides/workflow/node/tools.md)
  * [Debug and Preview](guides/workflow/debug-and-preview/README.md)
    * [Preview and Run](guides/workflow/debug-and-preview/yu-lan-yu-yun-hang.md)
    * [Step Run](guides/workflow/debug-and-preview/step-run.md)
    * [Conversation/Run Logs](guides/workflow/debug-and-preview/log.md)
    * [Checklist](guides/workflow/debug-and-preview/checklist.md)
    * [Run History](guides/workflow/debug-and-preview/history.md)
  * [Application Publishing](guides/workflow/publish.md)
* [Knowledge Base](guides/knowledge-base/README.md)
  * [Create Knowledge Base & Upload Documents](guides/knowledge-base/create-knowledge-and-upload-documents.md)
  * [Knowledge Base and Document Maintenance](guides/knowledge-base/knowledge-and-documents-maintenance.md)
  * [Integrate Knowledge Base within Application](guides/knowledge-base/integrate-knowledge-within-application.md)
  * [Retrieval Test/Citation](guides/knowledge-base/retrieval-test-and-citation.md)
  * [Sync Data from Notion](guides/knowledge-base/sync-from-notion.md)
  * [Sync Data from Website](guides/knowledge-base/sync-from-website.md)
  * [Maintain Knowledge Base via API](guides/knowledge-base/maintain-dataset-via-api.md)
  * [External Data Tool](guides/knowledge-base/external-data-tool.md)
* [Tools](guides/tools/README.md)
  * [Quick Tool Integration](guides/tools/quick-tool-integration.md)
  * [Advanced Tool Integration](guides/tools/advanced-tool-integration.md)
  * [Tool Configuration](guides/tools/tool-configuration/README.md)
    * [StableDiffusion](guides/tools/tool-configuration/stable-diffusion.md)
    * [SearXNG](guides/tools/tool-configuration/searxng.md)
* [Publishing](guides/application-publishing/README.md)
  * [Launch Your Webapp Quickly](guides/application-publishing/launch-your-webapp-quickly/README.md)
    * [Web App Settings](guides/application-publishing/launch-your-webapp-quickly/web-app-settings.md)
    * [Text Generator Application](guides/application-publishing/launch-your-webapp-quickly/text-generator.md)
    * [Conversation Application](guides/application-publishing/launch-your-webapp-quickly/conversation-application.md)
  * [Embedding In Websites](guides/application-publishing/embedding-in-websites.md)
  * [Developing with APIs](guides/application-publishing/developing-with-apis.md)
  * [Re-develop Based on Frontend Templates](guides/application-publishing/based-on-frontend-templates.md)
* [Annotation](guides/biao-zhu/README.md)
  * [Logs and Annotation](guides/biao-zhu/logs.md)
  * [Annotation Reply](guides/biao-zhu/annotation-reply.md)
* [Monitoring](guides/monitoring/README.md)
  * [Data Analysis](guides/monitoring/analysis.md)
  * [Integrate External Ops Tools](guides/monitoring/integrate-external-ops-tools/README.md)
    * [Integrate LangSmith](guides/monitoring/integrate-external-ops-tools/integrate-langsmith.md)
    * [Integrate Langfuse](guides/monitoring/integrate-external-ops-tools/integrate-langfuse.md)
* [Extension](guides/extension/README.md)
  * [API-Based Extension](guides/extension/api-based-extension/README.md)
    * [External Data Tool](guides/extension/api-based-extension/external-data-tool.md)
    * [Deploy API Tools with Cloudflare Workers](guides/extension/api-based-extension/cloudflare-workers.md)
    * [Moderation](guides/extension/api-based-extension/moderation.md)
  * [Code-Based Extension](guides/extension/code-based-extension/README.md)
    * [External Data Tool](guides/extension/code-based-extension/external-data-tool.md)
    * [Moderation](guides/extension/code-based-extension/moderation.md)
* [Collaboration](guides/workspace/README.md)
  * [Discover](guides/workspace/app/README.md)
  * [Invite and Manage Members](guides/workspace/invite-and-manage-members.md)
* [Management](guides/management/README.md)
  * [Manage App](guides/management/manage-app.md)

## Community

* [Seek Support](community/support.md)
* [Become a Contributor](community/contribution.md)

## Development

* [Backend](development/backend/README.md)
  * [DifySandbox](development/backend/sandbox/README.md)
    * [Contribution Guide](development/backend/sandbox/contribution.md)

## Learn More

* [Use Cases](learn-more/use-cases/README.md)
  * [Build a Notion AI Assistant](learn-more/use-cases/build-an-notion-ai-assistant.md)
  * [Create a MidJourney Prompt Bot with Dify](learn-more/use-cases/create-a-midjourney-prompt-bot-with-dify.md)
  * [Create an AI Chatbot with Business Data in Minutes](learn-more/use-cases/create-an-ai-chatbot-with-business-data-in-minutes.md)
* [Extended Reading](learn-more/extended-reading/README.md)
  * [What is LLMOps?](learn-more/extended-reading/what-is-llmops.md)
  * [Retrieval-Augmented Generation (RAG)](learn-more/extended-reading/retrieval-augment/README.md)
    * [Hybrid Search](learn-more/extended-reading/retrieval-augment/hybrid-search.md)
    * [Re-ranking](learn-more/extended-reading/retrieval-augment/rerank.md)
    * [Retrieval Modes](learn-more/extended-reading/retrieval-augment/retrieval.md)
* [FAQ](learn-more/faq/README.md)
  * [Self-Host Related](learn-more/faq/self-host-faq.md)
  * [LLM Configuration and Usage](learn-more/faq/use-llms-faq.md)

## Policies

* [Open Source License](policies/open-source.md)
* [User Agreement](policies/agreement/README.md)
  * [Terms of Service](https://dify.ai/terms)
  * [Privacy Policy](https://dify.ai/privacy)
