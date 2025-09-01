# LangChain Notebooks

This repository hosts a collection of Jupyter notebooks developed in Google Colab, demonstrating practical applications of LangChain for data-driven and educational tasks. Each notebook showcases experiments leveraging advanced language models, APIs, and vector databases.

## Notebooks

- **[Football Team Standings (Llama)](./Llama.ipynb)**  
  This notebook utilizes Ollama and LLaMA 3.1 to generate national football team standings based on current player data and statistics retrieved from the [Football API](https://v3.football.api-sports.io/).  
  **Note**: For optimal performance in Google Colab, select a runtime with GPU acceleration (e.g., T4 GPU).

- **[Educational Study Materials (RAG)](./RAG_EDUCATION.ipynb)**  
  This notebook employs ChatGroq and Retrieval-Augmented Generation (RAG) techniques to create educational study materials, including concise summaries, practice questions, and references. Articles are sourced from [OpenAlex](https://api.openalex.org/works) and stored in a Qdrant database for efficient RAG performance.

## Technologies Used

- **LangChain**: A framework for developing applications powered by language models.
- **LangGraph**: A tool for designing and managing complex workflows within LangChain.
- **Qdrant**: A vector database optimized for storing and retrieving embeddings in RAG applications.
- **HuggingFace Transformers**: A library providing pre-trained models and tools for natural language processing tasks.
- **Ollama**: A platform for running and managing large language models, such as LLaMA 3.1.
- **LLaMA 3.1**: A high-performance language model for text generation and analysis.
- **ChatGroq**: An AI model for conversational tasks and content generation.
- **APIs**:
  - [Football API](https://v3.football.api-sports.io/): Provides football player and team statistics.
  - [OpenAlex](https://api.openalex.org/works): Supplies academic articles for educational content generation.

