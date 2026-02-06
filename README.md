# HealthBot - AI-Powered Patient Education System

**Capstone Project and Exercises for Udacity Course 'AI Agents with LangChain and LangGraph' (December 2025)**

## Overview

This repository contains the capstone project and learning exercises from the Udacity course "AI Agents with LangChain and LangGraph." The HealthBot project demonstrates how to build an intelligent AI agent system for patient education using modern agentic AI frameworks including LangChain and LangGraph.

HealthBot is designed to provide accessible healthcare information through conversational AI, helping patients understand medical conditions, treatments, and health management through natural language interactions.

## Course Topics Covered

This repository is organized into 5 modules that progressively build skills in developing AI agent systems:

### Module 1: Introduction to AI Agents and LangChain Fundamentals
- Understanding agentic AI systems and their applications
- Setting up the LangChain development environment
- Working with Large Language Models (LLMs) via APIs
- Building basic chatbots with memory capabilities
- Implementing prompt engineering techniques (Chain of Thought, ReAct, Few-Shot)
- Creating simple conversational interfaces

### Module 2: Advanced LangChain Features and Agent Design
- Implementing output parsers and structured responses
- Managing chat history and conversation context
- Building multi-step workflows using Runnables and LCEL (LangChain Expression Language)
- Streaming responses for real-time interactions
- Integrating external tools and APIs
- Working with TypedDict and Pydantic for robust data validation

### Module 3: Introduction to LangGraph and State Management
- Understanding graph-based agent workflows
- Implementing nodes, edges, and state management
- Building cyclical and dynamic workflows
- Managing agent state with TypedDict and Pydantic
- Creating conditional routing and decision logic
- Implementing short-term and long-term memory systems

### Module 4: Advanced Agent Capabilities - RAG and Database Integration
- Implementing Retrieval-Augmented Generation (RAG) pipelines
- Working with vector databases for semantic search
- Building database agents with natural language to SQL conversion
- Integrating embeddings for knowledge retrieval
- Managing persistent memory with SQLite
- Implementing Agentic RAG with reflection and query reformulation

### Module 5: Production AI Agents - Evaluation, Monitoring, and Best Practices
- Implementing human-in-the-loop workflows
- Agent observability and debugging with MLflow
- Evaluating and benchmarking agent performance
- Building reliable and trustworthy AI systems
- Integrating multiple data sources for comprehensive knowledge bases
- Deploying production-ready healthcare AI agents

## Project Structure

```
HealthBot_AI_Powered_Patient_Education_System/
├── Module1/          # Introduction to AI Agents and LangChain
├── Module2/          # Advanced LangChain Features
├── Module3/          # LangGraph and State Management
├── Module4/          # RAG and Database Integration
├── Module5/          # Production AI Agents
├── .gitignore
├── LICENSE
└── README.md
```

## Technologies Used

- **Python 3.x** - Primary programming language
- **LangChain** - Framework for building LLM applications
- **LangGraph** - Graph-based workflow orchestration
- **OpenAI API** - Large language model integration
- **Pydantic** - Data validation and settings management
- **SQLite** - Persistent storage for agent memory
- **Vector Databases** - Semantic search and knowledge retrieval
- **MLflow** - Agent observability and evaluation

## Key Features of HealthBot

- **Conversational Patient Education**: Natural language interface for healthcare information
- **Memory-Enabled Interactions**: Maintains conversation context across multiple turns
- **Knowledge Retrieval**: RAG-based system for accessing medical information
- **Dynamic Workflows**: Graph-based agent logic for complex decision-making
- **API Integration**: Real-time access to external healthcare data sources
- **Evaluation & Monitoring**: Built-in observability for agent performance tracking

## Prerequisites

- Basic Python programming knowledge
- Understanding of software engineering concepts (Git, virtual environments, debugging)
- Familiarity with APIs and JSON data structures
- No machine learning experience required

## Installation

1. Clone this repository:
```bash
git clone https://github.com/mjgrav2001/HealthBot_AI_Powered_Patient_Education_System.git
cd HealthBot_AI_Powered_Patient_Education_System
```

2. Create and activate a virtual environment:
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

3. Install required dependencies:
```bash
pip install -r requirements.txt
```

4. Set up API keys:
```bash
# Create a .env file and add your OpenAI API key
echo "OPENAI_API_KEY=your_api_key_here" > .env
```

## Usage

Each module contains Jupyter notebooks with exercises and implementations. Navigate to the specific module directory and open the notebooks:

```bash
jupyter notebook
```

Start with Module 1 and progress sequentially through the modules to build your understanding of AI agent development.

## Learning Outcomes

By completing this course and capstone project, you will learn to:

- Build sophisticated AI agents that can think, reason, and act autonomously
- Implement memory systems for context-aware conversations
- Integrate external tools and APIs into agent workflows
- Design graph-based workflows with LangGraph for complex decision logic
- Create RAG pipelines for knowledge-enhanced AI responses
- Evaluate and monitor agent performance in production environments
- Apply best practices for building reliable and trustworthy AI systems

## Healthcare Context

This project specifically focuses on patient education applications, demonstrating how AI agents can:

- Explain medical conditions in accessible language
- Provide information about treatment options
- Answer common health-related questions
- Guide patients through healthcare resources
- Maintain patient privacy and data security
- Operate within ethical boundaries of medical information provision

**Note**: This is an educational project. HealthBot is not a substitute for professional medical advice, diagnosis, or treatment. Always consult qualified healthcare providers for medical concerns.

## Contributing

This is a learning project from a Udacity course. While primarily for educational purposes, suggestions and improvements are welcome through issues and pull requests.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- **Udacity** - For creating the "AI Agents with LangChain and LangGraph" course
- **LangChain & LangGraph Communities** - For excellent frameworks and documentation
- **OpenAI** - For providing LLM capabilities through their API

## Resources

- [Udacity Course: AI Agents with LangChain and LangGraph](https://www.udacity.com/course/ai-agents-with-langchain-and-langgraph--cd13764)
- [LangChain Documentation](https://docs.langchain.com/)
- [LangGraph Documentation](https://langchain-ai.github.io/langgraph/)
- [OpenAI API Documentation](https://platform.openai.com/docs)

## Contact

For questions or feedback about this project, please open an issue in this repository.

---

**Course Completion**: December 2025  
**Repository Author**: [mjgrav2001](https://github.com/mjgrav2001)
