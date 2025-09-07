🎲 Game Theory Naïve RAG System


This project implements a Retrieval-Augmented Generation (RAG) system specialized for Game Theory problem solving.
It combines ChromaDB for vector storage and retrieval with OpenAI’s API for embeddings and language model inference, built entirely in Python.
The system ingests raw text files, splits them into chunks, generates embeddings, stores them in ChromaDB, and uses retrieved context to provide concise, expert-style answers to user queries.


🚀 Features
Automated ingestion of .txt documents from a datafolder/.
Splits large documents into overlapping chunks for better recall.
Stores embeddings in ChromaDB for semantic retrieval.
Combines retrieved context with OpenAI’s LLM to answer questions.
Tailored for Game Theory explanations with a concise, expert-style response.
Interactive CLI loop for asking multiple questions.


🛠️ Tech Stack
Python 3.10+
ChromaDB – vector database
OpenAI API – embeddings and completions
python-dotenv – for managing environment variables
