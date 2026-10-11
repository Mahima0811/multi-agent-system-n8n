# multi-agent-system-n8n
Multi-Agent System using n8n, Groq LLM, conversational memory, and Tavily web search.

## 1. Project Overview
This project implements a Multi-Agent System (MAS) using n8n. It uses multiple AI agents, a large language model, conversational memory, and a web-search tool to answer user queries.

## 2. Objective
To explore how multiple AI agents can work within a single workflow, process user queries, and use external information sources to generate responses.

## 3. Technologies Used
- **n8n:** Workflow automation and agent orchestration
- **Groq Chat Model:** Language model integration
- **Simple Memory:** Conversational context
- **Tavily Search:** Web-search tool for retrieving relevant information

## 4. Workflow Architecture
1. The user submits a message through the chat trigger.
2. The first AI Agent processes the incoming query.
3. The workflow passes the result to the second AI Agent.
4. The configured model and memory support the agents' processing.
5. The Tavily search tool can retrieve relevant web information when invoked.
6. The workflow returns a response to the user.

## 5. Example Test
**User query:** Who is Lionel Messi?

**Observed result:** The workflow returned a response describing Messi's football career, achievements, and professional background.

## 6. Project Files
- `multi-agent-system.json` — exported n8n workflow (to be uploaded).

## 7. Setup Instructions
1. Import the workflow JSON into n8n.
2. Configure the required Groq and Tavily credentials.
3. Verify the AI Agent, memory, and tool connections.
4. Test the workflow using the chat trigger.

## 8. Security
Do not upload API keys, access tokens, passwords, or private credentials. Configure credentials securely within n8n.

## 9. Limitations
Responses depend on the selected language model, tool configuration, availability of web-search results, and quality of retrieved information.

## 10. Academic Purpose
This repository documents an academic project demonstrating a multi-agent workflow using n8n.
