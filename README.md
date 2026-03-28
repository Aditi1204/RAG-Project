# 🧠 RAG System with OpenAI + ChromaDB

A simple **Retrieval-Augmented Generation (RAG)** project built using **OpenAI API**, **LangChain**, and **ChromaDB** for persistent local vector storage.

---

## 🚀 Features

* 🔍 Retrieve relevant information from your own text data
* 🧠 Generate answers using OpenAI LLM
* 💾 Store embeddings locally using ChromaDB (persistent memory)
* ⚡ Fast and scalable retrieval
* 📂 Works with custom documents

---

## 🏗️ Tech Stack

* **OpenAI API** (LLM + embeddings)
* **LangChain**
* **ChromaDB** (vector database)
* **Python**

---

## 📌 What is RAG?

Retrieval-Augmented Generation (RAG) combines:

1. **Retriever** → Fetch relevant chunks from your data
2. **Generator (LLM)** → Generate answers using retrieved context

---

## 📂 Project Structure

```
├── data/                # Your custom documents
├── chroma_db/           # Persistent vector storage
├── app.py               # Main application
├── requirements.txt
└── README.md
```

---



## 🔄 How It Works

1. Load documents from `data/`
2. Split text into chunks
3. Convert text → embeddings using OpenAI
4. Store embeddings in **ChromaDB**
5. On query:

   * Retrieve relevant chunks
   * Pass to LLM
   * Generate answer

---

## 🧠 Example Flow

```
User Query → Embed Query → Retrieve Docs → LLM → Answer
```

---

## 💾 Persistent Memory (ChromaDB)

* Stores embeddings locally
* No need to recompute every time
* Faster retrieval
* Works offline after indexing

---

## 📸 Example Output

```
Q: What is RAG?
A: RAG is a technique that combines retrieval and generation...
```

---

## 🛠️ Future Improvements

* Add PDF / CSV support
* Add UI (Streamlit / React)
* Add multi-document support
* Deploy as API

---


## ⭐ Acknowledgements

* OpenAI
* LangChain
* ChromaDB
