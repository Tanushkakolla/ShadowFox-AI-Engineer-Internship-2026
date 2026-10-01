# ShadowFox AI Engineer Internship

This repository contains the completed projects for the ShadowFox AI Engineer Virtual Internship.

The projects cover three progressive levels, starting with a basic AI-powered student utility, followed by document-based Question Answering using RAG, and finally an advanced production-style RAG system.

## 🟢 Beginner — AI Student Utility

A simple AI-powered student utility designed to provide useful assistance through an LLM.

### Features

- AI-powered student assistance
- LLM-based responses
- Prompt-driven generation
- Simple user interface
- Input handling
- Validation and error handling
- Environment-based API configuration

### Technologies

- Python
- LLM API
- HTML/CSS
- Python utility modules

---

## 🟡 Intermediate — Document Question Answering

A document-based Question Answering system that retrieves relevant information from documents and uses it to generate answers.

The system follows a Retrieval-Augmented Generation approach instead of relying only on the language model's internal knowledge.

### RAG Pipeline

Document Upload → Document Loading → Text Chunking → Embeddings → Vector Store → Similarity Retrieval → Relevant Context → Question Answering → Response

### Features

- Document loading
- Text extraction
- Text chunking
- Embedding generation
- Vector storage
- Similarity-based retrieval
- Grounded question answering
- Grounding verification
- Automated tests

### Technologies

- Python
- RAG
- Embeddings
- Vector Search
- LLM API
- Pytest

---

## 🔴 Advanced — Production-Style RAG Assistant

An advanced Retrieval-Augmented Generation application designed for grounded question answering over documents.

The system combines document ingestion, preprocessing, chunking, embeddings, retrieval, reranking, grounded generation, and response validation into a structured AI workflow.

### Architecture

User Query → Query Processing → Retrieval → Reranking → Relevant Context → LLM Generation → Groundedness Validation → Final Response

### Features

- PDF document processing
- TXT document processing
- Markdown document processing
- Document ingestion and preprocessing
- Text chunking
- Embedding generation
- Vector search
- Document-scoped retrieval
- Query processing and refinement
- Reranking
- Grounded answer generation
- Groundedness validation
- Safe handling of unsupported questions
- FastAPI backend
- Streamlit interface
- LangGraph workflow
- Pydantic-based validation
- Docker support
- Automated testing

### Technologies

- Python
- FastAPI
- Streamlit
- Pydantic
- LangGraph
- FAISS
- Sentence Transformers
- Cross-Encoder
- LLM API
- Docker
- Pytest

---

## 🧠 Skills Demonstrated

- Large Language Models
- Prompt Engineering
- Retrieval-Augmented Generation
- Document Processing
- Text Chunking
- Embeddings
- Vector Search
- Semantic Retrieval
- Reranking
- Grounded Generation
- Hallucination Reduction
- FastAPI
- Streamlit
- Pydantic
- LangGraph
- FAISS
- Docker
- Automated Testing
- AI Application Development

---

## 🧪 Testing

The projects include testing and validation appropriate to their respective levels.

The advanced project includes automated tests for core application and RAG functionality.

Run the tests with:

    pytest -q

---

## 🔐 Environment Configuration

API keys and other secrets are not included in the repository.

Each project provides an `.env.example` file containing the required environment variables.

Create a local `.env` file and add the required API credentials before running the applications.

The `.env` file should not be committed to GitHub.

---

## 📁 Repository Structure

ShadowFox-AI-Engineer-Internship-2026/
├── Beginner/
├── Intermediate/
├── Advanced/
└── README.md

---

## 🎯 Internship Progression

Beginner
↓
AI & LLM Integration
↓
Intermediate
↓
Document Retrieval + RAG
↓
Advanced
↓
Production-Style RAG
↓
Retrieval + Reranking + Groundedness
↓
AI Engineering

---

## 👩‍💻 Author

ShadowFox AI Engineer Intern

Completed as part of the ShadowFox AI Engineer Virtual Internship Program.

---

## 📜 About

This repository contains the completed Beginner, Intermediate, and Advanced projects developed during the ShadowFox AI Engineer Virtual Internship.
