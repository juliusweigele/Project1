# Project1 - AI Assistant

A local AI assistant using Ollama + LangGraph with tool calling.

## Requirements

- Python 3.14+
- [Ollama](https://ollama.com)
- [uv](https://github.com/astral-sh/uv)

## Setup

```sh
# Install and start Ollama
brew install ollama
ollama pull llama3.1
ollama serve

# Install dependencies
uv sync

# Run
uv run python main.py
```

## Features

- Chat with a local LLM
- Tool calling (e.g. calculator)
- No API key needed — runs 100% locally