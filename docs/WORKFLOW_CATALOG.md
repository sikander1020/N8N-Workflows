# Workflow Catalog

This catalog summarizes the workflows found in the workspace and how they fit together as a professional n8n portfolio.

| Workflow | Category | Summary | Primary integrations |
| --- | --- | --- | --- |
| Ad Creation | Creative automation | Telegram-driven ad concept flow that analyzes a product image and generates structured ad prompts for review and approval. | Telegram, OpenAI, file/image analysis |
| AI-Powered Multi-Social Media Post Automation: Google Trends & Perplexity AI | Content automation | Researches trending topics, selects a blog angle, and routes content to multiple social platforms. | Google Trends, Tavily/Perplexity-style research, OpenAI, X, Facebook, LinkedIn |
| email ai agent | Inbox automation | Classifies incoming emails and drafts responses based on message intent and priority. | Gmail, OpenAI |
| FYP | Assistant / health workflow | Webhook-based medical assistant that returns treatment guidance and escalates severe cases. | Webhook, OpenAI |
| inventory update ai | Ops automation | Chat-based inventory assistant that updates spreadsheet stock data using AI tool calls. | Chat trigger, OpenAI, Google Sheets |
| Generate Veo3 Videos | Video generation | Creates Veo3 text prompts, stores them in Sheets, and triggers video generation. | OpenAI, Google Sheets, Replicate, wait polling |
| POV videos | Video concept generation | Produces sequential POV prompt ideas and sends them into image/video generation pipelines. | OpenAI, image generation, Runway, polling |
| RAG Pipeline and Chatbot | Knowledge base / RAG | Ingests documents from Google Drive into Pinecone and exposes them through a chat agent. | Google Drive, Pinecone, OpenAI, chat trigger |
| Generate AI Videos with Google Veo3, Save to Google Drive and Upload to YouTube | Video publishing | Generates AI videos, stores them in Drive, writes metadata to Sheets, and uploads to YouTube. | Google Sheets, Google Drive, Veo3, YouTube |

## Suggested folder grouping

- workflows/content/
- workflows/video/
- workflows/rag/
- workflows/ops/
- workflows/assistants/

## Publishing order

1. Start with the most stable workflows: email, inventory, and RAG.
2. Add the more advanced media pipelines: ad creation, Veo3, POV, and YouTube upload.
3. Finish with the profile-facing documentation and polished screenshots.
