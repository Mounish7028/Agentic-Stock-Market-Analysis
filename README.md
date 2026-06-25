# 🤖 Intelligent Single-Agent AI System using LangGraph

An intelligent AI assistant built using **LangGraph**, **LangChain**, **Qwen3-14B (LM Studio)**, and **Google Gemini 2.5 Flash**. The agent autonomously reasons about user queries, selects the appropriate tools, maintains conversation memory, and returns accurate responses through an orchestrated workflow.

---

## 🚀 Features

* 🧠 Intelligent reasoning using **Qwen3-14B** running locally via **LM Studio**
* 🔄 Agent orchestration with **LangGraph**
* 💬 Multi-turn conversation memory
* 🌐 Web search integration using DuckDuckGo
* 🧮 Safe mathematical calculations
* 📈 Real-time stock market analysis using Yahoo Finance
* ✍️ AI-powered text summarization with Gemini 2.5 Flash
* 🛠️ Modular tool architecture using LangChain Tools
* 📚 Structured notebook with explanations and workflow visualization

---

## 🏗️ Architecture

```text
               User Query
                    │
                    ▼
        Qwen3-14B (LM Studio)
                    │
            LangGraph Agent
                    │
        ┌───────────┼───────────┐
        │           │           │
        ▼           ▼           ▼
   Web Search   Calculator   Stock Tool
        │                       │
        └───────────┬───────────┘
                    ▼
          Gemini Summarizer
                    │
                    ▼
            Final AI Response
```

---

## 🛠️ Tech Stack

| Category      | Technologies               |
| ------------- | -------------------------- |
| Framework     | LangGraph, LangChain       |
| LLM           | Qwen3-14B (LM Studio)      |
| Secondary LLM | Gemini 2.5 Flash           |
| Search        | DuckDuckGo Search          |
| Finance       | Yahoo Finance (yFinance)   |
| Language      | Python                     |
| Memory        | LangGraph State Management |
| Notebook      | Jupyter Notebook           |

---

## 📂 Project Structure

```text
langgraph_single_agent.ipynb
│
├── Environment Setup
├── Imports & Configuration
├── Tool Creation
│   ├── Web Search Tool
│   ├── Calculator Tool
│   ├── Stock Analysis Tool
│   └── Gemini Summarizer
├── Agent State
├── LangGraph Workflow
├── Memory Management
├── Example Queries
└── Interactive Chat Interface
```

---

## ⚙️ Available Tools

### 🔍 Web Search

Retrieves up-to-date information from the internet using DuckDuckGo.

### 🧮 Calculator

Safely evaluates mathematical expressions and performs statistical calculations.

### 📈 Stock Analysis

Fetches historical stock prices and enables calculations such as averages and trends using Yahoo Finance.

### ✍️ AI Summarizer

Uses Gemini 2.5 Flash to generate concise summaries of lengthy text.

---

## 💡 Example Queries

```text
What is the capital of Japan?

Search the latest AI news.

Calculate (25 * 8) + 120 / 5

What is the average stock price of TCS over the last 7 days?

Summarize this article:
<insert long text>
```

---

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/your-repository.git
cd your-repository
```

### 2. Install Dependencies

```bash
pip install -r requirements.txt
```

### 3. Configure

* Start **LM Studio**
* Load the **Qwen3-14B** model
* Configure the OpenAI-compatible local endpoint
* Add your **Gemini API Key**

### 4. Run

Open the notebook:

```bash
jupyter notebook
```

Execute all cells and start interacting with the AI agent.

---

## 📌 Learning Highlights

* Building AI agents using LangGraph
* Tool calling with LangChain
* Local LLM deployment using LM Studio
* Hybrid LLM architecture (Local + Cloud)
* Stateful conversation memory
* Multi-tool orchestration
* Agent workflow design and execution

---

## 📖 Future Enhancements

* Multi-Agent Architecture
* RAG with Vector Databases
* Persistent Memory
* Streaming Responses
* Voice Input & Output
* FastAPI/Flask Deployment
* Docker Support
* Authentication & User Sessions

---

## 🤝 Contributing

Contributions, feature requests, and suggestions are welcome. Feel free to fork the repository and submit a pull request.

---

## 📜 License

This project is intended for educational and research purposes. Feel free to modify and extend it for your own learning.

---

## 👨‍💻 Author

**Mounish Reddy**

If you found this project useful, consider giving it a ⭐ on GitHub!
