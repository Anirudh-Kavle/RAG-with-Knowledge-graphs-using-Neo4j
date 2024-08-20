# Agentic RAG with Neo4j

## Table of Contents
- [Description](#description)
- [Dependencies](#dependencies)
- [Setup](#setup)
- [Features](#features)

## Description

This project implements an advanced RAG system using Neo4j as a knowledge graph. It combines multiple indexing methods, including vector search, summary indexing, and knowledge graph querying, to provide comprehensive and context-aware responses to user queries about document content.

The system processes PDF documents, creates various indexes, and allows users to query the content using natural language. It leverages the power of LLM's and graph databases to offer a sophisticated information retrieval and generation system.

## Dependencies

Before you begin, ensure you have the following:

- Python 3.7 or newer
- An OpenAI API key
- Neo4j database (accessible via URI)

## Setup

1. Clone the repository:
   ```
   git clone https://github.com/Anirudh-Kavle/RAG-with-Knowledge-graphs-using-Neo4j.git
   cd RAG-with-Knowledge-graphs-using-Neo4j
   ```

2. Set up your environment variables:
   ```
   OPENAI_API_KEY=your_openai_api_key
   NEO4J_URI=your_neo4j_uri
   NEO4J_USERNAME=your_neo4j_username
   NEO4J_PASSWORD=your_neo4j_password
   ```
   
3. Place your PDF document in the project directory or update the file path in the script.

## Features

- Multiple Indexing Methods:
  - Vector Index: For semantic similarity search
  - Summary Index: For hierarchical summarization
  - Knowledge Graph Index: For relationship-based querying

- Integration with Neo4j:
  Utilizes Neo4j as a graph database to store and query relationships extracted from the document.

- Flexible Querying:
  Supports both RAG-based querying (combining vector and summary retrieval) and knowledge graph querying.

- Comprehensive Responses:
  Provides detailed, context-aware responses to user queries, leveraging multiple information retrieval techniques.
