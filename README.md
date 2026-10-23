Harry A. Layman, PhD
=======================

Senior Technology Advisor and AI Solutions Architect, CogWrite Semantic Technologies (San Diego).
Production AI systems end to end: multi-tenant SaaS, RAG pipelines, agentic workflows, and LLM infrastructure.

### see also: https://cogwrite.ai   |   https://www.linkedin.com/in/harrylayman/  |  https://cogwrite.ai/gallery-1-1 

## A few examples of my work (AI-based solutions, agentic AI, LLM-powered)

### Cognosa web app -- multi-tenant RAG application platform

https://github.com/harry-at-cognosa/cognosa-web-app

Cognosa is a FastAPI + LangChain "AI as a Service" platform: multi-tenant, multi-LLM, multi-context, multi-vector-database. It supports OpenAI, Anthropic, Google, Alibaba and open-source models hosted by Ollama, including Meta's Llama. Vector databases supported include ChromaDB, pgvector and Qdrant (Qdrant works best). More information at [files.cognosa.net/cognosa-info](http://files.cognosa.net/cognosa-info/).

### p51 local automator -- desktop or dedicated Mac mini server for a small office or home

https://github.com/harry-at-cognosa/p51-local-automator

A multi-user automation platform that runs securely on your LAN. Everything runs locally except calls to your chosen LLM vendor API. Currently under construction.

Build multi-step automations, including human-in-the-loop (HITL) steps, with access to the full range of Apple and Google services via local MCP servers, so there are no leaky remote back ends to crash your workflows. Each user's automations run under that user's own Apple and Google / Google Workspace privileges to reach email, documents, authoring and reading tools, and a range of database and API services. LLM-powered with the vendor of your choice. Built-in agentic workflows are fully customizable. Samples include daily, weekly or on-demand email and calendar summaries, and workflows that check data from a variety of sources, raise alerts, and trigger follow-on tasks that send email, author documents or reports, update Google Sheets, or invoke other services.

### AWS serverless document summarization workflow

https://github.com/harry-at-cognosa/p41-aws-genai-workflow

AWS-native serverless pipeline (Lambda + Bedrock + Claude) for document summarization. v1.0 personal MVP; v2.0 will port to FastAPI / PostgreSQL.

### Sales Quote Manager automation application

Front-end web app (primary UI for admin users and Area Sales Managers):

https://github.com/harry-at-cognosa/listmgr1

This FastAPI web app shares the Sales Quote Manager database of templates and sales quotes across all country / currency / product category / product line combinations.

Back end:

https://github.com/harry-at-cognosa/listldr1

Home to the back-end functions that implement the complex business logic. Executes batch jobs (mass updates to templates) and provides, via API, single template / quote conversions, cloning, and regeneration after price, area or currency changes.

More information at [files.cognosa.net/quotemgr-info](http://files.cognosa.net/quotemgr-info/).

### agentic-os -- content generation pipeline

(WIP, private)

https://github.com/harry-at-cognosa/agentic-os

### haldraw -- local infinite-canvas diagramming app with shape / label / text / connector re-vectorization!

https://github.com/harry-at-cognosa/haldraw

For years I wanted a simple drawing app to replace "Simple Diagrams". With Claude's help I had one in a matter of days (Electron + React + SQLite). An unsigned Electron .dmg for macOS is in `/dist`.

### Is It Journalism -- a future project

Mock-up with example results (try the "details" button):

https://harry-at-cognosa.github.io/isitj/

A second mock-up, "Is It Real", is not live yet.

### Contact

CogWrite Semantic Technologies -- harry@cognosa.net
