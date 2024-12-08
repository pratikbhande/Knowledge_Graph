# Knowledge_Graph
# Neo4j-LLM-Powered Knowledge Graph and Hybrid Search

This project demonstrates the integration of a Neo4j graph database, a vector-based search system, and large language models (LLMs) to create a robust system for hybrid search and question answering. It combines structured graph-based data and unstructured document retrieval, offering precise and context-rich responses to queries.

---

## Features

- **Hybrid Search**: Combines Neo4j graph queries and vector-based semantic search for more accurate results.
- **Entity Extraction**: Extracts entities (e.g., people, organizations) from text using an LLM-based pipeline.
- **Knowledge Graph Construction**: Converts documents into graph entities and relationships using a graph transformer.
- **Unstructured Data Retrieval**: Leverages embeddings for semantic similarity search on text documents.
- **Question Condensing**: Handles follow-up questions by rephrasing them into standalone queries.
- **End-to-End Query Handling**: Processes both structured and unstructured data sources to generate concise, relevant answers.

---

## Prerequisites

Ensure you have the following installed and configured:

1. **Python Libraries**:
   - `langchain-core`
   - `langchain-openai`
   - `langchain-community`
   - `neo4j`
   - `sentence-transformers`
   - `google-colab` (for cloud setup)
   - `yfiles-jupyter-graphs` (for graph visualization)

2. **Environment**:
   - Neo4j database instance with credentials.
   - OpenAI API key for LLM integration.

3. **Tools**:
   - A Python environment (e.g., Jupyter Notebook, Colab) with widget support.

---

## Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/your-repo.git
   cd your-repo
