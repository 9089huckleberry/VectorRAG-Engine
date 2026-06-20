# VectorRAG Engine

A high-performance Vector Database and Retrieval-Augmented Generation (RAG) system built in C++.

VectorRAG Engine demonstrates how modern semantic search and AI retrieval systems work internally by implementing HNSW, KD-Tree, and Brute Force nearest-neighbor search algorithms alongside a complete RAG pipeline powered by local Large Language Models through Ollama.

## Features

* HNSW, KD-Tree, and Brute Force vector search implementations
* Cosine, Euclidean, and Manhattan distance metrics
* Semantic similarity search over high-dimensional embeddings
* Retrieval-Augmented Generation (RAG) pipeline
* Local LLM integration using Ollama and Llama 3.2
* RESTful API for vector and document operations
* Interactive visualization dashboard with PCA projection

## Tech Stack

* C++
* HNSW
* KD-Tree
* Ollama
* Llama 3.2
* REST APIs
* HTML
* JavaScript

## Architecture

```text
User Query
    ↓
Embedding Generation
    ↓
Vector Search (HNSW / KD-Tree)
    ↓
Context Retrieval
    ↓
LLM Processing
    ↓
AI Generated Response
```

## Key Concepts

* Vector Databases
* Approximate Nearest Neighbor (ANN) Search
* Semantic Search
* Vector Embeddings
* Retrieval-Augmented Generation (RAG)
* High-Dimensional Indexing


