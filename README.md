# 🤖 Agentic AI – Multi-Agent Intelligence Platform

An AI-powered multi-agent platform built with **Python, Agno, Groq, and Streamlit**. This project demonstrates the power of Agentic AI by combining multiple specialized AI agents to perform different real-world tasks, including travel assistance, financial analysis, persistent memory management, multilingual communication, and YouTube video analysis.

The platform integrates Large Language Models (LLMs) with external tools and APIs to deliver intelligent, context-aware, and research-driven responses.

---

## 🚀 Features

### ✈️ 1. AI Travel Agent

An intelligent travel assistant designed to help users explore destinations and research travel-related information.

**Key Features:**
- Provides travel-related assistance.
- Searches the web using DuckDuckGo.
- Researches travel destinations and safety information.
- Includes current date and time in the AI context.
- Generates helpful and informative travel recommendations.

### 📈 2. AI Financial Analyst

An AI-powered financial research agent that provides stock market information and financial insights.

**Key Features:**
- Retrieves stock market prices.
- Researches analyst recommendations.
- Analyzes stock fundamentals.
- Uses Yahoo Finance tools for financial data.
- Uses DuckDuckGo for additional financial research.
- Presents financial information in structured Markdown tables.

### 🧠 3. AI Memory Agent

An AI agent that stores and retrieves user-specific information using an SQLite database.

**Key Features:**
- Stores user-specific memories.
- Maintains conversation history.
- Retrieves previously stored information.
- Supports personalized AI interactions.
- Uses SQLite for persistent memory storage.

### 🌐 4. Multilingual AI Agent Team

A collaborative AI team designed to generate responses in multiple languages.

**Available Agents:**
- 🇬🇧 English Agent
- 🇨🇳 Chinese Agent
- 🇮🇳 Hindi Agent
- 🇧🇩 Bangla Agent

**Key Features:**
- Uses Agno Team to coordinate multiple agents.
- Provides multilingual responses.
- Assigns a specific language to each agent.
- Displays individual agent responses.

### 🎥 5. AI YouTube Video Analyzer

An AI-powered YouTube video analysis application with a Streamlit web interface.

**Key Features:**
- Analyzes YouTube video content.
- Extracts video transcripts using YouTube Tools.
- Generates structured video summaries.
- Creates meaningful timestamp segments.
- Identifies major topics and key learning points.
- Organizes video content into detailed analysis reports.
- Provides a simple web interface using Streamlit.

---

## 🛠️ Technologies & Tools

| Technology | Purpose |
|---|---|
| Python | Core Programming Language |
| Agno | AI Agent Framework |
| Groq | AI Model Inference |
| GPT-OSS 120B | Large Language Model |
| OpenAI | Alternative LLM Integration |
| Streamlit | Web Application Interface |
| SQLite | Persistent Memory Database |
| DuckDuckGo | Web Search Integration |
| Yahoo Finance | Stock Market Data |
| YouTube Tools | YouTube Video Analysis |
| YouTube Transcript API | Transcript Extraction |
| Python Dotenv | Environment Variable Management |
| Rich | Terminal Output Formatting |

---

## 📂 Project Structure

```text
AGENTIC_AI/
│
├── agent.py
│   └── AI Travel Agent
│
├── finanace.py
│   └── AI Financial Analyst
│
├── memory.py
│   └── AI Memory Agent
│
├── team.py
│   └── Multilingual AI Agent Team
│
├── youtube_analyzer.py
│   └── YouTube Analysis Agent
│
├── ui.py
│   └── Streamlit Web Interface
│
├── requirements.txt
│
├── .env
│   └── API Keys and Environment Variables
│
├── .gitignore
│
├── README.md
│
└── agno.db
    └── SQLite Database (Generated Locally)
```

---

## ⚙️ Installation & Setup

Follow these steps to run the project on your local machine.

### 1. Clone the Repository

```bash
git clone YOUR_GITHUB_REPOSITORY_URL
```

### 2. Navigate to the Project Directory

```bash
cd AGENTIC_AI
```

### 3. Create a Virtual Environment

```bash
python -m venv venv
```

### 4. Activate the Virtual Environment

**Windows PowerShell:**

```powershell
venv\Scripts\Activate.ps1
```

If PowerShell blocks script execution, use:

```powershell
venv\Scripts\activate.bat
```

### 5. Install Dependencies

```bash
python -m pip install -r requirements.txt
```

### 6. Configure Environment Variables

Create a `.env` file in the root project directory.

Add your API keys:

```env
OPENAI_API_KEY=your_openai_api_key
GROQ_API_KEY=your_groq_api_key
```

**API Key Resources:**

- [OpenAI API Keys](https://platform.openai.com/api-keys)
- [Groq API Keys](https://console.groq.com/keys)

**Important:** Never upload your `.env` file or expose your API keys publicly.

---

## 📦 Required Dependencies

Create a `requirements.txt` file with the following packages:

```text
agno
openai
groq
python-dotenv
sqlalchemy[asyncio]
greenlet
rich
ddgs
yfinance
youtube-transcript-api
streamlit
```

Install all dependencies:

```bash
pip install -r requirements.txt
```

---

## ▶️ Run the Project

Each AI agent can be executed independently.

### Run AI Travel Agent

```bash
python agent.py
```

### Run AI Financial Analyst

```bash
python finanace.py
```

### Run AI Memory Agent

```bash
python memory.py
```

### Run Multilingual AI Team

```bash
python team.py
```

### Run YouTube Analyzer

```bash
streamlit run ui.py
```

After starting Streamlit, open your browser:

```text
http://localhost:8501
```

Enter a YouTube video URL and click **Analyze Video** to generate the analysis report.

---

## 🔐 Environment & Security

This project uses environment variables to protect API credentials.

The `.env` file should never be committed to GitHub.

Recommended `.gitignore` configuration:

```gitignore
.env
venv/
__pycache__/
*.pyc
agno.db
*.db
.streamlit/secrets.toml
```

Keep your API keys private and use secure environment variables when deploying the application.

---

## 🎯 Project Objectives

- Understand the fundamentals of Agentic AI.
- Build specialized AI agents using the Agno framework.
- Integrate external tools with AI agents.
- Explore multi-agent collaboration.
- Implement persistent AI memory using SQLite.
- Work with financial and web search APIs.
- Analyze YouTube videos using AI.
- Develop AI-powered web applications using Streamlit.
- Gain practical experience with LLM-based application development.

---

## 🔮 Future Improvements

- Develop a unified AI assistant dashboard.
- Add more specialized AI agents.
- Implement cloud-based persistent memory.
- Add user authentication and authorization.
- Improve YouTube transcript and timestamp accuracy.
- Introduce interactive financial charts and visualizations.
- Build a modern React-based frontend.
- Integrate FastAPI for backend services.
- Deploy the platform with cloud infrastructure.

---

## 👨‍💻 Author

**Famid Khandoker**

Computer Science & Engineering Student

**Areas of Interest:**
- Artificial Intelligence
- Agentic AI
- Python Development
- Full-Stack Web Development
- Software Engineering

---

## ⭐ Support

If you find this project useful or interesting, consider giving it a ⭐ on GitHub.

Your support and feedback are always appreciated!

---

**Built with Python, Agno, Groq, and a passion for Artificial Intelligence.**
