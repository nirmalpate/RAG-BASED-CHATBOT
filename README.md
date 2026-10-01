# RAG-BASED-CHATBOT
RAG BASED FULLY FLEDGE PROJECT 
# 🔍 Production RAG & Vector Search Engine

An end-to-end **Retrieval-Augmented Generation (RAG)** pipeline and vector search engine built with **Python**, **LangChain**, **Sentence-Transformers**, **ChromaDB**, and **Scikit-Learn**. 

This repository demonstrates how to ingest documents, split them into optimal text chunks, generate high-dimensional vector embeddings, index them in an **HNSW graph**, and perform fast vector similarity search with manual cosine similarity re-ranking.

---

## 🛠️ Tech Stack & Dependencies

* **Language:** Python 3.9+
* **Framework:** [LangChain](https://www.langchain.com/) (Document loading & text splitting)
* **Embedding Model:** [Sentence-Transformers](https://www.sbert.net/) (`all-MiniLM-L6-v2`)
* **Vector Database:** [ChromaDB](https://www.trychroma.com/) (HNSW Graph Indexing)
* **Math & Re-Ranking:** NumPy & Scikit-Learn (`cosine_similarity`)

---

## 🏗️ Architecture & Data Pipeline Flow
