# 🤖 Agentic AI Projects

A collection of AI agents and multi-agent systems built using **Python, Agno, and Large Language Models (LLMs)**.

This repository documents my hands-on journey into Agentic AI, exploring how intelligent agents can use external tools, maintain memory, collaborate with other agents, and perform specialized tasks.

## 🚀 Projects

### 1. Basic AI Agent (`agent.py`)

A foundational AI agent built using the Agno framework.

**Concepts explored:**
- Creating and configuring AI agents.
- Integrating LLMs.
- Understanding agent execution and responses.

### 2. Finance Agent (`Finance.py`)

An AI-powered financial research agent designed to retrieve and analyze financial information.

**Key Features:**
- Stock price retrieval.
- Company fundamentals and financial information.
- Analyst recommendations.
- Web-based financial research.

**Tools & Technologies:**
- Agno
- Groq
- Qwen
- YFinance Tools
- DuckDuckGo Search

### 3. Multi-Agent System (`team.py`)

Exploration of multi-agent architecture, where multiple specialized agents collaborate to complete tasks.

**Concepts explored:**
- Multi-agent collaboration.
- Task delegation.
- Agent coordination.
- Specialized agent responsibilities.

### 4. Memory Agent (`memory.py`)

An AI agent experimenting with persistent memory and conversational context.

**Concepts explored:**
- Agent memory.
- Conversation history.
- SQLite-based storage.
- Retrieving previously stored information.

**Technologies:**
- Agno
- SQLite
- Groq
- Python

## 🛠️ Tech Stack

| Technology | Purpose |
|---|---|
| Python | Core programming language |
| Agno | Agent development framework |
| Groq | LLM inference |
| Qwen | Language model |
| SQLite | Persistent data storage |
| YFinance | Financial data retrieval |
| DuckDuckGo | Web search |


## ⚙️ Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/Krish07chawla/Agentic_AI.git
```

### 2. Navigate to the project directory

```bash
cd Agentic_AI
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

### 4. Configure environment variables

Create a `.env` file in the project directory:

```env
GROQ_API_KEY=your_groq_api_key
```

Add any other API keys required by the individual agents.

### 5. Run an agent

For example, to run the Finance Agent:

```bash
python Finance.py
```

To run another agent:

```bash
python agent.py
python memory.py
python team.py
```

## 🎯 Learning Objectives

Through these implementations, I am exploring:

- Agent architecture and execution.
- Tool calling and external integrations.
- LLM-powered applications.
- Persistent memory and context management.
- Multi-agent collaboration and delegation.
- Building autonomous AI workflows.

## 🔮 Future Improvements

- Implement more advanced agentic workflows.
- Explore RAG (Retrieval-Augmented Generation).
- Build agents with multiple specialized tools.
- Improve multi-agent coordination.
- Integrate additional LLM providers.
- Develop and deploy more AI-powered applications.

## 👨‍💻 Author

**Krish Chawla**

B.Tech Computer Science Student | Exploring Agentic AI, Generative AI, Machine Learning and LLM Applications.

GitHub: [@Krish07chawla](https://github.com/Krish07chawla)

---

⭐ If you find this repository interesting, feel free to explore the projects and follow my journey into Agentic AI.
