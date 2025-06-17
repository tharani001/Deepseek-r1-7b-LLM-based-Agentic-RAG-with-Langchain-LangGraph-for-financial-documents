
## 🚀 Overview

This project builds a full-stack document understanding and response generation system. It uses:

- **Docling** and **MarkdownTextSplitter** for preprocessing and chunking documents  
- **nomic-embed-text** for embedding chunks into 768-dimensional vectors  
- **FAISS** for fast vector-based semantic retrieval  
- A custom retriever that filters relevant documents automatically (no manual filters!)  
- An **agent graph** composed of nodes that rewrite queries, validate relevance, and generate accurate responses  
- Powered by the **LLAMA3.2:3b** model

## 🧩 Key Features

- 🔍 **Automatic Semantic Retrieval** — custom retriever handles relevance filtering internally  
- 🧠 **Autonomous Agent Graph** — modular nodes for query rewriting, doc validation, and response generation  
- 🧾 **464 Document Chunks** — embedded into high-dimensional space for deep contextual understanding  
- ⚡ **Self-iterating Query Refinement** — ensures responses only generate when retrieval is strong

## 🛠️ Stack

- **LLM**: LLAMA3.2:3b  
- **Embedding**: nomic-embed-text  
- **Vector Store**: FAISS  
- **Parsing & Chunking**: Docling + MarkdownTextSplitter  
- **Agent Graph**: Custom-built with tool and function nodes  

