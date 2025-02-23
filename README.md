# LangChain Tools & Agents - Practical Implementations

## Overview
This repository contains hands-on implementations of LangChain's **Tools** and **Agents**, showcasing their capabilities in integrating external data sources, executing dynamic tasks, and enhancing AI-driven workflows.

## Features
- **LangChain Tools**: Leveraging built-in and custom tools to interact with external APIs, databases, and services.
- **Web Search Integration**: Using APIs like BraveSearch for real-time information retrieval.
- **Custom Tools Implementation**: Creating specialized tools using the `@tool` decorator.
- **LangChain Agents**: Implementing agents that dynamically decide which tool to use based on user input.
- **Task Automation**: Executing tasks such as web searches, database queries, and API calls through LangChain Agents.


## Setup Instructions
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/langchain-tools-agents.git
   ```
2. Navigate to the repository:
   ```bash
   cd langchain-tools-agents
   ```
3. Create and activate a virtual environment:
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```
4. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
5. Set up environment variables (if needed):
   ```bash
   export API_KEY='your_api_key_here'  # On Windows: set API_KEY=your_api_key_here
   ```

## Dependencies
langchain
nest-asyncio
psutil
tornado>=6.1
traitlets>=5.4.0
ipython
python-dotenv
langchain-openai
langchain-core
langchain_community
bs4
faiss-cpu
langchain_groq
wikipedia
arxivs`



