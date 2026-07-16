# Agentic AI Engineering Course 🤖

Welcome to the **Agentic AI Engineering Course** repository! This repository contains all the code, notebooks, presentations, and resources you need to master building autonomous AI agents and agentic workflows.

## 📖 About The Course

This course takes you on a comprehensive journey from understanding the fundamentals of AI agents to building complex, multi-agent systems and integrating them using state-of-the-art frameworks and protocols. You will learn to work with industry-standard tools like **OpenAI Agents SDK, AutoGen, LangGraph, CrewAI, MCP, and n8n**.

Whether you're looking to automate workflows, build AI tutors, or orchestrate teams of AI agents, this repository provides hands-on, practical examples to guide your learning.

## 🗂️ Course Structure

The course is divided into progressive modules, each focusing on a core technology or concept in the Agentic AI ecosystem:

### Module 1: Introduction
- Introduction to Agentic AI principles and concepts.
- **Resources**: `Module 1.pptx`

### Module 2: OpenAI Agents SDK - Single Agent
- Learn to build your first AI agent.
- Empower your agents with memory and tool-calling capabilities.
- **Projects**:
  - `1. Build a Simple AI Agent With OpenAI Agents SDK.ipynb`
  - `2. AI Agents with Memory.ipynb`
  - `3. AI Agents with Tools.ipynb`

### Module 3: OpenAI Agents SDK - Multi Agents
- Transition from single to multi-agent workflows.
- Implement guardrails and seamless agent handoffs.
- **Projects**:
  - `4. Build Multi AI Agents Workflows.ipynb`
  - `5. Autonomous AI Agents with Gaurdrails and Handoffs.ipynb`

### Module 4: AutoGen
- Build interactive, multi-model AI agent teams using Microsoft's AutoGen.
- **Projects**:
  - `Building Interactive Multi-Model AI Agent Teams with AutoGen.ipynb`

### Module 5: LangGraph
- Design complex, stateful agentic AI workflows using LangGraph.
- **Projects**:
  - `Build Agentic AI Workflows Using LangGraph.ipynb`

### Module 6: CrewAI
- Automate data science and predictive analytics tasks using role-playing AI agents.
- **Projects**:
  - `Automating Data Science with CrewAI Agents.ipynb`
  - `Predictive Analytics Using Machine Learning.ipynb`

### Module 7: MCP Servers
- Understand the Model Context Protocol (MCP).
- Build practical applications like an AI Tutor.
- **Projects**:
  - `Build an AI Tutor Using MCP and OpenAI Agents SDK.ipynb`
  - `MCP Server.ipynb`
  - `mcp.ipynb`

### Module 8: n8n (No-Code/Low-Code Workflows)
- Construct visual agentic workflows.
- Integrate APIs, memory, Google Sheets, calendars, and email triggers.
- **Workflows include**: Basic Summarization, Memory & Search API, Structured Output, Tooling, and more (`.json` templates provided).

### Additional Materials
- **Prompt Library**: A curated collection of prompts to enhance your agent's performance (`Prompt Library.docx`).
- **Datasets**: Practical datasets (e.g., `cancer.csv`, `Supplement_Sales_Weekly.csv`) for hands-on machine learning and data science projects.

## 🚀 Getting Started

### Prerequisites

To get the most out of this repository, you should have the following installed:
- **Python 3.8+**
- **Jupyter Notebook / JupyterLab** or an IDE like **VS Code** with Jupyter support.
- API Keys for the respective services (e.g., OpenAI API Key).
- **n8n** (if running the Module 8 workflows locally).

### Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/kumarprakhar14/Agentic_AI_Course.git
   cd Agentic_AI_Course
   ```

2. **Set up a virtual environment (recommended):**
   ```bash
   python -m venv venv
   
   # On Windows
   venv\Scripts\activate
   
   # On macOS/Linux
   source venv/bin/activate
   ```

3. **Install dependencies:**
   Each module's notebook contains the specific `pip install` commands required for that section. Ensure you run those cells first before executing the core logic.

4. **Environment Variables:**
   Create a `.env` file in the root directory or inside specific modules to store your API keys:
   ```env
   OPENAI_API_KEY="your-api-key-here"
   ```

## 🧠 How to Use This Repository

- **Notebooks (`.ipynb`)**: Follow the Jupyter notebooks sequentially within each module. They contain the code, explanations, and outputs.
- **Presentations (`.pptx`)**: Review the slide decks in each module folder for theoretical foundations before diving into the code.
- **n8n Workflows (`.json`)**: Import these files directly into your n8n instance to explore no-code AI automation.

## 🤝 Contributing

This is a learning repository, but suggestions for improvements or additional examples are always welcome! Feel free to open an issue or submit a pull request.

## 📄 License

*This repository is intended for educational purposes as part of the Agentic AI Engineering Course.*
