# 🔍 Retrieval-Augmented Generation (RAG) using LangChain & Google Gemini

This project demonstrates how to build a **Retrieval-Augmented Generation (RAG)** pipeline using [LangChain](https://www.langchain.com/), [Chroma](https://www.trychroma.com/), and [Google Gemini](https://deepmind.google/technologies/gemini/). It retrieves relevant information from a real webpage, embeds the content using Gemini's embedding model, stores it in a vector database, and uses a language model to answer user queries based on retrieved context.

---

## 🚀 Features

- 📄 Loads and parses a live webpage using `WebBaseLoader`
- ✂️ Splits large documents into chunks using `RecursiveCharacterTextSplitter`
- 🧠 Embeds text with `GoogleGenerativeAIEmbeddings` (Gemini model)
- 📦 Stores and retrieves embeddings using `Chroma` vector store
- 🤖 Uses `ChatGoogleGenerativeAI` (Gemini 1.5 Pro) to generate answers
- 🔗 Chains components with LangChain to create an efficient RAG pipeline

---

## 📚 Technologies Used

- Python 🐍
- [LangChain](https://docs.langchain.com/)
- [Google Generative AI (Gemini)](https://ai.google.dev/)
- [Chroma Vector DB](https://docs.trychroma.com/)
- `beautifulsoup4` for HTML parsing

---

## 🧪 Use Case

A modular and reproducible pipeline to:
- Build question-answering bots over web or private content
- Understand how LLMs like Gemini can be enhanced using vector-based retrieval
- Prototype custom RAG applications quickly

---

## 🛠 Setup Instructions

1. **Clone the repository**
   ```bash
   git clone https://github.com/mahmoodalikhan1999/rag_langchain_gemini/rag-langchain-gemini.git
   cd rag-langchain-gemini
