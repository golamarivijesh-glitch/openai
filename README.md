# LangChain & OpenAI — Getting Started

A beginner-friendly collection of Jupyter notebooks exploring LangChain and OpenAI.

## 📒 Notebooks

### 1. Getting Started (`1_1_1-GettingStarted.ipynb`)
Introduction to core LangChain concepts:
- Setting up OpenAI and LangSmith API keys via `.env`
- Invoking `ChatOpenAI` (GPT-4o) directly
- Building prompt templates with `ChatPromptTemplate`
- Chaining components using the LangChain pipe (`|`) operator
- Parsing model output with `StrOutputParser`

### 2. Simple Gen AI App (`1_1_2-Simpleapp.ipynb`)
A practical RAG (Retrieval-Augmented Generation) pipeline:
- Web scraping with `WebBaseLoader`
- Document splitting and embedding with OpenAI embeddings
- Vector storage and similarity search using FAISS
- Retrieval Q&A chain with `create_retrieval_chain`
- LangSmith tracing integration for monitoring

### 3. New Project Template (`newproject.ipynb`)
A clean starter template with environment variable setup for new LangChain projects.

## 🛠️ Tech Stack
- Python 3.13
- LangChain & LangChain-OpenAI
- OpenAI GPT-4o
- FAISS (vector store)
- LangSmith (tracing & monitoring)
- python-dotenv

## 🚀 Setup
1. Clone the repo
2. Create a `.env` file with your keys:
