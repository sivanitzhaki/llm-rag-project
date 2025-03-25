# RAG for Insurance Documents

## 📌 By Sivan Itzhaki

![download](https://github.com/user-attachments/assets/51f6c82a-2e93-4b84-841b-8fdd74bcf63c)


## 🔹 RAG-Based Insurance Policy Q&A System
This notebook presents an **AI-powered Q&A system** using Retrieval-Augmented Generation (RAG) to extract, analyze, and retrieve **accurate answers** from insurance policies.

## 🔥 Challenge
Insurance documents contain vast information on **terms, coverage, and obligations**. Retrieving relevant details efficiently is challenging, especially when handling **multiple documents**.

## ✅ Solution: RAG System
A **Retrieval-Augmented Generation (RAG) system** was developed to:
- **Retrieve relevant sections** using **FAISS** & embeddings.
- **Generate precise, context-aware answers** using a **Large Language Model (LLM)**.

## 🛠 Methodology
### 📄 Document Processing & Chunking
- **Preprocessing:** Removed unnecessary headers/footers, handled Hebrew formatting.
- **Chunking:** Used `RecursiveCharacterTextSplitter` to preserve context.

### 🔍 Embedding & LLM Selection
- **Embeddings:** Compared **OpenAI** vs. **MiniLM (Hugging Face)** for retrieval accuracy.
- **LLM:** Evaluated **GPT-4o** (faster, cost-effective) vs. **O1-mini** (detailed reasoning, slower).

### 🎯 Prompt Engineering
- Strict reliance on **retrieved content** to avoid **hallucinations**.
- **Source citation enforcement** for transparency.
- **Few-shot learning** to improve response consistency.

## 🚀 Outcome
A fully implemented **RAG system** providing **accurate, structured responses** from insurance policies.

## 🔮 Future Improvements
✔ Improve **document processing**.
✔ Refine **chunking structure**.
✔ Test alternative **embeddings & LLMs**.
✔ Optimize **prompt engineering** with examples.
✔ Monitor **LLM response quality**.
✔ Balance **cost vs. performance**.
✔ Implement a **UI interface** allowing users to ask questions and receive answers.

## 🎨 Example UI Interface

![download](https://github.com/user-attachments/assets/db1ce596-e46b-4851-88fa-16f3296cd87c)

---


