<div align="center">

# 📚 RAG

### A Retrieval-Augmented Generation pipeline for document-grounded question answering

Built with **LangChain** · Powered by **PyMuPDF** & **pypdf** · Managed with **uv**

[![Python](https://img.shields.io/badge/Python-3.13+-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://www.python.org/)
[![LangChain](https://img.shields.io/badge/LangChain-RAG-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white)](https://www.langchain.com/)
[![uv](https://img.shields.io/badge/uv-Package_Manager-DE5FE9?style=for-the-badge)](https://docs.astral.sh/uv/)
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebooks-F37626?style=for-the-badge&logo=jupyter&logoColor=white)](https://jupyter.org/)

</div>

---

## ✨ Overview

This project provides the foundation for a **document question-answering system** based on the RAG pattern. Instead of relying purely on an LLM's pretrained knowledge, relevant chunks of your own documents are **retrieved** and passed as **context** — grounding responses in real, verifiable source material.

> 💡 **RAG in a nutshell:** `Documents → Chunking → Embeddings → Retrieval → LLM Answer`

---

## 🚀 Features

| | |
|---|---|
| 📄 **PDF Ingestion** | Parse and extract text using PyMuPDF and pypdf |
| 🔗 **LangChain Powered** | Built on LangChain + LangChain Community for retrieval orchestration |
| 🧪 **Notebook-Driven** | Prototype and iterate freely inside Jupyter notebooks |
| ⚡ **Fast Setup** | Reproducible, lightning-fast dependency management via `uv` |

---

## 🗂️ Project Structure

```
Rag/
├── Notebook/          📓 Jupyter notebooks for experimentation & prototyping
├── data/              📄 Source documents used for retrieval
├── main.py            🚪 Entry point
├── pyproject.toml     ⚙️  Project metadata and dependencies
├── requirements.txt   📦 Pip-installable dependency list
└── uv.lock            🔒 Locked dependency versions
```

---

## 🛠️ Requirements

- Python **3.13+**
- [`uv`](https://docs.astral.sh/uv/) *(recommended)* or `pip`

---

## 📥 Installation

**1. Clone the repository**

```bash
git clone https://github.com/pulibharat/Rag.git
cd Rag
```

**2. Install dependencies**

<table>
<tr><th>Using uv (recommended)</th><th>Using pip</th></tr>
<tr>
<td>

```bash
uv sync
```

</td>
<td>

```bash
pip install -r requirements.txt
```

</td>
</tr>
</table>

---

## ▶️ Usage

**Run the main script:**

```bash
python main.py
```

**Or explore interactively:**

```bash
jupyter notebook Notebook/
```

> 📌 Drop any PDFs you want to query into the `data/` directory before running the pipeline.

---

## 📦 Dependencies

| Package | Purpose |
|---|---|
| `langchain` | Core RAG orchestration framework |
| `langchain-community` | Community-maintained integrations |
| `langchain-core` | Core abstractions for chains, prompts, and retrievers |
| `pymupdf` | High-performance PDF parsing |
| `pypdf` | Additional PDF reading support |

---

## 🗺️ Roadmap

- [ ] Document chunking and embedding pipeline
- [ ] Vector store integration
- [ ] Retrieval + LLM answer generation chain
- [ ] Evaluation of retrieval quality

---

## 🤝 Contributing

Contributions, issues, and feature requests are welcome!
Feel free to open a **pull request** or file an **issue**. ⭐ Star the repo if you find it useful!

---

## 📄 License

No license has been specified for this project yet. Consider adding one (e.g., **MIT**, **Apache 2.0**) to clarify usage rights for others.

<div align="center">

Made with 🧠 and ☕

</div>
