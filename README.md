# 💬 Gen AI Chatbot

A simple conversational chatbot built with **Streamlit** and **LangChain Groq**, powered by the Groq LLM API.

## Features

- 🤖 Chat with a Groq-powered LLM
- 🧠 Maintains full conversation history in session
- ⚡ Fast inference via Groq API
- 🌐 Runs locally or in GitHub Codespaces

## Setup

### 1. Clone the repo

```bash
git clone https://github.com/YOUR_USERNAME/streamlit-genai-chatbot.git
cd streamlit-genai-chatbot
```

### 2. Install dependencies

```bash
pip install -r requirements.txt
```

### 3. Configure your API key

Copy the example env file and add your Groq API key:

```bash
cp .env.example .env
```

Then edit `.env`:

```
GROQ_API_KEY=your_groq_api_key_here
```

Get a free API key at [console.groq.com](https://console.groq.com).

### 4. Run the app

```bash
streamlit run chatbot.py
```

Open [http://localhost:8501](http://localhost:8501) in your browser.

## Run in GitHub Codespaces

This project includes a `.devcontainer` configuration. Simply open it in Codespaces and the app will start automatically.

> ⚠️ Remember to set your `GROQ_API_KEY` as a Codespaces secret.

## Tech Stack

- [Streamlit](https://streamlit.io/) — UI framework
- [LangChain Groq](https://python.langchain.com/docs/integrations/chat/groq/) — LLM integration
- [Groq API](https://console.groq.com/) — Fast LLM inference
