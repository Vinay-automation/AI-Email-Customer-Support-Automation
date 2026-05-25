# AI Email Customer Support Automation

An AI-powered customer support email automation workflow built using **n8n**, **Supabase Vector Store**, **Google Gemini Embeddings**, and **OpenRouter LLMs**.

This workflow automatically:
- monitors incoming Gmail support emails
- classifies emails into support/promotional categories
- retrieves contextual knowledge using RAG (Retrieval-Augmented Generation)
- drafts intelligent AI-powered email replies
- uses vector search for contextual support responses
- supports scalable AI customer support automation

---

# Workflow Architecture

## Incoming Emails
Receives new customer emails using Gmail Trigger.

## Email Classification
Uses an LLM-powered classifier to categorize emails:
- Support Service
- Promotional

## AI Retrieval & Response Generation
Uses:
- AI Agent
- Supabase Vector Store
- Gemini Embeddings
- OpenRouter Chat Models

to retrieve contextual knowledge and draft intelligent email responses.

---

# Tech Stack

- n8n
- Docker
- Supabase
- PostgreSQL
- Vector Database
- Google Gemini Embeddings
- OpenRouter
- Gmail API
- AI Agents
- RAG Architecture

---

# Features

- Gmail-triggered automation
- AI-powered email classification
- Retrieval-Augmented Generation (RAG)
- Vector similarity search
- Context-aware response drafting
- Gmail draft creation
- Self-hosted Dockerized setup
- Modular AI workflow architecture

---

# Workflow Overview

```text
Incoming Email
    ↓
Email Extraction
    ↓
AI Classification
    ↓
AI Agent
    ↓
Vector Database Retrieval
    ↓
Contextual AI Response
    ↓
Draft Email Creation
```

---

# Screenshots

<img width="626" height="260" alt="Workflow_image" src="https://github.com/user-attachments/assets/9e60f7a5-82d6-42ca-acb9-ba972e9d26b6" />

---

# Use Cases

- AI Customer Support
- Automated Helpdesk
- AI Email Assistant
- FAQ Automation
- Support Ticket Drafting
- Knowledge Base Retrieval
- AI Workflow Automation

---

# Future Improvements

Planned improvements:
- Confidence score evaluation
- Human approval workflow
- Slack escalation alerts
- Knowledge base auto-learning
- Customer/order lookup tools
- Sentiment analysis
- Multi-channel support automation

---

# Local Development Setup

## Clone Repository

```bash
git clone https://github.com/YOUR_USERNAME/ai-email-customer-support-automation.git
```

---

## Start n8n

```bash
docker compose up -d
```

---

## Configure Credentials

Add:
- Gmail API credentials
- OpenRouter API key
- Supabase credentials
- Gemini API key

inside n8n credential manager.

---

# Project Goals

This project was built to explore:
- AI workflow orchestration
- RAG systems
- AI agents
- vector databases
- business workflow automation
- scalable AI-powered customer support systems

---

# Author

Vinay Kumar

Exploring:
- AI Automation
- n8n
- AI Agents
- RAG Systems
- Workflow Engineering
- Vector Databases
- PostgreSQL
- Docker

---
