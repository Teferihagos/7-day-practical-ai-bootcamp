# 7-Day Practical AI Bootcamp

## Overview

This repository contains the projects and practical implementations built as part of the [AI Engineering Bootcamp: Apps, RAG, Agents, MCP](https://www.udemy.com/course/ai-engineering-bootcamp-apps-rag-agents-mcp/learn/lecture/56865197?utm_source=gemini#overview). The focus is on building locally-hosted, privacy-first AI applications leveraging Retrieval-Augmented Generation (RAG), autonomous AI agents, and the Model Context Protocol (MCP).

## Tech Stack

* **Frontend UI:** Streamlit
* **Local LLM Orchestration:** Ollama (featuring Llama 3.2)
* **Vector Database:** ChromaDB
* **Document Processing:** PyMuPDF
* **Environment Management:** Python-dotenv

## Project Roadmap

The repository is structured to progressively build out modern AI systems:

1. **AI App Development:** Constructing interactive, web-based chat interfaces using Streamlit.
2. **Local LLM Integration:** Utilizing Ollama to serve open-weight models locally for secure, offline inference.
3. **Document Ingestion:** Parsing, cleaning, and chunking complex PDF documents via PyMuPDF.
4. **Retrieval-Augmented Generation (RAG):** Generating vector embeddings and utilizing ChromaDB for semantic search and context retrieval to reduce hallucinations.
5. **Agentic Workflows:** Designing autonomous AI agents capable of reasoning, routing, and tool use.
6. **Model Context Protocol (MCP):** Implementing standardized context window management for complex, multi-step LLM interactions.

## Local Setup & Installation

### Prerequisites

* macOS/Linux environment
* Python 3.9+
* [Ollama](https://ollama.com/?utm_source=gemini) installed and running in the background.

### 1. Clone the Repository

```bash
git clone https://github.com/Teferihagos/7-day-practical-ai-bootcamp.git
cd 7-day-practical-ai-bootcamp

```

### 2. Activate Your Environment

Ensure your Python virtual environment (e.g., `nu_stats_venv`) is activated:

```bash
source /Users/baria/nu_stats_venv/bin/activate

```

### 3. Install Dependencies

Install the required packages directly into your active virtual environment:

```bash
pip install -r requirements.txt

```

### 4. Pull the Local Model

Ensure Ollama is running, then pull the target model (if you haven't already):

```bash
ollama run llama3.2

```

*(Press `Ctrl + D` to exit the chat prompt once it downloads).*

### 5. Run the Application

Launch the Streamlit frontend:

```bash
python3 -m streamlit run app.py

```

## Author

**Teferi Hagos**

* [GitHub Profile](https://github.com/Teferihagos?utm_source=gemini)