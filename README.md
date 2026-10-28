# Agriculture RAG Chatbot

## Project Overview
An AI-powered agriculture chatbot that answers users' agriculture-related questions using information retrieved from a document knowledge base. The chatbot uses Retrieval-Augmented Generation (RAG) and delivers responses through WhatsApp.

## My Role
**Backend Workflow Architecture and AI Integration**

This was a collaborative project, and I was responsible for designing and implementing the main backend workflow architecture in n8n.

### Key Contributions
- Designed and configured the n8n workflow pipeline.
- Developed and configured the AI agent.
- Integrated Supabase Vector Database for document retrieval.
- Configured workflow routing and decision logic.
- Connected services through API integrations.
- Debugged and tested the workflow to help ensure responses reached users through WhatsApp.

## Technologies Used
- n8n
- Supabase Vector Database
- OpenAI
- Retrieval-Augmented Generation (RAG)
- WhatsApp integration
- API integration

## How It Works
1. A user sends an agriculture-related question through WhatsApp.
2. The n8n workflow processes the incoming message.
3. The AI agent retrieves relevant information from the Supabase knowledge base.
4. The agent generates a response grounded in the retrieved information.
5. The workflow sends the response back to the user through WhatsApp.

## Project Type
Collaborative backend automation and AI integration project.

*Note: This repository documents my contribution to a team project. Workflow files are shared subject to team permission and security review.*
