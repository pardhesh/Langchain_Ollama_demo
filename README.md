# Langchain Ollama Demo 🚀

This is a simple Streamlit demo app that integrates [LangChain](https://www.langchain.com/) with [Ollama](https://ollama.com/) to run local LLMs. It uses a chat-based prompt to respond to user questions using the `gemma3:1b` model.

## 🔧 Requirements

- Python 3.9+
- [Ollama](https://ollama.com/) installed and running locally
- LangChain
- Streamlit
- python-dotenv (for environment variables)
.

🧠 What It Does
Takes a question from the user via Streamlit UI

Uses a structured prompt template

Sends the question to a local Ollama LLM (gemma3:1b)

Displays the model's response in the browser

📌 Notes
You can change the model (e.g., to mistral or llama2) if gemma3:1b doesn't run well on your system.

Ensure Ollama is running in the background!

