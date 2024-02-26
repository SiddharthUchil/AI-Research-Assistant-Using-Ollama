# AI Research Assistant Using Ollama

Welcome to this exciting project where we create an AI research assistant right on your computer using Ollama! This powerful tool is designed to streamline your research process, from searching for articles to obtaining specific insights. The best part? It costs $0 to run!

## Overview

This project involves several steps:

1. **Searching for Research Articles**: We use the `arXiv` Python package to search for research articles.
2. **Converting Articles into Embeddings**: The articles are then converted into embeddings.
3. **Storing Embeddings in a Database**: The embeddings are stored in a Quadrant database for easy access and retrieval.
4. **Using a Large Language Model with Ollama**: We use a large language model  to clarify any doubts directly from the research articles.
5. **Building a User-Friendly Interface using Gradio**: Finally, we build a user-friendly interface for this entire process.

## Getting Started

1. Download the model using the following command:

```bash
ollama pull llama2:7b-chat

2. Install the necessary dependencies:

pip install arxiv langchain_community langchain gpt4all qdrant-client gradio

