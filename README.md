# 🧠 Document Retriever Search Engine on Wikipedia Data

This project implements a lightweight, retrieval-based search engine on a simplified version of Wikipedia using modern AI tools like OpenAI Embeddings, Chroma Vector Database, and LangChain.

---

## 🚩 Problem Statement

The vastness of unstructured data like Wikipedia makes it challenging to extract relevant and meaningful information efficiently. Traditional keyword-based search systems often fall short in understanding context and semantics. 

**The goal of this project is to build a context-aware document retriever** that:
- Understands the meaning behind user queries
- Retrieves the most relevant Wikipedia passages
- Lays the groundwork for a full Retrieval-Augmented Generation (RAG) system

---

## 🛠️ What This Project Does

- Downloads a compressed Wikipedia dataset in `.jsonl.gz` format.
- Parses and pre-processes articles to extract key content (first 3 paragraphs).
- Converts the text into embeddings using OpenAI’s `text-embedding-3-small` model.
- Stores the embeddings in ChromaDB, an open-source vector database.
- Enables intelligent retrieval of similar articles/passages using LangChain's retrieval wrapper.

---

## 📂 Project Structure

```bash
.
├── M4_L12_Project_Build_a_Document_Retriever_Search_Engine.ipynb  # Main Notebook
├── simplewiki-2020-11-01.jsonl.gz                                # Wikipedia data (JSONL, compressed)
├── README.md                                                     # This file

```

## 🧪 Technologies Used
Python

OpenAI Embeddings API (text-embedding-3-small)

LangChain

Chroma Vector Database

JSONL & Gzip for data handling
