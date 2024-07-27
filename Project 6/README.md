
# MCQ Quiz Creator App

## Overview

This application creates multiple-choice questions (MCQs) based on the documents provided. The process involves converting documents into chunks, generating vector embeddings, performing similarity searches, and creating questions with the help of a language model.

## Features

- **Create MCQs from Documents**: Generate multiple-choice questions based on the content of the provided documents.
- **Document Processing**: Convert documents into chunks and vector embeddings.
- **Similarity Search**: Perform a similarity search using vector embeddings to find relevant content.
- **Response Generation**: Use a language model to generate MCQ questions based on user input and relevant document vectors.
- **JSON Output**: Convert the generated MCQs into JSON format using a predefined template.

## Model Configuration

- **LLM (Language Model) Used**: `mistralai/Mistral-7B-Instruct-v0.2`
- **Embedding Model**: `all-MiniLM-L6-v2`

## Frameworks and Tools

- **LangChain**: For building language model applications.
- **Pinecone**: For vector database management and similarity search.

