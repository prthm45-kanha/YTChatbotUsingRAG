# YTChatbotUsingRAG

A Retrieval-Augmented Generation (RAG) chatbot for querying YouTube video content and transcripts.

## Features
- YouTube video transcript extraction
- Text chunking and embedding generation
- Vector search and context retrieval
- LLM response generation with source citations

## Getting Started

### Prerequisites
- Python 3.10+
- Virtual environment (recommended)

### Installation
```bash
# Clone the repository
git clone https://github.com/prthm45-kanha/YTChatbotUsingRAG.git
cd YTChatbotUsingRAG

# Create and activate virtual environment
python -m venv .venv
source .venv/bin/activate  # On Windows: .venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt
```

### Configuration
Create a `.env` file from `.env.example`:
```bash
cp .env.example .env
```
Configure your API keys in `.env`.
