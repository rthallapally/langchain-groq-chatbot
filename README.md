# 🧠 LangChain GROQ Chatbot

An interactive chatbot application built with LangChain and Groq, deployed using Streamlit, leveraging LLMs to have engaging and intelligent conversations.

This project showcases how to integrate LangChain with Groq’s inference API, with configurable parameters and a clean, modular codebase.


# 🚀 Features
Uses LangChain and Groq for natural language understanding & response generation.

Streamlit-powered web interface.

Configurable temperature, max tokens, and model parameters via .env.

Easy to deploy locally or on the cloud.

Clear logging with colored output.


# 🔧 Installation

1️⃣ Clone the repo:

git clone <your-repo-url>

cd langchain-groq-chatbot


2️⃣ Install dependencies:

pip install -r requirements.txt


3️⃣ Set up your .env file:

…and fill in your GROQ_API_KEY and other parameters:

GROQ_API_KEY="your-key"

APP_NAME="LangChain Groq Chatbot"

MODEL_NAME="mixtral-8x7b-3276"

TEMPERATURE=0.7

MAX_TOKENS=1024

LOG_LEVEL="INFO"


# 🖥️ Usage

Run the chatbot with:

streamlit run app.py



# 📝 Requirements

Python ≥ 3.7

langchain

langchain-groq

python-dotenv

streamlit

requests

colorlog



# 🌟 Notes

Your .env contains sensitive information — don’t share it publicly

The .gitignore already excludes .env and any virtual environments



