# llm-chatbot

This project implements a conversational chatbot using LangChain and a pre-trained Hugging Face language model. The chatbot maintains memory to support coherent, context-aware conversations. It demonstrates how to use modern NLP tools to build a lightweight, customizable dialogue system.

## Objective

To explore the use of large language models (LLMs) for conversational agents with memory, using open-source tools. This chatbot is designed for therapeutic-style interactions but can be extended to other domains.

## Features

- Uses Hugging Face LLMs (e.g., `flan-t5-base`)
- Conversation history powered by LangChain's `ConversationBufferMemory`
- Fully local, no API keys or hosted models required
- Simple command-line interface for quick testing

## Technologies

- Python
- LangChain
- Hugging Face Transformers
- SentenceTransformers
- Accelerate

## Installation

```bash
pip install langchain transformers sentence-transformers accelerate
