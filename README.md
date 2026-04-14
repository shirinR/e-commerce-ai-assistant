Multi-Agent AI Shopping Copilot with Safety Guardrails
This project demonstrates a sophisticated multi-agent AI system designed to enhance the e-commerce shopping experience. It orchestrates several specialized AI agents to process user queries, retrieve relevant product information, analyze customer reviews, and ensure compliance with safety and ethical guidelines.

Key Features:

Multi-Agent Orchestration: Utilizes a central orchestration agent to coordinate interactions between specialized agents.
Intent Agent: Extracts structured shopping intent (product type, price, features) from natural language queries.
Product Search Agent: Retrieves relevant products from a vector store (FAISS) based on extracted intent and product features.
Review Analyzer Agent: Synthesizes customer feedback, identifies sentiment, extracts pros, cons, and key themes from product reviews.
Compliance Agent: Implements safety and policy guardrails, filtering non-compliant products and validating AI-generated responses.
Evaluation Agent: Provides mechanisms to assess the performance and reliability of the individual agents and the overall system.
RAG Pipeline: Leverages Retrieval Augmented Generation (RAG) for efficient and context-aware information retrieval.
Tech Stack:

Backend: Python, FastAPI
Agent Orchestration: LangChain / LangGraph
Vector Search: FAISS (for product catalog and reviews)
LLM: GPT (e.g., GPT-4o-mini) or open-source alternatives
Data: Kaggle product datasets (e.g., IKEA product catalog)
This project serves as a comprehensive example of building robust, intelligent, and ethical AI systems for e-commerce applications.
