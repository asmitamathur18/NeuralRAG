# NeuralRAG

An intelligent Retrieval-Augmented Generation (RAG) chatbot that combines semantic document retrieval with Large Language Models (LLMs) to deliver accurate, context-aware answers from custom knowledge bases.

![Python](https://img.shields.io/badge/Python-3.10+-blue?logo=python)
![Streamlit](https://img.shields.io/badge/Streamlit-App-red?logo=streamlit)
![LLM](https://img.shields.io/badge/LLM-Powered-green)
![RAG](https://img.shields.io/badge/Retrieval-Augmented%20Generation-orange)

---

## Overview

NeuralRAG is an AI-powered chatbot that retrieves relevant information from a custom document collection before generating responses using a Large Language Model. By grounding responses in retrieved knowledge, the system provides more accurate, reliable, and context-aware answers than traditional conversational AI systems.

---

## Features

- Document-based question answering
- Semantic search using vector embeddings
- Large Language Model integration
- Retrieval-Augmented Generation (RAG)
- Context-aware response generation
- Interactive Streamlit interface
- Secure API key management using environment variables

---

## Project Structure

```text
NeuralRAG/
│
├── database/            # Vector store and database utilities
├── llm/                 # LLM integration
├── preprocessing/       # Document preprocessing
├── utils/               # Helper functions
├── app.py               # Streamlit application
├── config.py            # Configuration settings
├── requirements.txt     # Project dependencies
├── .env.example         # Environment variable template
├── .gitignore
└── README.md
```

---

## Installation

Clone the repository:

```bash
git clone https://github.com/asmitamathur18/NeuralRAG.git
```

Navigate to the project directory:

```bash
cd NeuralRAG
```

Install the required dependencies:

```bash
pip install -r requirements.txt
```

---

## Configuration

Create a `.env` file in the project root and add your API key:

```env
GOOGLE_API_KEY=your_api_key_here
```

---

## Running the Application

Start the Streamlit application:

```bash
streamlit run app.py
```

The application will launch in your default web browser.

---

## Technology Stack

- Python
- Streamlit
- Large Language Models (LLMs)
- Retrieval-Augmented Generation (RAG)
- Semantic Search
- Vector Embeddings

---

## Future Enhancements

- Multi-document support
- Conversation memory
- Support for PDF, DOCX, and TXT document ingestion
- Source citations for generated responses
- Integration with multiple LLM providers
- Cloud deployment

---

## Contributing

Contributions are welcome. Feel free to fork the repository, open an issue, or submit a pull request.

---

## License

This project is intended for educational and research purposes.
