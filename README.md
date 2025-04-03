# Expert Knowledge Worker

## Author: [Pouria Ebrahimnezhad]

**Date:** [2025-01-25]

---

## 📌 Overview

The **Expert Knowledge Worker** is an AI-powered conversational chatbot designed to answer questions about a fictional company, **InsureLLM**, and its products, policies, and employees.

This project implements **Retrieval-Augmented Generation (RAG)** to enhance the chatbot’s response accuracy by retrieving relevant information before generating answers. The focus is on **cost-effectiveness and accuracy**, ensuring an efficient knowledge assistant.

---

## 🛠️ Technologies Used

- **Python** – Core programming language.
- **LangChain** – Document loading, chunking, and retrieval.
- **OpenAI GPT-4o-mini** – Low-cost yet powerful language model.
- **OpenAI Embeddings** – Converts text into vector representations.
- **ChromaDB** – Stores and retrieves vector embeddings efficiently.
- **Gradio** – Provides an interactive web interface.
- **FAISS** (Optional) – Alternative high-performance vector search.
- **dotenv** – Manages API keys securely.

---

## 📸 Screenshot of Application Output

\
*(Replace the above path with the actual location of the image in your repository.)*

---

## 📥 Installation

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/yourusername/expert-knowledge-worker.git
cd expert-knowledge-worker
```

### 2️⃣ Set Up Virtual Environment

```bash
python3 -m venv venv
source venv/bin/activate  # On Windows, use: venv\Scripts\activate
```

### 3️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

### 4️⃣ Set Up Environment Variables

Create a `.env` file in the project root and add:

```ini
OPENAI_API_KEY=your-api-key-here
```

---

## 📑 Requirements File (`requirements.txt`)

```text
gradio
langchain
openai
dotenv
chromadb
faiss-cpu  # Optional if using FAISS
```

---

## 🤝 Contributions

Pull requests and suggestions are welcome! If you find any issues, please open an **issue** in the repository.

---

### 🚀 Happy Coding!
