# GenAI-Based Article Chatbot 🤖📄

This project is a **Generative AI chatbot** that extracts information from uploaded articles and answers user queries contextually. It uses **LangChain**, **Mistral API**, and **FAISS** to build a Retrieval-Augmented Generation (RAG) pipeline.

---

## 🔧 Tech Stack

- **LangChain** – Orchestrates chatbot flow and prompt templates.
- **Mistral API** – Powers the LLM (Large Language Model) responses.
- **FAISS** – Vector database to store and retrieve embedded article chunks.
- **Python** – For backend logic and data processing.
- **Streamlit** *(optional)* – For basic web UI.

---

## 💡 Features

- Upload article or PDF
- Extract and chunk article content
- Store chunks as vector embeddings using FAISS
- Answer user queries using context from stored vectors
- Uses RAG to ensure accurate, grounded responses

---

## 🚀 Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/genai-article-chatbot.git
   cd genai-article-chatbot
