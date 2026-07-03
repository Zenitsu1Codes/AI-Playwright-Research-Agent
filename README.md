# 🕵️ AI Playwright Research Agent

An AI-powered web research assistant built with **LangGraph**, **LangChain**, **Playwright**, and **Groq LLM**. The agent can browse websites, navigate pages, extract information, and answer user questions by interacting with the web like a human.

Unlike traditional chatbots that rely only on pretrained knowledge, this agent uses a real browser to gather up-to-date information before generating responses.

---

# ✨ Features

* 🌐 Real browser automation using Playwright
* 🤖 AI-powered reasoning with Groq LLM
* 🧠 LangGraph agent workflow
* 🔍 Autonomous web navigation and research
* 📄 Extracts and summarizes webpage content
* 💬 Interactive Gradio chat interface
* ⚡ Memory support for multi-turn conversations
* 🔧 Modular tool-based architecture

---

# 🛠 Tech Stack

* Python
* LangGraph
* LangChain
* Groq (Llama 3.3)
* Playwright
* Gradio
* Python Dotenv
* Nest AsyncIO

---

# 📂 Project Structure

```text
playwright-research-agent/
│
├── playwright_researcher.ipynb
├── requirements.txt
├── .env
└── README.md
```

---

# 🧠 Architecture

```text
                 User Query
                      │
                      ▼
              LangGraph Agent
                      │
          ┌───────────┴───────────┐
          ▼                       ▼
     Groq LLM              Playwright Browser
          │                       │
          └───────────┬───────────┘
                      ▼
             Web Navigation & Search
                      │
                      ▼
             Extract Web Information
                      │
                      ▼
              Generate Final Answer
```

---

# 🚀 Features

* Browse websites using a real Chromium browser
* Navigate between pages automatically
* Extract content from websites
* Answer questions using live web data
* Maintain conversation history
* Tool-based AI agent powered by LangGraph

---

# ⚙️ Installation

Clone the repository:

```bash
git clone https://github.com/Zenitsu1Codes/AI-Playwright-Research-Agent.git

cd playwright-research-agent
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Install Playwright browsers:

```bash
playwright install
```

---

# 🔑 Environment Variables

Create a `.env` file:

```env
GROQ_API_KEY=your_groq_api_key
```

---

# ▶️ Usage

Run the notebook and ask questions such as:

* Research the latest AI news.
* Visit the LangGraph documentation and summarize it.
* Compare GPT-4 and Llama 3.
* Extract key points from a company website.

The agent will browse the web, gather information, and generate a structured response.

---

# 📚 Learning Outcomes

This project demonstrates:

* AI Agents
* LangGraph workflows
* Browser automation with Playwright
* Tool Calling
* LLM orchestration
* Memory management
* Web research automation
* Interactive AI applications

---

# 🔮 Future Improvements

* Multi-agent collaboration
* PDF and report generation
* Citation support
* Screenshot capture
* Web search integration
* Parallel browsing
* Deployment with FastAPI or Streamlit

---

# 👨‍💻 Author

**Harsh Asarsa**

AI • Python • Agentic AI • LangGraph • Automation

If you found this project useful, consider giving it a ⭐ on GitHub.
