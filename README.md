📌 Overview

The AI Blog Writing Agent is an agentic AI system that automatically generates complete blog articles from a user prompt.

Unlike traditional prompt-based LLM applications, this project implements a planning-based multi-agent architecture that breaks a task into smaller subtasks, performs internet research when required, and synthesizes the results into a structured blog post.

The system uses LangGraph orchestration with multiple specialized agents responsible for planning, researching, writing, and compiling the final article.

This project demonstrates how modern AI agents are built in production systems using orchestration patterns instead of simple prompts.


🚀 Features

🧠 Planning-based AI Agent
----The agent plans how to generate the blog before execution.

🔎 Automated Internet Research
----Uses external search tools to gather relevant information.

👷 Worker Agents
--Multiple workers generate different blog sections.

🖼 Automatic Image Generation
----Images are added dynamically to improve readability.

📚 Citation Support
----Sources used during research can be referenced.

🔄 Reducer Node
----Combines all generated sections into a final article.

🌐 Streamlit UI
----Simple interface to generate blogs interactively.

🛠️ Tech Stack

AI & LLM
------LangChain
 LangGraph
OpenAI / Gemini LLMs

Backend
-------Python

Tools
-------Tavily Search API
Prompt Engineering
   Agent Orchestration

Interface
-------Streamlit
