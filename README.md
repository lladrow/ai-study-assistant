# AI Study Assistant

AI-powered educational tutor that generates quizzes, flashcards, audio summaries, and interactive learning materials from PDFs, videos, and structured documents using LLMs and vector search.

## Features

- Quiz generation (MCQs with explanations)
- Flashcard creation (Q/A format)
- Audio summaries (Text-to-Speech)
- PDF and YouTube content ingestion
- Progress tracking dashboard
- Vector-based content grounding

## Tech Stack

- Python
- Streamlit
- LangChain
- OpenAI API
- Google Text-to-Speech API
- FAISS (Vector Store)
- SQLite

## Architecture

Content → Processing → Chunking → Embeddings → LLM → Study Materials → Dashboard

## Deployment

Streamlit Cloud
