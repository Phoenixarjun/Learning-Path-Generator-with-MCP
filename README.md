# 🚀 Learning Path Generator with Model Context Protocol (MCP)

[![MCP](https://img.shields.io/badge/MCP%20Enabled-Yes-blueviolet)]()
[![License: MIT](https://img.shields.io/badge/License-MIT-lightgrey.svg)](https://opensource.org/licenses/MIT)
[![LangChain](https://img.shields.io/badge/LangChain-💡%20LLM%20Orchestration-blue)](https://github.com/langchain-ai/langchain)
[![LangGraph](https://img.shields.io/badge/LangGraph-⚙️%20Multi-Agent%20Workflows-purple)](https://github.com/langchain-ai/langgraph)
[![LangChain MCP](https://img.shields.io/badge/LangChain--MCP-🔗%20Real%20World%20Actions-brightgreen)](https://github.com/langchain-ai/langchain-mcp)
[![Google GenAI](https://img.shields.io/badge/LangChain--Google%20GenAI-🌐%20Search%20Enabled-lightblue)](https://github.com/langchain-ai/langchain-google-genai)
[![Streamlit](https://img.shields.io/badge/Streamlit-🖥️%20Frontend-orange)](https://streamlit.io)

> ✨ **An AI-powered Streamlit app that generates intelligent, goal-based learning journeys by combining the power of LLMs, real-time APIs, and workflow automation — all orchestrated through Model Context Protocol (MCP).**

## 📌 Overview

This project transforms a simple learning goal like  
> _"I want to learn Python basics in 3 days"_  
into a fully structured, personalized learning path with YouTube video modules, document storage via Google Drive or Notion, and automatic task tracking — in seconds.

Whether you're an independent learner or building scalable AI workflows, this project shows how to move from **prompts ➝ real-world outcomes.**

---

## 🧠 Built With

| Stack                        | Description                                                                 |
|-----------------------------|-----------------------------------------------------------------------------|
| **LangChain**               | Framework for building LLM-powered applications with modular components.   |
| **LangGraph**               | Graph-based system for orchestrating multi-agent, stateful AI workflows.   |
| **LangChain-MCP Adapters**  | Bridges LLMs with real-world tools (Drive, Notion, Gmail) via MCP.         |
| **LangChain-Google GenAI**  | Connects to Google’s Generative AI models for real-time content retrieval. |
| **Streamlit**               | Python framework for building interactive, data-driven web apps.           |


---

## ⚙️ Features

- 🎯 Generate **goal-based learning paths**
- 🎥 **YouTube integration** for curated video lessons
- 📁 Sync with **Google Drive** for docs & resources
- 📝 Auto-create structured notes in **Notion**
- 🔁 **Real-time progress tracking**
- 🧠 Powered by **MCP (Model Context Protocol)**
- 🎨 Clean, fast UI built with Streamlit

---

## 📸 Screenshots

| Home Page | Learning Path |
|----------|----------------|
| <img width="1919" height="894" alt="Screenshot 2025-07-20 190327" src="https://github.com/user-attachments/assets/f81a8303-d214-4e4b-a461-83777fc7be1d" /> | <img width="1917" height="898" alt="Screenshot 2025-07-20 190344" src="https://github.com/user-attachments/assets/3629ede1-8e42-44d2-a272-1b22d878ffcc" />

---

## 🔑 Prerequisites

- Python **3.10+**
- [Google AI Studio API Key](https://makersuite.google.com/app)
- **Pipedream endpoints** for:
  - YouTube (required)
  - Google Drive or Notion (pick one or both)

---

## 🛠 Installation

```bash
# Clone the repo
git clone https://github.com/Phoenixarjun/Learning-Path-Generator-with-MCP
cd Learning-Path-Generator-with-MCP

# Create virtual environment
python -m venv venv
.\venv\Scripts\activate   # For Windows

# Install dependencies
pip install -r requirements.txt
````

---

## ⚙️ Configuration

Before launching the app, set your secrets in the sidebar or use `.env` variables:

* Google AI Studio API key
* YouTube integration URL (via Pipedream)
* Notion or Google Drive endpoint URL

---

## ▶️ Running the App

```bash
streamlit run app.py
```

Then open: `http://localhost:8501` in your browser.

---

## 🧠 How It Works

1. User enters learning goal (e.g., "Learn Python in 7 days")
2. LLM + MCP converts it to an action plan
3. Connects to YouTube for videos
4. Optionally syncs notes to Notion or Drive
5. Displays progress in real-time with a simple UI

---

## 📁 Project Structure

```
mcp-learning-path/
├── app.py               # Main Streamlit app
├── utils.py             # Helper functions
├── prompt.py            # Prompt templates
├── requirements.txt     # Dependencies
├── screenshots/         # UI screenshots
└── README.md            # Project documentation
```

---

## 👨‍💻 Author

**Naresh B A**
🚀 Full Stack Developer | AI/ML Explorer | LLMs & Agentic AI | NLP Enthusiast
Crafting future-ready solutions by blending code, cognition, and creativity.
[LinkedIn](https://www.linkedin.com/in/nareshba) • [GitHub](https://github.com/nareshbabu8)

---

## 📄 License

This project is licensed under the **MIT License**. See the [LICENSE](LICENSE) file for details.

---

## 💬 Feedback & Contributions

Feel free to raise issues or submit PRs. Ideas, improvements, or collaborations — all are welcome!
