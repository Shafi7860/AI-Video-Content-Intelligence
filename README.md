# AI-Powered Video Content Intelligence System

An AI-powered application designed to process video content, extract meaningful information, generate summaries, and enable users to interact with video content through natural language queries.

## Project Overview

This project explores the use of Artificial Intelligence, Natural Language Processing (NLP), and Large Language Models (LLMs) to transform unstructured video content into searchable and understandable information.

The system uses speech transcription and Retrieval-Augmented Generation (RAG) to help users understand video content without watching the entire video.

## Key Features

- **Video Processing:** Extract and process audio from video content.
- **Speech-to-Text:** Convert spoken content into text using OpenAI Whisper.
- **AI Summarization:** Generate concise summaries of video transcripts.
- **Question Answering:** Ask questions about video content using a RAG-based architecture.
- **Semantic Search:** Retrieve relevant information from video transcripts.
- **Interactive Interface:** Interact with the system through a user-friendly application.

## Technology Stack

| Category | Technologies |
|---|---|
| Programming Language | Python |
| Speech Recognition | OpenAI Whisper |
| NLP | Hugging Face Transformers |
| LLM Framework | LangChain |
| Vector Database | ChromaDB |
| Frontend | Streamlit |
| Development Tools | VS Code, Git, GitHub |

## System Architecture

1. Video input through a supported source.
2. Audio extraction and preprocessing.
3. Speech transcription using Whisper.
4. Text processing and chunking.
5. Embedding generation and vector storage.
6. Context retrieval using RAG.
7. LLM-based summarization and question answering.
8. Results displayed through the application interface.

## Installation and Setup

### 1. Clone the repository

```bash
git clone https://github.com/Shafi7860/AI-Video-Content-Intelligence.git
cd AI-Video-Content-Intelligence
```

### 2. Create a virtual environment

```bash
python -m venv venv
```

### 3. Activate the environment

Windows:

```bash
venv\Scripts\activate
```

### 4. Install dependencies

```bash
pip install -r Requirements.txt
```

### 5. Configure API credentials

Create a `.env` file and configure the API credentials required by the application. Never upload API keys or secrets to GitHub.

### 6. Run the application

```bash
streamlit run app.py
```

Check the repository's actual entry point and configuration before running these commands.

## Project Structure

```text
AI-Video-Content-Intelligence/
│
├── core/
├── utils/
├── app.py
├── main.py
├── test.py
├── Requirements.txt
├── .gitignore
└── README.md
```

## Planned Enhancements

- Transformer-based sentiment analysis using RoBERTa.
- Named Entity Recognition using spaCy.
- Topic modelling using BERTopic.
- Emotion detection from audio and text.
- Advanced content analytics dashboard.
- Improved contextual retrieval and response generation.

## Learning Objectives

- Understand practical applications of NLP and LLMs.
- Implement speech recognition using deep learning.
- Explore Retrieval-Augmented Generation.
- Develop modular AI pipelines.
- Build interactive AI applications.

---

**Author:** Mohd Shafi Sutriwala

**GitHub:** https://github.com/Shafi7860