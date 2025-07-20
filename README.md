# 🤖 BASIC_CHATBOT

A modular and scalable conversational AI chatbot built with **LangChain**, **LangGraph**, and **Streamlit**. This chatbot serves as a foundational framework for building more advanced agentic and LLM-based assistants, showcasing how to structure workflows and handle state management using modern tools in the generative AI ecosystem.

---

## 🧠 Project Overview

This project demonstrates how to use **LangChain** for language model orchestration and **LangGraph** to build stateful, agentic workflows in a modular design. It includes:

- A simple but extensible chatbot interface
- Clear separation of state, logic, and UI
- Integration with LLMs (OpenAI/Groq/Gemini-ready)
- Streamlit frontend for user interaction
- Easily pluggable nodes for advanced agent behaviors

---

## 🔧 Features

✅ LangChain-powered LLM backend  
✅ LangGraph for building agentic workflows  
✅ Modular structure (state, nodes, graph)  
✅ Streamlit web interface  
✅ Easy to extend with new features or LLMs  
✅ Supports multiple model providers  

---

## 🛠️ Tech Stack

| Component     | Role                                 |
|---------------|--------------------------------------|
| Python        | Programming language                 |
| LangChain     | LLM orchestration & chaining         |
| LangGraph     | Agentic state-based graph structure  |
| Streamlit     | Web-based user interface             |
| OpenAI/Groq   | LLM providers (configurable)         |

---

## 📁 Project Structure

```text
BASIC_CHATBOT/
├── src/
│   └── langgraphagenticai/
│       ├── nodes/
│       │   └── basic_chatbot_node.py  # LLM node logic
│       ├── state/
│       │   └── state.py               # Chat state definition
│       └── main.py                    # Graph setup and build
├── app.py                             # Streamlit app interface
├── requirements.txt
└── README.md
