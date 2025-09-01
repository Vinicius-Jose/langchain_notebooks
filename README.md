# LangChain Notebooks

This repository contains a collection of Jupyter notebooks developed in Google Colab, showcasing experiments with LangChain for various applications.

## Description

- **[Llama](./Llama.ipynb)**: This notebook leverages Ollama and LLaMA 3.1 to generate national football team standings based on current player data and statistics. Data is sourced from the [Football API](https://v3.football.api-sports.io/).

- **[RAG Education](./RAG_EDUCATION.ipynb)**: This notebook utilizes ChatGroq and Retrieval-Augmented Generation (RAG) techniques to create educational study materials. It generates concise summaries, practice questions, and references for the content. Articles are retrieved from [OpenAlex](https://api.openalex.org/works), downloaded, and stored in a Qdrant database for optimized RAG performance.

## Technologies Used

- **LangChain**: Framework for building applications with language models.
- **LangGraph**: Tool for creating and managing complex workflows with LangChain.
- **Qdrant**: Vector database for efficient storage and retrieval of embeddings in RAG applications.
- **HuggingFace Transformers**: Library providing pre-trained models and tools for natural language processing.
- **Ollama**: Platform for running and managing large language models like LLaMA 3.1.
- **LLaMA 3.1**: A high-performing language model used for generating text and insights.
- **ChatGroq**: AI model for conversational tasks and content generation.
- **APIs**:
  - [Football API](https://v3.football.api-sports.io/): Source for football player and team statistics.
  - [OpenAlex](https://api.openalex.org/works): Source for academic articles used in educational content generation.
