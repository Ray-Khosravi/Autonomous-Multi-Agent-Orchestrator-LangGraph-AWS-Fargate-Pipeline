# Agentic AI Orchestrator
🌟 An autonomous Multi-Agent system using LangGraph for stateful workflows. Built with a FastAPI backend, SonarQube for code quality, and deployed via serverless AWS Fargate. Designed for scalable, enterprise-grade agentic orchestration.

🏗️ Enterprise Architecture & MLOps Pipeline
The project implements a "Production-First" mentality, ensuring that the AI agents are governed by a robust CI/CD and infrastructure layer.

<img width="1802" height="827" alt="Multi+AI+Agent+Workflow" src="https://github.com/user-attachments/assets/e0324bf8-3db1-4af9-a658-f66a7201f2fb" />



🧩 Intelligence Layer (The Brain)
Stateful Orchestration: Utilizes LangGraph to maintain conversation state and manage complex transitions between specialized agents.

Specialized Tooling: Integrated Groq API for ultra-low latency inference and Tavily API for real-time web search and information retrieval.

Modular Design: Custom exception handling and logging designed for long-running agentic tasks.

🚀 Application & DevOps Layer
Full-Stack UI/UX: A high-speed FastAPI backend paired with a Streamlit frontend for interactive agent monitoring.

Jenkins CI/CD Pipeline: * Automated Testing: Triggered on every commit via GitHub hooks.

Quality Gate: SonarQube integration for deep static code analysis and security scanning.

Automated Registry: Secure builds pushed to AWS Elastic Container Registry (ECR).

Serverless Deployment: Fully orchestrated on AWS Fargate, ensuring horizontal scalability without managing underlying EC2 instances.

🛠️ Technical Stack
AI Frameworks: LangChain, LangGraph (State Machine Agents)

LLM Providers: Groq (Llama 3/Mixtral), Tavily (Search)

Backend: FastAPI, Python 3.x

Frontend: Streamlit

CI/CD & Quality: Jenkins, SonarQube, Docker

Cloud (AWS): ECR, Fargate, IAM Roles

💡 Engineering Excellence: Why This Matters
As an AI Engineer, I focused on three pillars for this project:

Controllability: Using LangGraph to prevent "Agent Loops" and ensure the LLM follows specific business logic.

Scalability: Decoupling the frontend and backend, allowing the agents to scale independently on AWS.

Reliability: Implementing a Jenkins-led CI/CD pipeline that enforces 80%+ test coverage and code quality before any deployment.



👋 Contact & Connect

Ray Khosravi - AI / Machine Learning Engineer

[LinkedIn](https://www.linkedin.com/in/raoufkhosravi/)

raykhosravi1993@gmail.com
