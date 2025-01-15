<div align = "center">
<h1>LangGraph: Multi-Agent Workflows</h1>
</div>

## Introduction
Agentic workflows fundamentally change how we interact with LLMs by making it an iterative process. Instead of one-shot prompt, users and LLMs engage in a back-and-forth conversations. Users start by providing an initial prompt, the LLM clarifies or asks questions, and then refines its responses based on this conversation. This collaborative approach goes beyond simply generating text – it allows for a more nuanced and effective use of LLMs. 

This workshop focuses on the basics of LangGraph – the framework for building agentic and multi-agent applications. LangGraph allows LLMs to determine the control flow of an application and building systems that reliably execute these tasks. Therefore, in this workshop, we will focus on creating an Question Answering application with AgenticRAG together with the introduction of basic LangGraph techniques.

This workshop will focus on leveraging LangGraph to create a basic chatbot:
- Introduction to LangGraph
- Hands-on walkthrough of functionalities of LangGraph
- Creation of AgenticRAG with LangGraph

![image.png](assets/Architecture.drawio.png)
 
## Setup and Installation
- Clone the repository:
```
git clone
cd CDEFG_codebase
```

- To start, you need to first create a virtual environment and install all dependencies and all required libraries.
```
pip install virtualenv
python3.12 -m venv .venv
pip install -r requirements.txt
```

- Setting up API Keys
Create the .env file and populate the keys shown in .env.sample

- Access the .ipynb notebook



# CDEFG_workshop
