# 🤖 Gemini Pro — AI Chatbot

An AI-powered conversational chatbot built using **Python, Streamlit, and the Google Gemini API**. The application provides an interactive interface for users to ask questions and receive AI-generated responses through multi-turn conversations.

## 📌 Project Overview

Gemini Pro — AI Chatbot demonstrates the integration of a generative AI model into a Python web application. Using Streamlit for the user interface and the Google Gemini API for AI-generated responses, the project explores conversational AI and practical applications of large language models (LLMs).

## ✨ Features

- 💬 **AI-Powered Conversations:** Generate responses to user prompts using the Gemini API.
- 🔄 **Multi-Turn Interaction:** Support conversational exchanges across multiple messages.
- 🖥️ **Interactive Web Interface:** Use a simple interface built with Streamlit.
- 🐍 **Python Integration:** Connect application logic with the generative AI API.
- ⚡ **Real-Time Responses:** Display responses when the API returns them.
- 🔑 **API Configuration:** Connect to Google's Gemini service using an API key.

## 🛠️ Tech Stack

| Technology | Purpose |
|---|---|
| Python | Application logic |
| Streamlit | Web interface |
| Google Gemini API | Generative AI responses |
| LLMs | Conversational text generation |

## 🏗️ How It Works

```text
User enters a prompt
        │
        ▼
Streamlit Interface
        │
        ▼
Python Application
        │
        ▼
Google Gemini API
        │
        ▼
AI-Generated Response
        │
        ▼
Response displayed to user
```

## ⚙️ Getting Started

### Prerequisites

- Python 3.9 or a compatible version
- pip
- A Google Gemini API key

### 1. Clone the Repository

```bash
git clone https://github.com/Kirankavala143/Ml-Projects.git
cd Ml-Projects
```

### 2. Navigate to the Project Directory

```bash
cd gemini-pro-streamlit-chatbot-main
```

### 3. Install Dependencies

If the project contains a `requirements.txt` file, run:

```bash
pip install -r requirements.txt
```

Otherwise, install the packages required by the source code.

### 4. Configure Your API Key

Set up your Gemini API key using the configuration method expected by the application. For example, if the application reads an environment variable named `GOOGLE_API_KEY`:

```env
GOOGLE_API_KEY=your_gemini_api_key
```

Never commit API keys, passwords, or other secrets to GitHub.

### 5. Run the Application

If the main application file is named `app.py`, run:

```bash
streamlit run app.py
```

Use the actual Python filename if it differs.

## 🎯 Use Cases

- Conversational AI applications
- Generative AI experimentation
- Question answering
- Learning and exploring large language models
- Building interactive Python AI applications

## 📚 What I Learned

- Integrating a generative AI API into a Python application
- Building interactive interfaces using Streamlit
- Processing user prompts and displaying model responses
- Understanding multi-turn conversational interactions
- Managing API configuration for AI-powered applications

## 👨‍💻 Project Information

- **Project Name:** Gemini Pro — AI Chatbot
- **Category:** Generative AI / Conversational AI
- **Technologies:** Python, Streamlit, Google Gemini API
- **Repository:** [ML-Projects on GitHub](https://github.com/Kirankavala143/Ml-Projects)

---

⭐ Explore the repository to learn more about the implementation.

**Built with Python, Streamlit, and Google Gemini.**
