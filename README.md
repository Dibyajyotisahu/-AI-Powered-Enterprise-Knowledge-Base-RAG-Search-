# AI-Powered Enterprise Knowledge Base & RAG Search

An AI-powered document intelligence platform that enables users to upload PDF and DOCX files, perform semantic search, and receive accurate context-aware answers using Retrieval-Augmented Generation (RAG).

Built with FastAPI, React, MongoDB Atlas Vector Search, OpenAI Embeddings, LangChain, Docker, and AWS.

---

## Project Overview

This project is an enterprise-grade knowledge management system designed to help teams quickly retrieve information from large collections of documents.

Users can upload PDFs and Word documents, which are processed through a RAG pipeline. The system extracts text, generates embeddings, stores them in a vector database, and retrieves the most relevant document sections when users ask questions.

Instead of manually searching through lengthy documents, users can interact with the knowledge base using natural language and receive grounded answers based on the uploaded content.

---

## Key Features

* Upload and process PDF and DOCX documents
* AI-powered semantic search using vector embeddings
* Retrieval-Augmented Generation (RAG) pipeline
* Context-aware question answering
* User authentication and role-based access
* Document management dashboard
* Chat history and audit logging
* Dockerized deployment
* Cloud-ready architecture with AWS

---

## Tech Stack

### Frontend

* React 18
* TypeScript
* React Query
* Recharts

### Backend

* Python
* FastAPI
* LangChain
* JWT Authentication

### Database

* MongoDB Atlas
* MongoDB Atlas Vector Search

### AI & Machine Learning

* OpenAI Embeddings
* GPT Models
* Retrieval-Augmented Generation (RAG)

### Cloud & DevOps

* Docker
* GitHub Actions
* AWS ECS
* AWS S3

---

## System Architecture

### Document Ingestion Pipeline

PDF/DOCX Upload

↓

Text Extraction

↓

Text Chunking

↓

Embedding Generation

↓

MongoDB Atlas Vector Storage

### Question Answering Pipeline

User Question

↓

Question Embedding

↓

Vector Similarity Search

↓

Relevant Context Retrieval

↓

LLM Response Generation

↓

Answer Display

---

## Project Structure

enterprise-knowledge-base/

frontend/

├── src/

├── components/

├── pages/

├── services/

backend/

├── app/

│ ├── api/

│ ├── auth/

│ ├── rag/

│ ├── database/

│ ├── services/

│ └── models/

infrastructure/

├── docker/

├── github-actions/

docs/

README.md

---

## Workflow

1. User uploads PDF or DOCX documents.
2. Documents are processed and split into smaller chunks.
3. Embeddings are generated using OpenAI models.
4. Embeddings are stored in MongoDB Atlas Vector Search.
5. User submits a question.
6. The system retrieves the most relevant document chunks.
7. Retrieved context is sent to the language model.
8. The model generates an accurate answer based on document content.

---

## Deployment

The application is containerized using Docker and deployed on AWS.

Deployment Pipeline:

Source Code

↓

GitHub Actions CI/CD

↓

Docker Image Build

↓

AWS ECS Deployment

↓

Production Environment

---

## Future Enhancements

* Multi-document conversational memory
* Team workspaces
* Role-based access control
* Document summarization
* Source citation and reference highlighting
* Multi-tenant architecture
* Analytics dashboard
* Enterprise SSO integration

---

## Learning Outcomes

* Retrieval-Augmented Generation (RAG)
* Vector Databases and Semantic Search
* FastAPI Backend Development
* React Frontend Development
* OpenAI API Integration
* Docker and Cloud Deployment
* CI/CD with GitHub Actions
* Enterprise AI Application Design

---

## Author

Dibyajyoti Sahu

B.Tech CSE (Data Science)

Institute of Technical Education and Research, SOA University

Email: [sahud812003@gmail.com](mailto:sahud812003@gmail.com)

GitHub: github.com/your-github-username

LinkedIn: linkedin.com/in/your-linkedin-profile
